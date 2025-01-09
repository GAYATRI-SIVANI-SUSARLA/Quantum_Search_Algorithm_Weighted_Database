# Adaptive-Grover-Algorithm for Weighted data search
- This project implements an Adaptive-Grover-Algorithm using Qiskit, analyzing different dataset
   distributions and producing visualization results.
- Special thanks to Yifan Sun and Lian-Ao Wu for [Quantum search algorithm on weighted databases](https://www.nature.com/articles/s41598-024-81701-7), which has been a helpful reference.
## Abstract 
- The Adaptive Grover Algorithm is designed for weighted data search problems, it is
   essential for quantum subroutines in various complex algorithms.
- Our analysis and implementation reveal the adaptive quantum search nature compared to linear 
    search.
- We addressed the key challenges in designing an adaptive Grover search compared it with the 
   original Grover Algorithm, and explained about results for distributions in real-world weighted 
   data.
- In conclusion, our project provides a few enhancements to the original Grover’s search 
   implementation strategies and scalability of the algorithm.

  ## Installation
  ### Prerequisites
  - Python 3.7 or later
  - pip or conda package manager
  ### Installing Qiskit
  Follow these steps to install Qiskit and the required dependencies:
```python
 # Create and activate a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install Qiskit and dependencies
pip install qiskit
```
For detailed installation and troubleshooting, refer to the [Official Qiskit Installation Guide](https://docs.quantum.ibm.com/guides/install-qiskit)

## Data Description
The project uses quantum state measurement data located in the data/ directory. The dataset includes:
```
data/
├── heavy_tail_samples.txt       
├── normal_distribution_samples.txt
├── normal_distribution_samples.txt
├── quasi_uniform_samples.txt
└── uniform_distribution.txt
```

Example distribution from our dataset:
[heavy tail_distribution](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Data/heavy_tail.jpg)








