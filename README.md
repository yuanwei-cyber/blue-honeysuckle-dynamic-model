# blue-honeysuckle-dynamic-model
Mathematica code for "Dynamic response of Blue Honeysuckle fruit-stem system"
# Mathematica Code for: [Dynamic response of Blue Honeysuckle fruit-stem system based on mathematical model]

This repository contains the *Mathematica* notebook (`*.nb`) file used to perform the analytical calculations and generate the figures for the manuscript:

> **[Dynamic response of Blue Honeysuckle fruit-stem system based on mathematical model]**  
> *[Yuan Wei, Wang Ruiyin, Wang Yecheng, Feng Fang, Ma Decai]*  
> *PLOS ONE* (Under Review)

## Description
The core of this repository is the file `Unstable region of the fruit stem vibration.nb, Relationship between the excitation frequency and damping ratio.nb, Stem is perpendicular to excitation direction.nb, Stem is parallel to  excitation direction.nb, fruit stem vibration.cae`. The Mathematica code implements the dynamic model of the blue honeysuckle fruit-stem system as described in the manuscript. The key operations performed include:
- Calculation of the unstable region for fruit-stem vibration.
- Determination of the unstable region characterizing the relationship between excitation frequency and damping ratio.
- Generation of the amplitude-frequency response curves for the stem when it is perpendicular to the excitation direction.
- Generation of the amplitude-frequency response curves for the stem when it is parallel to the excitation direction.
- Execution of finite element simulations for fruit-stem vibration using Abaqus (via the .cae file).

## Requirements
- **Software:** Wolfram *Mathematica* (Version 12.0 or higher recommended). *Abaqus* (Version 2017 or higher recommended).  
- **No additional toolboxes or packages are required.**

## Usage
1.  Download or clone this repository.
2.  Open the *.nb file in *Mathematica*, or *.cae file in *Abaqus*.
3.  Execute the notebook cells sequentially (Press `Shift+Enter`) in *Mathematica*, Select the job and click Submit in *Abaqus*. This will create the input files (.inp, .jnl, etc.) and start the finite element analysis solve
4.  The main results and plots will be generated automatically. Key parameters (material properties from Table 1) are defined at the beginning of the notebook.

## File Structure
- Unstable region of the fruit stem vibration.nb: Mathematica notebook for the primary instability analysis.
- Relationship between the excitation frequency and damping ratio.nb: Mathematica notebook for frequency-damping analysis.
- Stem is perpendicular to excitation direction.nb: Mathematica notebook for perpendicular excitation response.
- Stem is parallel to excitation direction.nb: Mathematica notebook for parallel excitation response.
- fruit stem vibration.cae: Abaqus simulation file for finite element analysis.
- `LICENSE`: The MIT license file.

## Citation
If you use this code in your research, please cite the associated manuscript (when published). The code is permanently archived at: https://github.com/yuanwei-cyber/
blue-honeysuckle-dynamic-model

## License
This work is licensed under the MIT License. See the `LICENSE` file for details.
