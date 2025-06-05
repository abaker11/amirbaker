# AB Web Solutions - Website Deployment Guide

## Deployment Options

This package contains two deployment options:

### Option 1: Multi-Page Website (Recommended)
All HTML files with CSS and JS embedded directly within each file. No external dependencies.

- `index.html` - Home page
- `services.html` - Services page
- `portfolio.html` - Portfolio page
- `projects.html` - Programming Projects page
- `about.html` - About page
- `pricing.html` - Pricing page
- `contact.html` - Contact page

### Option 2: Single-Page Version (Super Safe)
Everything combined into one HTML file with tabbed navigation.

- `ab_web_solutions_single_page.html` - Contains all pages in one file

## Deployment Instructions

### For Netlify:
1. Log in to Netlify
2. Click "Add new site" > "Deploy manually"
3. Drag and drop all the HTML files from this package
4. You're done! Your site will be live instantly

### For Vercel:
1. Log in to Vercel
2. Click "Add New Project" > "Import Project"
3. Select "Upload" and choose all the HTML files from this package
4. Click "Deploy"

### For custom domain setup:
1. In your domain provider (like Namecheap), set up these DNS records:
   - Type: A Record, Name: @, Value: Netlify/Vercel IP address
   - Type: CNAME, Name: www, Value: Your netlify/vercel subdomain

## Important Notes

- All styles and scripts are embedded directly in each HTML file
- All Calendly links should be updated to your actual Calendly URL
- Both deployment options are fully self-contained and will work on any hosting platform
- The multi-page version maintains proper URL structure, but the single-page version uses hash navigation

## Need Help?
Contact us for deployment assistance.
