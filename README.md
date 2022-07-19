# Chemputer Machine Code

This repo will consist in a chemputer process unit software. It will contain core modules for operating 
compact and reconfigurable manufacturing platform for chemical synthesis of APIs.
It will map platform graphs to device drivers, and provide a platform controller for chemputer steps execution.
The controlers must be equipped with devices for real-time monitoring and final formulation of high purity APIs. 
For the preparation of target molecules, commercially available starting materials may be employed.
The physical setup unit must be able to perform complex multistep synthesis, work-up procedures as well as 
purification operations such as crystallization. 
The project is designed for Synthesisable Accessibility, Issue tracking, Automatic bug reports and User feedback.
The material in each chemputer module may be based on customized flow equipment, or retrofitted synthesis glassware, 
connected using chemical-resistant parts as polytetrafluoroethylene tubing for pumps transfer reaction mixtures between each module. 
Quality control may have In-line analysis to collect high-performance liquid chromatography coupled to mass spectrometry 
(HPLC-MS), NMR, infrared, UV spectroscopy and pH.

## Contributors






## Prerequisites

 - Python 
 - pyserial
 - OpenCV
 - networkx




## Run Tests

 - To run the test suite and make sure your installation is working correctly:
 - pytest tests -rf
 
 ### Usage

```python
from chempiler import Chempiler
import ChemputerAPI

c = Chempiler(
    experiment_code="my-experiment",
    output_dir="experiments/my-experiment",
    graph_file="my-graph.json",
    simulation=False,
    device_modules=[ChemputerAPI]
)
```

### Developing

The following instructions are intended for Chempiler developers 

To make enhancements to Chempiler, you will want to install it in development mode. By doing this, you `chempiler` package is kept up-to-date with the changes that you make to the code so you won't have to re-install the package to make your changes visible.

```bash
git clone <git URL for this repo>
cd Chempiler
pip install -r requirements.txt
pip install -e .
```

To run the unit tests that come with the Chempiler, we will need to install next under development packages.


### Project structure

This repository will contain subfolders and files in the chempiler folder.


Functionalities:

- Separate phases
- Set temperature
- Wait for temp
- Vent vacuum
