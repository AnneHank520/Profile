# 🌐 Xinhang Li - Personal Portfolio Website

This is a responsive personal portfolio website built using HTML, CSS, and JavaScript. It showcases my skills, projects, and contact information as a web developer and AI specialist.

## 📌 Features

- 🌙 Light/Dark theme toggle  
- 🌍 Language switch (English / Chinese)
- 📱 Responsive design for mobile, tablet, and desktop
- 🖼️ Portfolio project showcase with swiper carousel
- 📄 Downloadable CV
- 📬 Contact information section
- ⚙️ Modular structure with reusable components

## 🛠️ Tech Stack

| Frontend | Description |
|----------|-------------|
| **HTML5 / CSS3** | Structured and styled content |
| **JavaScript / jQuery** | DOM interaction, language switching |
| **Swiper.js** | Carousel for project display |
| **Unicons** | Icon library |
| **i18n plugin** | Custom multi-language support (English & Chinese) |

## 🧩 Folder Structure

```
project-root/
│
├── index.html                    # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css            # Main stylesheet
│   ├── js/
│   │   ├── main.js               # UI interaction and theme toggle
│   │   ├── iconfont.js           # Icon loader
│   │   ├── jquery2.1.4.min.js    # jQuery core
│   │   ├── jquery.i18n.min.js    # i18n plugin
│   │   └── cn-en-translate.js    # Language toggle logic
│   ├── img/                      # Images (portfolio, avatar, etc.)
│   ├── i18n/
│   │   ├── i18n_en.json          # English language pack
│   │   └── i18n_cn.json          # Chinese language pack
│   └── pdf/
│       └── Hank Resume.pdf       # Downloadable resume
```

## 🧪 How to Run Locally

1. **Clone this repo**
```bash
git clone https://github.com/your-username/portfolio-website.git
cd portfolio-website
```

2. **Open `index.html` in your browser**
```bash
# No build tools required
```

> ✅ No Node.js or build setup required. It’s a static website!

## 🌐 Language Toggle

Click the translate icon in the top navigation bar to switch between English and Chinese. The current language is saved in `localStorage` so your preference is remembered.

## 📌 To Do / Optional Enhancements

- [ ] Add blog section
- [ ] Integrate contact form backend
- [ ] Add animation to project cards
- [ ] Deploy to GitHub Pages / Netlify


