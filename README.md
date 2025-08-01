## 📺 YouTube Clone

🚀 A YouTube clone built with HTML and CSS, featuring a fixed header, collapsible sidebar, video and shorts sections, and a responsive design optimized for screens up to 600px. This project showcases mastery of flexbox and media queries for a seamless, user-friendly layout.



## ✨ Features
- 🔥 Fixed header for consistent navigation  
- 📜 Collapsible sidebar for enhanced usability  
- 🎥 Video section with a grid layout  
- 📱 Shorts section for vertical video display  
- 🛠 Responsive design for screens up to 600px  
- 🏎 Smooth layout with flexbox and media queries  



## 📌 Tech Stack
- Frontend: HTML, CSS  
- Deployment: GitHub Pages  



## 📂 Project Structure
```

youtube-clone/
├── assets/
│   ├── css/
│   │   ├── styles.css
│   ├── images/
│   │   ├── thumbnails/
│   │   ├── icons/
├── index.html
├── README.md
```


## 🚀 Getting Started

### 1️⃣ Clone the Repository  

```bash

git clone https://github.com/SyedAbdullah23/Youtube-Clone
cd Youtube-Clone
```

### 2️⃣ Run the App

Open index.html in a web browser, or use a local server (e.g., Live Server extension in VS Code) for best results:

```bash
npx live-server
```



## ⚡ How It Works

1. The fixed header remains at the top, providing access to navigation and search.  
2. The collapsible sidebar toggles to save space, using CSS flexbox for layout.  
3. The video section displays a responsive grid of video thumbnails, optimized with media queries for smaller screens.  
4. The shorts section mimics YouTube’s vertical video format, styled with CSS.  
5. Media queries ensure a seamless experience on screens up to 600px.  

Example Code:
```bash
<header class="fixed top-0 w-full bg-white shadow">
  <nav class="flex items-center justify-between p-4">
    <div class="logo">YouTube</div>
    <input type="text" placeholder="Search" class="border rounded">
  </nav>
</header>
```

```bash

.video-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
}
@media (max-width: 600px) {
  .video-grid {
    flex-direction: column;
    align-items: center;
  }
}
```



## 📸 Screenshots

### 💬 Main Interface

[Insert screenshot or placeholder: A view of the fixed header, sidebar, and video grid]



## 🚀 Deployment

### 🌐 Deploy to GitHub Pages
1. Push your project to GitHub.  
2. Enable GitHub Pages in the repository settings (use the main branch).  
3. Access the live site at https://syedabdullah23.github.io/Youtube-Clone.  

## 🤝 Contributing
1. Fork this repository  
2. Create a new branch (feature-branch)  
3. Commit your changes  
4. Push to GitHub  
5. Open a Pull Request (PR)  

## 🛠 Future Enhancements
- ✅ Add JavaScript for sidebar toggle functionality  
- ✅ Implement video playback with HTML5  
- ✅ Add search functionality  
- ✅ Enhance accessibility with ARIA attributes  

## 📜 License
This project is licensed under the MIT License.  

## ⭐ Support & Feedback
- 💬 Found a bug? Open an issue!  
- 🌟 Like this project? Give it a star!  

## 🔥 Follow for More!
- 🚀 [GitHub](https://github.com/SyedAbdullah23)  
- 📺 [LinkedIn](https://www.linkedin.com/in/syed-abdullah)
