<div align="center">
  <img src="assets/banner.svg" alt="REUBG DEV — Reuben Binu George" width="100%" />
</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-reubg.in-00F2FE?style=for-the-badge&logo=googlechrome&logoColor=white)](https://reubg.in)
[![Alternative Domain](https://img.shields.io/badge/Alt_Domain-reubg.dev-38BDF8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://reubg.dev)
[![GitHub](https://img.shields.io/badge/GitHub-@daneyyhh-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/daneyyhh)
[![Stack](https://img.shields.io/badge/Focus-Full%20Stack%20%7C%20MERN%20%7C%20Unity-34D399?style=for-the-badge)](https://github.com/daneyyhh?tab=repositories)
[![Email](https://img.shields.io/badge/Direct_Email-daneyyhh64@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daneyyhh64@gmail.com)

</div>

---

### ✦ Architecture & Engineering Focus

I am **Reuben Binu George** (**REUBG DEV**), a Full Stack and Game Developer dedicated to engineering high-performance web systems, real-time architectures, and interactive 3D simulations. 

* **Full-Stack Web Engineering**: Deep specialization in the **MERN Stack** (MongoDB, Express, React, Node.js), event-driven WebSockets with **Socket.IO**, and responsive UI architectures using modern tools.
* **Game Development & Physics**: Building 3D physics-based mechanics, obstacle dynamics, and interactive simulations in **Unity** with **C#**.
* **Interface & Human Interaction**: Designing clean, high-contrast, technical design systems in **Figma** and bringing them to life with **Three.js** and fluid modern CSS.

> *"Build. Design. Experiment."* — Architecting production-grade software with clean separations of concern, atomic state management, and intuitive user experiences.

---

### 🛠️ Technical Arsenal

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Backend & Real-Time** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) |
| **Databases** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Languages** | ![JavaScript](https://img.shields.io/badge/JavaScript%20(ES6+)-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) |
| **Game Development** | ![Unity](https://img.shields.io/badge/Unity_3D-000000?style=flat-square&logo=unity&logoColor=white) |
| **Design & UI/UX** | ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) |
| **Tools & DevOps** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

</div>

---

### 🚀 Featured Engineering Projects

#### 1. [NEXORA — Advanced Full-Stack MERN E-Commerce Platform](https://github.com/daneyyhh/nexora-mern-ecommerce)
*Production-grade, architectural e-commerce platform bridging storefront actions with real-time admin fulfillment.*

#### 2. [3D Bouncing Ball Game — Unity Physics Platformer](https://github.com/daneyyhh/3d-bouncing-ball-game)

#### 3. [AI Chess Game — Interactive Engine & Board](https://github.com/daneyyhh/ai-chess-game)

#### 4. [Personal Portfolio — Interactive Experience](https://github.com/daneyyhh/portfolio)

---

#### 📅 Isometric Contribution Calendar
<div align="center">
  <img src="github-calendar.svg" alt="GitHub Isometric Contribution Calendar" width="800" style="max-width: 100%; height: auto;" />
</div>

<br />

#### ⚡ Recent Engineering Activity
<div align="center">
  <img src="github-activity.svg" alt="Recent GitHub Activity Stream" width="800" style="max-width: 100%; height: auto;" />
</div>

---

### ✅ GitAscii, Cool GIFs & Profile Readme Generator

- GitAscii integration (embed generated SVGs from the `gitascii` branch):

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/daneyyhh/daneyyhh/gitascii/profiles/default/dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/daneyyhh/daneyyhh/gitascii/profiles/default/light.svg" />
  <img alt="GitAscii Profile" src="https://raw.githubusercontent.com/daneyyhh/daneyyhh/gitascii/profiles/default/dark.svg" width="100%" />
</picture>

- Cool GIF accents (sourced from Anmol-Baranwal/Cool-GIFs-For-GitHub) are used near the header for subtle motion.

- Quick README Builder: profile-readme-generator (https://profile-readme-generator.com) — open the site, design and copy the generated markdown into this README.

---

## 🛰️ GitHub 3D Contribution Grid (GitHub-Profile-3D-Contrib)

Add a 3D contribution calendar to your profile using the action by yoshi389111. This action generates attractive SVGs and commits them into the repository so they can be embedded in your README.

1) Create the workflow file at `.github/workflows/profile-3d.yml` with the following content:

```yaml
name: GitHub-Profile-3D-Contrib

on:
  schedule: # daily at 18:00 UTC (adjust to prefered time)
    - cron: "0 18 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v5
      - uses: yoshi389111/github-profile-3d-contrib@latest
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A .
          if git commit -m "generated"; then
            git push
          fi
```

2) First run: go to Actions → GitHub-Profile-3D-Contrib → Run workflow (workflow_dispatch) to generate the images immediately.

3) Generated images (examples) will appear under `profile-3d-contrib/`:

- `profile-3d-contrib/profile-green-animate.svg`
- `profile-3d-contrib/profile-green.svg`
- `profile-3d-contrib/profile-season-animate.svg`
- `profile-3d-contrib/profile-season.svg`
- `profile-3d-contrib/profile-south-season-animate.svg`
- `profile-3d-contrib/profile-south-season.svg`
- `profile-3d-contrib/profile-night-view.svg`
- `profile-3d-contrib/profile-night-green.svg`
- `profile-3d-contrib/profile-night-rainbow.svg`
- `profile-3d-contrib/profile-gitblock.svg`

4) Embed one of the generated SVGs in your README. Example (green animated version):

```md
![](./profile-3d-contrib/profile-green-animate.svg)
```

Or use the raw URL from the repository (stable once generated):

```md
![](https://raw.githubusercontent.com/daneyyhh/daneyyhh/main/profile-3d-contrib/profile-green-animate.svg)
```

Notes & options
- If you want activity from private repositories included, create a personal access token (with the least required scopes) and store it as a repository secret (for example, `MY_PERSONAL_ACCESS_TOKEN`) then set `GITHUB_TOKEN: ${{ secrets.MY_PERSONAL_ACCESS_TOKEN }}` in the workflow.
- You can pass `SETTING_JSON` (path to a JSON file in your repo) to customize colors, year, orientation, and more. See `sample-settings/` in the action repo for examples.
- The action is MIT-licensed; it generates files directly in your repository (committed by the workflow).

---

### 🌐 Connect & Collaborate

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-reubg.in-00F2FE?style=for-the-badge&logo=googlechrome&logoColor=white)](https://reubg.in)
[![Alternative Domain](https://img.shields.io/badge/Alt_Domain-reubg.dev-38BDF8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://reubg.dev)
[![GitHub](https://img.shields.io/badge/GitHub-@daneyyhh-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/daneyyhh)
[![Email](https://img.shields.io/badge/Direct_Email-daneyyhh64@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daneyyhh64@gmail.com)

<br />

```text
REUBG DEV // Reuben Binu George
Full Stack Developer • Game Developer • UI/UX Designer
Bengaluru, India • Available for Full-Time Roles & High-Impact Contracts
```

</div>

---

<sub>Animated artwork and icons sourced from community assets and third-party projects (Cool GIFs, GitAscii, GitHub-Profile-3D-Contrib). Follow each project's license and attribution rules when reusing their assets.</sub>
