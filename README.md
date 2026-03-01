# Close - Static Website

This repository contains the static website for the Close iOS app, hosted at [close.matj.io](https://close.matj.io).

## About Close

Close is an iOS app that helps you maintain meaningful relationships by reminding you to stay in touch with friends, family, and colleagues. The app features:

- **Smart Scheduling**: Set custom contact frequencies (daily, weekly, monthly, or custom intervals)
- **Gentle Reminders**: Receive thoughtful notifications with quick actions to call, message, or mark as done
- **Seamless Integration**: Import contacts from your device and sync with existing contact lists
- **Visual Status**: Color-coded indicators show which relationships need attention
- **Personal Notes**: Add notes to remember important details about each contact
- **Privacy First**: All data stays on your device - no data collection or transmission

## Website Structure

```
/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── styles.css          # Main stylesheet
├── screenshots/        # App screenshots
│   ├── Simulator Screenshot - iPhone 17 Pro - 2025-10-22 at 18.48.36.png
│   ├── Simulator Screenshot - iPhone 17 Pro - 2025-10-22 at 18.49.55.png
│   ├── Simulator Screenshot - iPhone Air - 2025-10-22 at 18.59.46.png
│   └── Simulator Screenshot - iPhone Air - 2025-10-22 at 19.00.01.png
└── README.md           # This file
```

## Features

### Landing Page (`index.html`)
- Hero section with app description and call-to-action
- Features section highlighting key app capabilities
- Screenshots gallery showing app interface
- Download section with App Store link
- Responsive design for all device sizes

### Privacy Policy (`privacy.html`)
- Comprehensive privacy policy explaining data handling
- GDPR, CCPA, and COPPA compliance information
- Clear explanation of privacy-first approach
- Contact information for privacy inquiries

### Styling (`styles.css`)
- Modern, clean design with Inter font family
- Responsive grid layouts
- Smooth animations and hover effects
- Mobile-first responsive design
- Accessibility considerations

## Setup and Deployment

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/matjic/close.matj.io.git
   cd close.matj.io
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Visit `http://localhost:8000` to view the website

### Deployment

The website is designed to be deployed as a static site. You can deploy it to:

- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder or connect to Git repository
- **Vercel**: Connect to Git repository or upload files
- **Any static hosting service**: Upload files to any web server

### Customization

To customize the website:

1. **Update App Store Link**: Replace the placeholder download link in `index.html` with your actual App Store URL
2. **Modify Content**: Edit the text content in `index.html` and `privacy.html` to match your app's specific features
3. **Update Screenshots**: Replace the screenshots in the `screenshots/` directory with your own app screenshots
4. **Customize Styling**: Modify `styles.css` to match your brand colors and design preferences
5. **Update Contact Information**: Change email addresses and contact details in the privacy policy

## Privacy Policy

The privacy policy emphasizes Close's privacy-first approach:

- No data collection or transmission
- All data stored locally on device
- No third-party data sharing
- Compliance with GDPR, CCPA, and COPPA
- Clear explanation of device permissions

## Browser Support

The website is designed to work on all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This website is licensed under the same license as the Close app. See the `LICENSE` file for details.

## Contributing

If you find any issues or have suggestions for improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Contact

For questions about the website or the Close app:
- Website: [close.matj.io](https://close.matj.io)
- Privacy inquiries: privacy@close.matj.io

---

Built with ❤️ for maintaining meaningful relationships.
