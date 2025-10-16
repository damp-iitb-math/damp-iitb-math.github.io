# IITB Mathematics DAMP Website

A clean, modern website for the IIT Bombay Mathematics Department Academic Mentorship Programme (DAMP).

## Features

- **Course Reviews**: Browse detailed student reviews of mathematics courses
- **Team Section**: Meet the DAMP team members with photos and roles
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **GitHub Pages Ready**: Automatically deploys when pushed to main branch

## Deployment

This website is designed to be deployed on GitHub Pages:

1. Push your code to the `main` branch
2. Go to your repository settings
3. Navigate to Pages section
4. Set source to "GitHub Actions"
5. The site will automatically deploy at `https://yourusername.github.io/repository-name`

## Local Development

To run locally, simply open `index.html` in your browser. No build process required!

## Structure

- `index.html` - Main website file
- `style.css` - Custom styling
- `script.js` - JavaScript with embedded course review data
- `team/` - Team member photos
- `iitb_logo.png` - IIT Bombay logo
- `.github/workflows/` - GitHub Actions for automatic deployment

## Contributing

To add new course reviews, update the `courseReviews` array in `script.js`.
To add team members, add their photo to the `team/` folder and update the `teamMembers` array.

---

Built with ❤️ by the IITB Math DAMP Team

