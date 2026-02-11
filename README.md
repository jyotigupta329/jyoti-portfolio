# Jyoti Kumari - Portfolio Website

Professional portfolio website showcasing 9 years of Full Stack Development experience.

## 🚀 Live Demo

Your portfolio will be live at: `https://[your-github-username].github.io/jyoti-portfolio`

## 📦 Hosting Instructions

### Option 1: GitHub Pages (Recommended - FREE)

1. **Create a GitHub Account** (if you don't have one)
   - Go to [github.com](https://github.com)
   - Sign up for free

2. **Create a New Repository**
   - Click the "+" icon in the top right
   - Select "New repository"
   - Name it: `jyoti-portfolio`
   - Make it **Public**
   - Click "Create repository"

3. **Upload Your Files**

   **Method A: Using GitHub Website (Easiest)**
   - Click "uploading an existing file"
   - Drag and drop `portfolio.html`
   - Add your resume PDF (if you have one)
   - Click "Commit changes"

   **Method B: Using Command Line**

   ```bash
   cd /Users/jyotikumari/Documents/jyoti-portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/[your-username]/jyoti-portfolio.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll to "Pages" section (left sidebar)
   - Under "Source", select "main" branch
   - Select "/ (root)" folder
   - Click "Save"

5. **Rename portfolio.html to index.html**
   - In your repository, click on `portfolio.html`
   - Click the pencil icon (Edit)
   - Change filename to `index.html`
   - Commit changes

6. **Access Your Live Portfolio**
   - Wait 2-3 minutes for deployment
   - Visit: `https://[your-username].github.io/jyoti-portfolio`
   - Your portfolio is now live! 🎉

### Option 2: Netlify (FREE)

1. Go to [netlify.com](https://netlify.com)
2. Sign up with GitHub
3. Drag and drop your folder
4. Your site will be live instantly!
5. You can customize the URL

### Option 3: Vercel (FREE)

1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your repository
4. Deploy automatically

## 📝 Adding Your Resume

1. Save your resume as `resume.pdf`
2. Place it in the same folder as `portfolio.html`
3. Open `portfolio.html` in a text editor
4. Find both instances of:
   ```html
   href="#"
   ```
   (in the Download Resume buttons)
5. Replace with:
   ```html
   href="resume.pdf"
   ```
6. Upload the updated files

## 🎨 Customization

### Update Contact Information

All contact details are in the HTML file. Search for:

- Email: `jyoti.gupta329@gmail.com`
- Phone: `+1-512-669-1332`
- LinkedIn: `linkedin.com/in/jyotigupta329`

### Change Colors

Look for these color codes in the CSS:

- Primary Blue: `#3b82f6`
- Secondary Purple: `#8b5cf6`
- Dark Navy: `#0f172a`

### Add More Projects

Add new timeline items in the Experience section following the existing structure.

## 🌐 Custom Domain (Optional)

### For GitHub Pages:

1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In repository settings → Pages → Custom domain
3. Enter your domain name
4. Configure DNS settings with your domain provider

### DNS Configuration:

Add these records:

```
Type: A
Host: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153

Type: CNAME
Host: www
Value: [your-username].github.io
```

## 📱 Features

✅ Fully responsive (mobile, tablet, desktop)
✅ Smooth scrolling navigation
✅ Scroll animations with Intersection Observer
✅ Professional blue/purple gradient theme
✅ Single-page application
✅ Download resume functionality
✅ Interactive timeline
✅ Skills categorization
✅ Contact information
✅ Professional statistics display

## 🔧 Technologies Used

- HTML5
- CSS3 (with animations)
- JavaScript (ES6)
- Font Awesome Icons
- Google Fonts (Poppins)

## 📞 Support

If you need help:

1. Check GitHub Pages documentation: [pages.github.com](https://pages.github.com)
2. Ensure `index.html` is in the root directory
3. Make sure repository is public
4. Wait a few minutes after enabling Pages

## 📄 License

© 2026 Jyoti Kumari. All rights reserved.

---

**Made with ❤️ using HTML, CSS, and JavaScript**
