Simulation of Agents and Structures

## Introduction

This project is a C++ based simulation of various agents and structures, modeling interactions within a simulated environment. The project includes several classes representing different types of agents, structures, and utilities to control and visualize the simulation.

## Directory Structure

The project files are organized as follows:

```
Final/
│
├── Agent.cpp
├── Agent.h
├── Agent_factory.cpp
├── Agent_factory.h
├── Controller.cpp
├── Controller.h
├── Farm.cpp
├── Farm.h
├── Geometry.cpp
├── Geometry.h
├── Model.cpp
├── Model.h
├── Moving_object.cpp
├── Moving_object.h
├── Peasant.cpp
├── Peasant.h
├── p_main.cpp
├── Sim_object.cpp
├── Sim_object.h
├── Soldier.cpp
├── Soldier.h
├── Structure.cpp
├── Structure.h
├── Structure_factory.cpp
├── Structure_factory.h
├── Town_Hall.cpp
├── Town_Hall.h
├── Utility.h
├── View.cpp
├── View.h
├── Views.cpp
└── Views.h
```

## Files Overview

### Agents

- **Agent.cpp / Agent.h**: Defines the base class for all agents in the simulation.
- **Agent_factory.cpp / Agent_factory.h**: Contains factory methods to create different types of agents.
- **Moving_object.cpp / Moving_object.h**: Defines a class for objects that have movement capabilities.
- **Peasant.cpp / Peasant.h**: Implements the Peasant class, a type of agent that can perform tasks.
- **Soldier.cpp / Soldier.h**: Implements the Soldier class, a type of agent with combat capabilities.

### Structures

- **Farm.cpp / Farm.h**: Implements the Farm class, a type of structure in the simulation.
- **Structure.cpp / Structure.h**: Defines the base class for all structures.
- **Structure_factory.cpp / Structure_factory.h**: Contains factory methods to create different types of structures.
- **Town_Hall.cpp / Town_Hall.h**: Implements the Town Hall class, a central structure in the simulation.

### Controllers and Models

- **Controller.cpp / Controller.h**: Manages the interaction between the user and the simulation.
- **Model.cpp / Model.h**: Represents the data model of the simulation, keeping track of agents and structures.
- **Sim_object.cpp / Sim_object.h**: Defines the base class for all simulation objects.

### Utilities

- **Geometry.cpp / Geometry.h**: Provides geometric calculations and utilities.
- **Utility.h**: Contains utility functions used throughout the project.

### Views

- **View.cpp / View.h**: Defines the base class for all views in the simulation.
- **Views.cpp / Views.h**: Implements different views for visualizing the simulation data.

### Main Program

- **p_main.cpp**: The entry point of the program, initializing and running the simulation.

## Compilation and Execution

To compile and run the project, follow these steps:

1. **Navigate to the Project Directory**:
   ```bash
   cd path/to/File
   ```

2. **Compile the Project**:
   ```bash
   g++ -o simulation p_main.cpp Agent.cpp Agent_factory.cpp Controller.cpp Farm.cpp Geometry.cpp Model.cpp Moving_object.cpp Peasant.cpp Sim_object.cpp Soldier.cpp Structure.cpp Structure_factory.cpp Town_Hall.cpp View.cpp Views.cpp
   ```

3. **Run the Executable**:
   ```bash
   ./simulation
   ```

## Key Classes and Their Responsibilities

### Agent

- **Agent**: Base class for all agents, managing position and state.
- **Moving_object**: Extends Agent, adding movement capabilities.
- **Peasant**: A specific type of agent that can collect and deliver resources.
- **Soldier**: A specific type of agent with combat capabilities.

### Structure

- **Structure**: Base class for all structures, managing resources and state.
- **Farm**: A type of structure that produces food.
- **Town_Hall**: A central structure for resource management.

### Controller and Model

- **Controller**: Manages user input and directs the simulation.
- **Model**: Holds the state of the simulation, including all agents and structures.

### Utilities

- **Geometry**: Provides geometric calculations, such as distance and angles.
- **Utility**: A collection of helper functions.

### Views

- **View**: Base class for displaying the simulation state.
- **Views**: Different implementations of views for various aspects of the simulation.

## Future Enhancements

- Adding more types of agents and structures.
- Implementing advanced interactions between agents and structures.
- Enhancing the user interface for better visualization and control.


## Acknowledgments

- Developed by Zeinab Sattarian
- Inspired by various agent-based modeling techniques and simulations.

---

For any issues, contributions, or feature requests, please open an issue or submit a pull request.
