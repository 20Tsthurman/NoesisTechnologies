# Noesis Technologies Website

A professional website for Noesis Technologies built with HTML, Tailwind CSS, and Netlify Forms.

## Phase 1: Getting Started

### Files Included
- `index.html` - Home page
- `services.html` - Services page with detailed offerings
- `about.html` - About page (update content as needed)
- `contact.html` - Contact page with working form
- `images/logo.png` - Your Noesis Technologies logo
- `README.md` - This file

### Local Testing
1. Open any HTML file in your browser to preview locally
2. Note: The contact form will only work once deployed to Netlify

## Deploying to Netlify (Phase 1 - Form Testing)

### Option 1: Drag and Drop (Easiest)
1. Go to [https://netlify.com](https://netlify.com) and create a free account
2. Once logged in, you'll see a drag-and-drop area
3. Drag the entire project folder into the upload area
4. Netlify will automatically deploy your site
5. You'll get a URL like `https://your-site-name.netlify.app`

### Option 2: GitHub Deploy (Recommended for Updates)
1. Create a GitHub repository
2. Push these files to your repository
3. Go to Netlify and click "Add new site" → "Import an existing project"
4. Connect your GitHub account
5. Select your repository
6. Click "Deploy site"

## Testing the Contact Form

Once deployed to Netlify:

1. Go to your live site URL
2. Navigate to the Contact page
3. Fill out and submit the form
4. Check your email - you should receive a notification from Netlify

### Setting Up Form Notifications

By default, Netlify will email you about form submissions. To customize:

1. Log into your Netlify dashboard
2. Go to your site
3. Click "Forms" in the left sidebar
4. You'll see your "contact" form
5. Click "Form notifications" to customize email settings

## Next Steps (Phase 2)

After confirming the form works:

- [ ] Add your professional photo to `/images/profile.jpg`
- [ ] Update About page content with your specific background
- [ ] Add any portfolio items or case studies
- [ ] Customize color scheme if desired
- [ ] Add Google Analytics (optional)
- [ ] Set up a custom domain (optional)

## File Structure

```
noesis-website/
├── index.html              # Home page
├── services.html           # Services page
├── about.html              # About page
├── contact.html            # Contact form page
├── images/
│   ├── logo.png           # Your logo
│   └── profile.jpg        # Your photo (add this later)
└── README.md              # This file
```

## Customization Notes

### Colors
The site uses your brand colors:
- Primary Blue: `#0F4C75`
- Light Blue: `#3282B8`
- Accent: `#BBE1FA`

### Content Updates
- All content is in plain HTML - easy to edit
- Search for specific text to find and update it
- Use Ctrl+F (or Cmd+F on Mac) to find content quickly

### Adding Your Photo
1. Save your professional photo as `profile.jpg`
2. Place it in the `images/` folder
3. The About page is already set up to use it

## Support

If you have issues:
- Netlify form not working? Make sure `data-netlify="true"` is in the form tag
- Images not showing? Check that file paths are correct (case-sensitive!)
- Need to make changes? Edit the HTML files and re-deploy

## Technical Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript (for mobile menu)
- Netlify Forms (for contact form)

---

Built with care by Noesis Technologies 🚀
