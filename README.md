<div align="center">

<!-- Animated Deep-Space Purple Glassmorphism Banner -->
<svg width="100%" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Deep Purple Gradient -->
    <linearGradient id="deepPurple" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#2D1B69" />
      <stop offset="50%" stop-color="#7209B7" />
      <stop offset="100%" stop-color="#A663CC" />
    </linearGradient>
    
    <!-- Glass Effect Filter -->
    <filter id="glassBlur">
      <feGaussianBlur stdDeviation="40" />
    </filter>
    
    <!-- Star Pattern -->
    <pattern id="stars" x="0" y="0" width="100" height="100" patternUnits="userSpaceOnUse">
      <circle cx="10" cy="10" r="1" fill="#FFFFFF" opacity="0.6" />
      <circle cx="50" cy="30" r="0.5" fill="#A663CC" opacity="0.8" />
      <circle cx="80" cy="60" r="1.5" fill="#7209B7" opacity="0.4" />
      <circle cx="20" cy="80" r="0.8" fill="#FFFFFF" opacity="0.7" />
    </pattern>
  </defs>
  
  <!-- Deep Space Background -->
  <rect width="1200" height="300" fill="#0A0A0F" />
  <rect width="1200" height="300" fill="url(#stars)" opacity="0.3" />
  
  <!-- Floating Glass Orbs -->
  <g filter="url(#glassBlur)" opacity="0.8">
    <circle r="120" cx="150" cy="100" fill="url(#deepPurple)">
      <animate attributeName="cx" values="150;1050;150" dur="20s" repeatCount="indefinite" />
      <animate attributeName="cy" values="100;200;100" dur="15s" repeatCount="indefinite" />
    </circle>
    
    <circle r="80" cx="1000" cy="200" fill="url(#deepPurple)" opacity="0.6">
      <animate attributeName="cx" values="1000;200;1000" dur="25s" repeatCount="indefinite" />
      <animate attributeName="cy" values="200;80;200" dur="18s" repeatCount="indefinite" />
    </circle>
    
    <circle r="60" cx="600" cy="50" fill="url(#deepPurple)" opacity="0.4">
      <animate attributeName="cy" values="50;250;50" dur="12s" repeatCount="indefinite" />
    </circle>
  </g>
  
  <!-- Main Title with Bounce Animation -->
  <text x="50%" y="40%" dominant-baseline="middle" text-anchor="middle" 
        fill="#FFFFFF" font-size="48" font-family="'SF Pro Display', 'Segoe UI', system-ui" 
        font-weight="700" style="text-shadow: 0 0 20px rgba(166, 99, 204, 0.8);">
    <animate attributeName="font-size" values="48;52;48" dur="3s" repeatCount="indefinite" />
    Hi! I'm Anish Vyapari ✨
  </text>
  
  <!-- Subtitle -->
  <text x="50%" y="60%" dominant-baseline="middle" text-anchor="middle" 
        fill="#B8B8CC" font-size="20" font-family="'SF Pro Display', 'Segoe UI', system-ui">
    Robotics Engineer • AI/ML Developer • Drone Systems Specialist
  </text>
  
  <!-- Location with pulse -->
  <text x="50%" y="75%" dominant-baseline="middle" text-anchor="middle" 
        fill="#A663CC" font-size="16" font-family="'SF Pro Display', 'Segoe UI', system-ui">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite" />
    📍 Navi Mumbai, India 🇮🇳
  </text>
</svg>

<!-- Glassmorphism Profile Card -->
<div style="
  margin-top: -60px;
  padding: 25px 35px;
  backdrop-filter: blur(20px) saturate(180%);
  -webkit-backdrop-filter: blur(20px) saturate(180%);
  background: rgba(45, 27, 105, 0.15);
  border: 1.5px solid rgba(255, 255, 255, 0.2);
  border-radius: 24px;
  color: #F0F0F0;
  max-width: 700px;
  box-shadow: 0 8px 32px rgba(45, 27, 105, 0.4);
  transform: translateY(0);
  transition: transform 0.3s ease;
">
  <h3 style="margin: 0 0 15px 0; color: #FFFFFF; font-size: 24px; text-align: center;">
    🚀 Building the Future with Autonomous Systems
  </h3>
  <p style="margin: 0; text-align: center; line-height: 1.6; font-size: 16px; color: #D0D0E0;">
    Passionate about <strong style="color: #A663CC;">Computer Vision</strong>, 
    <strong style="color: #7209B7;">Machine Learning</strong>, and 
    <strong style="color: #2D1B69;">Robotics Integration</strong> • 
    Creating intelligent systems that bridge hardware and software
  </p>
</div>

<!-- Bouncy Social Links -->
<p align="center" style="margin-top: 30px;">
  <a href="https://www.linkedin.com/in/anish-vyapari-8a8089258/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" 
         style="margin: 8px; transform: scale(1); transition: transform 0.3s ease;" 
         onmouseover="this.style.transform='scale(1.1) rotate(-2deg)'" 
         onmouseout="this.style.transform='scale(1)'"/>
  </a>
  <a href="mailto:anishvyaparionline@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" 
         style="margin: 8px; transform: scale(1); transition: transform 0.3s ease;" 
         onmouseover="this.style.transform='scale(1.1) rotate(2deg)'" 
         onmouseout="this.style.transform='scale(1)'"/>
  </a>
  <a href="https://www.instagram.com/anish_vyapari/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" 
         style="margin: 8px; transform: scale(1); transition: transform 0.3s ease;" 
         onmouseover="this.style.transform='scale(1.1) rotate(-2deg)'" 
         onmouseout="this.style.transform='scale(1)'"/>
  </a>
</p>

<!-- Animated Stats -->
<p align="center" style="margin-top: 25px;">
  <img src="https://github-readme-stats.vercel.app/api?username=AnishVyapari&show_icons=true&theme=tokyonight&bg_color=0A0A0F&title_color=A663CC&text_color=F0F0F0&icon_color=7209B7&border_color=2D1B69&border_radius=15" 
       style="margin: 10px; transition: transform 0.3s ease;" 
       onmouseover="this.style.transform='scale(1.05)'" 
       onmouseout="this.style.transform='scale(1)'"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnishVyapari&theme=tokyonight&background=0A0A0F&ring=A663CC&fire=7209B7&currStreakLabel=F0F0F0&border=2D1B69" 
       style="margin: 10px; transition: transform 0.3s ease;" 
       onmouseover="this.style.transform='scale(1.05)'" 
       onmouseout="this.style.transform='scale(1)'"/>
</p>

</div>

---

## 🤖 About Me

<img align="right" width="300" src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" alt="Coding GIF"/>

I'm a **Computer Science Engineering (AI & ML)** student at **RAIT**, passionate about creating intelligent autonomous systems. My focus lies in the intersection of **robotics**, **computer vision**, and **machine learning**.

- 🚁 **Autonomous UAVs**: Vision-based navigation & inspection systems
- 🤖 **Robotics**: Perception, control, and intelligent automation  
- 🧠 **Deep Learning**: Real-world applications in computer vision
- 🔧 **Edge Computing**: Hardware-software integration for embedded AI
- 📡 **IoT Systems**: Connected devices and sensor networks

---

## 🛠️ Tech Arsenal

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

### AI/ML & Robotics
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)

### Development
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnishVyapari&layout=compact&theme=tokyonight&bg_color=0A0A0F&title_color=A663CC&text_color=F0F0F0&border_color=2D1B69&border_radius=15" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AnishVyapari&bg_color=0A0A0F&color=F0F0F0&line=A663CC&point=7209B7&area=true&hide_border=true" alt="Activity Graph" />
</div>

---

## 🎯 Current Focus

- 🔬 **Research**: Advanced path planning algorithms for autonomous drones
- 🏗️ **Building**: Computer vision pipeline for real-time object detection
- 📚 **Learning**: Deep reinforcement learning for robotic control
- 🌱 **Growing**: Open source contributions in robotics community

---

<div align="center">
  
  ### 💬 Let's Connect and Build Something Amazing!
  
  ![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=AnishVyapari.AnishVyapari&left_color=2D1B69&right_color=A663CC&left_text=Profile%20Views)
  
  <img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="100"/>
  
  **"The future belongs to those who learn more skills and combine them in creative ways."** 🚀
  
</div>
