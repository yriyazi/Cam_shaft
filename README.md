# Cam_shaft
One of my most fulfilling experiences began when Dr. Saeimi Sadigh, my professor, discussed poor valve spring quality, causing rattle and exhaust manifold failure. I worked around the clock with the guidance of Dr. Jahdi to create and simulate a CAD replica of the motor to study it for the first time. I borrowed a camshaft from the university's auto mechanic shop, cast the camshaft in plaster, and measured the valve with a caliper. I then attempted to determine the appropriate stiffness for the valve spring in different situations. This project convinced me that physical systems are not bound to their models.

Video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/7ErJ2Q-R0Ss/0.jpg)](https://youtu.be/7ErJ2Q-R0Ss)


This repository contains a model of a camshaft that has been designed and simulated using SolidWorks and MSC Adams. The camshaft is based on a real car's camshaft and includes the determination of the angle of the remaining shaft, as well as the implementation of contact and spring elements in MSC Adams.

## Contents

- [Introduction](#introduction)
- [SolidWorks Modeling](#solidworks-modeling)
- [MSC Adams Simulation](#msc-adams-simulation)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction
The camshaft is a crucial component in an internal combustion engine, responsible for controlling the opening and closing of the engine's valves. This repository presents a detailed model of a camshaft that closely resembles the design of a camshaft found in a real car. The model has been developed using SolidWorks, a popular computer-aided design (CAD) software, and simulated using MSC Adams, a multi-body dynamics simulation software.

## SolidWorks Modeling

The camshaft model was created in SolidWorks, following the design specifications of a real car's camshaft. The SolidWorks model includes the accurate geometry and dimensions of the cam lobes, journals, and remaining shafts. The model has been created with precision to ensure a realistic representation of the camshaft.

## MSC Adams Simulation

After the completion of the SolidWorks model, the camshaft was imported into MSC Adams for simulation purposes. In MSC Adams, contact and spring elements were defined to simulate the interactions between various components of the camshaft during its operation. The contact elements were utilized to model the contact forces between the cam lobes and the engine's valve lifters, while the spring elements were used to simulate the spring-back effect caused by the valve springs.

<p align="center" width="100%">
    <img width="90%" src="Image\vel_angular-vel.png"> 
</p>

The simulation in MSC Adams allows for a comprehensive analysis of the cam shaft's behavior, enabling engineers to evaluate its performance, identify potential issues, and optimize its design for improved efficiency and durability.

## Installation

To use the camshaft model and perform simulations, follow the steps below:

1. Clone this repository to your local machine.
1. Install SolidWorks and MSC Adams on your computer.
1. Open the SolidWorks model file (.sldprt) in SolidWorks for viewing and modification.
1. Import the SolidWorks model into MSC Adams for simulation purposes.

## Usage

Once you have installed SolidWorks and MSC Adams and imported the camshaft model, you can use the files in this repository for the following purposes:

1. View and modify the SolidWorks model of the camshaft.
1. Perform simulations in MSC Adams to analyze the behavior of the camshaft under different operating conditions.
1. Modify the contact and spring elements in MSC Adams to customize the simulation setup as per your requirements.
1. Optimize the design of the camshaft based on the simulation results obtained from MSC Adams.

Feel free to explore the files and adapt them to suit your specific needs.


![Alt Text](https://github.com/yriyazi/Storage/blob/main/Camshaft/plaster%20molding.jpg)
            
## License

The contents of this repository are licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and files as per the terms of the license.

Please note that this camshaft model is for demonstration and educational purposes only. It is recommended to consult with automotive engineering experts and perform real-world testing before implementing any designs in actual vehicles.

______________________________________________________________________

*Note: This was not a real project and was completely pursued by my passion for mechanical engineering.*
