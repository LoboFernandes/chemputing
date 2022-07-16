# Chemputer Machine Code
This repo will contain a chempiler library, base layer for operating compact and reconfigurable manufacturing platform for programing chemical synthesis of APIs.


It will map platform graphs to device drivers, and provide a platform controller for chemputer steps execution.
The controlers must be equipped with devices for real-time monitoring and final formulation of high purity APIs. 
For the preparation of target molecules, commercially available starting materials may be employed.
The physical setup must be able to perform complex multistep synthesis, work-up procedures as well as purification operations such as crystallization. 
The project is designed for Synthesisable Accessibility, Issue tracking, Automatic bug reports and User feedback.
The material in each chemputer module may be based on customized flow equipment, or retrofitted synthesis glassware, connected using chemical-resistant polytetrafluoroethylene tubing for pumps transfer reaction mixtures between each module. 
Quality control may have In-line analysis to collect high-performance liquid chromatography coupled to mass spectrometry (HPLC-MS), NMR, infrared, UV spectroscopy and pH.


Prerequisites

-Python 
-pyserial
-OpenCV
-networkx



Run Tests
To run the test suite and make sure your installation is working correctly:
pytest tests -rf




Project structure
This repository contains the following subfolders and files in the chempiler folder.


Functionalities:

Separate phases
Wait for temp
Set temperature
Vent vacuum
