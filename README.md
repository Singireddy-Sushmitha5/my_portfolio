# 🚀 Sushmitha Singireddy — Interactive 3D Portfolio

An immersive, Three.js-powered portfolio website featuring anti-gravity physics, orbiting credential cores, and real-time telemetry visualizations. Built as a single-page experience with zero dependencies beyond Three.js.

![Portfolio Preview](hologram.jpg)

---

## ✨ Features

- **Three.js 3D Scene** — Icosahedron hero core with wireframe shell, orbiting credential cards, floating debris, and 2200+ space dust particles
- **14 Orbiting Credential Cores** — Each card displays project/certification details with unique color themes and interactive hover effects
- **Gravity Engine HUD** — Switch between Zero-G, Micro-G, Hyper-G, and Anti-Gravity Burst modes to control the physics simulation
- **Inspection Modal with Telemetry View** — Click any core to open a detailed modal with animated canvas visualizations (shield, neural net, binary tree, radar, analytics, etc.)
- **Verified Certificate Document View** — Toggle between the animated telemetry and the actual certificate image for verified credentials
- **Custom Lerped Cursor** — Smooth-damped custom cursor with hover detection on 3D objects
- **Fully Responsive** — Adapts to all screen sizes with mobile-optimized layouts

---

## 📁 Project Structure

```
my-portfolio/
├── index.html              # Single-page portfolio (HTML + CSS + JS)
├── hologram.jpg             # Hero background asset
├── certificates/            # Verified certificate images
│   ├── cert-dsa.jpg
│   ├── cert-zerotrust.jpg
│   ├── cert-android.jpg
│   ├── cert-genai.jpg
│   ├── cert-java.jpg
│   ├── cert-be10x.jpg
│   ├── cert-servicenow.jpg
│   ├── cert-genai-nasscom.jpg
│   ├── cert-cybersecurity.jpg
│   └── cert-aiml.jpg
└── README.md                # This file
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic layout |
| **CSS3** | Glassmorphism styling, animations, responsive design |
| **JavaScript** | Interactive logic, gravity physics, modal system |
| **Three.js (r128)** | 3D rendering, raycasting, camera lerping |
| **Google Fonts** | Inter & Orbitron typefaces |

---

## 🖥️ Run Locally

No build step needed. Just serve the files with any static server:

```bash
# Using Python
cd "my-portfolio"
python -m http.server 8000

# Using Node.js (if installed)
npx serve .
```

Then open **http://localhost:8000** in your browser.

---

## 🌐 Deployment Guide

### Option 1 — GitHub Pages (Free)

#### Step 1: Install Git

- Download and install Git from [https://git-scm.com/download/win](https://git-scm.com/download/win)
- Restart your terminal after installation

#### Step 2: Create a GitHub Repository

1. Go to [https://github.com/new](https://github.com/new)
2. **Repository name**: `my-portfolio` (or `<your-username>.github.io` for a personal site)
3. Set visibility to **Public**
4. **Do NOT** initialize with a README (we already have one)
5. Click **Create repository**

#### Step 3: Push Your Code

Open PowerShell or Terminal in the project folder and run:

```bash
git init
git add .
git commit -m "Deploy interactive 3D portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/my-portfolio.git
git push -u origin main
```

> Replace `<your-username>` with your actual GitHub username.

#### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Click **Save**

#### Step 5: Access Your Live Site

Wait 1–2 minutes, then visit:

| Repo Name | Live URL |
|---|---|
| `my-portfolio` | `https://<your-username>.github.io/my-portfolio/` |
| `<your-username>.github.io` | `https://<your-username>.github.io/` |

---

### Option 2 — Render (Free Static Site Hosting)

[Render](https://render.com) is a cloud platform that can host static sites for free with automatic deployments from GitHub.

#### Step 1: Push to GitHub First

Follow **Steps 1–3** from the GitHub Pages guide above to push your code to a GitHub repository.

#### Step 2: Create a Render Account

1. Go to [https://render.com](https://render.com)
2. Click **Get Started for Free**
3. Sign up using your **GitHub account** (recommended for easy repo access)

#### Step 3: Create a New Static Site

1. From the Render Dashboard, click **New +** → **Static Site**
2. Connect your GitHub account if not already connected
3. Select the repository: `my-portfolio`
4. Configure the deployment settings:

| Setting | Value |
|---|---|
| **Name** | `sushmitha-portfolio` (or any name you like) |
| **Branch** | `main` |
| **Build Command** | *(leave empty — no build step needed)* |
| **Publish Directory** | `.` |

5. Click **Create Static Site**

#### Step 4: Wait for Deployment

- Render will pull your code from GitHub and deploy it
- This usually takes **30–60 seconds**
- Once complete, the status will show **"Live"** with a green indicator

#### Step 5: Access Your Live Site

Your portfolio will be live at:

```
https://sushmitha-portfolio.onrender.com
```

> The URL is based on the name you chose in Step 3. You can also set up a custom domain in Render's settings.

#### Step 6: Automatic Redeployments (Optional)

Every time you push new changes to the `main` branch on GitHub, Render will **automatically redeploy** your site. No manual action needed!

```bash
# After making changes locally:
git add .
git commit -m "Update portfolio with new certifications"
git push origin main
# Render will auto-deploy within ~60 seconds
```

---

### Option 3 — Netlify (Free Alternative)

1. Go to [https://app.netlify.com](https://app.netlify.com)
2. Drag and drop your entire `my-portfolio` folder onto the deploy zone
3. Your site will be live instantly at a `*.netlify.app` URL

---

## 📜 Certifications Included

| # | Title | Provider | Certificate |
|---|---|---|---|
| 01 | Campus Vote Hub | Academic Project | — |
| 02 | ServiceNow Virtual Internship | ServiceNow University / SmartBridge | ✅ |
| 03 | AI Tools & ChatGPT Workshop | Be10X | ✅ |
| 04 | Web Development | Brainovision | — |
| 05 | Core Programming Modules | B.Tech Academics | — |
| 06 | Database Management Systems | B.Tech Academics | — |
| 07 | Zero Trust Cloud Security | Zscaler & EduSkills | ✅ |
| 08 | Android Developer Internship | Google for Developers & EduSkills | ✅ |
| 09 | Java Full Stack Developer | EduSkills Academy & AICTE | ✅ |
| 10 | DSA for DeepTech Bootcamp | Brainovision Solutions & AICTE | ✅ |
| 11 | GenAI Data Analytics Simulation | Tata & Forage | ✅ |
| 12 | Gen AI NASSCOM Assessment | FutureSkills Prime & NASSCOM | ✅ |
| 13 | Cybersecurity Internship | Palo Alto Networks & EduSkills | ✅ |
| 14 | AI-ML Virtual Internship | Google for Developers & EduSkills | ✅ |

---

## 👩‍💻 Author

**Singireddy Sushmitha**
- 📧 [singireddysushmithareddy104@gmail.com](mailto:singireddysushmithareddy104@gmail.com)
- 💼 [LinkedIn](https://linkedin.com/in/sushmitha-singireddy-7b5559352)
- 🐙 [GitHub](https://github.com/Singireddy-Sushmitha5)

---

## 📄 License

This project is open source and available for personal use and learning purposes.
