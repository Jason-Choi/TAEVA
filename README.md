# Waltzboard: Multi-Criteria Optimization for Automatic Dashboard Design

![figure](https://user-images.githubusercontent.com/2310571/236782548-6976a025-f97e-443f-8e07-50e5d442890e.png)

**_Waltzboard_** is an automatic dashboard design system that optimizes the design in terms of four design criteria, namely Specificity, Interestingness, Diversity, and Coverage. With these criteria, Waltzboard not only optimizes for the expressiveness and interestingness of a single visualization but also improves the diversity and coverage of the dashboard as a whole. Users are able to express their intent for desired dashboard design to Waltzboard, including specifying preferred or constrained attributes and adjusting the weight of the Oracle. This flexibility in expressing intent enables Waltzboard to design dashboards that are well-aligned with the user's own analytic goals leading to more effective and efficient data exploration and analysis.

## Installation

```
pip install waltzboard
```

## Usage Example

- Detailed documentations are under construction!

```python
from waltzboard import Waltzboard
gl = Waltzboard(df)
gl.train(["rect", "count", "Creative_Type"])
gl.infer().display()
```

## Demo for Waltzboard Library

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12_Wm74nT2_X9zJlV0PJ0SeEVhyOc0eUf)

## Demo for Web-based Interface

```
pip install .
python app.py
cd client
pnpm install
pnpm dev
```

## Development

TBA

## Reference

### Multi-Criteria Optimization for Automatic Dashboard Design

**_Jiwon Choi_** and Jaemin Jo

Presented in 2023 Eurographics Conference on Visualization (EuroVis), Leipzig, Germany

Invited to IEEE Pacific Visualization Symposium 2023, Seoul, Korea
