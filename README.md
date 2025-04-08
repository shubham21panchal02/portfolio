# Modern Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, JavaScript, and Node.js. Features smooth animations, a contact form, and a clean, professional design.

## Features

- Responsive design that works on all devices
- Smooth scroll animations using AOS (Animate On Scroll)
- Interactive navigation with active section highlighting
- Contact form with email functionality
- Modern UI with hover effects and transitions
- Mobile-friendly navigation menu
- Scroll to top button
- Project showcase section
- Skills section with icons
- Social media links

## Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/portfolio-website.git
cd portfolio-website
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your email credentials:
```
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-specific-password
```

Note: For Gmail, you'll need to use an App Password. You can generate one in your Google Account settings under Security > 2-Step Verification > App passwords.

## Running the Application

1. Start the development server:
```bash
npm run dev
```

2. Open your browser and navigate to:
```
http://localhost:3000
```

## Project Structure

```
portfolio-website/
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   ├── images/
│   └── index.html
├── server.js
├── package.json
├── .env
└── README.md
```

## Customization

1. Update your personal information in `public/index.html`
2. Add your projects in the projects section
3. Modify the skills section to showcase your expertise
4. Update social media links
5. Customize colors in `public/css/style.css` by modifying the CSS variables in the `:root` selector

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Node.js
- Express.js
- Nodemailer
- AOS (Animate On Scroll)
- Font Awesome Icons

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- AOS (Animate On Scroll) library
- Font Awesome for icons
- Google Fonts 