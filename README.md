# Estate Inventory Application

Welcome to the Estate Inventory Application project! This application helps users track and manage estate assets through a structured, user-friendly web interface. The foundation is derived from a comprehensive estate inventory form template that covers all major asset categories.

## 📋 Table of Contents
1. [Overview](#-overview)
2. [Features](#-features)
3. [Technologies](#-technologies)
4. [Installation](#-installation)
5. [Usage](#-usage)
6. [Project Structure](#-project-structure)
7. [Contributing](#-contributing)
8. [License](#-license)
9. [Disclaimer](#-disclaimer)

## 🎯 Overview

The **Estate Inventory Application** streamlines the process of cataloging estate assets. It replaces manual paper forms with a modern, browser-based solution that allows for easy data entry, updates, and review. The primary goal is to ensure you have an up-to-date and comprehensive record of:
- Real estate holdings
- Financial accounts
- Personal property
- Digital assets
- Important documents

All in one secure, accessible place.

## ✨ Features

- **Dynamic Data Management**: Add, edit, or delete entries for each asset category in real time
- **Search and Filter**: Quickly locate specific assets within large estates
- **Documentation Tracking**: Store references to physical or digital documents for each asset
- **Value Summaries**: View aggregated totals for quick estate valuation
- **Responsive Interface**: Use on desktops, tablets, or smartphones
- **Data Export**: (Planned Feature) Export data to printable PDF or CSV formats for offline records

## 💻 Technologies

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**

*No external frameworks or libraries are used to simplify deployment and ensure maximum portability.*

## 🚀 Installation

1. Clone the repository
   ```bash
   git clone https://github.com/revsmoke/Estate.git
   ```

2. Open `index.html` in any modern browser to run locally

3. For advanced features (recommended), set up a local server:
   ```bash
   # Using Python (choose one):
   python -m http.server 8000    # Python 3
   python -m SimpleHTTPServer 8000    # Python 2
   
   # Then visit http://localhost:8000
   ```

## 📝 Usage

1. Launch the application by opening `index.html`
2. Navigate through asset categories:
   - Real Estate
   - Financial Accounts
   - Vehicles
   - Personal Property
   - Digital Assets
3. Add new entries using category-specific forms
4. Update existing entries to maintain current records
5. Review estate summaries in the "Summary of Estate Value" section
6. Track document locations in the "Important Documents Location" section

## 📁 Project Structure

```
estate-inventory-app/
├── index.html         # Main HTML file containing the entire app
├── style.css         # Styles for clean, responsive design
└── script.js         # Client-side logic and data management
```

### Component Details

- **index.html**:
  - Structured layout reflecting the estate asset inventory
  - Sections corresponding to major asset categories
  - Summary section for total estate value

- **style.css**:
  - Responsive design implementation
  - Clean, user-friendly interface styling

- **script.js**:
  - Client-side data manipulation
  - Form submissions handling
  - Local storage management

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This software is provided as a tool to help organize and track estate assets. It does **not** provide legal, financial, or tax advice. Always consult qualified professionals regarding estate planning and management matters.

---
Made with ❤️ & 💨 by RevSmoke
