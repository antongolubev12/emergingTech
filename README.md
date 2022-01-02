# Emerging Technology.
This repository was a way of learning more about two new but very important techologies;
1. Machine learning
2. Quantum computing  

Each of these topics is discussed in its own Jupyter notebook. The making of this project allowed  
me to flesh out my research and independent learning skills and the experience of making it will aid me  
should I ever need to learn about an unfamiliar topic or skill in the future be it for my own personal projects or  
in industry.  
  
This project made me realise that even if a topic seems very daunting or difficult, if you take it one step at a time and  
research what you don't understand bit by bit then it quickly becomes managable to learn and undestand.

---

## Scikit-Learn Jupyter notebook.
This notebook gives an overview of what the Scikit-Learn library is and what it is used for.  
It explains three machine learning algorithms that are used for classification of data, including:  
- Support Vector Machine
- Decision Tree Algorithm
- Random Forest 


The explanations discuss in detail how these algorithms work.  
Classification of the wine quality dataset[1] is performed and some reasons why algorithms may give a low prediction score are discussed.  
The notebook also contains plots and diagrams meant to serve as a visual aid to help understand what the algorithms are doing. 

---

## Quantum-computing Jupyter notebook.
The notebook explains quantum computing by comparing it to classical computing. Similarities and differences are discussed.  
It also discusses Deutsch's algorithm and its significance in quantum computing.  
Deutsch's algorithm is then simulated in qiskit, a python package that simulates a quantum computer.

---

### How to use scikit learn
You must install NumPy and Scipy.
````
pip install numpy
````
````
pip install scipy
````

If you have NumPy and Scipy already installed, the easiest way to install sckikit-learn is:
In conda:
```
conda install scikit-learn
```

### How to run the notebook
- Install Jupyter:
````
conda install -c conda-forge jupyterlab
````
- Navigate to desired folder
- Run: "jupyter lab"

[1] https://archive.ics.uci.edu/ml/datasets/wine+quality
