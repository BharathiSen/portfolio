# Assets Folder

This folder contains images and other media assets for the portfolio website.

## 📁 Recommended Structure

```
assets/
├── images/
│   ├── profile.jpg          # Your profile picture
│   ├── favicon.ico          # Website favicon
│   └── projects/            # Project screenshots (optional)
└── Bharathi_S_Resume.pdf    # Your resume file
```

## 📝 Instructions

### Adding Your Profile Picture

1. Add a professional profile picture to `assets/images/` (recommended: square format, 500x500px or larger)
2. Name it `profile.jpg` or `profile.png`
3. Update the HTML in `index.html`:
   - Find the `.profile-circle` div in the hero section
   - Replace the `<i>` icon with `<img src="assets/images/profile.jpg" alt="Bharathi S">`
4. Add this CSS to `style.css`:
   ```css
   .profile-circle img {
       width: 100%;
       height: 100%;
       object-fit: cover;
       border-radius: 50%;
   }
   ```

### Adding Your Resume

1. Export your resume as a PDF
2. Name it `Bharathi_S_Resume.pdf`
3. Place it in the `assets` folder
4. The download button in `main.js` is already configured to use this file

### Adding a Favicon

1. Create or generate a favicon (16x16 or 32x32px)
2. Save it as `favicon.ico` in the `assets` folder
3. Add this line in the `<head>` section of `index.html`:
   ```html
   <link rel="icon" type="image/x-icon" href="assets/favicon.ico">
   ```

### Optional: Project Screenshots

1. Create a `projects` subfolder inside `assets/images/`
2. Add screenshots of your projects
3. Reference them in your project cards

## ✨ Tips

- **Image Optimization**: Compress images before uploading (use tools like TinyPNG)
- **Formats**: Use JPG for photos, PNG for graphics with transparency
- **File Names**: Use lowercase and hyphens (e.g., `profile-picture.jpg`)
- **Alt Text**: Always add descriptive alt text for accessibility

---

**Note**: This is a placeholder file. The actual assets will be added by you.
