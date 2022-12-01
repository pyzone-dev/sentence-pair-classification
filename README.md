# sentence-pair-classification
Fine-tune BERT for Sentence Pair Classification task tutorial

- [Open in Google Colab](https://colab.research.google.com/github/pyzone-dev/sentence-pair-classification/)
- Tutorial: [Fine-tune BERT for Sentence Pair Classification](https://colab.research.google.com/github/pyzone-dev/sentence-pair-classification/blob/main/sentence_pair_classification.ipynb)

```
Model weights saved in ./results/checkpoint-7900/pytorch_model.bin
Deleting older checkpoint [results/checkpoint-7700] due to args.save_total_limit
{'loss': 0.0066, 'learning_rate': 6.451612903225807e-07, 'epoch': 2.91}
 97%|████████████████████████████████████████████████████████████████████████████████████▎  | 8000/8250 [5:20:04<03:04,  1.36it/s]The following columns in the evaluation set don't have a corresponding argument in `RobertaForSequenceClassification.forward` and have been ignored: question, context. If question, context are not expected by `RobertaForSequenceClassification.forward`,  you can safely ignore this message.
***** Running Evaluation *****
  Num examples = 22000
  Batch size = 64
{'eval_loss': 0.018584178760647774, 'eval_f1': 0.9785344189489267, 'eval_runtime': 164.1653, 'eval_samples_per_second': 134.011, 'eval_steps_per_second': 2.095, 'epoch': 2.91}
 97%|████████████████████████████████████████████████████████████████████████████████████▎  | 8000/8250 [5:22:48<03:04,  1.36it/s]Saving model checkpoint to ./results/checkpoint-8000
Configuration saved in ./results/checkpoint-8000/config.json
Model weights saved in ./results/checkpoint-8000/pytorch_model.bin
Deleting older checkpoint [results/checkpoint-7800] due to args.save_total_limit
{'loss': 0.0042, 'learning_rate': 3.870967741935484e-07, 'epoch': 2.95}
 98%|█████████████████████████████████████████████████████████████████████████████████████▍ | 8100/8250 [5:24:06<01:50,  1.35it/s]The following columns in the evaluation set don't have a corresponding argument in `RobertaForSequenceClassification.forward` and have been ignored: question, context. If question, context are not expected by `RobertaForSequenceClassification.forward`,  you can safely ignore this message.
***** Running Evaluation *****
  Num examples = 22000
  Batch size = 64
{'eval_loss': 0.01884392462670803, 'eval_f1': 0.9783144406111385, 'eval_runtime': 165.3622, 'eval_samples_per_second': 133.041, 'eval_steps_per_second': 2.08, 'epoch': 2.95}
 98%|█████████████████████████████████████████████████████████████████████████████████████▍ | 8100/8250 [5:26:51<01:50,  1.35it/s]Saving model checkpoint to ./results/checkpoint-8100
Configuration saved in ./results/checkpoint-8100/config.json
Model weights saved in ./results/checkpoint-8100/pytorch_model.bin
Deleting older checkpoint [results/checkpoint-7900] due to args.save_total_limit
{'loss': 0.0082, 'learning_rate': 1.2903225806451614e-07, 'epoch': 2.98}
 99%|██████████████████████████████████████████████████████████████████████████████████████▍| 8200/8250 [5:28:09<00:36,  1.35it/s]The following columns in the evaluation set don't have a corresponding argument in `RobertaForSequenceClassification.forward` and have been ignored: question, context. If question, context are not expected by `RobertaForSequenceClassification.forward`,  you can safely ignore this message.
***** Running Evaluation *****
  Num examples = 22000
  Batch size = 64
{'eval_loss': 0.01884007453918457, 'eval_f1': 0.9787759131293189, 'eval_runtime': 164.9596, 'eval_samples_per_second': 133.366, 'eval_steps_per_second': 2.085, 'epoch': 2.98}
 99%|██████████████████████████████████████████████████████████████████████████████████████▍| 8200/8250 [5:30:54<00:36,  1.35it/s]Saving model checkpoint to ./results/checkpoint-8200
Configuration saved in ./results/checkpoint-8200/config.json
Model weights saved in ./results/checkpoint-8200/pytorch_model.bin
Deleting older checkpoint [results/checkpoint-8000] due to args.save_total_limit
100%|███████████████████████████████████████████████████████████████████████████████████████| 8250/8250 [5:31:35<00:00,  1.36it/s]

Training completed. Do not forget to share your model on huggingface.co/models =)


{'train_runtime': 19895.0898, 'train_samples_per_second': 13.27, 'train_steps_per_second': 0.415, 'train_loss': 0.027081513957543806, 'epoch': 3.0}
100%|███████████████████████████████████████████████████████████████████████████████████████| 8250/8250 [5:31:35<00:00,  2.41s/it]
The following columns in the evaluation set don't have a corresponding argument in `RobertaForSequenceClassification.forward` and have been ignored: question, context. If question, context are not expected by `RobertaForSequenceClassification.forward`,  you can safely ignore this message.
***** Running Evaluation *****
  Num examples = 22000
  Batch size = 64
{'eval_loss': 0.016812607645988464, 'eval_f1': 0.9798155993022676, 'eval_runtime': 167.2537, 'eval_samples_per_second': 131.537, 'eval_steps_per_second': 2.057}

```
