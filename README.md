# ThermaSesh Marketing Website

A modern, responsive marketing website for the ThermaSesh app - the ultimate thermal therapy companion for Apple Watch and iPhone.

## 🚀 Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Performance Optimized**: Fast loading with lazy loading and optimized assets
- **Accessibility**: Semantic HTML and keyboard navigation support
- **SEO Ready**: Meta tags, Open Graph, and semantic structure

## 📁 Project Structure

```
website/
├── index.html          # Main landing page
├── css/
│   └── styles.css     # All styling and responsive design
├── js/
│   └── script.js      # Interactive functionality
├── images/            # Website images and assets
├── assets/            # Additional assets
└── README.md          # This file
```

## 🧪 Testing Instructions

### Local Testing

1. **Navigate to the website directory:**
   ```bash
   cd website/
   ```

2. **Start a local server:**
   
   **Option A - Using Python (if installed):**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   
   **Option B - Using Node.js (if installed):**
   ```bash
   npx http-server -p 8000
   ```
   
   **Option C - Using PHP (if installed):**
   ```bash
   php -S localhost:8000
   ```

3. **Open your browser and go to:**
   ```
   http://localhost:8000
   ```

### What to Test

#### 🖥️ Desktop Testing
- [ ] Navigation menu works properly
- [ ] All sections load and display correctly
- [ ] Smooth scrolling between sections
- [ ] Hero animations and gradient effects
- [ ] Feature cards hover effects
- [ ] Screenshot gallery interactions
- [ ] Download buttons functionality
- [ ] Footer links work

#### 📱 Mobile Testing
- [ ] Hamburger menu opens/closes correctly
- [ ] All content is readable on small screens
- [ ] Touch interactions work smoothly
- [ ] Images and layouts adapt properly
- [ ] No horizontal scrolling issues
- [ ] Buttons are easily tappable

#### 🎨 Visual Testing
- [ ] Fonts load correctly (Inter font family)
- [ ] Gradients and colors display properly
- [ ] Images appear sharp on retina displays
- [ ] Animations are smooth (60fps)
- [ ] No layout shifts during loading
- [ ] Consistent spacing and alignment

#### ⚡ Performance Testing
- [ ] Page loads quickly (< 3 seconds)
- [ ] Smooth scrolling performance
- [ ] No JavaScript errors in console
- [ ] Images load progressively
- [ ] Animations don't cause lag

### Browser Compatibility

Test in the following browsers:

- **Desktop:**
  - [ ] Chrome (latest)
  - [ ] Firefox (latest)
  - [ ] Safari (latest)
  - [ ] Edge (latest)

- **Mobile:**
  - [ ] iOS Safari
  - [ ] Chrome Mobile
  - [ ] Samsung Internet

### Responsive Breakpoints

Test these specific screen sizes:

- [ ] **Desktop**: 1920px, 1440px, 1024px
- [ ] **Tablet**: 768px, 834px (iPad)
- [ ] **Mobile**: 375px (iPhone), 414px (iPhone Plus), 360px (Android)

## 🔧 Customization

### Adding Images

Replace placeholder images in the `images/` folder:

- `logo.png` - App logo (32x32px for nav, higher res for other uses)
- `watch-screenshot.png` - Apple Watch app screenshot
- `phone-screenshot.png` - iPhone app screenshot
- `screenshot-1.png` to `screenshot-4.png` - App screenshots for gallery
- `app-store-badge.svg` - Official App Store download badge

### Updating Content

1. **App Store Link**: Update the download link in `index.html`:
   ```html
   <a href="https://apps.apple.com/app/thermasesh/id6447648037">
   ```

2. **Contact Information**: Update email addresses and social links in the footer

3. **Analytics**: Add Google Analytics or other tracking codes before `</head>`

### Color Scheme

The website uses a blue gradient theme. Main colors:
- Primary Blue: `#007AFF`
- Secondary Purple: `#5856D6`
- Text Dark: `#1a1a1a`
- Text Light: `#666`
- Background: `#fafafa`

## 🚀 Deployment

### GitHub Pages
1. Push the website to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main` or `marketing-website`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty)
3. Set publish directory: `website`
4. Deploy automatically on push

### Vercel
1. Import your GitHub repository
2. Set framework preset: "Other"
3. Set root directory: `website`
4. Deploy

## 📈 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Twitter Card support
- Alt tags for all images
- Proper heading hierarchy (H1 → H6)

## 🔒 Security

- No external dependencies (except Google Fonts)
- No user data collection
- Safe external links (`rel="noopener"`)
- Content Security Policy ready

## 📞 Support

If you encounter any issues:

1. Check browser console for JavaScript errors
2. Verify all image paths are correct
3. Ensure you're running a local server (not opening file directly)
4. Test in different browsers
5. Check responsive design in browser dev tools

## 🎯 Next Steps

Consider adding:
- [ ] Contact form with backend integration
- [ ] Blog/news section
- [ ] User testimonials with photos
- [ ] App usage statistics/metrics
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Newsletter signup
- [ ] Live chat widget

---

Made with ❤️ for ThermaSesh users