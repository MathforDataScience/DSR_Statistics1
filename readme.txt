# -------------------------------
# Installation:
# install Python 3.10+ on your system, restart system
# Example here: Windows 11

# -------------------------------
# Installation:
c:
cd C:\(...)\tutorial_env
python -m venv .venv
# Windows:
.venv\Scripts\activate.bat
# Linux, MacOS:
.venv\Scripts\activate
pip install -r requirements.txt

# -------------------------------
# Launch:
c:
cd C:\(...)\tutorial_env
# Windows:
.venv\Scripts\activate.bat
# Linux, MacOS:
.venv\Scripts\activate
jupyter notebook

