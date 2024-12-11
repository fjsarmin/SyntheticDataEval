# Evaluation of Synthetic Data and _k_-anonymized data.

---

**This project aims to study the privacy and utility aspects of various synthetic data publishing techniques and k-anonymization.**

---

### Setup
To perform the experiments, the following repositories need to be installed:

- [synthetic_data_release](https://github.com/spring-epfl/synthetic_data_release)  
- [dp-transformers](https://github.com/microsoft/dp-transformers)  
- [synthcity](https://github.com/vanderschaarlab/synthcity)  
- [SDV](https://github.com/sdv-dev/SDV)  

---

### Notebook Descriptions

1. **`false_positive_test.ipynb`**  
   Demonstrates how the presence of non-member outliers increases the false positive rate of the attacker.

2. **`ML_utility-MIA-kanon.ipynb` (for k-anonymized data)**  
   Reports the following:  
   - (a) The attacker's advantage using TensorFlow Privacy's Membership Inference Attack (MIA).  
   - (b) The classification performance of a machine learning (ML) classifier trained with k-anonymized data.

3. **`ML_utility-MIA-synth.ipynb` (for synthetic data)**  
   Reports the following:  
   - (a) The attacker's advantage using TensorFlow Privacy's Membership Inference Attack (MIA).  
   - (b) The classification performance of a machine learning (ML) classifier trained with synthetic data.
