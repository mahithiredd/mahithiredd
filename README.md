<h1 align="center">☁️ Tanguturi Mahithi Reddy</h1>
<h3 align="center">Aspiring Cloud Architect | AI Enthusiast | Tech Explorer</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&width=435&lines=Cloud+Computing+%7C+AI+%7C+ML+%7C+IoT+%F0%9F%93%A1;Always+Learning+Something+New...+%F0%9F%93%9A;Solving+problems+with+intelligent+tech+%E2%9C%8C%EF%B8%8F" alt="Typing SVG" />
</p>

---

## 🌤️ About Me

Hi there! I'm Mahithi — a passionate AI undergraduate with a dream to architect tomorrow’s cloud systems. Whether it's optimizing energy use with Green Cloud, building precision farming models, or deploying AI pipelines, I love making technology purposeful and powerful.

- 🎓 **B.Tech Artificial Intelligence** @ Amrita Vishwa Vidyapeetham  
- ☁️ AWS Certified | Green Cloud Researcher  
- 🤖 Building smart, sustainable, and scalable solutions  
- 🧠 Curious about **Edge AI**, **Serverless**, and **ML Ops**

---

## 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mahithiredd&show_icons=true&theme=tokyonight&hide_border=false&rank_icon=github" height="180"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahithiredd&layout=compact&theme=tokyonight&hide_border=false" height="180"/>
</div>

---

## 🧰 Tech Toolbox

<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,python,pytorch,docker,mysql,mongodb,anaconda,git,github,linux,latex,vscode,jupyter,kaggle" />
</div>

---

## 🧠 Projects That I'm Proud Of

- 🔬 **Precision Farming (2024)**  
  Applied wavelet transforms + ML/DL for accurate crop yield predictions.  
  _AI + Agriculture = Sustainable future!_

- 🧠 **Brain Tumor Detection (2023)**  
  CNN-based MRI image classification for early diagnosis support.  

- ♻️ **Green Cloud for IoT (2025 - Publication)**  
  Merged ML with edge and cloud to save energy in sensor networks.  

- 🧮 **Metaheuristic Scheduling**  
  Explored GA, ACO, SA for optimizing job shop production timelines.

---

## 📜 Certifications

- ✅ [AWS Academy Graduate (2024)](https://www.credly.com/badges/4f12e002-8014-4511-b41d-129d62ef740e/linked_in_profile)  
- 🧠 [AI from IIT Roorkee + Wipro Disk IDES (2023)](https://cert.diceid.com/cid/dSKGLjlCLG)  
- 🧪 [MATLAB Image Processing (2023)](https://matlabacademy.mathworks.com/progress/share/certificate.html?id=7e27ce34-279a-4b63-8a05-00dffb90a302)

---

## 🌐 Let's Connect!

<p align="center">
  <a href="mailto:mahitanguturi@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/mahithi-tanguturi"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://tryhackme.com"><img src="https://img.shields.io/badge/TryHackMe-88cc14?style=for-the-badge&logo=tryhackme&logoColor=white"/></a>
  <a href="https://www.hackerrank.com"><img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white"/></a>
</p>

---


## 🎮 Mini Cloud Game

> Want to play with the clouds? Try catching them!  
> *(Tip: View this game in your browser or portfolio site — GitHub won't render it.)*

<details>
<summary>🌩️ Click to Launch "Catch the Cloud" Game</summary>

```html
<canvas id="cloudGame" width="300" height="200" style="border:1px solid #ccc;"></canvas>
<script>
  const canvas = document.getElementById('cloudGame');
  const ctx = canvas.getContext('2d');
  let x = Math.random() * 280;
  let y = 0;
  let score = 0;

  function drawCloud() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    ctx.font = "20px Arial";
    ctx.fillText("☁", x, y);
    ctx.fillText("Score: " + score, 10, 190);
    y += 2;
    if (y > 180) {
      x = Math.random() * 280;
      y = 0;
    }
    requestAnimationFrame(drawCloud);
  }

  canvas.addEventListener('click', function (e) {
    const clickX = e.offsetX;
    const clickY = e.offsetY;
    if (clickX >= x && clickX <= x + 20 && clickY >= y && clickY <= y + 20) {
      score++;
      x = Math.random() * 280;
      y = 0;
    }
  });

  drawCloud();
</script>

---

## ✨ Fun Quote

> “You can’t predict the cloudburst—but you *can* architect the cloud.” ☁️🚀  
> — *Future Mahithi, probably during a keynote at AWS re:Invent 😉*

---
