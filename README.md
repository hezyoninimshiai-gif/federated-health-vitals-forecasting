# Federated Learning for Privacy-Preserving Health Vitals Forecasting

Final-year research project by a 3-member team.

## Project Pipeline

eICU Dataset
→ Data Preprocessing
→ Simulated Hospital Clients
→ Sliding-Window Time-Series Data
→ LSTM
→ Federated Learning using Flower + FedAvg
→ Differential Privacy using Opacus / DP-SGD
→ Centralized vs FL vs FL+DP Comparison
→ Streamlit Dashboard

## Team Responsibilities

### Rishika — Data & Federated Core
- eICU data preprocessing
- Feature preparation
- Simulated hospital clients
- Sliding-window time-series generation
- Flower clients/server
- FedAvg implementation

### Nimshi — Model & Privacy
- LSTM model
- Centralized baseline
- Differential Privacy
- Opacus / DP-SGD
- FL + DP experiments
- Model comparison

### Gowtham — Environment & Integration
- Environment setup
- Dependency management
- Integration of all modules
- Experiment execution support
- Streamlit dashboard
- Final pipeline integration

## Repository Structure

```text
data/           Dataset documentation
preprocessing/  Data preprocessing and client creation
models/         LSTM model
federated/      Flower + FedAvg implementation
privacy/        Differential Privacy
experiments/    Training and comparison experiments
results/        Experiment results
dashboard/      Streamlit dashboard
notebooks/      Research/experimental notebooks
