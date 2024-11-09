# Replication of GRASPED Model (BPAD)

This repository contains the replication of the **GRASPED** model from the [BPAD](https://github.com/guanwei49/BPAD) project. It includes modifications to the GRASPED model and additional results from various runs.

For more details on the entire BPAD project, including other models, please refer to the original repository: [BPAD - Behavioral Prediction for Adaptive Design](https://github.com/guanwei49/BPAD).

## Repository Structure

The directory structure is adapted from the original repository, focusing on the **GRASPED** model. It includes the following new files:

- `environment.yml`: Conda environment file to recreate the environment for the project.
- `requirements.txt`: Python package dependencies.

For more information on the overall file structure and the other models, refer to the [original BPAD repository](https://github.com/guanwei49/BPAD).

## Setup Instructions

To replicate the experiments and results, follow these steps:

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/your_username/your_repo_name.git
cd your_repo_name

### 2. Create and Activate the Conda Environment

Ensure that you have Conda installed. Then, create and activate the environment by running the following commands:

```bash
conda env create -f environment.yml
conda activate gruae

### 3. Install Additional Python Dependencies

Use pip to install any additional dependencies that might not be covered in the environment.yml file:

```bash
pip install -r requirements.txt


### Acknowledgements
- The original GRASPED model and BPAD repository by guanwei49.
- This repository serves as a replication of the GRASPED model from the BPAD project.
For more details on the original work, please visit the BPAD repository.

