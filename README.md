<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- ![Convolutional layer](sample/qiskit.png) -->
  <img src="sample/qiskit.png" alt="Logo" width="80" height="80">


  <h3 align="center">Image Classification Using Quantum Machine
Learning</h3>

  <p align="center">
    A quantum computing approach to the problem of image classification using deep learning.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This project deals with the efficient use of QML by leveraging the principles of Quantum Mechanics for parameter reduction and accurate image processing. QCNNs highlights the benefits and challenges of employing quantum techniques in medical image classification, outperforming CNN models in terms of precision and recall when it comes to handling datasets of higher dimensionality, namely MNIST.

* Ansatz <br>
  Convolutional layer
![Convolutional layer](sample/conv_layer.jpeg)
  Pooling layer
![Pooling layer](sample/pooling_layer.jpeg)
* QCNN architecture
![QCNN](sample/QCNN.png)
* Loss (calculated over 60 epochs)
![Calculated loss](sample/loss.jpeg)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* Qiskit
* Tensorflow
* Google Colab

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Jupyterlab
  ```sh
  pip install jupyterlab
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/OwaisK4/QCNN
   ```
2. Install dependencies
   ```sh
   pip install -r requirements.txt
   ```
3. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```
4. Run the notebook using Jupyterlab.
   ```sh
   jupyter-lab QCP.ipynb
   ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Owais Ali Khan - [21K-3298](k213298@nu.edu.pk) - owaisalikhan2003@example.com

Hassaan Gatta - [21K-3177](k213177@nu.edu.pk) - hassaangatta@gmail.com

Babar Subzwari - [21K-3202](k213202@nu.edu.pk)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Qiskit](https://www.ibm.com/quantum/qiskit)
* [Tensorflow](https://www.tensorflow.org/)
* [Colab](https://colab.google/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
