# Autonomous Warehouse Robot Simulation

**An intelligent warehouse robot simulation built using Python, Pygame, and the A* pathfinding algorithm.**

This project demonstrates autonomous robot navigation, path planning, and obstacle-aware movement in a virtual warehouse environment.

[![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/chandramolleti0-wq/autonomous-warehouse-robot)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## Table of Contents

- [Project Overview](#-project-overview)
- [Project Demonstration Video](#-project-demonstration-video)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [System Architecture](#-system-architecture)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Running the Project](#-running-the-project)
- [Running Tests](#-running-tests)
- [Applications](#-applications)
- [Limitations](#️-limitations)
- [Future Improvements](#-future-improvements)
- [Learning Outcomes](#-learning-outcomes)
- [License](#-license)
- [Author](#-author)

---

## Project Overview

The **Autonomous Warehouse Robot Simulation** is a Python-based project that demonstrates how a robot can navigate a warehouse environment and find a route to a destination while accounting for configured obstacles.

The project uses **Pygame** to visualize the simulation and the **A* pathfinding algorithm** to calculate routes.

The goal is to explore how intelligent navigation and path-planning techniques can be applied to warehouse automation concepts.

## Project Demonstration Video

Watch the project demonstration to see the warehouse robot simulation in action.

**[Click here to watch the project demonstration](https://drive.google.com/file/d/1ivjJZKlQ8gUq2K5xmkND5yT6qNJcvsV8/view?usp=drive_link)**

*The demonstration video is hosted on Google Drive.*

> **Important:** `https://drive.google.com/file/d/1ivjJZKlQ8gUq2K5xmkND5yT6qNJcvsV8/view?usp=drive_link`

## Features

- **Autonomous Navigation** — Simulates a robot navigating through a warehouse.
- **A* Pathfinding** — Calculates a route from a starting position to a destination.
- **Obstacle-Aware Path Planning** — Plans around configured obstacles when a valid route exists.
- **Warehouse Environment** — Represents a warehouse layout in a virtual environment.
- **Visual Simulation** — Uses Pygame to display the robot and its surroundings.
- **Configuration Support** — Uses JSON configuration for warehouse settings.
- **Automated Testing** — Includes a test suite for checking project functionality.
- **Optional Computer Vision Extension** — OpenCV can be used for extending the project with visual recognition, depending on the implemented modules.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pygame | Simulation graphics and visualization |
| A* Algorithm | Pathfinding and route planning |
| JSON | Warehouse configuration |
| Pytest | Automated testing |
| OpenCV | Optional computer vision extension |

## System Architecture

```text
       Warehouse Configuration
                  |
                  v
       Warehouse Environment
                  |
                  v
        Robot Start Position
                  |
                  v
          A* Pathfinding
                  |
                  v
       Obstacle-Aware Routing
                  |
                  v
          Robot Movement
                  |
                  v
       Pygame Visualization
```

### How It Works

1. **Environment Setup:** The warehouse layout is loaded from the project configuration.
2. **Robot Initialization:** The robot starts at its configured position.
3. **Path Planning:** The A* algorithm searches for a route to the destination.
4. **Obstacle Handling:** The route planner accounts for obstacles represented in the environment.
5. **Movement Simulation:** The robot follows the planned route according to the implemented logic.
6. **Visualization:** Pygame displays the warehouse and robot movement.

## Project Structure

```text
autonomous-warehouse-robot/
│
├── main.py
├── requirements.txt
│
├── src/
├── config/
│   └── warehouse.json
│
├── tests/
├── scripts/
├── assets/
│
├── README.md
└── LICENSE
```

*Note: This is a simplified overview. Your actual repository may contain additional files and modules.*

## Installation

### Prerequisites

- Python installed on your computer
- Git, if cloning the repository
- The dependencies listed in `requirements.txt`

The project documentation records testing with Python 3.12.3. Use a compatible Python version if you encounter dependency issues.

### Step 1: Clone the Repository

```bash
git clone https://github.com/chandramolleti0-wq/autonomous-warehouse-robot.git
```

### Step 2: Navigate to the Project Folder

```bash
cd autonomous-warehouse-robot
```

### Step 3: Create a Virtual Environment

```bash
python -m venv .venv
```

### Step 4: Activate the Virtual Environment

For Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

If PowerShell blocks activation, you can use the virtual environment's Python executable directly.

### Step 5: Install Dependencies

```bash
python -m pip install -r requirements.txt
```

## Running the Project

From the project root directory, run:

```bash
python main.py --demo
```

If the `--demo` option is not supported by your current version, check the options implemented in `main.py` and use the appropriate command.

Follow the on-screen instructions to interact with the simulation.

## Running Tests

Run the automated test suite with:

```bash
python -m pytest
```

The project documentation records **101 tests passed** in its documented testing environment. Results may vary depending on the code version and environment used.

## Applications

The concepts demonstrated in this project are relevant to:

- Warehouse automation
- Autonomous mobile robot navigation
- Pathfinding and route planning
- Robotics education and simulation
- Obstacle-aware navigation
- Smart logistics and material movement

These are potential application areas of the concepts, not claims of real-world deployment.

## Limitations

- This is a software simulation, not a physical warehouse robot.
- Navigation performance depends on the implemented algorithm and warehouse configuration.
- Real-world sensor integration and hardware control require additional development.
- Optional computer vision features depend on the actual implementation.
- Performance and functionality should be verified by running the project and its tests.

## Future Improvements

- Dynamic obstacle detection and path replanning
- Multiple robot coordination
- Package pickup and delivery simulation
- Warehouse task scheduling
- Route optimization and performance metrics
- Camera-based package recognition
- Reinforcement-learning-based navigation
- Integration with real robots and sensors
- Improved simulation graphics and reporting

## Learning Outcomes

This project provides an opportunity to explore:

- Python programming and modular project design
- A* pathfinding and route planning
- Obstacle-aware navigation
- Interactive simulation using Pygame
- JSON configuration management
- Automated testing and debugging
- Robotics and autonomous-system fundamentals

## License

This project is licensed under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the complete license text. Ensure that the file exists in the repository and contains the correct MIT License text.

## Author

**Chandra Sekhar Molleti**

- **GitHub Profile:** [chandramolleti0-wq](https://github.com/chandramolleti0-wq)
- **Project Repository:** [Autonomous Warehouse Robot Simulation](https://github.com/chandramolleti0-wq/autonomous-warehouse-robot)

---

⭐ If you find this project interesting, consider giving the repository a star.

**Built with Python to explore autonomous navigation, intelligent path planning, and robotics simulation.**
