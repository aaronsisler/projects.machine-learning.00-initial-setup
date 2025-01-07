# projects.machine-learning.00-python-refresher

## General Notes

- Current latest version of Python is 3.13.1

### Section 03: What we have done

### Section 02: What we have done

- Needed to turn off the auto activate base that was turned on back in the day

  `conda config --set auto_activate_base false`

- conda create -p venv python=3.11 ipykernel
- conda create -p venv python=3.11
- conda activate venv/
- `python --version` now correctly shows 3.11.11 which was showing 3.13.1 before with the conda base auto activated
- Used to pip install all packages from a requirements file: `pip install -r requirements.txt`
- Added in a handful of aliases to the .zshrc They are condaa, condad, condac
- Added `Black Formatter` which seems to be a thing for Python. Worked on save but it gave me some VS Code magic because of Prettier and it did some automagic configuration behind the User Settings scenes.... Don't like that...
