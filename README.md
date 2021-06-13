# NIR-II Design
Prediction model used in the paper: Design of High-Performance Near-Infrared-II Molecular Fluorophores

## Prediction Demo and Data Availability
- Access the [jupyter notebook](https://github.com/cpfpengfei/NIRII-ML-Design/blob/main/%5BDemo%5D%20Model%20Prediction.ipynb) to view the demo on HOMO LUMO energy gap predictions with our trained model.
- The 24 NIR-II fluorophore cores and their predictions are available in the current [`Predictions.csv`](https://github.com/cpfpengfei/NIRII-ML-Design/blob/main/Predictions.csv) 

## Guide: Energy gap predictions 
You can also use our trained model to make energy gap predictions given a NIR-II fluorphore SMILES input. 
1. Download this repository and ensure all packages required are installed 
2. Start the jupyter notebook and follow the steps (particularly, edit the `To_Predict.csv` file with the SMILES you need to predict, shown below)

![image](https://user-images.githubusercontent.com/28598792/121802952-b1208000-cc71-11eb-9c5f-2e56f8beb784.png)

3. The new predictions will then be saved in `Predictions.csv`

## Requirements
- [numpy](https://numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [Tensorflow](https://www.tensorflow.org/)
- [RDKIT](https://www.rdkit.org/)
- [Deepchem 2.4](https://github.com/deepchem/deepchem)
