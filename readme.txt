Installation 

To get this project up and running, please follow these steps.

1. Set up the Conda Environment 

    This project requires GDAL, a geospatial data library, which is best installed using Conda due to its complex dependencies.
    First, create a new Conda environment and install Python within it. 

    conda create -n game-env python=3.8.16

    After the environment is created, activate it:
    
    conda activate game-env

2. Next, install GDAL from the conda-forge channel, which is often recommended for geospatial packages.

    conda install -c conda-forge gdal

3. Install Project Dependencies: With GDAL successfully installed, you can now install the remaining Python modules from the requirements.txt file.

    pip install -r requirements.txt
    
You are now ready to run the project!

#----------------------------------------------#

Numerical Experiments

The agent-based model and the associated online learning algorithm framework is consolidated within the /guard-policy-simulations directory.

You can invoke the model by executing the corresponding `game_model.py'.

for example: 

$python guard-policy-simulations/FPL-UE-model-BRSAM/game_model.py

The simulation outputs are saved in corresponding `simulation-outputs' directory.