<p align="right"><sub><b>Português</b> · <a href="./README.en.md">English</a></sub></p>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg" />
  <img width="100%" alt="Matheus Lemes — uma imagem passa por camadas convolucionais e por uma rede neural até a classe prevista" src="./assets/hero-dark.svg" />
</picture>
</p>

<p align="center">
  <b>Software que percebe o mundo físico — do sensor à rede neural.</b><br />
  <sub>Engenharia de Software @ UnB · Brasília · IA · Visão Computacional · Sistemas Embarcados</sub>
</p>

<p align="center">
  <a href="https://matheus-lemes.matheuslemesam.chatgpt.site">Portfólio</a> &nbsp;·&nbsp;
  <a href="https://github.com/1emes?tab=repositories">Repositórios</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/matheus-lemes-amaral-877a71309/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:matheuslemesam@gmail.com">E-mail</a>
</p>

## Olá! 👋

Sou o **Matheus**, estudante de Engenharia de Software na **Universidade de Brasília (UnB)**. Gosto de software que sai da tela e encosta no mundo real: câmeras, sensores, satélites e os modelos que dão sentido aos dados que eles geram.

- 🧠 Meu foco hoje é **inteligência artificial** — em especial **deep learning** e **visão computacional**.
- 🛰️ Fui integrante da **Gama CubeDesign**, onde participei da missão **GamaSat-01**.
- ⚙️ Trabalho com **sistemas embarcados e telemetria** para missões de alta altitude.
- 🌐 Quando uma ideia precisa de interface, construo com **TypeScript, React e Node**.

## 🛰️ Missão GamaSat-01

<table>
<tr>
<td>

Na **Gama CubeDesign**, equipe de CubeSat da UnB, participei da missão **GamaSat-01** para a competição **CubeDesign 2025**, trabalhando no **sensoriamento remoto** da carga útil.

O objetivo: a partir das imagens capturadas pelo satélite, **detectar manchas de óleo no mar** e **identificar a embarcação responsável**, cruzando a posição da mancha com os dados **AIS** dos navios na região.

```text
câmera ─▶ máscara HSV ─▶ contorno + área ─▶ grade da missão ─▶ cruzamento AIS ─▶ MMSI do poluidor ─▶ JSON
```

- Segmentação da mancha no espaço de cor **HSV** com **OpenCV** (limiarização, morfologia e contornos)
- Cálculo e estabilização da **área da mancha** ao longo dos frames
- Conversão de pixels para o **sistema de coordenadas da missão**
- Detecção de embarcações com **transformada de Hough**
- Identificação do poluidor pela **menor distância** entre navio (AIS) e contorno da mancha, com saída em **JSON**

<sub><samp>C++ · OpenCV · AIS</samp></sub> &nbsp;→&nbsp; **[Sensoriamento-CubeDesign2025](https://github.com/1emes/Sensoriamento-CubeDesign2025)**

</td>
</tr>
</table>

## 🔭 Trajetória

| | Onde | O quê |
|:-:|---|---|
| 🎈 | **Laboratório Céu Aberto** | Sistemas embarcados, telemetria e rastreamento para missões de alta altitude |
| 🛰️ | **Gama CubeDesign** <sub>· ex-integrante</sub> | Missão GamaSat-01 — sensoriamento remoto e processo trainee de eletrônica |
| 🔭 | **LaSE · Sapiens-1** | Projeto do Laboratório de Sistemas Espaciais da UnB |

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/strata-divider-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/strata-divider-light.svg" />
  <img width="100%" alt="" src="./assets/strata-divider-dark.svg" />
</picture>
</p>

## 🧪 Projetos

**[MRI-segmentation](https://github.com/1emes/MRI-segmentation)** &nbsp;<sub><samp>Python · visão computacional</samp></sub><br />
Detecção de tumores cerebrais em imagens de ressonância magnética.

**[Image-Captioning-DL](https://github.com/1emes/Image-Captioning-DL)** &nbsp;<sub><samp>PyTorch · encoder–decoder</samp></sub><br />
Encoder CNN combinado com decoders LSTM, GRU e Transformer, comparados lado a lado na geração automática de legendas.

**[ds18b20-Esp](https://github.com/1emes/ds18b20-Esp)** &nbsp;<sub><samp>C++ · ESP · IoT</samp></sub><br />
Sensor de temperatura DS18B20 em um microcontrolador ESP, com leituras servidas por um servidor web embarcado.

<details>
<summary><samp>Mais experimentos</samp></summary>
<br />

- **[Bird_Detection-DL](https://github.com/1emes/Bird_Detection-DL)** — Detecção de espécies de pássaros com redes convolucionais.
- **[IA2-CNN-FineTuning-GradCam](https://github.com/1emes/IA2-CNN-FineTuning-GradCam)** — Fine-tuning de CNN, explicado com Grad-CAM.
- **[EDA-2025.2](https://github.com/1emes/EDA-2025.2)** — Estruturas de dados em C (UnB).
- **[Crusty](https://github.com/1emes/Crusty)** — Compilador escrito em Rust — fork do projeto em equipe de Compiladores 1.

</details>

## 🧰 Stack

<table>
  <tr><td><samp>IA / ML</samp></td><td><img src="https://img.shields.io/badge/PyTorch-0B1220?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" /> <img src="https://img.shields.io/badge/TensorFlow-0B1220?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow" /> <img src="https://img.shields.io/badge/Keras-0B1220?style=flat-square&logo=keras&logoColor=D00000" alt="Keras" /> <img src="https://img.shields.io/badge/OpenCV-0B1220?style=flat-square&logo=opencv&logoColor=5C3EE8" alt="OpenCV" /> <img src="https://img.shields.io/badge/Jupyter-0B1220?style=flat-square&logo=jupyter&logoColor=F37626" alt="Jupyter" /></td></tr>
  <tr><td><samp>Embarcados</samp></td><td><img src="https://img.shields.io/badge/C-0B1220?style=flat-square&logo=c&logoColor=A8B9CC" alt="C" /> <img src="https://img.shields.io/badge/C%2B%2B-0B1220?style=flat-square&logo=cplusplus&logoColor=00599C" alt="C++" /> <img src="https://img.shields.io/badge/ESP32-0B1220?style=flat-square&logo=espressif&logoColor=E7352C" alt="ESP32" /> <img src="https://img.shields.io/badge/Arduino-0B1220?style=flat-square&logo=arduino&logoColor=00979D" alt="Arduino" /></td></tr>
  <tr><td><samp>Web</samp></td><td><img src="https://img.shields.io/badge/TypeScript-0B1220?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" /> <img src="https://img.shields.io/badge/React-0B1220?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Node.js-0B1220?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" /></td></tr>
  <tr><td><samp>Linguagens</samp></td><td><img src="https://img.shields.io/badge/Python-0B1220?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" /> <img src="https://img.shields.io/badge/Rust-0B1220?style=flat-square&logo=rust&logoColor=F74C00" alt="Rust" /> <img src="https://img.shields.io/badge/Bash-0B1220?style=flat-square&logo=gnubash&logoColor=4EAA25" alt="Bash" /></td></tr>
  <tr><td><samp>Ferramentas</samp></td><td><img src="https://img.shields.io/badge/Claude%20Code-0B1220?style=flat-square&logo=claude&logoColor=D97757" alt="Claude Code" /> <img src="https://img.shields.io/badge/Codex-0B1220?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjRTZFREYzIiBzdHJva2Utd2lkdGg9IjIuNCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJNNCA2bDYgNi02IDZNMTMgMThoNyIvPjwvc3ZnPg==" alt="Codex" /> <img src="https://img.shields.io/badge/Docker-0B1220?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" /> <img src="https://img.shields.io/badge/Git-0B1220?style=flat-square&logo=git&logoColor=F05033" alt="Git" /> <img src="https://img.shields.io/badge/GitHub-0B1220?style=flat-square&logo=github&logoColor=E6EDF3" alt="GitHub" /></td></tr>
  <tr><td><samp>Ambiente</samp></td><td><img src="https://img.shields.io/badge/Arch%20Linux-0B1220?style=flat-square&logo=archlinux&logoColor=1793D1" alt="Arch Linux" /> <img src="https://img.shields.io/badge/Hyprland-0B1220?style=flat-square&logo=hyprland&logoColor=58E1FF" alt="Hyprland" /> <img src="https://img.shields.io/badge/Vim-0B1220?style=flat-square&logo=vim&logoColor=019733" alt="Vim" /></td></tr>
</table>

## 📡 Contato

Sempre aberto a conversar sobre **IA, visão computacional, sistemas embarcados e projetos espaciais**.

<p>
  <a href="https://matheus-lemes.matheuslemesam.chatgpt.site"><img src="https://img.shields.io/badge/Portf%C3%B3lio-57D9E8?style=for-the-badge&labelColor=0B1220&logo=googlechrome&logoColor=0B1220" alt="Portfólio" /></a>
  <a href="mailto:matheuslemesam@gmail.com"><img src="https://img.shields.io/badge/E--mail-F3B66A?style=for-the-badge&logo=gmail&logoColor=0B1220" alt="E-mail" /></a>
  <a href="https://www.linkedin.com/in/matheus-lemes-amaral-877a71309/"><img src="https://img.shields.io/badge/LinkedIn-B6A0FF?style=for-the-badge&logo=linkedin&logoColor=0B1220" alt="LinkedIn" /></a>
</p>

<p align="center"><sub>Obrigado pela visita! ✦</sub></p>
