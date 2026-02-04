# 📧 Email Extractor Pro - Random 200 Email Selector

[![GitHub stars](https://img.shields.io/github/stars/SauravDnj/email-extractor-pro.svg)](https://github.com/SauravDnj/email-extractor-pro/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/SauravDnj/email-extractor-pro.svg)](https://github.com/SauravDnj/email-extractor-pro/network)
[![GitHub issues](https://img.shields.io/github/issues/SauravDnj/email-extractor-pro.svg)](https://github.com/SauravDnj/email-extractor-pro/issues)

> **A powerful, intelligent email extraction system that extracts emails from PDFs and documents, randomly selects 200 unique emails, and exports them to Excel - all while ensuring NO DUPLICATES across multiple runs!**

Perfect for email marketing campaigns, lead generation, sales outreach, and data analysis.

---

## 🌟 Features

### 🎯 Core Features
- ✅ **PDF Email Extraction** - Extract all email addresses from PDF files automatically
- ✅ **Document Processing** - Support for text documents and pasted content
- ✅ **Random Selection** - True random algorithm for fair 200-email selection
- ✅ **Zero Duplicates** - Intelligent tracking prevents selecting the same email twice
- ✅ **Beautiful Excel Export** - Professional formatted spreadsheets with statistics
- ✅ **Multiple Provider Detection** - Gmail, Yahoo, Outlook, Educational, Government
- ✅ **Google Maps Lead Scraper** - Bonus tool for extracting business data

### 🚀 Advanced Features
- 📊 Real-time statistics dashboard
- 🔄 Multiple run support with history tracking
- 💾 Persistent browser storage
- 📱 Mobile responsive design
- 🎨 Beautiful, modern UI
- 📥 Drag & drop file upload
- 📋 One-click copy to clipboard
- 🔐 100% client-side processing (privacy-safe)

---

## 🚀 Quick Start

### Option 1: Web Interface (Recommended - No Installation!)

1. **Download the repository**
   ```bash
   git clone https://github.com/SauravDnj/email-extractor-pro.git
   cd email-extractor-pro
   ```

2. **Open in browser**
   - Double-click `pdf_email_extractor_web.html` for PDF extraction
   - OR double-click `email_extractor_interface.html` for text extraction
   - OR double-click `lead_scraper_interface.html` for Google Maps leads

3. **Start extracting!**
   - Upload your PDF or paste text
   - Click "Select Random 200"
   - Download Excel file
   - Done! ✅

### Option 2: Python Scripts (For Developers)

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the extractor**
   ```bash
   # For PDF extraction
   python pdf_email_extractor.py
   
   # For text/document extraction
   python email_extractor.py
   
   # For Google Maps lead scraping
   python lead_scraper.py
   ```

---

## 📦 What's Included

### 🌐 Web Interfaces (No Installation Required)
- `pdf_email_extractor_web.html` - PDF email extraction interface
- `email_extractor_interface.html` - Text/document email extraction
- `lead_scraper_interface.html` - Google Maps lead scraper

### 🐍 Python Scripts
- `pdf_email_extractor.py` - PDF processing backend
- `email_extractor.py` - General email extraction
- `lead_scraper.py` - Lead scraping system

### 📚 Documentation
- `README.md` - This file
- `PDF_EXTRACTOR_GUIDE.txt` - Detailed PDF extractor guide
- `README.txt` - General email extractor guide
- `LICENSE` - MIT License

---

## 💡 Use Cases

### 1. **Email Marketing Campaigns** 📧
Extract 200 random contacts for each campaign batch, ensuring no one receives duplicate emails.

### 2. **Lead Generation** 🎯
Build targeted prospect lists from PDF databases with intelligent provider detection.

### 3. **Sales Outreach** 📞
Segment your contact list into random batches for different sales teams.

### 4. **A/B Testing** 🧪
Create randomized test groups for marketing experiments with zero overlap.

### 5. **Survey Distribution** 📊
Randomly select participants from large databases while tracking responses.

### 6. **Google Maps Data Scraping** 🗺️
Extract business information including emails, phones, and ratings from Google Maps listings.

---

## 🎓 How It Works

### The Smart Duplicate Prevention System

```
📄 Upload PDF (1000 emails)
    ↓
🔍 Extract all emails
    ↓
🎲 Randomly select 200
    ↓
💾 Save to history
    ↓
📥 Export to Excel

Next Run:
    ↓
🚫 Exclude previously selected 200
    ↓
🎲 Select DIFFERENT 200 from remaining 800
    ↓
💾 Update history (now 400 tracked)
    ↓
📥 Export to Excel
```

### Excel Export Format

**Sheet 1: Random 200 Emails**
| # | Email Address | Domain | Provider Type | Status |
|---|---------------|--------|---------------|--------|
| 1 | saurav@example.com | example.com | Corporate | New |
| 2 | saurav@gmail.com | gmail.com | Gmail | New |
| ... | ... | ... | ... | ... |

**Sheet 2: Summary & Statistics**
- Source file information
- Total emails found
- Previously selected count
- Provider breakdown
- Extraction timestamp

---

## 🛠️ Technical Stack

### Frontend
- **HTML5** - Modern semantic markup
- **CSS3** - Responsive design with gradients
- **JavaScript (ES6+)** - Client-side processing
- **PDF.js** - PDF parsing library
- **SheetJS (XLSX)** - Excel file generation

### Backend (Optional)
- **Python 3.7+** - Core processing
- **PyPDF2** - PDF text extraction
- **openpyxl** - Excel file creation
- **Regular Expressions** - Email pattern matching

---

## 📊 Statistics Dashboard

The web interface provides real-time statistics:

- 📈 **Total Emails Found** - All unique emails discovered
- ✅ **Selected** - Currently selected 200 emails
- 🔄 **Previously Used** - Emails from past runs
- 🆓 **Available** - New emails ready for selection

---

## 🔐 Privacy & Security

✅ **100% Client-Side Processing**
- All data processed in your browser
- Nothing sent to external servers
- Your emails remain completely private

✅ **No Data Collection**
- No analytics or tracking
- No cookies (except localStorage)
- Open source - verify the code yourself

✅ **Secure Storage**
- History saved in browser localStorage
- Specific to your device only
- Easy to clear anytime

---

## 📱 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Opera 76+ | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

---

## 🐛 Bug Reports & Feature Requests

Found a bug or have an idea? Please [open an issue](https://github.com/SauravDnj/email-extractor-pro/issues) with:

- Clear description
- Steps to reproduce (for bugs)
- Expected vs actual behavior
- Screenshots (if applicable)

---

## 📝 Changelog

### Version 1.0.0 (2026-02-04)
- ✨ Initial release
- 📄 PDF email extraction
- 📧 Text/document email extraction
- 🗺️ Google Maps lead scraper
- 📊 Excel export with statistics
- 🔄 Duplicate prevention system
- 🎨 Beautiful web interfaces

---

## 👨‍💻 Author

**Saurav**
- GitHub: [@SauravDnj](https://github.com/SauravDnj)
- Project Link: [https://github.com/SauravDnj/email-extractor-pro](https://github.com/SauravDnj/email-extractor-pro)

---

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=SauravDnj/email-extractor-pro&type=Date)](https://star-history.com/#SauravDnj/email-extractor-pro&Date)

---

## 🙏 Acknowledgments

- **PDF.js** - Mozilla's PDF parsing library
- **SheetJS** - Amazing Excel file generation
- **Open Source Community** - For inspiration and support

---

## 💬 Support

If you find this project helpful:
- ⭐ Star the repository
- 🐛 Report bugs
- 💡 Suggest features
- 🔗 Share with others

---

## 🚀 Roadmap

### Upcoming Features
- [ ] Multi-language support
- [ ] CSV import/export
- [ ] Advanced filtering options
- [ ] Email validation
- [ ] Cloud storage integration
- [ ] Batch PDF processing
- [ ] API endpoint
- [ ] Chrome extension

---

## 📧 Contact

For questions or support, please open an issue or reach out:
- GitHub Issues: [https://github.com/SauravDnj/email-extractor-pro/issues](https://github.com/SauravDnj/email-extractor-pro/issues)

---

<div align="center">

**Made with ❤️ by [SauravDnj](https://github.com/SauravDnj)**

If this project helped you, please consider giving it a ⭐!

[⬆ Back to Top](#-email-extractor-pro---random-200-email-selector)

</div>
