# ARTEMIS: An Alarm Threshold and Policy Mining System for the Intensive Care Unit

This is ARTEMIS, a system for finding suitable alarm policies in intensive care units.

* `src/artemis` contains the module's source code
* `examples` contains Jupyter notebooks that demonstrate ARTEMIS's usage

## Setup

To make this run, you need to:

1. Install required Python modules via `pip install -r requirements.txt`
2. Place the demo data in the `../../physionet.org` (or somewhere else and adjust the path)

To download the demo data, please refer to the instruction on the [PhysioNet site](https://physionet.org/content/eicu-crd-demo/2.0.1/).
The instructions ask you to run `wget -r -N -c -np https://physionet.org/files/eicu-crd-demo/2.0.1/` which automatically creates the proper file structure.

After downloading the data, you can run the Jupyter notebooks in the `examples` folder, to see how ARTEMIS works.
