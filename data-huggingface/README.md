---
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: dev
    path: data/dev-*
  - split: test
    path: data/test-*
dataset_info:
  features:
  - name: input
    dtype: string
  - name: target
    dtype: string
  splits:
  - name: train
    num_bytes: 316739508
    num_examples: 1199705
  - name: dev
    num_bytes: 39645742
    num_examples: 150171
  - name: test
    num_bytes: 39708222
    num_examples: 150124
  download_size: 265500526
  dataset_size: 396093472
---
# Dataset Card for "gramatika1500k"

[More Information needed](https://github.com/huggingface/datasets/blob/main/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)