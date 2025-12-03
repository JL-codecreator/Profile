<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Flip Text Animation</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: #0d1117;
    color: #fff;
    font-family: 'Arial', sans-serif;
    overflow: hidden;
  }

  .flip-text {
    font-size: 3em;
    font-weight: bold;
    display: flex;
  }

  .flip-text span {
    display: inline-block;
    animation: flip 1.5s infinite;
    animation-delay: calc(var(--i) * 0.2s);
    perspective: 1000px;
  }

  @keyframes flip {
    0% { transform: rotateX(0deg); color: #ff4d6d; }
    50% { transform: rotateX(180deg); color: #ffd700; }
    100% { transform: rotateX(0deg); color: #ff4d6d; }
  }
</style>
</head>
<body>
  <div class="flip-text">
    <span style="--i:0">H</span>
    <span style="--i:1">e</span>
    <span style="--i:2">l</span>
    <span style="--i:3">l</span>
    <span style="--i:4">o</span>
    <span style="--i:5"> </span>
    <span style="--i:6">I</span>
    <span style="--i:7">'</span>
    <span style="--i:8">m</span>
    <span style="--i:9"> </span>
    <span style="--i:10">A</span>
    <span style="--i:11">R</span>
    <span style="--i:12">I</span>
    <span style="--i:13">A</span>
    <span style="--i:14">T</span>
    <span style="--i:15">E</span>
  </div>
</body>
</html>

---

## 🛠️ Skills & Expertise

### **Frontend**
- **HTML5, CSS3, JavaScript (ES6+)**  
  Build responsive and interactive web interfaces with clean, semantic code.
- **React.js & TypeScript**  
  Create scalable and maintainable front-end applications with modern frameworks.
- **Tailwind CSS & Styled Components**  
  Build beautiful UIs with utility-first CSS frameworks and component styling.

### **Backend**
- **Node.js & Express.js**  
  Develop server-side applications, RESTful APIs, and handle server logic.
- **Supabase / PostgreSQL**  
  Database management, authentication, and real-time data handling.
- **API Integration**  
  Connect frontend with backend using RESTful APIs and third-party services.

### **Tools & Other Skills**
- **Git & GitHub** – Version control and collaborative workflows.
- **Figma / UI Design** – Design modern and user-friendly interfaces.
- **Problem Solving & Debugging** – Identify issues and optimize applications.

---

## 💡 About Me
I am a passionate **Full Stack Web Developer** with experience in building dynamic and responsive web applications. I enjoy working with modern technologies and creating seamless user experiences. Always eager to learn and improve my skills while contributing to meaningful projects.

---

<p align="center">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="250" alt="coding animation"/>
</p>
