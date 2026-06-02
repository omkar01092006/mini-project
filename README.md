# 🗺️ GBFS Route Planner — Greedy Best-First Search Visualizer

An interactive route-planning application that demonstrates the **Greedy Best-First Search (GBFS)** algorithm through real-time visualization on a city map. The project animates node exploration, displays routing metrics, and illustrates how heuristic-based search operates in artificial intelligence.

> The frontend implementation is fully integrated into `index.html`.

---

## ✨ Features

### 🚀 Greedy Best-First Search Engine

* Implements the **Greedy Best-First Search (GBFS)** algorithm.
* Uses the **Haversine Distance Formula** as the heuristic function `h(n)` to estimate the straight-line distance from a node to the destination.

### 🎬 Interactive Visualization

* Step-by-step animation of node expansion.
* Displays exploration order in real time.
* Highlights visited nodes and selected routes dynamically.

### ⚡ Adjustable Animation Speed

* Interactive slider to control visualization speed.
* Allows users to observe the algorithm at different execution rates.

### 📊 Performance Metrics Dashboard

Tracks:

* Total distance traveled
* Number of node expansions
* Path length
* Search efficiency
* Route completion statistics

### 🗺️ Responsive SVG Map Interface

* Custom SVG-based city map rendering.
* Interactive node tooltips.
* Dynamic path highlighting.
* Responsive layout for different screen sizes.

---

## 🛠️ Tech Stack

| Technology        | Purpose                     |
| ----------------- | --------------------------- |
| Python 3.x        | Backend & Algorithm Logic   |
| Flask             | Web Server                  |
| HTML5             | Structure                   |
| CSS3              | Styling & Animations        |
| JavaScript (ES6+) | Visualization & Interaction |
| SVG               | Interactive Map Rendering   |

### Typography

* **Syne** – Headings and visual branding
* **JetBrains Mono** – Metrics, logs, and technical data

---

## 📁 Project Structure

```text
gbfs-route-planner/
│
├── app.py                  # Flask application
├── gbfs_planner.py         # GBFS algorithm implementation
│
├── templates/
│   └── index.html          # UI, styling, and visualization logic
│
└── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gbfs-route-planner.git
cd gbfs-route-planner
```

### 2. Install Dependencies

```bash
pip install flask
```

### 3. Verify Python Installation

```bash
python --version
```

---

## ▶️ Run Standalone Algorithm

Execute only the routing logic:

```bash
python gbfs_planner.py
```

---

## 🌐 Run the Web Application

Start the Flask server:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

---

## 🧠 How Greedy Best-First Search Works

GBFS chooses the node that appears closest to the goal according to a heuristic function.

### Heuristic Function

```text
h(n) = Haversine Distance to Goal
```

At each step, the algorithm expands the neighboring node with the smallest heuristic value.

### Advantages

* Fast exploration
* Low computational overhead
* Easy to visualize

### Limitations

* Does not guarantee the shortest path
* Can become trapped in locally optimal routes
* Less accurate than Dijkstra's Algorithm or A* Search

---

## 📸 Screenshots

Add screenshots of your visualizer here:

```text
screenshots/
├── home.png
├── route-search.png
└── metrics-panel.png
```

---

## 🔮 Future Enhancements

* A* Search Comparison Mode
* Dijkstra Algorithm Integration
* Real Map API Support
* Multiple Destination Routing
* Route Export Functionality
* Dark/Light Theme Toggle

---

## 👨‍💻 Author

Developed as an educational Artificial Intelligence project to demonstrate heuristic search algorithms and interactive pathfinding visualization.

⭐ If you found this project useful, consider giving it a star!
