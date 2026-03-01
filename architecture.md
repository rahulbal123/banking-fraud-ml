# System Architecture

## Data Layer
- CSV transaction ingestion
- JSON customer ingestion
- XML device risk ingestion
- PDF KYC extraction

## ETL Layer
- Schema validation
- Referential integrity check
- Business rule validation
- Null & duplicate handling

## Feature Layer
- Velocity features
- Risk ratio features
- Time-based features
- One-hot encoding

## Model Layer
- XGBoost Classifier
- Imbalance handling
- ROC-AUC evaluation

## Deployment Simulation
- Model serialization
- Real-time inference simulation
- Latency measurement

## Monitoring
- Drift detection (KS test)
- Logging simulation
- Schema change detection