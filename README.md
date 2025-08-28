
# Physics-Informed Neural Networks for Temperature Forecasting in Bangladesh

This repository contains the code and methodology for improving daily temperature forecasting in Bangladesh using Physics-Informed Neural Networks (PINNs). The model incorporates meteorological data and seasonal knowledge to enhance prediction accuracy.

## Description
The model integrates physical constraints, such as the annual temperature cycle, into a neural network framework to ensure both data-driven predictions and physical consistency. This approach results in more accurate and interpretable climate forecasting, which can be used for climate risk management in Bangladesh.

## Project Structure
- `Final_ICCIT (4).ipynb`: Jupyter notebook containing the PINN model and training code.
- `ICCIT___2 (1).pdf`: Paper outlining the methodology and results of this study.
- `Data/`: (If applicable) Folder containing datasets used for training.
- `Figures/`: (If applicable) Folder containing figures and visualizations.

## Results
The PINN model achieves the following:
- **RMSE**: 1.53°C
- **R²**: 0.8659
- **MSE**: 2.3333°C²
- **MAE**: 1.1270°C

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Climate-Prediction-PINN.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook (`Final_ICCIT (4).ipynb`) to train and test the model.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Research supported by [Your Institute Name].
- Special thanks to the dataset providers and contributors.

## Future Work
- Exploring hybrid models with more climate variables.
- Enhancing model robustness for extreme weather events.
- Including more meteorological stations for better generalizability.
