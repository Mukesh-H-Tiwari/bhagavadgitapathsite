# Bhagavad Gita Path - Website

This is the landing page and privacy policy website for the Bhagavad Gita Path mobile app.

## Files

- `index.html` - Main landing page
- `privacy.html` - Privacy Policy and Terms of Service page
- `style.css` - Stylesheet for both pages

## Features

### Landing Page (index.html)
- Hero section with app description
- Features showcase (8 key features)
- About the Bhagavad Gita section
- Download section (Google Play)
- Contact information
- Responsive design for mobile and desktop

### Privacy Policy Page (privacy.html)
- Complete privacy policy
- AdMob advertising disclosure
- Data collection and usage information
- User rights and choices
- Terms of Service
- Contact information
- GDPR, CCPA, and COPPA compliance

## Deployment

### Option 1: GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload these files to the repository
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at: `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop the `website` folder
3. Your site will be live instantly with a custom URL

### Option 3: Vercel (Free)
1. Sign up at [vercel.com](https://vercel.com)
2. Import the repository or upload files
3. Deploy with one click

### Option 4: Firebase Hosting (Free)
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase init hosting`
4. Deploy: `firebase deploy`

## Customization

### Update Google Play Link
In `index.html`, replace the `#` in the download button with your actual Google Play Store link:
```html
<a href="YOUR_PLAY_STORE_LINK_HERE" class="store-button">
```

### Add App Screenshots
Replace the phone mockup placeholder with actual app screenshots:
1. Add screenshot images to the website folder
2. Update the `.phone-screen` section in `index.html`

### Update Contact Email
The email `bytrcode.creation@gmail.com` is already included throughout the site.

## Privacy Policy URL

Once deployed, use your privacy policy URL in:
1. Google Play Console (Store Listing → Privacy Policy)
2. App's Settings screen
3. AdMob account settings

Example URLs:
- GitHub Pages: `https://yourusername.github.io/bhagavad-gita-path/privacy.html`
- Netlify: `https://your-site-name.netlify.app/privacy.html`
- Custom Domain: `https://yourdomain.com/privacy.html`

## Mobile Responsive

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## SEO Optimized

- Meta descriptions included
- Semantic HTML structure
- Fast loading times
- Mobile-friendly design

## Contact

For questions about the website:
- Email: bytrcode.creation@gmail.com

---

**Note:** Remember to update the Google Play Store link once your app is published!
