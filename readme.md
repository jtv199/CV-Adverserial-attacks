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
```

## Running the Notebook

To run the experiments:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/adversarial-attacks-defense.git
   ```
2. Navigate to the project directory:
   ```bash
   cd adversarial-attacks-defense
   ```
3. Launch Jupyter Lab or Notebook:
   ```bash
   jupyter lab
   ```
4. Open and run the **`adversarial_experiments.ipynb`** notebook.

### Using the Notebook

The notebook is structured to guide you through each stage of the experiments, from loading data, applying adversarial attacks, and running different defense strategies, to visualizing the results.

- **Sections to Explore:**
  - **Introduction to Adversarial Attacks**: Basic concepts and examples of adversarial noise.
  - **Experiment Setup**: Details on the models used, the data, and the attack implementation.
  - **Defense Methods Evaluation**: Testing simple defenses like blurring, compression, and adding noise.

## FAQ

- **Can I apply these techniques to other models?**  
  Yes! You can modify the notebook to use other pretrained models from PyTorch. The structure is flexible for adapting to different architectures.

- **Are there any limitations?**  
  These experiments are computationally intensive, especially when dealing with larger models like **ResNet-101**. Running them on a GPU is highly recommended.

## Contributing

Contributions are welcome! If you have ideas for new defense methods, or ways to improve the experiments, feel free to:

- Fork the repository.
- Create a feature branch.
- Submit a pull request.

## License

This project is licensed under the MIT License—see the **`LICENSE`** file for details.

## Acknowledgements

Thanks to the creators of the datasets and pretrained models used in this project. Special thanks to [Neuralception](https://www.neuralception.com/adversarialexamples-bim/) for providing insights into BIM attack implementation.

