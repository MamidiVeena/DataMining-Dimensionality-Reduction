# DataMining-Dimensionality-Reduction

**Dimensionality Reduction on MNIST dataset
This notebook discusses the importance of dimensionality reduction as a preprocessing step. We will show that high dimensional datasets can sometimes be expressed using only a few dimensions and that reducing dimensionality can make our datasets easier to work with and decrease the training time of our models.

What is dimensionalty and why is it important?
In simplistic terms, it is just the number of columns in the dataset, but it has significant downstream effects on the eventual models. The concept of the “curse of dimensionality” indicates that in high-dimensional spaces the proximity between objects have diminished differentiation effects. Even in relatively low dimensional problems, a dataset with more dimensions requires more parameters for the model to understand, and that means more rows to reliably learn those parameters. If the number of rows in the dataset is fixed, addition of extra dimensions without adding more information for the models to learn from can have a detrimental effect on the eventual model accuracy.

Dataset used for this activity:
The MNIST dataset is composed of 28x28 pixel images of handwriten digits from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.**Dimensionality Reduction on MNIST dataset
This notebook discusses the importance of dimensionality reduction as a preprocessing step. We will show that high dimensional datasets can sometimes be expressed using only a few dimensions and that reducing dimensionality can make our datasets easier to work with and decrease the training time of our models.

What is dimensionalty and why is it important?
In simplistic terms, it is just the number of columns in the dataset, but it has significant downstream effects on the eventual models. The concept of the “curse of dimensionality” indicates that in high-dimensional spaces the proximity between objects have diminished differentiation effects. Even in relatively low dimensional problems, a dataset with more dimensions requires more parameters for the model to understand, and that means more rows to reliably learn those parameters. If the number of rows in the dataset is fixed, addition of extra dimensions without adding more information for the models to learn from can have a detrimental effect on the eventual model accuracy.

Dataset used for this activity:
The MNIST dataset is composed of 28x28 pixel images of handwriten digits from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.
