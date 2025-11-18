# HOTEL RESERVATION CANCELLATIONS PREDICTION WITH DEEP NEURAL NETWORKS

This project develops a deep neural network to predict hotel reservation cancellations. It uses a dataset of 36,275 instances and 19 variables, tuning various hyperparameters and optimization techniques to maximize accuracy.

## Project Description

The main objective is to train a deep neural network capable of classifying whether a reservation will be canceled based on data such as the number of nights, number of adults, and the customer's cancellation history. To achieve this, we tested different combinations of activations, learning rates, regularization, and weight initialization methods.

The final model is optimized using a multilayer architecture with **ELU activation** and the **ADAM optimizer**, achieving 88% accuracy on the test set.

## Project Elements

- **InformeRedesNeuronalesProfundas.pdf**: Report that contains the full process of building and adjusting the neural network.
- **RedesNeuronalesProfundas.ipynb**: Jupiter Notebook that contains the whole code used to adjust the neural network.
- **GraficaModeloFinal.png**: Image that shows the results obtained with the final model.

All the contents are only available in spanish.

## Report Structure

- `Introduction`: Explains the problem and the dataset used.
- `Design Process`: Describes the network design and iterations of hyperparameter tuning.
- `Results`: Presents the final model and its performance metrics.
- `Conclusions`: Summarizes the hyperparameter tuning process and the results.

## Final Model Results

<img src="./GraficaModeloFinal.png" alt="Final Model" width="1000"/>

## Requirements

- Python 3.x
- Libraries: TensorFlow, Keras, NumPy, Pandas
- Dataset: Not available

## Authors

- [Fátima Fuchun Illana Guerra](https://github.com/Fatima-Illana)
- [Cristina Fernández Gómez](https://github.com/crisfernandez)
