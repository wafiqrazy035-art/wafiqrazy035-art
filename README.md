# Hi, I'm Wafiq Razy

Self-taught ML practitioner from Indonesia, focused on **model quantization & compression** and **quantitative trading systems**.

Building from first principles — implementing techniques from scratch rather than relying solely on libraries, to deeply understand what's happening under the hood.

---

## 🔬 Featured Work

### 🧠 [Quantization Experiments](https://github.com/wafiqrazy035-art/quantization-experiments)

Research-grade implementation of low-bit quantization techniques, built from scratch in PyTorch.

**7 quantization methods implemented:**
- INT4 (naive packed)
- Binary (1-bit) with Straight-Through Estimator
- Ternary (1.58-bit)
- FP8 E4M3 (custom NexFP8)
- Sparse Binary
- **PolarQuant** (polar coordinate-based)
- **QJL** (Quantized Johnson-Lindenstrauss)

**End-to-end integration** with full transformer model (attention, embedding, transformer block) + FP32 baseline for proper comparison. Includes reproducibility tests and systematic experiment scripts.

`Python` `PyTorch` `Quantization` `Transformers`

---

### 📈 Algorithmic Trading Systems

Multiple custom trading systems exploring different ML approaches:

- **[NexRL](https://github.com/wafiqrazy035-art/...)** — Custom reinforcement learning framework with contextual bandit core, regime-aware position sizing, and walk-forward backtesting
- **[Hybrid-Transformer-PPO](https://github.com/wafiqrazy035-art/Hybrid-Transformer-PPO-for-Quantitative-Trading)** — Transformer + PPO hybrid for quantitative trading
- **[AlphaWeaverAI](https://github.com/wafiqrazy035-art/AlphaWeaverAI)** — Multi-strategy AI trading framework
- **[nextrade-engine](https://github.com/wafiqrazy035-art/nextrade-engine)** — Lightweight multi-market trading engine
- **[Whale_Tracker](https://github.com/wafiqrazy035-art/Whale_Tracker)** — On-chain whale activity tracking

`Python` `PyTorch` `Reinforcement Learning` `Time Series`

---

### 📊 ML Foundations

Solid foundation in classical ML through hands-on Kaggle work:

- **Titanic** — Voting ensemble, public score 0.76794
- **Iris Classifier** — Multi-class with 96.67% accuracy (logistic regression baseline)
- **House Price Prediction** — Lasso regression, 0.13349 RMSE
- **Sentiment IMDB** — NLP classification, 90% accuracy on 50K reviews

`scikit-learn` `pandas` `Feature Engineering` `Cross-Validation`

---

## 🛠️ Tech Stack

**Languages:** Python

**ML/DL:** PyTorch · scikit-learn · pandas · NumPy · matplotlib · seaborn

**Specialties:** Model quantization · Reinforcement learning · Statistical validation · Time series analysis

**Tools:** Git · GitHub · Jupyter · VSCode

**Currently exploring:** Edge AI deployment · Sub-4-bit quantization techniques · Stat arbitrage

---

## 📖 Approach

I believe in **building from first principles** — implementing techniques from scratch helps me understand them at a level that simply using libraries can't provide.

For trading systems, I emphasize **rigorous statistical validation** before building — Information Coefficient testing, permutation tests, walk-forward backtesting — to avoid the common pitfall of strategies that look profitable in-sample but fail out-of-sample.

For ML systems, I focus on **end-to-end integration** rather than isolated components — quantization that works on a single tensor is different from quantization that works in a full transformer training loop.

---

## 📬 Contact

- 📧 Email: wafiqrazy035@gmail.com
- 💼 LinkedIn: [M. Wafiq Al Farazy](https://linkedin.com/in/...)
- 📊 Kaggle: [@wafiqrazy38](https://www.kaggle.com/wafiqrazy38)

---

*Open to freelance and internship opportunities in ML engineering, model compression, and quantitative research.*

📍 Indonesia
