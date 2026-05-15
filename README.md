# pa-outcome-engine
Machine learning system for predicting prior authorization outcomes using healthcare claims and clinical features.

The system classifies requests into:
- Approved
- Denied
- Partial Approval
- Alternative Therapy

Built using PostgreSQL, Python, XGBoost, and Amazon SageMaker.

PostgreSQL → Feature Engineering → XGBoost → Prediction API

Tech Stack
- Python
- PostgreSQL
- XGBoost
- Scikit-learn
- Amazon SageMaker
- Pandas

Features
- Synthetic healthcare PA dataset generation
- Multi-class classification modeling
- Feature engineering pipeline
- Model evaluation metrics
- Explainable AI feature importance

