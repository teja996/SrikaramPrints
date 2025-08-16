# Deployment Guide

## GitHub Pages (Recommended)

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it: `custom-prints-website`
4. Make it **Public** (required for free GitHub Pages)
5. Click "Create repository"

### Step 2: Upload Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop all project files:
   - `index.html`
   - `script.js`
   - `README.md`
   - Any images (optional)
3. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Scroll down to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose branch: `main` (or `master`)
5. Click "Save"
6. Wait 2-5 minutes for deployment

### Step 4: Access Your Site
Your website will be available at:
`https://yourusername.github.io/custom-prints-website`

## Alternative Hosting Options

### Netlify (Drag & Drop)
1. Go to [Netlify.com](https://netlify.com)
2. Sign up/Login
3. Drag your project folder to the deploy area
4. Your site is live instantly!

### Vercel
1. Go to [Vercel.com](https://vercel.com)
2. Connect your GitHub account
3. Import your repository
4. Deploy automatically

### Traditional Web Hosting
1. Upload files via FTP/SFTP
2. Point domain to hosting provider
3. Site is live!

## Custom Domain Setup

### GitHub Pages with Custom Domain
1. In repository Settings → Pages
2. Add your domain in "Custom domain" field
3. Create CNAME record pointing to `yourusername.github.io`
4. Wait for DNS propagation (up to 48 hours)

### Netlify with Custom Domain
1. In Netlify dashboard, go to Domain settings
2. Add custom domain
3. Update DNS records as instructed
4. SSL certificate provided automatically

## Post-Deployment Checklist

- [ ] Test website on different devices
- [ ] Check all links work correctly
- [ ] Verify contact form functionality
- [ ] Test social media links
- [ ] Update business contact information
- [ ] Add Google Analytics (optional)
- [ ] Submit to search engines

## Troubleshooting

### GitHub Pages Not Working?
- Ensure repository is **public**
- Check branch name (main vs master)
- Wait 5-10 minutes for deployment
- Check repository Settings → Pages for status

### Images Not Loading?
- Use relative paths: `images/photo.jpg`
- Check file names match exactly
- Ensure images are uploaded to repository

### Contact Form Issues?
- Form shows success message but doesn't send emails
- To make functional, integrate with:
  - Formspree
  - Netlify Forms
  - Your own backend

## Performance Tips

1. **Optimize Images**: Compress before uploading
2. **Minimize Files**: Remove unused code
3. **Use CDN**: Tailwind and Font Awesome already use CDN
4. **Test Speed**: Use Google PageSpeed Insights

## Security Considerations

- Keep repository public for GitHub Pages
- Don't include sensitive information in code
- Use environment variables for API keys (if adding backend)
- Regularly update dependencies

---

**Need Help?** Check the main README.md for detailed customization instructions.
