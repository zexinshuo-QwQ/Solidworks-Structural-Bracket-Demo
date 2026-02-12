# Design and Structural Analysis of a Heat Exchanger Support System

## Project Overview
This project demonstrates the mechanical design and structural analysis of a support system for an industrial shell-and-tube heat exchanger. The objective is to ensure that the support structure can safely sustain the equipment weight under operational conditions while maintaining acceptable deformation limits.

## Engineering Background
In chemical processing plants, heat exchangers are commonly installed in horizontal configurations and supported by saddle structures. Improper structural design may lead to excessive stress, deformation, or long-term fatigue failure. Therefore, structural verification is critical during the design stage.

## Design Requirements
- Equipment type: Shell-and-tube heat exchanger  
- Total weight: 1200 kg (~11,772 N)  
- Operating temperature: 180 °C  
- Support configuration: Two saddle supports  
- Material: Structural steel  
- Minimum safety factor: 2.0  
- Maximum allowable displacement: 2 mm  

## Tools and Software
- SolidWorks (3D modeling and simulation)
- SolidWorks Simulation (static structural analysis)
- Python (data post-processing and optimization)

## Methodology
1. Create a simplified 3D model of the heat exchanger and support system in SolidWorks  
2. Assign material properties and apply gravity load  
3. Define boundary conditions and contact interfaces  
4. Perform static structural simulation  
5. Extract stress, displacement, and safety factor results  
6. Conduct parametric analysis by varying support thickness  

## Results
Key simulation results include:
- Maximum von Mises stress distribution
- Maximum structural displacement
- Safety factor contour plots

The highest stress occurs near the saddle-support joints, while the maximum displacement is observed at the mid-span of the heat exchanger.

## Engineering Conclusion
The proposed support design satisfies the structural requirements with a safety factor greater than 2.0 and a maximum displacement below 2 mm. Parametric analysis indicates that increasing the saddle thickness improves structural performance but leads to higher material usage. A support thickness of 15 mm provides an optimal balance between strength and weight.

## Repository Structure
