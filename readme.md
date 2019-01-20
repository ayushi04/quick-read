## to get list of installed packages in venv
pip list --format=freeze > installed-packages.txt

## installing pyqt5 and all required packages in ubuntu
conda install -c anaconda pyqt
pip install PyQt5

## converting .ui to .py file
pyuic5 design_matrix.ui -o design_matrix.py
