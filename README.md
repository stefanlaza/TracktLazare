# TracktLazare

A minimalist expense tracker for managing recurring subscriptions and one-time purchases.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## ✨ Features

- 📊 **Smart Tracking** - Separate recurring and one-time expenses
- 🔍 **Search & Filter** - Find items by name or category
- 📈 **Visual Analytics** - Bar chart showing spending by category
- 💰 **Budget Alerts** - Set monthly budget and get warnings
- ✏️ **Edit & Duplicate** - Easily manage your items
- 💳 **Payment Tracking** - Tag items with payment methods
- 📝 **Notes** - Add details to any expense
- 📥 **Import/Export** - CSV backup and restore
- 📄 **PDF Reports** - Generate monthly or yearly expense reports
- 🌓 **Dark Mode** - Beautiful light and dark themes
- 📱 **Responsive** - Works on desktop, tablet, and mobile

## 🚀 Quick Start

### Option 1: GitHub Pages (Easiest)

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select your branch (usually `main`)
4. Click **Save**
5. Your app will be live at `https://yourusername.github.io/trackt/`

### Option 2: Local Development

Simply open `index.html` in your browser. No build tools required!

### Option 3: Docker

```bash
# Build the image
docker build -t trackt .

# Run the container
docker run -d -p 8080:80 trackt
```

Visit `http://localhost:8080` in your browser.

## 📖 Usage

### Adding Items

1. Click **"Add Item"**
2. Fill in the details:
   - Item name (required)
   - Amount (required)
   - Category
   - Type (Recurring or One-Time)
   - Day of month (for recurring items)
   - Payment method (optional)
   - Notes (optional)
3. Click **"Add Item"** to save

### Managing Items

- **Edit**: Click the pencil icon to modify an item
- **Duplicate**: Click the copy icon to create a similar item
- **Delete**: Click the trash icon to remove an item

### Setting a Budget

Enter your monthly budget in the header to:
- See remaining budget
- Get alerts when approaching or exceeding budget

### Search & Filter

Use the search bar and filters to:
- Search by item name
- Filter by category
- Sort by name, amount, or date

### Export & Import

**Export Options:**
- **CSV**: Full backup of all items
- **Monthly PDF**: Printable monthly report
- **Yearly PDF**: Annual expense projection

**Import:**
- Click the upload icon
- Select your CSV file
- Items will be added to your tracker

## 🎨 Category Icons

- 🎮 Entertainment
- 💪 Health
- 🍔 Food
- 💡 Utilities
- 🛍️ Shopping
- 📦 Other

## 🛠️ Tech Stack

- **HTML5** - Structure
- **Tailwind CSS** - Styling
- **Vanilla JavaScript** - Logic
- **Lucide Icons** - Icons
- **Chart.js** - Analytics

## 📝 CSV Format

When exporting/importing CSV files, use this format:

```csv
Name,Amount,Category,Type,Day of Month,Payment,Notes
"Netflix",15.99,"Entertainment","recurring",1,"Visa *1234",""
"Laptop",1299.00,"Shopping","one-time","N/A","Master *5678","MacBook Pro"
```

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📄 License

MIT License - feel free to use this project however you'd like!

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 🙏 Acknowledgments

- Tailwind CSS for the styling framework
- Lucide for the beautiful icons
- Chart.js for data visualization

---

Made with ❤️ by [Your Name]
