# 🛡️ MarginGuard

**Causal ML Decision Engine for Profit-Aware Incentive Routing**

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Causal ML](https://img.shields.io/badge/Causal%20ML-Uplift%20Modeling-2dd4bf)](https://github.com/thanhan25/marginguard-ai)

## 🎯 Problem
E-commerce and fintech companies waste millions subsidizing "Sure Things" — customers who would convert anyway without financing offers.

## 💡 Solution
MarginGuard uses causal machine learning (uplift modeling) to identify the **Persuadables** — users who convert *only because* an incentive was offered — and routes offers exclusively to them.

## 🏗️ Architecture
- **Meta-Learners**: S-Learner, T-Learner, X-Learner, R-Learner
- **Deep Representation**: TARNet & DragonNet with propensity regularization
- **Evaluation**: Qini Curve, AUUC, Net Profit vs. Treat-All Baseline
- **Deployment**: FastAPI microservice (<15ms latency at checkout)

## 📊 Dataset
Benchmarked on the **Criteo 13.9M RCT Dataset** — gold-standard randomized control trial with zero observational bias.

## 🚀 Quick Start
```bash
git clone https://github.com/thanhan25/marginguard-ai.git
cd marginguard-ai
pip install -r requirements.txt
python src/pipeline.py
```

## 💼 Business Impact
- **Preserve margin** on Sure Things (Uplift ≈ 0)
- **Capture profit** on Persuadables (Uplift > 0)
- **Avoid churn** on Sleeping Dogs (Uplift < 0)

## 🤝 Contributing
Seeking collaborators passionate about causal inference, PyTorch architectures, and production ML deployment.

## 📄 License
MIT License — see [LICENSE](LICENSE) for details.

## 👤 Author
**Thanh An Vo**  
M.Sc. Quantitative Economics, University of Bonn  
[LinkedIn](https://linkedin.com/in/an-vo-quant) | [thanhan25@gmail.com](mailto:thanhan25@gmail.com)
