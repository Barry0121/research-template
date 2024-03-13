# Template for repository any computational research 

## Replace this README.md with content specific to the project 

## Repository Structure 

* `src`: Main folder with core files, including model definition, training and evaluation scripts, etc. 
* `run.py`: The file to run for all the tasks. 
* `requirements.txt`: Specify denpendencies to build the environment. 
* `datasets`: All datasets are cached here. 
* `checkpoints`:
* `components`: External packages that requires manual setup are stored here. The idea is to just copy the files from target GitHub and setup entirely here in this repo. 
* `exps`: Store all experiments results. 
* `utils`: Contain general utility files, ex: download_data.sh, export_visualization.py, etc. 
* (Optional) `module`: In case this repo will need to be built into a package, module is where all the components are build files are specified. 
   * `setup_module.py` is the file to run if we want to build this module. 
 
 ## README Structure
 
 * Description: Talk about what this project is trying to achieve. 
 * Installation: Provide detail on how the environment should be setup, and some FAQ on possible issues is nice as well. 
 * "How to Run": Provide some example on how to run certain experiments. Give actual command and expected return. 
 * (Optional) Results: Show some results from the experiments. Visualizations, evaluation metric, some CV people also use GIFs. 
 * Citation/License: This should be self-explanatory.
