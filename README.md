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
![heavy tail_distribution](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Data/heavy_tail.jpg)
![normal](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Data/normal.jpg)
![quasi uniform](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Data/quasi_unifrom.jpg)
![uniform](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Data/unifrom.jpg)

The distribution graph shows the probability distribution of datasets.

## Running the Analysis 
1. Prepare your environment (see Installation section)
2. Run the `data_process.py`, and do a classical linear search on each database:
   `python3 data_process.py`
   Code Link: [Data_Process-Code](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/data_process.py)

3. Run the `quantum_step.py`, and do an adaptive Grover search on each database:
  `python3 quantum_step.py`
   Code Link: [Quantum Step-Code](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/quantum_step%20(1).py)

4. Run the script `compare.py` to analyze and compare the number of steps required to locate 
   each piece of data using classical versus quantum approaches:
   `python3 compare.py`
   Code Link: [Compare-Code](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/compare.py)

   ## Results
   The analysis results are saved in the `output/` directory:
   `output/
├── heavy_tail.jpg     
├── noraml.jpg   
├── quasi_uniform.jpg   
└── unifrom.jpg `
Example visualization of results:
![heavytail](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Output/heavy_tail%20(1).jpg)
![normal](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Output/normal%20(2).jpg)
![quasi uniform](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Output/quasi_uniform.jpg)
![uniform](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Output/unifrom%20(1).jpg)

## Final Paper
 Final Paper for the project: [Adaptive Grover for Quantum Search](https://github.com/GAYATRI-SIVANI-SUSARLA/Quantum_Search_Algorithm_Weighted_Database/blob/main/Adaptive_grover_for_Quantum_Search_Fianl_Paper.pdf)
  







