# Transformer-Based Beam Prediction for THz Drone Communication with RIS Integration

**Author:** Md Nurul Absar Siddiky  
**Course:** ECGR-6119/8119: Applied Artificial Intelligence (AI)  
**Instructor:** Dr. Minhaj Nur Alam  
**Department:** Electrical and Computer Engineering, University of North Carolina at Charlotte  
**Contact:** msiddiky@uncc.edu  

---

## Abstract

This project focuses on beam prediction in Terahertz (THz) communication for Unmanned Aerial Vehicles (UAVs) in a 6G network scenario. A transformer-based deep learning model is developed to predict optimal RIS beams by leveraging sequential data such as beam trajectories, positions, and Line-of-Sight (LoS) information. The proposed model demonstrates superior performance over classical LSTM and GRU models based on evaluation metrics like Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).

---

## Table of Contents

1. **Introduction**
   - Motivation and Challenges
   - Contributions
2. **Related Work**
3. **System Model and Problem Formulation**
   - System and Channel Model
   - Problem Formulation
4. **Solution Approach**
5. **Experimental Analysis and Discussion**
   - Experimental Settings
   - Result Analysis
6. **Conclusion**
7. **References**

---

## Key Features and Contributions

- **Problem Addressed:** Beam prediction for RIS in a 6G drone communication scenario.
- **Proposed Model:** A multivariate transformer-based deep learning model leveraging attention mechanisms.
- **Evaluation:** Compared with LSTM and GRU models, demonstrating superior accuracy and efficiency.
- **Dataset:** Includes 3D drone trajectories, beamforming vectors, LoS information, and sequence numbers.
- **Metrics:** Evaluated using RMSE, MAE, and MSE.

---

## Experimental Setup

1. **Framework:** DeepMIMO [Reference 15]  
2. **Scenario:** Drone communication in a downtown area with a base station, RIS, and drone grids.  
3. **Dataset:** Generated using DeepMIMO and includes:
   - Beam vectors, 3D positions, LoS, and path count.
   - 10,000 rows of time-sequential data with 21 feature vectors per sequence.
4. **Models Compared:** LSTM, GRU, and the proposed transformer model.  
5. **Evaluation Metrics:** RMSE, MAE, and MSE.  

---

## Results

- **Proposed Model:** Outperformed LSTM and GRU in training speed and accuracy.  
- **Key Observations:**
  - Stabilizes faster (by epoch 10) compared to LSTM/GRU (after epoch 27).
  - Validated its ability to predict RIS beam trajectories in dynamic scenarios.

---

## Conclusion

The transformer-based deep learning model effectively predicts RIS beams, addressing challenges in THz communication for UAVs. By leveraging advanced attention mechanisms, the model demonstrates significant improvement in prediction accuracy and resource efficiency, paving the way for enhanced 6G drone communication.

---

## References

For detailed references, see the **References** section in the full project report.


