# x1nk3r Portfolio Website

A modern, responsive portfolio website for full-stack developer x1nk3r with neon purple theme and dark/light mode toggle.

## Features

- Responsive design (mobile, tablet, desktop)
- Dark/light mode toggle with system preference detection
- Animated elements on scroll
- Contact form with simulated backend
- Modern Gen Z aesthetic with neon purple theme
- Project showcase with hover effects
- Skills section with categorized technologies

## Technologies Used

- HTML5, CSS3, JavaScript
- Express.js (for backend)
- Nodemailer (for contact form)
- Font Awesome icons
- Netlify for hosting

## Setup Instructions

1. Clone this repository
2. Install dependencies: `cd server && npm install`
3. Start development server: `npm run dev`
4. Open `http://localhost:3000` in your browser

## Deployment to Netlify

1. Push your code to a GitHub repository
2. Log in to Netlify and select "New site from Git"
3. Choose your repository and configure settings:
   - Build command: `npm install && npm run build`
   - Publish directory: `/`
4. Add environment variables for email (if using contact form):
   - `EMAIL_USER`: Your Gmail address
   - `EMAIL_PASS`: Your Gmail app password
5. Deploy!

## Customization

- Replace placeholder images in `assets/images/`
- Update project details in `index.html`
- Modify color scheme in CSS variables
- Add/remove skills as needed

## License

MIT License - feel free to use and modify for your own portfolio!