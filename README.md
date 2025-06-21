# Modern Portfolio Website

A unique and modern personal portfolio website built with HTML, CSS, and vanilla JavaScript. This portfolio features a minimalist yet visually stunning design with smooth animations and a fully responsive layout.

## Features

- **Light/Dark Theme Toggle**: Switch between light and dark themes with a smooth transition
- **Responsive Design**: Fully responsive layout that works on all devices
- **Smooth Animations**: Subtle animations enhance the user experience
- **Custom Cursor**: Interactive custom cursor that changes on hover
- **Project Filtering**: Filter projects by category
- **Blog Section**: Basic blog layout (no backend required)
- **Contact Form**: Working contact form using EmailJS
- **Downloadable Resume**: Option to download resume
- **Smooth Scrolling**: Smooth scroll between sections
- **SEO Optimized**: Meta tags and semantic HTML for better SEO

## Sections

1. **Home/Hero**: Introduction with animated text
2. **About Me**: Personal information and background
3. **Skills**: Technical skills with progress bars
4. **Projects**: Portfolio projects with filtering
5. **Resume**: Education and experience timeline with downloadable resume
6. **Blog**: Blog posts with individual article pages
7. **Contact**: Contact form with EmailJS integration

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript (no frameworks)
- EmailJS for contact form
- Font Awesome for icons

## Setup and Customization

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/portfolio-site.git
   ```

2. **Customize content**:
   - Replace placeholder text in `index.html` with your information
   - Update project details in the Projects section
   - Add your own blog posts in the blog directory
   - Replace images in the `assets/images` directory

3. **EmailJS Setup**:
   - Create an account at [EmailJS](https://www.emailjs.com/)
   - Create a new email service and template
   - Update the EmailJS configuration in `js/main.js`:
     ```javascript
     emailjs.init("YOUR_USER_ID");
     ```
   - Update the service and template IDs:
     ```javascript
     emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)
     ```

4. **Customize theme colors**:
   - Edit the CSS variables in `css/styles.css` to change the color scheme

## Deployment

This site is ready to be deployed on GitHub Pages:

1. Push your repository to GitHub
2. Go to repository settings
3. Navigate to the "Pages" section
4. Select the main branch as the source
5. Your site will be published at `https://yourusername.github.io/portfolio-site/`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- Fonts: [Google Fonts](https://fonts.google.com/)
- Icons: [Font Awesome](https://fontawesome.com/)
- Stock Images: [Unsplash](https://unsplash.com/)

---

Feel free to use this template for your personal portfolio. If you use it, I'd appreciate a credit link back to this repository.

Created with ❤️ by Kshitij Gawankar
