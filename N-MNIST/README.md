## Compare quantified neural networks for MNIST (images) data


In this specific directory, you can locate the following files:
* *preprocessing.ipynb* : Code for generating six different representations of event data, considering an accumulation of 300 events.
* *n2d2_NMNIST_data_representation.ipynb* : Code for obtaining models with various data representations. We compared results and selected the 2-channel representation for the next step.
* *n2d2_NMNIST_models.ipynb* : Code for for obtaining models using the N2D2 library. We used three architectures and compared results with different quantization levels (8, 4, 2, 1 bits).
* *model...* folders : Weights after training our models.
* *Score...* folders : Confusion matrices and other metrics for each model.
