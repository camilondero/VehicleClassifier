# VehicleClassifier
Artificial intelligence algorithms are applied to detect those publications or images where the mark, the model or year of the vehicle has been uploaded erroneously or absent.

## Getting Started
##### - Clone this repository
 `git clone https://github.com/camilondero/VehicleClassifier.git `
 
##### - Download this dataset
https://ai.stanford.edu/~jkrause/cars/car_dataset.html

##### - Upload files to google colab
#####  1. Run the Google Colab Make New Dataset.ipynb.
#####  2. Run the Google Colab Clasificacion_vehiculos_modelos.ipynb

<img src="/Resultados.png" alt="resultado"/>

##### - Using the Trained Models

If desired, the pre-trained models, as well as their weights, may be downloaded from here: https://drive.google.com/drive/folders/1oxye9yLPX-kYocMSqlo8sX6Q-GZp7aMd?usp=sharing , to utilize a model simply import into an enviroment with tensorflow. If loading the entire model, a function to calculate f1 must also be provided, see Clasificacion_vehiculos_modelos.ipynb for an example on how to import. If only the weights are needed, they may be loaded as normal via Tensorflow's model.load_weights function.

## Authors
##### - Francisco Javier Luque Sugrañes
##### - Camila Soledad Londero
##### - Elmer A. Fernandez
##### - Pablo Pastore




