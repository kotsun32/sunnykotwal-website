# Deployment Options for sunnykotwal.com

## Option 1: Netlify (Recommended)
1. Create account at netlify.com
2. Drag & drop your website folder to Netlify
3. Update your domain DNS to point to Netlify:
   - A record: 75.2.60.5
   - CNAME: www to your-site.netlify.app

## Option 2: Vercel
1. Create account at vercel.com
2. Import your GitHub repo or upload files
3. Connect your custom domain

## Option 3: GitHub Pages
1. Create GitHub repo with your files
2. Enable GitHub Pages in repo settings
3. Update DNS to point to GitHub Pages

## Option 4: Keep Squarespace, Add Custom Sections
If you want to keep Squarespace:
1. Use Code Injection for custom CSS
2. Add Code Blocks for custom HTML sections
3. Recreate the design within Squarespace's framework

## DNS Configuration
For any option, you'll need to update DNS at your domain registrar:
- Point A record to new hosting provider
- Update CNAME for www subdomain