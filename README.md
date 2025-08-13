````markdown
[!<img width="3780" height="1890" alt="banner_github" src="https://github.com/user-attachments/assets/9d6e301b-b93f-4637-a527-ba01bcb8215f" />
](https://raw.githubusercontent.com/DevmalyaBhattacharjee/DevmalyaBhattacharjee/main/banner.png)]((https://www.linkedin.com/in/devmalya-bhattacharjee-66a21927a/))

# 👋 Hello Devs! I'm Devmalya

```java
// Welcome to my GitHub
public class Introduction {
    public static void main(String[] args) {
        greet();
    }

    public static void greet() {
        System.out.println("Hello World!");
        System.out.println("I’m Devmalya 👨‍💻 — crafting code and solving problems one commit at a time!");
    }
}
````

---

### 🚀 Current Focus

* Learning **Spring Boot** and mastering **Java Full-Stack Development**
* Building scalable, production-ready web applications
* Strengthening **Data Structures & Algorithms** skills

---

### 🎓 Education

* Pursuing **B.Tech in Computer Science & Engineering** (Pre-final year, 2023–2027)

---

### 💼 Experience

* **100+ hours** dedicated to problem-solving on LeetCode & other platforms
* **Participant** — Smart India Hackathon 2024
* Developed multiple **full-stack projects** integrating modern tech stacks

---

### 🛠 Tech Stack

<p align="center">
<img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/SpringBoot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/Bootstrap-%237952B3.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/>
<img src="https://img.shields.io/badge/GSAP-%2388CE02.svg?style=for-the-badge&logo=greensock&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

---

### 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge\&logo=linkedin\&logoColor=white)]((https://www.linkedin.com/in/devmalya-bhattacharjee-66a21927a/))
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge\&logo=twitter\&logoColor=white)]((https://x.com/DevmalyaBh69215))
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:debmalyabhattacharya17.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge\&logo=firefox\&logoColor=white)](PORTFOLIO_URL)

---

## 🐍 GitHub Snake Contribution Animation

![snake gif](https://github.com/DevmalyaBhattacharjee/DevmalyaBhattacharjee/blob/output/github-contribution-grid-snake-dark.svg)

---

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"   # every day at 00:00 UTC
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: DevmalyaBhattacharjee
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
````
```
