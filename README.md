# physics_informed_RMs

Running the pRM Project

# Physics-informed Reward Machines (pRM) Project

This repository contains Jupyter notebook implementations and experiments for the Physics-informed Reward Machines (pRM) framework.

## Requirements

The project was developed using Python 3 and relies on several machine learning, reinforcement learning, and visualization libraries.

### Recommended Python Version

```Bash
Python 3.8+
```
Note: Some TensorFlow/Baselines dependencies may work best with Python 3.7–3.8.

Installation
1. Clone the Repository
```Bash
git clone https://github.com/DanielAjedamola/physics_informed_RMs
cd ....
```
2. Create a Virtual Environment
Using venv
```Bash
python -m venv prM_env
```

Activate the environment:

Linux / macOS
```Bash
source prM_env/bin/activate
```
Windows
```Bash
prM_env\Scripts\activate
```

3. Install Dependencies
Install the required Python packages:
```Bash
pip install numpy pandas matplotlib seaborn plotly gym torch tensorflow joblib
```
Additional dependencies:
```Bash
pip install mpi4py
```
4. Install OpenAI Baselines
This project uses components from OpenAI Baselines.
Install Baselines directly from GitHub:
```Bash
pip install git+https://github.com/openai/baselines.git
```

Running the Project
Launch Jupyter Notebook
Start Jupyter Notebook from the project directory:
```Bash
jupyter notebook
```
or with JupyterLab:
```Bash
jupyter lab
```

Run Experiments

Open and run the desired notebook (.ipynb) corresponding to the experiment or environment you want to reproduce.

Run all notebook cells sequentially.

Citation

If you use this codebase in your research, please cite the corresponding pRM publication.
```
@article{ajeleye2025physics,
  title={Physics-Informed Reward Machines},
  author={Ajeleye, Daniel and Trivedi, Ashutosh and Zamani, Majid},
  journal={arXiv preprint arXiv:2508.14093},
  year={2025}
}
```
