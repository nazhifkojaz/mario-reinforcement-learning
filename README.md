## Overview
This project implements a reinforcement learning model to play the Mario game. (based on this [tutorial](https://www.youtube.com/watch?v=2eeYqJ0uBKE))

## Project Structure
- `mario-rl/` - Contains the virtual environment.
- `logs/` - Contains logs generated during training.
- `train/` - Contains training scripts and resources.
- `train.ipynb` - Jupyter notebook for training and testing the model.

## Installation

1. Clone the repository.
2. Install the virtual environment.
    ```bash
    python3 -m venv mario-rl
    source mario-rl/bin/activate # on macOS/Linux
    mario-rl\Scripts\activate # on Windows
    ```
3. Install the dependencies.
    ```bash
    pip install -r requirements.txt
    ```
    
## Additional Resources
To run the project, you need to have MSVC14++ installed for the `nes_py` library. You can download it from the [Microsoft website](https://visualstudio.microsoft.com/).