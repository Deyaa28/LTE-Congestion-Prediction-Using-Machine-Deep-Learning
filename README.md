# LTE Congestion Prediction to Improve Cell Site Stability

## Abstract
This study addresses mobile network congestion issues, focusing on Orange Egypt Telecom's data. It employs machine learning and deep learning techniques to predict congested sites. The study compares Random Forest and XGBoost in machine learning and LSTM and GRU in deep learning, utilizing real network time series LTE data. The models achieve state-of-the-art results, showcasing the potential of deep learning, transfer learning, and fusion models in addressing challenges in wireless networks.

## Keywords
LTE, Mobile Network Congestion, PRB Utilization, Time Series, LSTM, Random Forest, Quality of Service (QoS), Cell Stability.

## Introduction
Integrity in an LTE (Long-Term Evolution) network is a significant concern, as it can jeopardize the reliability and quality of the network service. Unpredictable data transfer rates, frequent handovers, and varying signal strength levels are some signs of instability that can affect the user experience. Factors contributing to cell instability include interference from neighboring cells, increased user density, sudden changes in user mobility patterns, and environmental conditions. 

Congestion within a cellular network is a critical element that may contribute to the formation of unstable cells, compromising the overall network stability and user experience. There is a complex and multifaceted relationship between cellular instability and congestion, with resources, particularly Physical Resource Blocks (PRBs), being in greater demand as network traffic increases.

The effects of congestion on cell stability are profound, and understanding these dynamics is crucial for effective network management. Users may encounter lower data transfer speeds, more call drops, and worse voice quality in crowded situations. The increased demand for resources and network inefficiencies during congested periods increases the probability of service disruptions.

## Methodology
The research aims to predict LTE network congestion and improve infrastructure using AI, ML, and DL techniques. It utilizes machine learning models like Random Forest and XGBoost, as well as deep learning models like LSTM and GRU. The methodology involves data collection, preprocessing, machine learning model development, and deep learning model development.

### Data Collection
Orange Egypt provided an hourly LTE dataset collected weekly for 6 weeks for a cluster of 8 sites. The dataset consists of 39 KPIs, including PRB Utilization.

### Data Preprocessing
The dataset underwent preprocessing steps including dropping empty rows, selecting relevant KPIs, and imputing missing values.

### Machine Learning Model Development
Two scenarios were considered: training on congested sites and testing on normal sites, and vice versa. Random Forest and XGBoost algorithms were employed, and hyperparameters were tuned using grid search.

### Deep Learning Model Development
LSTM and GRU models were trained and tested on congested and normal sites. Hyperparameters were tuned, and early stopping was used to prevent overfitting.

## Results
### Machine Learning Models
Random Forest and XGBoost achieved state-of-the-art results in predicting PRB Utilization, with Random Forest outperforming XGBoost in some scenarios.

### Deep Learning Models
LSTM and GRU also achieved promising results in predicting PRB Utilization, with LSTM showing slightly better performance in some cases.
