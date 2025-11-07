# 🔍 Master OSINT Dorks Dashboard

![OSINT Dashboard](https://img.shields.io/badge/OSINT-Advanced-blue) ![Dorking](https://img.shields.io/badge/Dorking-Professional-red) ![Search](https://img.shields.io/badge/Search-Multi--Engine-green)

A comprehensive, next-generation OSINT (Open Source Intelligence) dorking tool that transforms Google and other search engines into powerful reconnaissance instruments. This Swiss Army knife for security researchers and penetration testers features 100+ specialized dorks across multiple categories and search engines.

## 🚀 Features

### 🔧 Multi-Engine Support
- **Google** - Traditional web search with advanced operators
- **Shodan** - IoT and network device discovery
- **GitHub** - Code and repository searching
- **Censys** - Certificate and service discovery
- **LinkedIn** - People and company intelligence
- **DuckDuckGo** - Privacy-focused searches
- **Binary Edge** - Security intelligence
- **Netlas** - Internet-wide scanning

### 🎯 Extensive Dork Categories
- **SQL Injection** - Find vulnerable parameters and error pages
- **Authentication** - Discover login panels and admin portals
- **Sensitive Files** - Locate exposed configs, backups, and databases
- **IoT Devices** - Find cameras, network equipment, and servers
- **Cloud Services** - Discover AWS S3, Google Drive, and Azure resources
- **OSINT Intelligence** - Uncover emails, documents, and personal data
- **WordPress** - CMS-specific vulnerabilities and admin panels
- **Error Detection** - Find debug information and error messages

### 💡 User Experience
- **One-Click Searching** - Click any dork card to instantly search
- **Real-time Filtering** - Filter dorks by name, engine, or category
- **Active Marking** - Mark frequently used dorks for quick access
- **Responsive Design** - Works on desktop and mobile devices
- **Dark Theme** - Easy on the eyes during extended sessions

## 🛠️ Installation

### Method 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start dorking!

### Method 2: Clone Repository
```bash
git clone https://github.com/xl337x/easydork
cd easydork
open index.html
```

### Method 3: Deploy to Web Server
Upload the `index.html` file to any web server (Apache, Nginx, GitHub Pages, etc.)

## 📖 Usage Guide

### Basic Workflow
1. **Enter Target Domain** - Input the domain you want to investigate
2. **Select Dork Category** - Use the filter to find relevant dorks
3. **Click to Search** - Click any dork card to open search in new tab
4. **Analyze Results** - Review the search results for valuable information

### Advanced Features
- **Domain Persistence** - Once entered, the domain remains active for all searches
- **Quick Filtering** - Type keywords to filter dorks in real-time
- **Active Marking** - Click "Mark" to highlight frequently used dorks
- **Multi-Engine** - Different dorks automatically use appropriate search engines

### Example Use Cases
```
# Find exposed admin panels
Enter: example.com → Click: "Auth - Admin Logins"

# Discover SQL injection points  
Enter: target.org → Click: "SQLi - PHP Pages"

# Locate sensitive files
Enter: company.com → Click: "Files - Config Files"

# Find IoT devices
Enter: network.local → Click: "IoT - Network Cameras"
```

## 🗂️ Dork Categories Overview

### 🔍 Basic Operators
- `site:` - Domain-specific searches
- `inurl:` - URL pattern matching
- `intitle:` - Title content searching
- `filetype:` - Specific file types
- Advanced combinations and cache searching

### 🎯 SQL Injection
- PHP/ASP parameter discovery
- Database error detection
- Category and search page vulnerabilities
- Oracle, MySQL, and SQL Server specific dorks

### 🔐 Authentication Systems
- Admin login portals
- WordPress/Drupal/Joomla panels
- Authentication bypass opportunities
- Default credential locations

### 📁 Sensitive Files
- Directory listings
- Configuration files (env, config, yml)
- Database backups and dumps
- SSH keys and certificates
- Source code exposures

### 🌐 IoT & Network
- Camera feeds and IP cameras
- Network device configurations
- Server technologies (Apache, Nginx, Tomcat)
- Jenkins and automation tools

### ☁️ Cloud Services
- AWS S3 bucket discovery
- Google Drive and Firebase
- Azure storage locations
- Misconfigured cloud resources

### 📊 OSINT Intelligence
- Email lists and contacts
- Confidential documents
- Financial records and spreadsheets
- Network diagrams and internal docs
- API keys and credentials

## ⚡ Quick Start Examples

### Basic Reconnaissance
```
site:target.com
site:target.com filetype:pdf
site:target.com inurl:admin
```

### Advanced Vulnerability Discovery  
```
site:target.com inurl:.php?id=
site:target.com "index of" password
site:target.com intitle:"login" intext:"username"
```

### Cloud and Infrastructure
```
site:s3.amazonaws.com target.com
site:drive.google.com target.com confidential
hostname:target.com port:22
```

## 🛡️ Legal & Ethical Usage

### ✅ Permitted Uses
- Security research on systems you own
- Authorized penetration testing
- Educational purposes
- Bug bounty programs (where permitted)
- Corporate security assessments

### ❌ Prohibited Uses
- Unauthorized system access
- Malicious hacking activities
- Privacy violations
- Harassment or stalking
- Any illegal activities

### 📜 Disclaimer
This tool is provided for educational and authorized security testing purposes only. Users are responsible for ensuring they have proper authorization before conducting any security assessments. The developers are not liable for misuse of this tool.

## 🔧 Technical Details

### Browser Compatibility
- Chrome 60+
- Firefox 55+ 
- Safari 12+
- Edge 79+

### Technologies Used
- Pure HTML5, CSS3, and JavaScript
- CSS Grid and Flexbox for layouts
- Modern ES6+ JavaScript features
- Responsive design principles

### File Structure
```
master-osint-dorks/
├── index.html          # Main application file
├── README.md           # This documentation
└── images/             # Screenshots and assets
```

## 🤝 Contributing

We welcome contributions to expand the dork library and improve functionality!

### How to Contribute
1. Fork the repository
2. Add new dorks to the `dorkLibrary` array
3. Follow the existing format for consistency
4. Test your changes thoroughly
5. Submit a pull request

### Dork Format Template
```javascript
{
    title: "Descriptive Name",
    engine: "SearchEngine",
    cat: "Category",
    desc: "Brief description of what this dork finds",
    template: "site:{domain} search_operator:value"
}
```

## 📊 Statistics

- **100+ Pre-configured Dorks** - Comprehensive coverage
- **8 Search Engines** - Multi-platform intelligence
- **15+ Categories** - Organized by vulnerability type
- **Zero Dependencies** - Runs in any modern browser

## 🐛 Issue Reporting

Found a bug or have a feature request? Please open an issue with:
- Detailed description of the problem
- Steps to reproduce
- Browser and version information
- Any relevant screenshots

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🌟 Star History

If you find this tool useful, please consider giving it a star ⭐ on GitHub!

## 🆕 Updates & Changelog

### v1.0.0 - Initial Release
- 100+ specialized dorks
- Multi-engine support
- Real-time filtering
- Active marking system
- Responsive design

---

**Happy Dorking!** 🚀

Remember: With great power comes great responsibility. Always use this tool ethically and legally.

---
<div align="center">

*Master OSINT Dorks Dashboard - Your Swiss Army Knife for Security Reconnaissance*


</div>
