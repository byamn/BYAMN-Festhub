# BYAMN Festhub 🎉

**Create & Share Beautiful Festival Greeting Cards for All Occasions**

BYAMN Festhub is a web-based platform that allows users to create personalized festival greeting cards for various celebrations including Christmas, Janmashtami, and other major festivals. With an intuitive interface and stunning templates, users can easily generate and share customized greetings with their loved ones.

![BYAMN Festhub](logo.png)

## ✨ Features

- **Multiple Festival Templates**: Support for Christmas, Janmashtami, and other major festivals
- **Personalized Greetings**: Add custom names to create personalized greeting cards
- **Random Wishes**: Curated collection of festival-specific wishes and messages
- **Social Sharing**: Share greetings via WhatsApp, Facebook, Twitter, and direct links
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Beautiful UI**: Modern, festive design with smooth animations
- **Multi-language Support**: Includes both English and Hindi text for Indian festivals
- **URL Shortener**: Built-in link shortening functionality
- **No Registration Required**: Start creating greetings immediately

## 🚀 Quick Start

### Option 1: Online Access
Visit the live website: [BYAMN Festhub](https://byamn.vercel.app/)

### Option 2: Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/byamn-festhub.git
   cd byamn-festhub
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Navigate to localhost**
   Open your browser and go to `http://localhost:8000`

## 📁 Project Structure

```
BYAMN-Festhub/
├── index.html              # Main landing page with festival categories
├── Christmas.html          # Christmas greeting card generator
├── Janmashtami.html        # Janmashtami greeting card generator
├── file.html              # URL shortener utility
├── redirect.html           # Redirect page with ads
├── logo.png               # Project logo
├── README.md              # Project documentation
├── LICENSE                # MIT License
├── .gitignore            # Git ignore rules
├── assets/               # Static assets (future)
│   ├── images/          # Image files
│   ├── css/             # Stylesheets
│   └── js/              # JavaScript files
└── docs/                # Documentation (future)
```

## 🎯 How to Use

1. **Visit the Homepage**: Start at `index.html` to browse available festival categories
2. **Select a Festival**: Click on any festival card (Christmas, Janmashtami, etc.)
3. **Enter Your Name**: Add your name to personalize the greeting
4. **Generate Greeting**: Click "Generate Greeting" to create your card
5. **Share**: Use the share button to send via social media or copy the link

## 🛠️ Dependencies

This project uses only vanilla web technologies with external CDN resources:

- **Font Awesome 6.4.0**: Icons
- **Google Fonts**: Typography (Poppins, Playfair Display, Tangerine, Kalam)
- **External Libraries**: None (Vanilla JavaScript, CSS, HTML)

No build process or package manager required!

## 🔧 Customization

### Adding a New Festival

1. Create a new HTML file (e.g., `diwali.html`)
2. Copy the structure from an existing festival page
3. Update the color scheme in CSS variables
4. Replace images array with festival-specific images
5. Update wishes array with appropriate messages
6. Add the new festival to the main `index.html` page

### Customizing Themes

Edit the CSS custom properties in each file:
```css
:root {
    --primary: #your-color;
    --secondary: #your-color;
    --accent: #your-color;
}
```

## 📱 Browser Support

- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/new-festival`
3. **Make your changes**: Add new festivals, improve UI, fix bugs
4. **Test thoroughly**: Ensure your changes work across devices
5. **Submit a pull request**: Describe your changes clearly

### Contribution Ideas

- 🎨 Add new festival templates (Diwali, Eid, Holi, etc.)
- 🌍 Add more language support
- 📱 Improve mobile responsiveness
- ✨ Enhance animations and transitions
- 🖼️ Add more greeting card designs
- 🔧 Optimize performance

## 📸 Screenshots

![Homepage](screenshots/homepage.png)
*Main landing page with festival categories*

![Christmas Greeting](screenshots/christmas.png)
*Christmas greeting card generator*

![Mobile View](screenshots/mobile.png)
*Mobile responsive design*

> **Note**: Add screenshots to `/screenshots/` directory

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Font Awesome**: For beautiful icons
- **Google Fonts**: For typography
- **Festival Images**: Various sources (ensure proper attribution)
- **Community**: For feedback and contributions

## 📞 Contact & Support

- **Website**: [BYAMN Festhub](https://byamn.vercel.app/)
- **Issues**: [GitHub Issues](https://github.com/yourusername/byamn-festhub/issues)
- **Feature Requests**: [GitHub Discussions](https://github.com/yourusername/byamn-festhub/discussions)

## 🔮 Roadmap

- [ ] Add more festivals (Diwali, Eid, Holi, etc.)
- [ ] Implement card customization (fonts, colors)
- [ ] Add card download functionality
- [ ] Create admin panel for easy content management
- [ ] Add user accounts and saved greetings
- [ ] Implement PWA features for offline access
- [ ] Add animation effects to greeting cards

---

**Made with ❤️ for spreading festival joy worldwide**

⭐ **Star this repository if you find it helpful!**