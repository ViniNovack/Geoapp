# 📐 GeoApp — Geometry Reference for High School

An **interactive educational desktop application** built with **Processing 4**, designed to help high school students study and practice plane and spatial geometry. Developed as a team project using **AI as one of the development tools**.

---

## 🎯 Goal

GeoApp was created to give students a visual, interactive, and accessible way to study geometry — consulting formulas, understanding their derivations, calculating results in real time, and testing their knowledge through a built-in quiz.

---

## 🛠️ Technologies Used

![Processing](https://img.shields.io/badge/Processing_4-006699?style=for-the-badge&logo=processingfoundation&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

> 🤖 **AI was used as a development tool** throughout the project to assist with logic, design decisions, and problem solving.

---

## ✨ Features

### 🏠 Home Screen
- Animated main menu with decorative geometric shapes in the background
- Three navigation buttons: **2D Figures**, **3D Solids**, and **Quiz**
- Clean green-themed visual identity

### 📏 2D Figures
Six plane figures available through a sidebar menu, each with:

| Figure | Formula |
|---|---|
| Triangle (Equilateral, Isosceles, Scalene) | `A = b × h / 2` |
| Square / Rectangle | `A = l²` / `A = b × h` |
| Circle | `A = π × R²` |
| Regular Hexagon | `A = 3 × a² × √3 / 2` |
| Rhombus | `A = D × d / 2` |
| Trapezoid | `A = (B + b) × h / 2` |

Each figure screen includes:
- **Visual rendering** of the shape
- **Formula card** with a clickable deduction popup explaining how the formula is derived
- **Interactive calculator** — type in the values and get the area calculated in real time
- **Glossary panel** explaining each variable

### 🧊 3D Solids
Four solid categories available through a sidebar menu, each with:

| Solid | Variations | Formula |
|---|---|---|
| Prism | Square, Triangular, Hexagonal base | `V = Ab × h` |
| Pyramid | Square, Triangular, Hexagonal base | `V = Ab × h / 3` |
| Cone | — | `V = π × r² × h / 3` |
| Sphere | — | `V = 4 × π × r³ / 3` |

Each solid screen includes:
- **Animated 3D rendering** — the solid rotates automatically with lighting effects using the P3D renderer
- **Base area formula** with deduction popup
- **Volume formula** with deduction popup showing step-by-step derivation
- **Interactive volume calculator** with real-time results
- **Glossary panel** explaining each variable

### 📝 Quiz
A 10-question multiple-choice quiz covering both 2D and 3D geometry:
- **Progress bar** showing current question out of 10
- **A / B / C / D** answer options with hover highlights
- **Results screen** showing score, ✓ / ✗ per question, and the correct answer for each wrong response
- Option to **retry the quiz** or return to the home screen

### 🔊 Sound Effects
- Hover and click sounds powered by the **Processing Sound library**
- Graceful fallback if the library is not installed — the app runs normally without sound

---

## 📁 Project Structure

| 📄 File | 📖 Description |
|---|---|
| `app_atual.pde` | Main file — setup, draw loop, sound initialization and screen routing |
| `Inicial.pde` | Home screen rendering and navigation buttons |
| `dois_D.pde` | All 2D figure screens, sidebar menu and interactive area calculator |
| `tres_D.pde` | All 3D solid screens, sidebar menu, 3D rendering and volume calculator |
| `questionario.pde` | Quiz data, question flow, results screen and scoring logic |
| `funcoesUtilitarias.pde` | Shared UI components — cards, buttons, popups, input fields |
| `cores.pde` | Global color palette and theme variables |
| `variables.pde` | Global state variables — screen control, input values, assets |
| `sketch.properties` | Processing sketch configuration |

---

## ▶️ How to Run

1. Download and install **[Processing 4](https://processing.org/download)**
2. Clone or download this repository
3. Open the `app_atual.pde` file in Processing
4. *(Optional)* Install the **Sound** library via **Sketch → Import Library → Manage Libraries**
5. Click **Run** ▶️

---

## 👥 Team

Developed as a team project at **PUCPR** as part of the *Creative Experience exploring Artificial Intelligence* course.

Made with 💙 by **ViniNovack** and team
