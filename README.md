# Portfolio Website
<div align="center">
  <pre>
   _    _
  | |  | |
  | |__| | __ _ ___ ___  __ _ _ __
  |  __  |/ _` / __/ __|/ _` | '_ \
  | |  | | (_| \__ \__ \ (_| | | | |
  |_|  |_|\__,_|___/___/\__,_|_| |_|
  </pre>
</div>


Welcome to my **portfolio website**! This site showcases my skills, experience, education, projects, and how to get in touch with me. Built with **React** and **Vite** for a fast, modern web experience, featuring a physics-based 3D lanyard card, smooth animations, and a fully responsive layout.

---

## Live Preview

Check out the live preview of the portfolio website here:
[**Live Demo**](https://ezzouhir-hassan.vercel.app/)

---

### 🎯 Project Structure
```bash
portofolio/
├── public/
│   └── assets/
│       ├── proyek/         # Project screenshots
│       ├── tools/          # Technology icons
│       ├── card.glb        # 3D card model
│       ├── lanyard.png     # Lanyard texture
│       ├── me.png          # Profile photo
│       └── CV.pdf          # Downloadable CV
├── src/
│   ├── components/
│   │   ├── Aurora/         # Animated background
│   │   ├── BlurText/       # Blur reveal text animation
│   │   ├── ChromaGrid/     # Project grid with hover effect
│   │   ├── CountUp/        # Animated number counter
│   │   ├── Dock/           # macOS-style navigation dock
│   │   ├── GlassIcons/     # Glassmorphism icon cards
│   │   ├── Lanyard/        # Physics-based 3D lanyard card
│   │   ├── PreLoader/      # Page preloader
│   │   ├── ProfileCard/    # Interactive tilt profile card
│   │   ├── ProjectModal/   # Project detail modal
│   │   ├── ScrambledText/  # Text scramble animation
│   │   ├── ScrollReveal/   # Scroll-triggered reveal
│   │   ├── ShinyText/      # Shiny shimmer text effect
│   │   ├── SplitText/      # Split character animation
│   │   ├── Footer.jsx      # Footer with social links & dock
│   │   └── Navbar.jsx      # Navigation bar
│   ├── data.js             # Tools & projects data
│   ├── firebase.js         # Firebase config
│   ├── App.jsx             # Main app component
│   └── main.jsx            # Entry point
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```
---

## Sections of the Portfolio

The portfolio website consists of the following sections:

- **Hero**: Introduction with name, title, animated text, and profile card.
- **About**: Bio, stats, and the interactive 3D lanyard card.
- **Tools & Technologies**: Grid of skills and technologies I work with.
- **Projects**: ChromaGrid showcase of featured projects with modal detail view.
- **Contact**: Contact form powered by FormSubmit delivering directly to my email.

---

## 💻 Technologies Used
- **Frontend:** React 19 with Vite
- **Styling:** Tailwind CSS
- **3D / Physics:** React Three Fiber, React Three Drei, Rapier
- **Animations:** GSAP, AOS, Animate.css, Motion
- **Icons:** React Icons, Remixicon
- **Form:** FormSubmit.co
- **Deployment:** Vercel

---

## Installation ⬇️

You will need to download **Git** and **Node** to run this project.

### Git

- Download and install Git from the official website: [Git Downloads](https://git-scm.com/)
- Verify the installation:
  ```bash
  git --version
  ```

### Node

- Download and install Node.js from the official website: [Node.js Downloads](https://nodejs.org/)
- Make sure you have the latest version of both Git and Node on your computer.
- Verify the installation:
  ```bash
  node --version
  ```

# Getting Started 🎯

### Fork and Clone the Repository 🚀
1. Click the **Fork** button at the top-right corner of the page to create your own copy of the repository.
2. After forking, open your terminal and run the following commands to clone the repo:

  ```bash
  git clone https://github.com/Hassanezz11/portfolio.git
  ```
Navigate to the Project Directory 📂
Once the repository is cloned, change your directory to the project folder:
```bash
cd portofolio
```

Install Dependencies ⚙️
From the root directory of your project, install the necessary packages:
```bash
npm install
```

Run the Development Server 🚀
Start the development server to see your project live:
```bash
npm run dev
```

View the Project 🌐
Open your browser and visit http://localhost:5173/ to see the result! 🎉

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

### 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<div align="center"> Made with ❤️ by Hassan Ezzouhir </div>
