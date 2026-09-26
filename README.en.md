<p align="right"><sub><a href="./README.md">Português</a> · <b>English</b></sub></p>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg" />
  <img width="100%" alt="Matheus Lemes — the GamaSat-01 CubeSat in orbit points its sensor at the ocean, where an oil slick is segmented and linked to a vessel's AIS position" src="./assets/hero-dark.svg" />
</picture>
</p>

<p align="center">
  <b>Software that senses the physical world — from sensor to neural network.</b><br />
  <sub>Software Engineering @ UnB/FCTE · Brasília, Brazil · AI · Computer Vision · Embedded Systems</sub>
</p>

<p align="center">
  <a href="https://matheus-lemes.matheuslemesam.chatgpt.site">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://github.com/1emes?tab=repositories">Repositories</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/matheus-lemes-amaral-877a71309/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:matheuslemesam@gmail.com">Email</a>
</p>

## Hi there! 👋

I'm **Matheus**, a Software Engineering student at the **University of Brasília (UnB/FCTE)**. I like software that leaves the screen and touches the real world: cameras, sensors, satellites, and the models that make sense of the data they produce.

- 🧠 My current focus is **artificial intelligence**, especially **deep learning** and **computer vision**.
- 🛰️ I'm a former member of **Gama CubeDesign**, where I took part in the **GamaSat-01** mission.
- ⚙️ I work with **embedded systems and telemetry** for high-altitude missions.
- 🌐 When an idea needs an interface, I build it with **TypeScript, React and Node**.

## 🛰️ GamaSat-01 Mission

<table>
<tr>
<td>

At **Gama CubeDesign**, UnB/FCTE's CubeSat team, I took part in the **GamaSat-01** mission for the **CubeDesign 2025** competition, working on the payload's **remote sensing**.

The goal: from the images captured by the satellite, **detect oil slicks at sea** and **identify the vessel responsible**, cross-checking the slick's position against the **AIS** data of ships in the area.

```text
camera ─▶ HSV mask ─▶ contour + area ─▶ mission grid ─▶ AIS cross-check ─▶ polluter MMSI ─▶ JSON
```

- Slick segmentation in **HSV** color space with **OpenCV** (thresholding, morphology and contours)
- Computing and stabilizing the **slick area** across frames
- Converting pixels into the **mission coordinate system**
- Vessel detection with the **Hough transform**
- Identifying the polluter by the **minimum distance** between a ship (AIS) and the slick contour, with **JSON** output

<sub><samp>C++ · OpenCV · AIS</samp></sub> &nbsp;→&nbsp; **[Sensoriamento-CubeDesign2025](https://github.com/1emes/Sensoriamento-CubeDesign2025)**

</td>
</tr>
</table>

## 🔭 Journey

| | Where | What |
|:-:|---|---|
| 🎈 | **Laboratório Céu Aberto** | Embedded systems, telemetry and tracking for high-altitude missions |
| 🛰️ | **Gama CubeDesign** <sub>· former member</sub> | GamaSat-01 mission — remote sensing and electronics trainee program |
| 🔭 | **LaSE · Sapiens-1** | Project of UnB's Space Systems Laboratory (Laboratório de Sistemas Espaciais) |

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/strata-divider-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/strata-divider-light.svg" />
  <img width="100%" alt="" src="./assets/strata-divider-dark.svg" />
</picture>
</p>

## 🧪 Projects

**[MRI-segmentation](https://github.com/1emes/MRI-segmentation)** &nbsp;<sub><samp>Python · computer vision</samp></sub><br />
Brain tumor detection in magnetic resonance images.

**[Image-Captioning-DL](https://github.com/1emes/Image-Captioning-DL)** &nbsp;<sub><samp>PyTorch · encoder–decoder</samp></sub><br />
A CNN encoder paired with LSTM, GRU and Transformer decoders, compared head to head for automatic image captioning.

**[ds18b20-Esp](https://github.com/1emes/ds18b20-Esp)** &nbsp;<sub><samp>C++ · ESP · IoT</samp></sub><br />
A DS18B20 temperature sensor on an ESP microcontroller, with readings served by an embedded web server.

<details>
<summary><samp>More experiments</samp></summary>
<br />

- **[Bird_Detection-DL](https://github.com/1emes/Bird_Detection-DL)** — Bird species detection with convolutional networks.
- **[IA2-CNN-FineTuning-GradCam](https://github.com/1emes/IA2-CNN-FineTuning-GradCam)** — CNN fine-tuning, explained with Grad-CAM.
- **[EDA-2025.2](https://github.com/1emes/EDA-2025.2)** — Data structures in C (UnB).
- **[Crusty](https://github.com/1emes/Crusty)** — A compiler written in Rust — fork of a team project for Compilers 1.

</details>

## 🧰 Stack

<table>
  <tr><td><samp>AI / ML</samp></td><td><img src="https://img.shields.io/badge/PyTorch-0B1220?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" /> <img src="https://img.shields.io/badge/TensorFlow-0B1220?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow" /> <img src="https://img.shields.io/badge/Keras-0B1220?style=flat-square&logo=keras&logoColor=D00000" alt="Keras" /> <img src="https://img.shields.io/badge/OpenCV-0B1220?style=flat-square&logo=opencv&logoColor=5C3EE8" alt="OpenCV" /> <img src="https://img.shields.io/badge/Jupyter-0B1220?style=flat-square&logo=jupyter&logoColor=F37626" alt="Jupyter" /></td></tr>
  <tr><td><samp>Embedded</samp></td><td><img src="https://img.shields.io/badge/C-0B1220?style=flat-square&logo=c&logoColor=A8B9CC" alt="C" /> <img src="https://img.shields.io/badge/C%2B%2B-0B1220?style=flat-square&logo=cplusplus&logoColor=00599C" alt="C++" /> <img src="https://img.shields.io/badge/ESP32-0B1220?style=flat-square&logo=espressif&logoColor=E7352C" alt="ESP32" /> <img src="https://img.shields.io/badge/Arduino-0B1220?style=flat-square&logo=arduino&logoColor=00979D" alt="Arduino" /></td></tr>
  <tr><td><samp>Web</samp></td><td><img src="https://img.shields.io/badge/TypeScript-0B1220?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" /> <img src="https://img.shields.io/badge/React-0B1220?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Node.js-0B1220?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" /></td></tr>
  <tr><td><samp>Languages</samp></td><td><img src="https://img.shields.io/badge/Python-0B1220?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" /> <img src="https://img.shields.io/badge/Rust-0B1220?style=flat-square&logo=rust&logoColor=F74C00" alt="Rust" /> <img src="https://img.shields.io/badge/Bash-0B1220?style=flat-square&logo=gnubash&logoColor=4EAA25" alt="Bash" /></td></tr>
  <tr><td><samp>Tools</samp></td><td><img src="https://img.shields.io/badge/Claude%20Code-0B1220?style=flat-square&logo=claude&logoColor=D97757" alt="Claude Code" /> <img src="https://img.shields.io/badge/Codex-0B1220?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjRTZFREYzIiBzdHJva2Utd2lkdGg9IjIuNCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJNNCA2bDYgNi02IDZNMTMgMThoNyIvPjwvc3ZnPg==" alt="Codex" /> <img src="https://img.shields.io/badge/Docker-0B1220?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" /> <img src="https://img.shields.io/badge/Git-0B1220?style=flat-square&logo=git&logoColor=F05033" alt="Git" /> <img src="https://img.shields.io/badge/GitHub-0B1220?style=flat-square&logo=github&logoColor=E6EDF3" alt="GitHub" /></td></tr>
  <tr><td><samp>Environment</samp></td><td><img src="https://img.shields.io/badge/Arch%20Linux-0B1220?style=flat-square&logo=archlinux&logoColor=1793D1" alt="Arch Linux" /> <img src="https://img.shields.io/badge/Hyprland-0B1220?style=flat-square&logo=hyprland&logoColor=58E1FF" alt="Hyprland" /> <img src="https://img.shields.io/badge/Vim-0B1220?style=flat-square&logo=vim&logoColor=019733" alt="Vim" /></td></tr>
</table>

## 📡 Contact

Always happy to talk about **AI, computer vision, embedded systems and space projects**.

<p>
  <a href="https://matheus-lemes.matheuslemesam.chatgpt.site"><img src="https://img.shields.io/badge/Portfolio-57D9E8?style=for-the-badge&labelColor=0B1220&logo=googlechrome&logoColor=0B1220" alt="Portfolio" /></a>
  <a href="mailto:matheuslemesam@gmail.com"><img src="https://img.shields.io/badge/Email-F3B66A?style=for-the-badge&logo=gmail&logoColor=0B1220" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/matheus-lemes-amaral-877a71309/"><img src="https://img.shields.io/badge/LinkedIn-B6A0FF?style=for-the-badge&logo=linkedin&logoColor=0B1220" alt="LinkedIn" /></a>
</p>

<p align="center"><sub>Thanks for stopping by! ✦</sub></p>
