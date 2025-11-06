# Wine Quality Prediction – Neural Network (100 Epochs)

This project uses a simple Neural Network to predict wine quality based on physicochemical properties like acidity, sugar, pH, alcohol content, etc.  
The model was trained for 100 epochs and visualized with loss/accuracy graphs.

## 🔥 What’s Inside
- ✅ Google Colab Notebook (`.ipynb`)
- ✅ Training graphs (100 epochs)
- ✅ Presentation slides (`.pptx`)
- ✅ Instructions to download dataset
- ✅ Clean and beginner-friendly code

## 📌 Dataset
The dataset is the classic **Wine Quality Data Set (UCI Machine Learning Repository)**.

You can download it from here:  
https://archive.ics.uci.edu/dataset/186/wine+quality

After downloading:
- Put the `.csv` file in a folder named `data/` (optional)
- Or load it directly in Colab via file upload

## 🚀 How to Run
You can run the project in **Google Colab** (recommended):

1. Open the notebook  
2. Upload the dataset  
3. Run all cells to train the model  
4. View graphs and predictions

If you want to run locally:
```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

## 📊 Results & Visualizations

All the visualizations from data exploration and model training are available in the results folder:
| Graph                             | File                             |
| --------------------------------- | -------------------------------- |
| Feature distribution plots        | `feature_distributions.png`      |
| Quality score distribution        | `quality_score_distribution.png` |
| Predictions vs Actual Scatterplot | `predictions_vs_actual.png`      |
| Training Loss Curve               | `loss and mae_over_epochs.png`   |
| Training MAE Curve                | `loss and mae_over_epochs.png`   |
