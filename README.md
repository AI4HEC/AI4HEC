# AI4HEC - Official Website

![AI4HEC Banner](https://img.shields.io/badge/AI4HEC-Human--Elephant%20Coexistence-blue)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Enabled-success)

Welcome to the official repository for the **AI4HEC** (AI for Human-Elephant Coexistence) organization website. This is a static landing page hosted on GitHub Pages.

## 🌐 Live Website

Once deployed, this site will be available at: **https://ai4hec.github.io**

## 📋 About This Repository

This repository contains the source code for AI4HEC's public-facing website. AI4HEC is a research initiative at the University of Peradeniya focused on developing AI-based solutions to mitigate human-elephant conflict through:

- 🤖 Artificial Intelligence & Machine Learning
- 🔧 Embedded Systems & IoT
- 🦾 Robotics & Automation
- 🔊 Directional Audio Systems

## 🚀 Quick Start - Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. **Push this code to GitHub** (if not already done):
   ```bash
   git add .
   git commit -m "Initial commit: AI4HEC website"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub
   - Navigate to **Settings > Pages**
   - Under "Source", select **Deploy from a branch**
   - Choose the `main` branch and `/ (root)` folder
   - Click **Save**

3. **Wait a few minutes** for GitHub to build and deploy your site
   - Your site will be live at `https://ai4hec.github.io` (or `https://[username].github.io/[repo-name]` for project pages)

## 📁 Repository Structure

```
AI4HEC/
├── index.html          # Main landing page
├── style.css           # Custom CSS styles
├── assets/             # Static assets (images, icons)
│   └── .gitkeep
├── README.md           # This file
└── LICENSE             # Project license
```

## ✏️ Editing the Website

### Adding a New Project

1. Open `index.html`
2. Find the **Projects Section** (around line 90)
3. Copy an existing project card
4. Update the following:
   ```html
   <div class="project-card bg-gray-800 rounded-lg p-6 hover:bg-gray-700 transition duration-300">
       <a href="https://github.com/AI4HEC/YOUR-REPO" target="_blank" class="block">
           <div class="flex items-center mb-4">
               <i class="fas fa-icon-name text-3xl text-blue-500 mr-3"></i>
               <h3 class="text-xl font-semibold">repository-name</h3>
           </div>
           <p class="text-gray-400">Brief description of the project.</p>
           <div class="mt-4 text-blue-400 hover:text-blue-300">
               View Repository <i class="fas fa-arrow-right ml-2"></i>
           </div>
       </a>
   </div>
   ```

### Adding a Team Member

1. Open `index.html`
2. Find the **Team Section** (around line 150)
3. Copy an existing team card
4. Update the member's information:
   ```html
   <div class="team-card bg-gray-900 rounded-lg p-6 text-center hover:shadow-xl transition duration-300">
       <div class="w-32 h-32 mx-auto mb-4 bg-gray-700 rounded-full flex items-center justify-center">
           <img src="assets/team/member-name.jpg" alt="Member Name" class="rounded-full w-full h-full object-cover">
       </div>
       <h3 class="text-xl font-semibold mb-2">Member Name</h3>
       <p class="text-gray-400">Role/Title</p>
   </div>
   ```

### Updating the About Section

1. Open `index.html`
2. Find the **About Section** (around line 40)
3. Edit the paragraph text to update the mission statement

### Changing Colors/Styles

The site uses Tailwind CSS utility classes. Common customizations:

- **Background colors**: Change `bg-gray-900`, `bg-blue-600`, etc.
- **Text colors**: Change `text-gray-100`, `text-blue-400`, etc.
- **Hover effects**: Modify `hover:bg-gray-700`, `hover:text-blue-300`, etc.

For deeper customization, edit `style.css`.

## 🎨 Design Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Dark theme with gradient header
- ✅ Smooth scrolling and hover animations
- ✅ No build process required (pure HTML/CSS/JS)
- ✅ Uses Tailwind CSS via CDN
- ✅ Font Awesome icons included

## 📦 Adding Images/Assets

1. Add your images to the `assets/` folder (create subfolders like `assets/images/` if needed)
2. Reference them in HTML:
   ```html
   <img src="assets/images/your-image.jpg" alt="Description">
   ```

### Adding a Logo/Favicon

1. Place your logo in `assets/icons/`
2. Add to the `<head>` section of `index.html`:
   ```html
   <link rel="icon" type="image/png" href="assets/icons/favicon.png">
   ```

## 🔧 Technologies Used

- **HTML5** - Structure
- **CSS3** - Custom styling
- **Tailwind CSS** - Utility-first CSS framework (CDN)
- **Font Awesome** - Icons (CDN)
- **JavaScript** - Smooth scrolling functionality

## 📝 License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## 🤝 Contributing

This is the official AI4HEC organization website. For contributions:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📧 Contact

- **GitHub Organization**: [https://github.com/AI4HEC](https://github.com/AI4HEC)
- **Institution**: University of Peradeniya, Sri Lanka

---

**© 2025 AI4HEC | University of Peradeniya**  
*AI for Human-Elephant Coexistence*
About the project!
