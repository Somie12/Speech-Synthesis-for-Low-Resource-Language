## 🔗 Access Full Results

You can explore the full training results, checkpoints, and visualizations for the Conformer-based LID model at the link below:

[📁 Google Drive – lid_model_results_20250522_182133](https://drive.google.com/drive/folders/1itCJihuMkRx9ouccISsXvzWozaFIhf_0)







## 📂 Output Directory Structure

```
lid_model_results_YYYYMMDD_HHMMSS/
│
├── checkpoints/
│   └── (best models saved during training)
│
├── epoch_models/
│   └── (models saved after each epoch for resuming training)
│
├── logs/                                                # Training logs and history
│   ├── training_history.json
│   └── training_metrics.csv
│
├── test_results/                                         # Evaluation metrics and visualizations
│   ├── classification_metrics.csv
│   ├── confusion_matrix.csv
│   ├── confusion_matrix.png
│   ├── misclassification_analysis.csv
│   ├── predictions_distribution.png
│   ├── roc_curves.png
│   ├── sample_predictions.csv
│   ├── test_summary.json
│   └── top_misclassifications.png
│
├── visualizations/                                         # Training visual analytics (epoch-wise)
│   ├── batch_loss_dist_epoch_1.png
│   ├── batch_loss_dist_epoch_2.png
│   ├── ...
│   ├── batch_loss_dist_epoch_30.png
│   ├── combined_training_metrics.png
│   ├── epoch_training_time.png
│   ├── final_learning_curve.png
│   ├── learning_curves_1.png
│   ├── learning_curves_2.png
│   ├── ...
│   └── learning_curves_30.png
│
├── config.json                                                # Full training configuration
└── model_summary.txt                                          # Architecture summary of the model

```
