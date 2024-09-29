# **Adversarial Attacks and Defense Methods in Computer Vision** 

Welcome to the repository for exploring adversarial attacks and defenses in computer vision models! This project investigates how adversarial examples can manipulate machine learning models and evaluates various simple defenses to improve robustness.

[This is a companion piece to the main post here!](https://cookiemachine.notion.site/How-to-Fool-an-AI-Understanding-Adversarial-Attacks-and-Simple-Defenses-5-20-mins-1035c49abbfe80798b63cc4448f03810)

## **Project Overview**

This repository contains the Jupyter notebook used to conduct experiments on adversarial attacks, specifically targeting computer vision models like **ResNet** and **Vision Transformers (ViTs)**. Here, we delve into:

- How **adversarial noise** impacts model predictions.
- Different **defense methods** (e.g., compression, blurring, noise addition).
- Comparisons between models of different sizes and architectures.
- Insights into effective mitigation techniques for adversarial attacks.

## **Repository Structure**

- **`adversarial_experiments.ipynb`**: The main notebook containing all code, visualizations, and explanations for:
  - Implementing **Basic Iterative Method (BIM)** attacks.
  - Evaluating the impact of adversarial examples on different models.
  - Testing various defense methods and analyzing their effectiveness.

- **`data/`**: Sample images and datasets used for running adversarial attacks and defense tests.


## **Getting Started**

### **Prerequisites**

To run the notebook, you'll need the following Python packages:

- `numpy`
- `pytorch`
- `matplotlib`
- `torchvision`
- `scikit-image`
- `jupyterlab` or `notebook`

Install dependencies using:

```bash
pip install -r requirements.yaml
