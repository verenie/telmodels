# telmodels
Trained models from the TEL experiment.

# naming conventions
1. Models ending with <b>TEL</b> represent models trained with transfer learning via model fine-tuning by replacing the final
classification layer and retraining all layers with the small operational dataset.
2. Models ending with <b>ex</b> represent models trained with transfer learning via convolutional feature extraction by replacing the
final layer and only retraining the final layer, thus examining maximum feature transfer.
3. Models ending with <b>b</b> represent models that were initialized randomly and trained on the small operational dataset without
transfer learning.
4. Additional model <i>resnet152ACNTf0.pt</i> was trained with fine-tuning to access random fold performance on accuracy as a side experiment.

