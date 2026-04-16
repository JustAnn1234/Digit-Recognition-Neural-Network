# Digit-Recognition-Neural-Network
A machine learning project that recognizes handwritten digits (0-9) using a neural network classifier, deployed as an interactive Streamlit web app.

## Features

- **Handwritten Digit Recognition**: Upload images of digits and get instant predictions
- **Neural Network Model**: Trained on the sklearn digits dataset using MLPClassifier
- **Interactive Web App**: Built with Streamlit for easy use
- **Preprocessing Pipeline**: Automatic image preprocessing (grayscale, resize, normalization)

## Demo

The app is live at [Streamlit Cloud]([https://your-app-link.streamlit.app](https://digit-recognition-neural-network-hlqdf4clkvrfdgkwhj9ls4.streamlit.app/)) (replace with actual link if deployed).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/digit-recognition-nn.git
   cd digit-recognition-nn
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the Web App
```bash
streamlit run app.py
```
Open your browser to `http://localhost:8501` and upload digit images to test predictions.

### Training the Model
Open `Decision Tree Classifier.ipynb` in Jupyter and run the cells to:
- Load and explore the digits dataset
- Train the MLPClassifier model
- Evaluate performance with accuracy metrics
- Save the trained model as `digit_model.pkl`

## Model Details

- **Algorithm**: Multi-layer Perceptron (MLP) Classifier from scikit-learn
- **Dataset**: sklearn's digits dataset (1,797 8x8 grayscale images)
- **Preprocessing**: Images resized to 8x8, inverted, and scaled to 0-16 range
- **Accuracy**: ~95% on test set (run notebook for exact metrics)

## Project Structure

```
├── app.py                 # Streamlit web application
├── Decision Tree Classifier.ipynb  # Jupyter notebook for model training
├── digit_model.pkl        # Trained neural network model
├── requirements.txt       # Python dependencies
└── README.md             # This file
```

## Technologies Used

- Python 3.x
- scikit-learn
- Streamlit
- NumPy
- Pillow (PIL)
- Matplotlib
- Joblib

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- sklearn digits dataset for training data
- Streamlit for the web framework
- Open source community for inspiration</content>
<parameter name="filePath">c:\Users\hassa\Neural network\README.md
