# Acquisition Software Digital Pen Tablet (WACOM INTUOS PRO)
Acquisition software used to collect data for the paper: *"Dual-Component Analysis of Trail Making Test: Task vs. Movement Coordination "*.

## Overview
This repository contains acquisition software to record kinematic data from a digital pen tablet (WACOM INTUOS PRO). 
The software allows to configure tasks, and exports .csv files with kinematic data, comprised of pen position (x,y), pressure, azimuth and elevation, sampled every 5 milliseconds.

## Installation
Clone the repository:
git clone https://github.com/kim-uittenhove/Coregraph-Acquisition-Software.git
cd your-repo

## Usage
Refer to the PDF documentation for a detailed guide to the acquisition software.
Obtain SDK key from WACOM and insert it in the configuration file.
Configure tasks in the configuration file.

## Repository Structure
- `Release/` : Dependencies for running the application
- `Documentation-CoreGraph/` : PDF documentation of acquisition software
- Shortcut to application
- Shortcut to configuration file

## License
This code is released under the UNIL–CHUV Software License Agreement for Academic Non-Commercial Research Purposes Only. See the [LICENSE.txt](LICENSE.txt) file for the complete terms and conditions.

## Citation
Uittenhove, K., Richiardi, J., Von Gunten, A., & Jopp, D. (2025). Acquisition Software for Digital Pen Tablet Data (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.16753413

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16753413.svg)](https://doi.org/10.5281/zenodo.16753413)

## Acknowledgments
We thank François Beaune (GitHub: @dictoon) for his valuable support in testing and debugging the data acquisition software, for coordinating with the WACOM development team, and for providing insightful feedback on potential algorithmic approaches.
We also thank the Swiss National Science Foundation (SNSF) for supporting this research through the Sinergia grant CRSII15_186239/1, awarded to principal investigators Daniela Jopp, Stefano Cavalli, Armin von Gunten, François Hermann, and Mike Martin.
