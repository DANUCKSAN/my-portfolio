# Danucksan GSAP Three.js Portfolio Website

A modern **3D animated developer portfolio website** built with **React**, **Vite**, **Three.js**, **React Three Fiber**, **GSAP**, **Tailwind CSS**, and **EmailJS**.

This project showcases personal information, technical skills, selected projects, professional experience, and a working contact form inside a visually engaging 3D web experience.

## Overview

This portfolio website was created to present my frontend and full-stack development skills through an interactive and animated user interface.

The website uses **Three.js** and **React Three Fiber** to render 3D models and visual elements, while **GSAP** is used to create smooth animations. It also includes a responsive layout, project showcase section, work experience section, and an EmailJS-powered contact form.

## Features

* Modern 3D animated portfolio design
* Interactive hero section with 3D scene
* Three.js models rendered using React Three Fiber
* Smooth GSAP text and section animations
* Responsive design for desktop, tablet, and mobile
* About section with personal introduction and skills
* Selected projects showcase
* Interactive project navigation
* 3D computer preview for project display
* Work experience section with animated 3D developer model
* Contact form using EmailJS
* Success and error alert messages for form submission
* Footer with social media links
* Clean React component structure
* Fast development and build process using Vite

## Tech Stack

* React.js
* Vite
* JavaScript
* Three.js
* React Three Fiber
* React Three Drei
* GSAP
* Tailwind CSS
* EmailJS
* React Responsive
* Leva
* Maath
* ESLint
* Prettier

## Project Structure

```bash
danucksan-Gsap-threeJS-portfolio-website/
├── public/
│   ├── assets/
│   ├── models/
│   └── textures/
│
├── src/
│   ├── components/
│   │   ├── Alert.jsx
│   │   ├── Button.jsx
│   │   ├── Cube.jsx
│   │   ├── DemoComputer.jsx
│   │   ├── Developer.jsx
│   │   ├── HackerRoom.jsx
│   │   ├── HeroCamera.jsx
│   │   ├── Loading.jsx
│   │   ├── ReactLogo.jsx
│   │   ├── Rings.jsx
│   │   └── Target.jsx
│   │
│   ├── constants/
│   │   └── index.js
│   │
│   ├── hooks/
│   │   └── useAlert.js
│   │
│   ├── sections/
│   │   ├── About.jsx
│   │   ├── Contact.jsx
│   │   ├── Experience.jsx
│   │   ├── Foooter.jsx
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   └── Projects.jsx
│   │
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## Main Sections

### Navbar

The navigation bar includes links to the main sections of the portfolio:

* Home
* About
* Work
* Contact

It also includes a responsive mobile menu for smaller screens.

### Hero Section

The hero section introduces the portfolio owner with animated text and a 3D scene. It includes a 3D hacker room model, floating objects, React logo, cube, rings, and target elements.

### About Section

The about section highlights personal background, technical skills, passion for coding, and contact information.

### Projects Section

The projects section displays selected work with project details, technology tags, live-style previews, and navigation controls.

Featured projects include:

* CarePulse - Health Management System
* Zuno - Modern Video Conferencing Platform
* StoreIt - Storage Management System

### Experience Section

The experience section showcases professional experience with an interactive 3D developer model.

Experience includes:

* IT & Marketing Consultant at Electrifying Australia
* Software Developer at Mobitel Pvt Ltd
* Associate Software Developer Intern at Mobitel Pvt Ltd

### Contact Section

The contact section includes a working form powered by EmailJS. Users can send their name, email address, and message directly from the website.

### Footer

The footer includes copyright information and social media links.

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/DANUCKSAN/danucksan-Gsap-threeJS-portfolio-website.git
```

### 2. Navigate to the project folder

```bash
cd danucksan-Gsap-threeJS-portfolio-website
```

### 3. Install dependencies

```bash
npm install
```

### 4. Create an environment file

Create a `.env` file in the root directory and add your EmailJS credentials:

```env
VITE_APP_EMAILJS_SERVICE_ID=your_emailjs_service_id
VITE_APP_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
VITE_APP_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
```

### 5. Start the development server

```bash
npm run dev
```

The project will run locally at:

```bash
http://localhost:5173
```

## Available Scripts

### Start development server

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

### Run linting

```bash
npm run lint
```

## Environment Variables

| Variable                       | Description               |
| ------------------------------ | ------------------------- |
| `VITE_APP_EMAILJS_SERVICE_ID`  | EmailJS service ID        |
| `VITE_APP_EMAILJS_TEMPLATE_ID` | EmailJS email template ID |
| `VITE_APP_EMAILJS_PUBLIC_KEY`  | EmailJS public key        |

## 3D and Animation Features

This project uses Three.js and GSAP to create a modern animated portfolio experience.

Main animation and 3D features include:

* 3D hero scene
* Responsive 3D object positioning
* 3D developer model animations
* Floating 3D objects
* Project preview model
* Smooth GSAP text animation
* Interactive model behaviour on hover
* Canvas loading state
* Responsive 3D scaling for different screen sizes

## Contact Form

The contact form is integrated with EmailJS.

Form fields:

* Full name
* Email address
* Message

When the form is submitted successfully, a success alert is displayed. If the message fails, an error alert is shown.

## Deployment

This project can be deployed using platforms such as:

* Vercel
* Netlify
* GitHub Pages

### Build command

```bash
npm run build
```

### Output folder

```bash
dist
```

## Future Improvements

* Add more project case studies
* Add project live demo links
* Improve accessibility
* Add SEO metadata
* Add custom loading screen
* Add dark/light theme toggle
* Add blog section
* Add downloadable resume button
* Improve mobile 3D performance
* Add GitHub Actions deployment workflow

## Repository Description

A modern 3D animated developer portfolio website built with React, Vite, Three.js, React Three Fiber, GSAP, Tailwind CSS, and EmailJS.

## Topics

```txt
react
react18
vite
threejs
react-three-fiber
reactthreefiber
drei
gsap
tailwindcss
tailwind3
javascript
frontend
portfolio
portfolio-website
3d-website
web-animation
emailjs
responsive-design
developer-portfolio
vercel
```

## Author

**Danucksan Sathiyaraj**

GitHub: DANUCKSAN

## License

This project is open-source and available for learning, portfolio, and demonstration purposes.
