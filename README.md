# Bharathi S - Portfolio

Modern, clean, and responsive single-page portfolio website.

## 🚀 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations** - AOS (Animate On Scroll) library for elegant scroll animations
- **Clean UI** - Modern design with pastel gradients and soft shadows
- **Interactive Navigation** - Sticky navbar with active section highlighting
- **Contact Form** - Functional contact form with validation
- **Professional Sections**:
  - Hero/Home
  - About & Education
  - Internship Experience
  - Projects
  - Skills
  - Certifications
  - Research Works
  - Achievements
  - Contact

## 📁 Project Structure

```
Bharathi-portfolio/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── main.js             # JavaScript functionality
├── assets/
│   └── images/         # Folder for profile image and icons
└── README.md           # This file
```

## 🎨 Color Palette

- **Primary Accent**: `#6C63FF`
- **Background**: `#F8F9FC`
- **Text Primary**: `#1F1F1F`
- **Text Secondary**: `#6B7280`
- **White**: `#FFFFFF`

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins)
- AOS.js (Animate On Scroll)

## 📦 Setup & Deployment

### Local Development

1. Clone or download the repository
2. Open `index.html` in your browser
3. No build process required!

### GitHub Pages Deployment

1. Push the code to your GitHub repository
2. Go to repository Settings → Pages
3. Select the main branch as the source
4. Your site will be live at `https://bharathis28.github.io/Bharathi-portfolio/`

### Adding Your Resume

1. Add your resume PDF to the `assets` folder
2. Update the download link in `main.js`:
   ```javascript
   const link = document.createElement('a');
   link.href = 'assets/Bharathi_S_Resume.pdf';
   link.download = 'Bharathi_S_Resume.pdf';
   link.click();
   ```

### Adding Profile Image

1. Add your profile image to `assets/images/`
2. Replace the icon in `index.html` with:
   ```html
   <div class="profile-circle">
       <img src="assets/images/profile.jpg" alt="Bharathi S">
   </div>
   ```
3. Add this CSS to `style.css`:
   ```css
   .profile-circle img {
       width: 100%;
       height: 100%;
       object-fit: cover;
       border-radius: 50%;
   }
   ```

## 📧 Contact Form Integration

The contact form currently shows an alert. To make it functional:

### Option 1: FormSpree
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: EmailJS
1. Sign up at emailjs.com
2. Add EmailJS SDK to `index.html`
3. Update form handler in `main.js`

### Option 3: Netlify Forms
Add `netlify` attribute to the form tag

## 🎯 Customization

### Changing Colors
Update CSS variables in `style.css`:
```css
:root {
    --primary-color: #6C63FF;
    --background: #F8F9FC;
    --text-primary: #1F1F1F;
}
```

### Adding New Sections
1. Add section HTML in `index.html`
2. Add navigation link in navbar
3. Style the section in `style.css`
4. Update smooth scrolling in `main.js`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available for personal use.

## 👤 Author

**Bharathi S**
- Email: bharathi.ece2023@citchennai.net
- LinkedIn: [bharathisenthilkumar28](https://www.linkedin.com/in/bharathisenthilkumar28)
- GitHub: [bharathiS28](https://github.com/bharathiS28)

---

Built with ❤️ by Bharathi S
