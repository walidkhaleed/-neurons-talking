# **Neural Spike Analysis Project**

## **Overview**
This project focuses on analyzing neural activity through extracellular recordings. It involves identifying spike times, characterizing neuron activity, and distinguishing spikes from different neurons in both simulated and real datasets. The aim is to decode brain activity and address challenges in noisy data analysis.

## **Project Structure**
The repository consists of the following components:

## **Getting Started**
### **Prerequisites**
- Python 3.8 or higher.
- Jupyter Notebook.
- Required Python libraries: `numpy`, `scipy`, `matplotlib`.

### **Installation**
1. Clone this repository:
   ```bash
   git clone https://github.com/walidkhaleed/neural-spike-analysis.git
   cd neural-spike-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### **Running the Code**
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Explore the notebooks in the following order:
   - `insightsGeneratedData.ipynb`
   - `processRealData.ipynb`
   - `solution.ipynb`

## **Key Features**
- **Spike Detection**: Identifies spike times in neural recordings.
- **Neuron Characterization**: Plots average waveforms and distinguishes neuron activity.
- **Algorithm Tuning**: Explores how parameter choices impact results.
- **Validation**: Compares results with ground truth to refine methods.

## **Datasets**
1. **Simulated Data**:
   - File: `sample_1.mat`
   - 2 minutes of neural recordings at 24 kHz sampling rate.
2. **Real Patient Data**:
   - File: `recording.npy`
   - Noisy neural recordings from an epileptic patient at 32.051 kHz sampling rate.

## **Results**
- Insights from neural spike detection and classification.
- Visualization of spike waveforms and neuron activity trends.
- Documentation of challenges and solutions in noisy data analysis.

## **Future Work**
- Extend algorithms for large-scale neural recordings.
- Apply machine learning techniques for improved noise filtering and classification.

## **Contributors**
- [walid](https://github.com/walidkhaleed) – Lead Developer

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Would you like me to refine this or assist with setting up a GitHub repository?
