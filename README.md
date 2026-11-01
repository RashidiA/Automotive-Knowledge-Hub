# 🚗 Automotive Knowledge Hub

A free, modern learning hub for **students and young engineers**. Explore how a car is designed, built, checked for quality and made safe for workers, using real, hands-on simulators that run in your browser.

🌐 **Live site:** [https://rashidia.github.io/Automotive-Knowledge-Hub/](https://rashidia.github.io/Automotive-Knowledge-Hub/)

---

## 🎯 Purpose

Connect mathematics, engineering principles and real automotive practice in one place. Instead of only reading about welding, robots, statistics or ergonomics, learners can open a simulator, change the settings and see what happens.

---

## ✨ What is on the hub

| Section | What it does |
|---|---|
| **Journey of a car** | Four stages (Design, Build, Quality, People and safety). Click a stage to filter the simulators that belong to it. |
| **Simulators** | Six cards with a short description, what you will learn, tags, a **Launch** button for the live app and a link to the source code. Search and stage filters included. |
| **Key terms** | 12 flip cards explaining terms such as body-in-white, Ackermann steering, weld lobe, Cpk, poka-yoke, REBA and Lifting Index. |
| **Quick quiz** | Five questions based on the simulators, with instant feedback and a saved best score. |
| **Extras** | Dark and light themes, keyboard shortcuts, animated background, mobile-friendly layout. |

**Keyboard shortcuts:** `/` search · `T` switch theme · `Esc` clear search

---

## 🛠️ Simulators linked from the hub

| Simulator | Stage | Focus | Live app | Source |
|---|---|---|---|---|
| **Automotive Simulations (student version)** | Design | Dashboard with Car Anatomy Lab (3D car, six systems, guided tour in English and Malay), spot welding, welding maths, car plant process, laser seam tracking and torque monitoring | [Open](https://rashidia.github.io/Automotive-simulation-student-version/) | [GitHub](https://github.com/RashidiA/Automotive-simulation-student-version) |
| **AR Gesture CAD Studio** | Design | Gesture-controlled 3D CAD with webcam hand tracking, STL import, extrusion and Boolean operations | [Open](https://ar-gesture-cad-studio-yovhcowlmh6mesydbs7wtj.streamlit.app/) | [GitHub](https://github.com/RashidiA/AR-Gesture-CAD-Studio) |
| **Industrial Robot Cloud Simulator** | Build | Offline robot programming for spot welding and material handling, inverse kinematics, gesture teach pendant | [Open](https://industrial-robot-cloud-simulator-54jggbftztagnuxosqtvzr.streamlit.app/) | [GitHub](https://github.com/RashidiA/Industrial-Robot-Cloud-Simulator) |
| **Spot Weld Process Simulator** | Build | Weld lobe mapping for multi-layer sheet steel, nugget growth and expulsion limits | [Open](https://spot-weld-process-simulator-jogq55brt4wsqfy8sgonbp.streamlit.app/) | [GitHub](https://github.com/RashidiA/Spot-Weld-Process-Simulator) |
| **Process Capability Study** | Quality | Cp, Cpk, PPM, control chart, histogram and PDF audit report | [Open](https://process-capability-study-apjprzx7rkxtwwerctdqz3.streamlit.app/) | [GitHub](https://github.com/RashidiA/Process-Capability-Study) |
| **Ergonomic Risk Evaluation (REBA)** | People and safety | Webcam posture scoring with REBA, NIOSH lifting analysis and PDF report | [Open](https://ergonomic-risk-evaluation-reba-xugjcmzcuciyhtkz3adgbk.streamlit.app/) | [GitHub](https://github.com/RashidiA/Ergonomic-Risk-Evaluation-REBA) |

> 💡 **Good to know**
> * Free Streamlit apps go to sleep when nobody uses them. If a page says it is waking up, wait about 30 seconds.
> * Apps marked **Webcam** ask for camera permission and work best on a laptop or desktop in good light. Video is processed for the simulation; check each app's repository for details.

---

## 🚀 Run it locally

The hub is a single static file with no build step and no dependencies.

1. **Clone or download** this repository.
2. Open `index.html` in any modern browser, or serve the folder with a local server (for example VS Code Live Server).

---

## ➕ Add or edit content

Everything is edited at the top of the `<script>` section in `index.html`:

| List | Use it to |
|---|---|
| `SIMS` | Add, remove or reword simulators (title, stage, colour, description, three learning points, tags, live link, repository link, icon). |
| `STAGES` | Rename or add journey stages. A simulator's `stage` must match a stage `id`. |
| `TERMS` | Add or edit key-term flip cards (`['Term', 'Meaning']`). |
| `QUIZ` | Add questions (`q` question, `o` options, `a` index of the correct option starting at 0, `w` explanation). |

After editing, commit the change. GitHub Pages republishes the site within a minute or two.

---

## 🌍 Publish with GitHub Pages

1. Go to **Settings → Pages** in the repository.
2. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
3. The site appears at `https://<your-username>.github.io/<repository-name>/`.

---

## 📂 Project structure

```text
├── index.html   # The whole hub: page, styles, content lists and scripts
└── README.md    # This file
```

---

## ⚠️ Disclaimer

The simulators are simplified for teaching. Their results are **not** for real vehicle design, welding procedure approval, quality certification or workplace safety decisions.

---

## 👤 Author

Created by [RashidiA](https://github.com/RashidiA). Suggestions for new simulators and topics are welcome: open an issue or a pull request.
