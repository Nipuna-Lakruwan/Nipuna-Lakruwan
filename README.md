<!-- ©2026 Nipuna Lakruwan | All Rights Reserved | CC BY-NC-ND 4.0 | github.com/Nipuna-Lakruwan | Unauthorized copying is strictly prohibited -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Nipuna%20Lakruwan&fontSize=52&fontColor=fff&animation=twinkling&fontAlignY=38&desc=building%20things%20that%20think%20%F0%9F%A7%A0&descSize=18&descAlignY=60&descAlign=50" width="100%" alt="Nipuna Lakruwan, building things that think"/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=800&color=58A6FF&center=true&vCenter=true&repeat=true&width=560&height=48&lines=Building+things+that+think+%F0%9F%A7%A0;Benchmarking+Sinhala+embeddings+%F0%9F%87%B1%F0%9F%87%B0;My+Mac+has+feelings+now.+Send+help+%F0%9F%92%BB;Software+engineer+%E2%86%92+AI+engineer+%F0%9F%9A%80;Powered+by+Ceylon+tea+%E2%98%95" alt="Building things that think. Benchmarking Sinhala embeddings. My Mac has feelings now."/>
<br/>
<a href="https://nipuna-lakruwan.github.io"><img src="https://img.shields.io/badge/Portfolio-nipuna--lakruwan.github.io-2f6fd6?style=flat-square&labelColor=0d1117" alt="Portfolio"/></a>&nbsp;<a href="https://pypi.org/project/lanka-rag/"><img src="https://img.shields.io/pypi/v/lanka-rag?label=pip%20install%20lanka-rag&style=flat-square&color=3fb950&labelColor=0d1117" alt="lanka-rag on PyPI"/></a>&nbsp;<img src="https://komarev.com/ghpvc/?username=nipuna-lakruwan&style=flat-square&color=58A6FF&label=Profile+Views" alt="Profile views"/>&nbsp;<img src="https://img.shields.io/badge/Open%20To-Remote%20Work-e3b341?style=flat-square&labelColor=0d1117" alt="Open to remote work"/>
</div>

---

<!-- ©2026 Nipuna Lakruwan | CC BY-NC-ND 4.0 | Do not copy or repurpose -->
## 🧠 Who I Am

<table><tr><td width="33%" align="center" valign="top"><br/><img src="./assets/anime.gif" width="180" alt="Animated character"/><br/><br/><strong>HELLO / ආයුබෝවන් / こんにちは</strong> 👋🏻<br/><br/><a href="https://nipuna-lakruwan.github.io"><img src="https://img.shields.io/badge/Portfolio-2f6fd6?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a> <a href="https://www.linkedin.com/in/nipuna-lakruwan-6b740627a"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="mailto:senarath.lakruwan@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a></td><td width="67%" valign="top">

I started by automating systems: Docker, CI/CD, Linux. Now I build the systems **that think**, and then I measure whether they actually do. Lately that means an open benchmark of which embedding models understand Sinhala (now on PyPI), native macOS apps in SwiftUI, and a Mac that complains out loud through a local LLM. Long story.

> *I don't just run models. I ship them, test them, and occasionally give them feelings.*

```python
class NipunaLakruwan:
    location  = "Kandana, Sri Lanka 🇱🇰"
    education = "B.Sc. Information Technology"
    languages = ["Sinhala", "English", "日本語 (learning)"]
    open_to   = ["Remote work", "AI engineering", "Open source"]

    stack = {
        "ai":     ["Python", "LangChain", "Ollama", "RAG", "embeddings"],
        "apple":  ["Swift 6", "SwiftUI", "Core Audio"],
        "infra":  ["Docker", "GitHub Actions", "Linux", "Redis"],
        "web":    ["React", "Next.js", "Node.js", "PHP"],
    }

    def currently(self):
        return "teaching search engines Sinhala, and my Mac to complain"

    def fuel(self):
        return "Ceylon tea ☕ (an unreasonable amount)"
```

</td></tr></table>

---

<!-- ©2026 Nipuna Lakruwan | CC BY-NC-ND 4.0 | Do not copy or repurpose -->
## 🚀 Featured Projects

### [🇱🇰 lanka-rag](https://github.com/Nipuna-Lakruwan/lanka-rag)
**Which embedding model understands Sinhala?** A reproducible retrieval benchmark of local embedding models on Sinhala, Tamil and Singlish, plus a local RAG assistant over Sri Lankan Acts.

- `bge-m3` leads Sinhala at **0.913** nDCG@10…
- …but a 30-year-old keyword algorithm (BM25) gets **0.899**. I re-ran it three times.
- Singlish is the open problem: the best model reaches **0.31**.

```bash
pip install lanka-rag
```
`Python` `LangChain` `Ollama` `BM25` `PyPI`

<a href="https://github.com/Nipuna-Lakruwan/lanka-rag"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nipuna-Lakruwan/lanka-rag/main/results/ndcg_heatmap_dark.svg"/><img src="https://raw.githubusercontent.com/Nipuna-Lakruwan/lanka-rag/main/results/ndcg_heatmap_light.svg" alt="Heatmap of nDCG@10 by model and task"/></picture></a>

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Nipuna-Lakruwan/mac-with-feelings"><img src="https://raw.githubusercontent.com/Nipuna-Lakruwan/mac-with-feelings/main/assets/moods.png" alt="Nine laptop faces, one per mood"/></a>

</td>
<td width="50%" valign="top">

### [💻 Mac With Feelings](https://github.com/Nipuna-Lakruwan/mac-with-feelings)
**Your Mac has feelings now.** A menu-bar app that reads CPU, heat, battery, memory and your 47 browser tabs, then a local LLM says out loud how it feels about it.

> *"47 tabs? I'm literally sweating right now."*

Side effect: my Mac now judges my tab count. It is not wrong.

`Swift 6` `SwiftUI` `Ollama` `AVSpeech`

</td>
</tr>
</table>

| Project | What it does | The honest footnote |
|:---|:---|:---|
| 📱 [Android Mirror](https://github.com/Nipuna-Lakruwan/AndroidMirror-macOS) | SwiftUI front end for ADB and scrcpy | Squinting at the phone on my desk was beneath me |
| 🎚️ [PulseEQ](https://github.com/Nipuna-Lakruwan/PulseEQ) | System-wide 10-band equalizer in the menu bar | My headphones deserved better than "Flat" |
| 🛂 [Visa Photo Guide](https://nipuna-lakruwan.github.io/visa-photo-guide/) | Crop visa photos to official rules, fully in the browser | Smiling is between you and the embassy |
| 🌦️ [Weather Sentinel](https://github.com/Nipuna-Lakruwan/weather-sentinel) | Rain alerts on Telegram via Docker + Actions cron | Sri Lankan rain doesn't send calendar invites |
| 📰 [Lanka News Dashboard](https://github.com/Nipuna-Lakruwan/news-dashboard) | Redis cache vs. no cache, side by side | A very elaborate way of saying "cache it" |
| 🎓 [Face-recognition attendance](https://github.com/Nipuna-Lakruwan/face-recognition-based-attendance-system-py) | Real-time attendance from a webcam | The natural predator of proxy attendance |
| ☕ [Java Project-Based Learning](https://github.com/Nipuna-Lakruwan/Java-Project-Based-Learning) | Progressively harder Java projects for beginners | My most-starred repo. Teaching keeps me honest |

<div align="center"><a href="https://nipuna-lakruwan.github.io"><b>More on my portfolio →</b></a> <sub>(there's a laptop there that talks back)</sub></div>

---

<!-- ©2026 Nipuna Lakruwan | CC BY-NC-ND 4.0 | Do not copy or repurpose -->
## ⚡ The Arsenal

<div align="center">

**🤖 AI & retrieval**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain"/> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/> <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>

**🍎 Apple platforms**<br/>
<img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift"/> <img src="https://img.shields.io/badge/SwiftUI-0071E3?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI"/> <img src="https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white" alt="Xcode"/>

**☁️ DevOps**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>

**🖥️ Web & data**<br/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/> <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>

<sub>No percentage bars. Nobody is 90% at FastAPI. Not even FastAPI.</sub>

</div>

---

<!-- ©2026 Nipuna Lakruwan | CC BY-NC-ND 4.0 | Do not copy or repurpose -->
## 🧮 Numbers Nobody Asked For

| | |
|---:|:---|
| **47** | browser tabs open while building my portfolio |
| **4** | pieces Python's `\w` regex chops ජනාධිපතිවරයා into |
| **3%** | free disk space on my Mac. Please send SSDs |
| **0** | frameworks used on my portfolio |
| **∞** | cups of Ceylon tea per benchmark run |

---

<!-- ©2026 Nipuna Lakruwan | CC BY-NC-ND 4.0 | Do not copy or repurpose -->
## 🐍 Snake Is Eating My Commits

<div align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nipuna-lakruwan/nipuna-lakruwan/output/github-contribution-grid-snake-dark.svg"/><source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nipuna-lakruwan/nipuna-lakruwan/output/github-contribution-grid-snake.svg"/><img src="https://raw.githubusercontent.com/nipuna-lakruwan/nipuna-lakruwan/output/github-contribution-grid-snake-dark.svg" alt="&#83;&#110;&#97;&#107;&#101;&#32;&#65;&#110;&#105;&#109;&#97;&#116;&#105;&#111;&#110;" width="82%"/></picture></div>

<details>
<summary><b>📈 More stats, for the stats enjoyers</b></summary>
<br/>

<div align="center"><img src="https://streak-stats.demolab.com/?user=nipuna-lakruwan&theme=tokyonight&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" height="170" alt="&#71;&#105;&#116;&#72;&#117;&#98;&#32;&#83;&#116;&#114;&#101;&#97;&#107;"/></div>

<div align="center"><img src="https://github-readme-activity-graph.vercel.app/graph?username=nipuna-lakruwan&custom_title=Nipuna%27s%20Contribution%20Graph&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FFFFFF&area_color=58A6FF&area=true&hide_border=true&theme=react-dark" width="95%" alt="&#65;&#99;&#116;&#105;&#118;&#105;&#116;&#121;&#32;&#71;&#114;&#97;&#112;&#104;"/></div>

<div align="center"><img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="&#51;&#68;&#32;&#67;&#111;&#110;&#116;&#114;&#105;&#98;&#117;&#116;&#105;&#111;&#110;&#32;&#71;&#114;&#97;&#112;&#104;" width="92%"/></div>

<div align="center"><img src="./github-metrics.svg" alt="&#71;&#105;&#116;&#72;&#117;&#98;&#32;&#77;&#101;&#116;&#114;&#105;&#99;&#115;" width="76%"/></div>

</details>

---

<!-- ©2026 Nipuna Lakruwan | CC BY-NC-ND 4.0 | Do not copy or repurpose -->
## 🌐 Let's Connect

<div align="center"><a href="https://nipuna-lakruwan.github.io"><img src="https://img.shields.io/badge/Portfolio-2f6fd6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>&nbsp;<a href="https://www.linkedin.com/in/nipuna-lakruwan-6b740627a"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;<a href="mailto:senarath.lakruwan@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>&nbsp;<a href="https://pypi.org/project/lanka-rag/"><img src="https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="PyPI"/></a><br/><br/><em>"The best way to predict the future is to build it. The second best is to benchmark it."</em></div>

<br/>

---

<div align="center"><sub><a href="./LICENSE"><img src="https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey?style=flat-square&logo=creative-commons&logoColor=white&labelColor=0d1117" alt="&#76;&#105;&#99;&#101;&#110;&#115;&#101;&#58;&#32;&#67;&#67;&#32;&#66;&#89;&#45;&#78;&#67;&#45;&#78;&#68;&#32;&#52;&#46;&#48;"/></a>&nbsp;<img src="https://img.shields.io/badge/Copyright-2026%20Nipuna%20Lakruwan-58A6FF?style=flat-square&labelColor=0d1117" alt="&#67;&#111;&#112;&#121;&#114;&#105;&#103;&#104;&#116;"/></sub><br/><sub>&#169; 2026 <strong>&#78;&#105;&#112;&#117;&#110;&#97;&#32;&#76;&#97;&#107;&#114;&#117;&#119;&#97;&#110;</strong>. All custom design, SVG assets, layout, and content in this repository are protected under the <a href="./LICENSE">CC BY-NC-ND 4.0</a> license.<br/>You may <strong>not</strong> copy, clone, or repurpose any part of this profile without explicit written permission.<br/>Violations may be subject to a <strong>DMCA takedown</strong>. For permissions: <a href="mailto:senarath.lakruwan@gmail.com">senarath.lakruwan@gmail.com</a></sub></div>

<!-- ©2026 Nipuna Lakruwan | CC BY-NC-ND 4.0 | End of profile -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&reversal=true" width="100%" alt=""/>
