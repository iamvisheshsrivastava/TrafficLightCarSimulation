# Traffic Light Car Simulation

Traffic Light Car Simulation is a project implemented in C++ that models the interaction between cars and traffic lights. It demonstrates basic object-oriented programming concepts, simulation techniques, and UI integration using Qt.

## Features

1. **Traffic Light Simulation**  
   - Models the behavior of a traffic light, including state changes between red, yellow, and green.

2. **Car Interaction**  
   - Simulates cars responding to the traffic light signals, showcasing realistic behavior.

3. **Graphical User Interface**  
   - Implements a user interface to visualize the simulation using Qt, allowing users to observe car and traffic light interactions.

4. **Object-Oriented Design**  
   - Utilizes C++ classes for a modular and extensible design (`Car`, `TrafficLight`, etc.).

## Project Structure

- **`Car.cpp` / `Car.h`**: Contains the implementation of the `Car` class, including car-specific behaviors and attributes.
- **`TrafficLight.cpp` / `TrafficLight.h`**: Implements the `TrafficLight` class, including state management and timing logic.
- **`main.cpp`**: Entry point of the application that initializes and runs the simulation.
- **`mainwindow.cpp` / `mainwindow.h` / `mainwindow.ui`**: Defines the graphical user interface using Qt.
- **`CMakeLists.txt`**: Build configuration file for compiling the project using CMake.

## Prerequisites

- **Development Environment**: Any C++ IDE or text editor with CMake support (e.g., CLion, Visual Studio, Qt Creator).
- **Build Tools**: CMake.
- **Dependencies**: Qt framework for UI components.

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone <repository_url>
   cd TrafficLightCarSimulation
   ```

2. **Build the Project**
   - Configure the project using CMake:
     ```bash
     cmake .
     ```
   - Build the executable:
     ```bash
     make
     ```

3. **Run the Simulation**
   - Execute the compiled binary:
     ```bash
     ./TrafficLightCarSimulation
     ```
