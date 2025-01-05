<!-- PROJECT TITLE & BADGES -->
# Traffic Light Car Simulation 
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)](#)
[![Qt](https://img.shields.io/badge/Qt-Framework-2596be.svg)](https://www.qt.io/)

Traffic Light Car Simulation is a **C++** project that demonstrates the interaction between cars and traffic lights. It highlights fundamental **Object-Oriented Programming** principles, **simulation** mechanics, and integrates a **Qt**-based user interface.

<div align="center">
  <img src="images/traffic-light-simulation.png" alt="Traffic Light Simulation Illustration" width="400"/>
</div>



---

## Table of Contents
1. [Features](#features)
2. [Project Structure](#project-structure)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
5. [License](#license)
6. [Contributing](#contributing)

---

## Features

1. **Traffic Light Simulation**  
   - Models the behavior of a traffic light, including transitions between **Red**, **Yellow**, and **Green** states.

2. **Car Interaction**  
   - Simulates cars that respond to the traffic light signals, displaying realistic stopping, waiting, and moving behaviors.

3. **Graphical User Interface**  
   - Integrates a user-friendly **Qt** interface to visualize traffic light changes and car movements in real time.

4. **Object-Oriented Design**  
   - Employs **C++ classes** (`Car`, `TrafficLight`, etc.) for maintainable, modular, and extensible code.

---

## Project Structure

```
TrafficLightCarSimulation/
├── Car.cpp / Car.h             # Implementation of the Car class and its attributes/behaviors
├── TrafficLight.cpp / TrafficLight.h  # Manages traffic light states (red, yellow, green) and timing
├── main.cpp                    # Application entry point; initializes and runs the simulation
├── mainwindow.cpp / .h / .ui   # Qt-based GUI files for visualizing the simulation
└── CMakeLists.txt              # Build configuration via CMake
```

---

## Prerequisites

- **Development Environment**  
  Any C++ IDE or text editor with CMake support (e.g., *CLion, Visual Studio, Qt Creator*).
  
- **Build Tools**  
  - [CMake](https://cmake.org/)

- **Dependencies**  
  - [Qt Framework](https://www.qt.io/) (for GUI components)

---

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository_url>
cd TrafficLightCarSimulation
```

### 2. Build the Project

1. **Configure** the project using CMake:
   
   ```bash
   cmake .
   ```

2. **Compile** the project:
   
   ```bash
   make
   ```

### 3. Run the Simulation

```bash
./TrafficLightCarSimulation
```

> **Note**  
> Depending on your operating system or IDE, you may need to run the executable differently (e.g., `.exe` on Windows).

---

## License

Distributed under the **MIT License**. See the [LICENSE](LICENSE) file for more information.

---

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to help make this project even better. 

1. **Fork** the Project
2. **Create** your Feature Branch (`git checkout -b feature/NewFeature`)
3. **Commit** your Changes (`git commit -m 'Add a NewFeature'`)
4. **Push** to the Branch (`git push origin feature/NewFeature`)
5. **Open** a Pull Request

---

<p align="center">Happy Coding! 🚦</p>
