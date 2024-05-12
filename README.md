# Fire Evacuation Simulation in a Slum Area

Welcome to the Fire Evacuation Simulation in a Slum Area repository! This project aims to simulate and analyze the evacuation dynamics of individuals within densely populated and economically disadvantaged urban settings during fire outbreaks. 🏙️🔥

## Overview

The **Fire Evacuation Simulation** is a sophisticated computational model developed to study and optimize evacuation strategies in slum communities facing fire emergencies. By accurately modeling the behavior of individuals during evacuations, this simulation provides valuable insights into the dynamics of evacuation processes and informs evidence-based interventions to enhance the safety and resilience of slum communities.

<img src="https://github.com/Rishit-katiyar/SlumFireEvacuationSimulation/assets/167756997/208b268b-bd72-422b-82c9-615bedcfc650" alt="awuidhiwaudhau7ry3eh" style="width: 49%; float: left;">
<img src="https://github.com/Rishit-katiyar/SlumFireEvacuationSimulation/assets/167756997/b4f36be2-b2d8-4c15-b3ad-bca5600bca35" alt="jendscalc" style="width: 49%; float: right;">

## Motivation

The motivation behind this project lies in addressing the unique challenges posed by fire emergencies in slum areas. Cramped living conditions, informal settlements, inadequate infrastructure, and limited access to emergency services exacerbate the vulnerability of residents to fire-related incidents. Therefore, understanding how individuals navigate through slum environments during evacuations is crucial for devising effective strategies to mitigate risks and save lives. 🚒🚨

## Simulation Framework

The simulation operates on an agent-based modeling framework, where each individual within the slum area is represented as an autonomous agent endowed with specific characteristics, behaviors, and decision-making capabilities. These individuals interact with their surroundings and fellow agents, adjusting their movements based on predefined rules and environmental stimuli. 

### Individual Behaviors
- **Alignment**: Individuals tend to align their velocities with those of nearby neighbors, simulating the tendency of people to move in the same direction during evacuations.
- **Cohesion**: Individuals exhibit cohesion by moving towards the center of their group, mimicking the behavior of people gathering and moving together during emergencies.
- **Separation**: To avoid overcrowding and collisions, individuals practice separation by maintaining a safe distance from nearby neighbors.
- **Building Avoidance**: Individuals actively avoid buildings by adjusting their trajectories to steer clear of obstacles, ensuring a smoother and safer evacuation process.

## Technical Implementation

The technical implementation of the simulation involves several components and algorithms working in concert to simulate the evacuation process realistically. 

### Simulation Setup
- **Slum Layout Generation**: The simulation begins by generating a virtual representation of the slum area, complete with randomly positioned buildings of varying sizes and shapes.
- **Initial Parameters Assignment**: Initial positions and velocities are then assigned to the individuals within the simulation space, with a KD-tree data structure employed to facilitate efficient nearest neighbor queries during the simulation.

### Simulation Dynamics
- **Update Function**: The heart of the simulation, the update function drives the iterative progression of the simulation by recalculating the positions and velocities of individuals at each time step based on their interactions and behaviors.
- **Emergent Behaviors**: Through this iterative process, individuals exhibit emergent behaviors such as flocking, clustering, and avoidance, mirroring the collective dynamics observed in real-world evacuations.

## Usage

To use the Fire Evacuation Simulation, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Rishit-katiyar/SlumFireEvacuationSimulation.git
   ```

2. Navigate to the project directory:

   ```bash
   cd SlumFireEvacuationSimulation
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the simulation script:

   ```bash
   python Fire_Evacuation_analysis.py
   ```

5. Explore the simulation and analyze the evacuation dynamics in the slum area.

## Visualization and Analysis

The simulation provides a rich visual interface that enables observers to track the movement of individuals in real-time as they navigate through the simulated slum environment. Individuals leave behind temporary trails as they move, with the intensity of the trails varying based on the density of individuals in a particular area. 

## Future Directions

Looking ahead, there are several avenues for enhancing the Fire Evacuation Simulation:

- Incorporating additional variables and parameters to increase realism.
- Conducting detailed analyses of evacuation strategies and interventions.
- Collaborating with stakeholders to implement evidence-based policies and interventions.

## Contributions

Contributions to the Fire Evacuation Simulation project are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more details.


# Thank you for your interest in the Fire Evacuation Simulation! 🙏🔥
