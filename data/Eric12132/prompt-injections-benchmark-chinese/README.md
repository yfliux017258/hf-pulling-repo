---
dataset_info:
  features:
  - name: prompt
    dtype: string
  - name: completion
    dtype: string
  - name: taiwan_translation
    dtype: string
  splits:
  - name: train
    num_bytes: 2305842
    num_examples: 1828
  - name: test
    num_bytes: 119268
    num_examples: 91
  download_size: 1521119
  dataset_size: 2425110
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: test
    path: data/test-*
---
