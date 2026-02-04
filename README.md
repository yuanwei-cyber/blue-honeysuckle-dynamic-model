# blue-honeysuckle-dynamic-model
Mathematica code for "Dynamic response of Blue Honeysuckle fruit-stem system"
# Mathematica Code for: [Dynamic response of Blue Honeysuckle fruit-stem system based on mathematical model]

This repository contains the *Mathematica* notebook (`*.nb`) file used to perform the analytical calculations and generate the figures for the manuscript:

> **[Dynamic response of Blue Honeysuckle fruit-stem system based on mathematical model]**  
> *[Yuan Wei, Wang Ruiyin, Wang Yecheng, Feng Fang, Ma Decai]*  
> *PLOS ONE* (Under Review)

## Description
The primary files in this repository are:

- Unstable region of the fruit stem vibration.nb
- Relationship between the excitation frequency and damping ratio.nb
- Stem is perpendicular to excitation direction.nb
- Stem is parallel to excitation direction.nb
- fruit stem vibration.cae
The Mathematica code implements the dynamic model of the Blue Honeysuckle(Lonicera caerulea L.) fruit-stem system as described in the manuscript. The key operations performed include:
- Determination of the unstable region for fruit-stem vibration.
- Characterization of the relationship between excitation frequency and damping ratio within the unstable region.
- Generation of the amplitude-frequency response curves for the stem when it is perpendicular to the excitation direction.
- Generation of the amplitude-frequency response curves for the stem when it is parallel to the excitation direction.
- Finite element analysis of fruit-stem vibration dynamics, facilitated by the provided Abaqus .cae file.

## Requirements
- Software: Wolfram Mathematica (Version 12.0 or higher is recommended). Abaqus/CAE (Version 2017 or higher is recommended for the finite element simulation).
- No additional toolboxes or packages are required to execute the Mathematica notebooks.

## Usage
1.  Download or clone this repository.
2.  Open the desired .nb file in Mathematica or the .cae file in Abaqus/CAE.
3.  In Mathematica: Execute the notebook cells sequentially (by pressing Shift+Enter). In Abaqus: Open the .cae file to access the complete model, then submit the job to start the analysis.
4.  The main results, including numerical outputs and plots, will be generated automatically. Key parameters (e.g., material properties corresponding to Table 1 in the manuscript) are defined at the beginning of the notebooks.
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
