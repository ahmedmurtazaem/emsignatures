# Ahmed Murtaza - Email Signature

A professional email signature design implemented from Figma specifications, featuring modern typography, clean layout, and responsive design.

## 🎨 Design Features

- **Modern Typography**: Uses Overused Grotesk font family for professional appearance
- **Responsive Design**: Optimized for both desktop and mobile email clients
- **Clean Layout**: Structured with header, info section, and footer
- **Social Media Integration**: Includes clickable social media icons
- **Professional Branding**: Custom EM logo and backdrop design

## 📁 Project Structure

```
EmailSignature/
├── index.html              # Main signature HTML
├── style.css               # Styling and responsive design
├── assets/                 # Image assets
│   ├── em-logo.svg         # EM Logo
│   ├── DeviceMobileCamera.svg
│   ├── Phone.svg
│   ├── PaperPlaneTilt.svg
│   ├── GlobeSimple.svg
│   ├── House.svg
│   ├── FacebookLogo.svg
│   ├── InstagramLogo.svg
│   ├── XLogo.svg
│   └── LinkedinLogo.svg
├── fonts/                  # Font files (to be uploaded)
│   └── README.md          # Font installation guide
└── README.md              # This file
```

## 🚀 Quick Start

### Option 1: Direct Use
1. Open `index.html` in your browser to preview
2. Copy the HTML content for use in email clients

### Option 2: Local Development
1. Clone or download this repository
2. Upload Overused Grotesk font files to the `fonts/` folder (see `fonts/README.md`)
3. Open `index.html` in your browser
4. Start a local server: `python3 -m http.server 8000`

## 📧 Email Client Compatibility

This signature is tested and compatible with:
- ✅ Gmail
- ✅ Outlook (Desktop & Web)
- ✅ Apple Mail
- ✅ Thunderbird
- ✅ Mobile Email Apps (iOS, Android)

## 🔧 Customization

### Personal Information
Edit these values in `index.html`:
```html
<h1 class="name">Ahmed Murtaza</h1>
<p class="title">Design @ Epicmetry</p>
```

### Contact Details
Update contact information:
```html
<span>+971 50 515 2813</span>
<span>+971 4 876 9396</span>
<span>a.murtaza@epicmetry.com</span>
<span>www.epicmetry.com</span>
<span>9W, 9WC, Dubai Airport Freezone, Dubai, UAE</span>
```

### Social Media Links
Add actual URLs to social icons:
```html
<a href="https://facebook.com/yourpage">
  <img src="assets/FacebookLogo.svg" alt="Facebook" class="social-icon">
</a>
```

## 🎯 Design Specifications

- **Dimensions**: 451x315px
- **Colors**: Dark gradient background with white text
- **Typography**: Overused Grotesk (Regular: 400, Book: 300)
- **Icons**: Custom SVG assets for optimal scaling
- **Responsive**: Adapts to mobile screens

## 📱 Mobile Optimization

The signature includes responsive breakpoints:
- **Desktop**: Full 451px width
- **Mobile**: Scales to screen width with adjusted font sizes

## 🔒 Font Requirements

To display correctly, upload these font files to `fonts/`:
- `OverusedGrotesk-Regular.woff2`
- `OverusedGrotesk-Regular.woff`
- `OverusedGrotesk-Book.woff2`
- `OverusedGrotesk-Book.woff`

*Note: Ensure you have proper licensing for Overused Grotesk font usage.*

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License

This email signature design is for demonstration purposes. Ensure you have appropriate licenses for:
- Overused Grotesk font family
- Any custom imagery used
- Brand assets

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

For questions about this email signature implementation, please open an issue in the repository.

---

**Designed with ❤️ for Epicmetry**
