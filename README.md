<h1>Neural Networks and Backpropagation: A Comparative Study of Gradient Descent Methods on MNIST</h1>

<p>This project explores the implementation and performance comparison of different gradient descent methods for training a neural network on the MNIST dataset. The MNIST dataset consists of 70,000 images of handwritten digits (0-9), each image being a 28x28 pixel grayscale image.</p>

<h2>Algorithms Implemented</h2>
<ul>
    <li><strong>Stochastic Gradient Descent (SGD)</strong></li>
    <li><strong>Mini-Batch Gradient Descent</strong></li>
</ul>

<h2>Project Overview</h2>
<p>The neural network is trained using the above gradient descent algorithms, and the results are compared to analyze their performance in terms of training loss and accuracy. The training and evaluation metrics are plotted to visualize the behavior of each algorithm.</p>

<h2>Dataset</h2>
<p>The dataset used in this project is the MNIST dataset, which contains images of handwritten digits. Each image is represented as a 28x28 pixel grayscale image. The <code>datatp1.csv</code> file contains the dataset, where the first column represents the labels (digits) and the remaining columns represent the pixel values of the images.</p>

<h2>Results</h2>
<p>The project demonstrates the differences in performance between the Stochastic Gradient Descent and Mini-Batch Gradient Descent algorithms. The results are visualized through graphs showing the training loss and accuracy over epochs.</p>

<h2>Usage</h2>
<p>To run this project, ensure you have the following dependencies installed:</p>
<ul>
    <li>Python 3.x</li>
    <li>Pandas</li>
    <li>NumPy</li>
    <li>PyTorch</li>
    <li>Matplotlib</li>
</ul>

<p>Clone the repository and run the Jupyter Notebook to train the neural network and visualize the results.</p>

<h2>File Structure</h2>
<ul>
    <li><code>datatp1.csv</code>: The MNIST dataset file.</li>
    <li><code>neural_network_training.ipynb</code>: The Jupyter Notebook containing the code for training the neural network and plotting the results.</li>
</ul>

</body>
</html>
