# Privacy-Preserving GPS Trace Generation

Generate synthetic GPS trajectories that preserve aggregate mobility patterns while protecting individual privacy using Markov chains and differential privacy techniques.

## 🎯 Overview

This project creates **realistic fake GPS tracks** that maintain useful patterns (hotspots, rush hours) without exposing real user routes. Perfect for mobility research, urban planning, and location analytics while respecting privacy.

## 🔧 Method

- **Markov Chain** model over spatial grid cells
- **Laplace noise** injection for privacy protection  
- **Contextual constraints** to preserve temporal/spatial distributions
- **Privacy-utility tradeoff** evaluation with KL divergence and re-identification metrics

## 📊 Results

- ✅ Perfect temporal pattern preservation (KL=0.000)
- ✅ Low spatial distortion (KL=0.132) 
- ✅ Strong privacy protection (NN distance=0.325)
- ✅ Clear privacy-utility tradeoff demonstrated

## 🚀 Try It Now

**[👉 Open Interactive Colab Notebook](https://colab.research.google.com/drive/1egHiO7QWQK2dysrlpPBg5A_can9Qhi48?usp=sharing)**

Click the link above to see the complete working implementation, run experiments, and visualize results instantly in your browser.

## 🎓 Academic Alignment

Implements techniques from privacy-preserving location analytics, metric differential privacy, and contextual synthetic data generation research.

## 📁 Repository Structure

- `notebook.ipynb` - Complete implementation and evaluation
- `README.md` - This file
- Results and visualizations included in notebook

---

*Built for research in statistical privacy and spatial computing applications.*
