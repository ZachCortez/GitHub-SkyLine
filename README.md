
---
## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Cityscape%20at%20Dusk.png" alt="Cityscape at Dusk" width="50" height="50" align="center" />   **GitHub‑SkyLine – 3D Commit History Viewer (2020–2025)**

This project showcases my personalized GitHub Skyline — a 3D visualization of my GitHub commit history from **2020 to 2025**, turned into a physical skyline you can view, interact with, or even 3D print!

![SkyLine Preview](https://raw.githubusercontent.com/ZachCortez/GitHub-SkyLine/main/skyline-preview.gif)

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Travel%20and%20Places/Classical%20Building.webp" alt="Classical Building" width="50" height="50" align="center"/> Interactive 3D Viewer

Click below to explore the skyline in your browser:

[![3D GitHub Skyline Preview](https://raw.githubusercontent.com/ZachCortez/GitHub-SkyLine/main/skyline-preview.png)](https://zachcortez.github.io/GitHub-SkyLine/viewer.html)

> <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/People/Index%20Pointing%20Up.webp" alt="Index Pointing Up" width="45" height="45" /> _Click the image to launch the 3D model viewer._

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Card%20Index%20Dividers.webp" alt="Card Index Dividers" width="50" height="50" align="center"/> Downloadable Files

- <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Crystal%20Ball.png" alt="Crystal Ball" width="35" height="35" align="center"/> [`ZachCortez-2020-25-github-skyline.stl`](https://raw.githubusercontent.com/ZachCortez/GitHub-SkyLine/main/ZachCortez-2020-25-github-skyline.stl) – 3D model file
- <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Activity/Video%20Game.webp" alt="Video Game" width="35" height="35" align="center"/> [`viewer.html`](https://zachcortez.github.io/GitHub-SkyLine/viewer.html) – Web viewer using [`<model-viewer>`](https://modelviewer.dev)

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Printer.webp" alt="Printer" width="50" height="50" align="center"/> 3D Printing

You can download the STL and send it to your favorite 3D printer:

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Flying%20Saucer.png" alt="Flying Saucer" width="45" height="45" align="center"/> [Download STL](https://raw.githubusercontent.com/ZachCortez/GitHub-SkyLine/main/ZachCortez-2020-25-github-skyline.stl)

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Animals%20and%20Nature/High%20Voltage.webp" alt="High Voltage" width="50" height="50" align="center"/> Features

- <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Tear%20Off%20Calendar.webp" alt="Tear Off Calendar" width="35" height="35" align="center"/>**3D STL Export (2020–2025):** Visualize multi‑year GitHub history in 3D
- <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Bar%20Chart.webp" alt="Bar Chart" width="35" height="35" align="center"/> **ASCII & CLI Preview:** Terminal preview before generating STL
- <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Animals%20and%20Nature/Cactus.webp" alt="Cactus" width="35" height="35" align="center"/> **Branch/Model Customization:** Choose branch or commit-specific views
- <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Locked%20With%20Key.webp" alt="Locked With Key" width="35" height="35" align="center"/> **No API Token Needed:** Uses authenticated `gh` CLI user automatically

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Toolbox.webp" alt="Toolbox" width="50" height="50"/> Tech Stack

- **Go (Golang)** – Core CLI logic
- **GitHub CLI (`gh`)** – Authentication & repo metadata
- **STL Model Builder** – Renders daily commits as skyline "towers"

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Syringe.webp" alt="Syringe" width="50" height="50" align="center"/> Installation

> **Step 1:** Authenticate GitHub CLI  
```bash
gh auth login
````

> **Step 2:** Install Skyline CLI extension

```bash
gh extension install github/gh-skyline
```

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Memo.webp" alt="Memo" width="50" height="50" /> Usage

| Command                       | Description                           |
| ----------------------------- | ------------------------------------- |
| `gh skyline`                  | Generate current year skyline         |
| `gh skyline --year 2020`      | Generate 2020 only                    |
| `gh skyline --year 2020-2025` | Multi-year skyline                    |
| `gh skyline --full`           | From GitHub join year through present |
| `-o`, `--output`              | Output file name                      |
| `-a`, `--art-only`            | Terminal preview only                 |
| `-d`, `--debug`               | Verbose CLI logging                   |
| `-u`, `--user`                | Specify GitHub username               |
| `-w`, `--web`                 | Open GitHub profile in browser        |

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Symbols/New%20Button.webp" alt="New Button" width="45" height="45" /> Example

```bash
gh skyline --year 2020-2025 -o zach-skyline-2020-2025.stl
```

Generate a skyline spanning your GitHub commit history from 2020 to 2025.

Terminal-only preview:

```bash
gh skyline --art-only
```

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Test%20Tube.webp" alt="Test Tube" width="50" height="50" align="center"/> How It Works

1. <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Inbox%20Tray.webp" alt="Inbox Tray" width="35" height="35" align="center"/> Pulls GitHub commit data using your authenticated account
2. <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Bar%20Chart.webp" alt="Bar Chart" width="35" height="35" align="center"/> Converts contributions into ASCII skyline
3. <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Travel%20and%20Places/Classical%20Building.webp" alt="Classical Building" width="35" height="35" align="center"/> Renders 3D STL model for download or printing

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Smileys/Robot.webp" alt="Robot" width="50" height="50" align="center"/> Project Structure

```
/
├── cmd/           • CLI entrypoint & flags  
├── github/        • GitHub API interaction  
├── ascii/         • Terminal skyline renderer  
├── stl/           • STL model creation  
├── types/         • Shared struct definitions  
└── main.go        • Brings everything together  
```

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Keyboard.webp" alt="Keyboard" width="50" height="50" align="center"/> Embed on Your GitHub Profile

To embed your STL model with preview:

```html
<script src="https://embed.github.com/view/3d/ZachCortez/GitHub-SkyLine/main/ZachCortez-2020-25-github-skyline.stl"></script>
```

---


## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Symbols/Free%20Button.webp" alt="Free Button" width="45" height="45" align="center"/> License

MIT License — see `LICENSE` for more info.
Skyline generated via: [skyline.github.com](https://skyline.github.com)

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/People/Man%20Technologist.webp" alt="Man Technologist" width="50" height="50" align="center"/> About Me

**Zach Cortez**
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Laptop.webp" alt="Laptop" width="35" height="35" align="center"/> GitHub: [@ZachCortez](https://github.com/ZachCortez)
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Objects/Identification%20Card.webp" alt="Identification Card" width="35" height="35" align="center"/> Portfolio: [zachcortez3dportfolio.vercel.app](https://zachcortez3dportfolio.vercel.app)


---
