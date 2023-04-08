# pyPIDtoolbox
Clone &amp; Python porting of https://github.com/bw1129/PIDtoolbox created by Brian White.

### Setup environment
```
sudo apt install git python3 pip3 jupyter-core
pip install nbconvert
pip install ipykernel

git clone https://github.com/pitronicteam/pyPIDtoolbox.git
cd pyPIDtoolbox
```

### Export BBL
Export BBL file to filename `baseline000.bbl.csv` in `pyPIDtoolbox` folder.

### Execute
```
jupyter nbconvert FFT.ipynb --to html
xdg-open FFT.html
```