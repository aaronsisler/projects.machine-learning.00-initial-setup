# projects.machine-learning.00-initial-setup

## General Notes

- Current latest version of Python is 3.13.1

## What we have done

- Needed to turn off the auto activate base that was turned on back in the day

  `conda config --set auto_activate_base false`

- conda create -p venv python=3.11 ipykernel
- conda create -p venv python=3.11
- conda activate venv/
- `python --version` now correctly shows 3.11.11 which was showing 3.13.1 before with the conda base auto activated
- Used to pip install all packages from a requirements file: `pip install -r requirements.txt`
