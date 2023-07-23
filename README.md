# 📄✏ Sensor Fault Detection Project
**Brief:** In electronics, a **wafer** (also called a slice or substrate) is a thin slice of semiconductor, such as a crystalline silicon (c-Si), used for the fabrication of integrated circuits and, in photovoltaics, to manufacture solar cells. The wafer serves as the substrate(serves as foundation for contruction of other components) for microelectronic devices built in and upon the wafer. 

It undergoes many microfabrication processes, such as doping, ion implantation, etching, thin-film deposition of various materials, and photolithographic patterning. Finally, the individual microcircuits are separated by wafer dicing and packaged as an integrated circuit.

#### Dataset is taken from Kaggle and stored in mongodb


💿 Installing
1. Environment setup.
```
conda create --prefix venv python==3.8 -y
```
```
conda activate venv/
````
2. Install Requirements and setup
```
pip install -r requirements.txt
```
5. Run Application
```
python app.py
```
6.train app.py
```
http://localhost:5000/train
```
7. Predict app.py
```
http://localhost:5000/predict
```
drop test.csv you will get a new csv file where you will get predicted output column

🔧 Built with
- flask
- Python 3.8
- Machine learning
- Scikit learn
- 🏦 Industrial Use Cases

