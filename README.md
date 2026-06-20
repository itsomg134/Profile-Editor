# 🧑‍💼 Profile Editor

A modern, responsive profile editor web application with real-time saving, avatar upload, and social links management. Built with vanilla HTML, CSS, and JavaScript — no frameworks required.

![Profile Editor Screenshot](https://raw.githubusercontent.com/yourusername/profile-editor/main/screenshot.png)

---

## ✨ Features

- **👤 Avatar Management** — Upload custom profile photos or use default avatars
- **📝 Editable Profile Fields** — First name, last name, email, phone, and bio
- **🔗 Social Links** — Twitter, LinkedIn, and GitHub integration
- **💾 Auto-Save** — Changes automatically saved to `localStorage`
- **🔄 Reset to Defaults** — One-click restore to original profile data
- **📱 Fully Responsive** — Works on desktop, tablet, and mobile devices
- **🎨 Modern UI** — Glassmorphism design with smooth animations

---

## 🚀 Live Demo

[View Live Demo](https://yourusername.github.io/profile-editor/)

---

## 📸 Preview

| Desktop View | Mobile View |
|--------------|-------------|
| ![Desktop](https://via.placeholder.com/600x350/1e2b4f/ffffff?text=Desktop+Preview) | ![Mobile](https://via.placeholder.com/300x500/1e2b4f/ffffff?text=Mobile+Preview) |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Structure & content |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling & responsive design |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Interactivity & data persistence |
| ![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=flat&logo=fontawesome&logoColor=white) | Icons |

---

## 📂 Project Structure

```
profile-editor/
├── index.html          # Main application file (everything in one file)
├── README.md           # Project documentation
└── screenshot.png      # Application preview image
```

The entire application is contained in a single `index.html` file:
- **CSS** — Embedded in `<style>` tags within the `<head>`
- **JavaScript** — Embedded in `<script>` tags before `</body>`
- **External Dependency** — Font Awesome CDN for icons

---

## 🏁 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/profile-editor.git
   ```

2. **Navigate to project folder:**
   ```bash
   cd profile-editor
   ```

3. **Open in browser:**
   ```bash
   open index.html
   ```
   Or simply double-click `index.html` in your file explorer.

---

## 🎮 Usage Guide

### Editing Your Profile
1. **Update personal info** — Type directly in any input field (auto-saves after 0.8 seconds)
2. **Change avatar** — Click the camera icon on the profile picture and select an image
3. **Add social links** — Enter Twitter, LinkedIn, and GitHub usernames/URLs

### Saving Data
- **Automatic** — Changes save automatically to your browser's localStorage
- **Manual** — Click "Save Changes" for immediate save confirmation
- **Status indicator** — Top-right corner shows save status

### Resetting
- Click **"Reset"** to restore all fields to default values
- Confirmation dialog prevents accidental resets

---

## 🔧 Configuration

### Default Profile Data
Edit the `defaultProfile` object in the JavaScript section to customize defaults:

```javascript
const defaultProfile = {
  avatar: 'https://randomuser.me/api/portraits/women/44.jpg',
  firstName: 'Emma',
  lastName: 'Wilson',
  email: 'emma.wilson@design.io',
  phone: '+1 (415) 555-0182',
  bio: 'Product designer & coffee enthusiast.',
  twitter: '@emmawilson',
  linkedin: 'linkedin.com/in/emmawilson',
  github: 'github.com/emmawils'
};
```

### Styling Customization
Modify CSS variables and classes to match your brand:
- Primary color: `#1e2b4f` (header, buttons)
- Background gradient: `linear-gradient(135deg, #f5f7fa 0%, #e9edf5 100%)`
- Glassmorphism effect in `.profile-editor`

---

## 🌟 Key Functionality

| Feature | Implementation |
|---------|---------------|
| **Avatar Upload** | FileReader API → Data URL → Image preview |
| **Data Persistence** | `localStorage` with JSON serialization |
| **Auto-Save** | Debounced input event listeners (800ms delay) |
| **Responsive Design** | CSS Grid + Flexbox + Media Queries |
| **Image Validation** | File type checking (`image/*`) |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit** your changes:
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push** to the branch:
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open** a Pull Request

### Ideas for Contributions
- [ ] Add profile visibility toggle (public/private)
- [ ] Implement dark/light theme switching
- [ ] Add more social media platforms
- [ ] Export profile as PDF
- [ ] Add profile URL slug/customization
- [ ] Backend integration (Firebase, Supabase)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for beautiful icons
- [Random User API](https://randomuser.me/) for default avatar images
- Modern CSS features: `backdrop-filter`, Grid, Flexbox

---

## 📧 Contact

Your Name — [@yourtwitter](https://twitter.com/yourtwitter) — your.email@example.com

Project Link: [https://github.com/yourusername/profile-editor](https://github.com/yourusername/profile-editor)

---

⭐️ **Star this repo** if you found it useful!
```

---

## 📝 Customization Tips

To make this README your own:

1. **Replace placeholders:**
   - `yourusername` → your actual GitHub username
   - `your.email@example.com` → your contact email
   - `@yourtwitter` → your Twitter handle

2. **Add screenshots:**
   - Take screenshots of your app
   - Save as `screenshot.png` in project root
   - Replace placeholder image URLs

3. **Update demo link:**
   - Deploy to GitHub Pages
   - Update the live demo URL

4. **Add badges:**
   Customize tech stack badges from [shields.io](https://shields.io)

5. **License file:**
   Create a `LICENSE` file with MIT or your preferred license text
