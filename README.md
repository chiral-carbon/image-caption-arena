Comparing the performance of different image captioning models on benchmark datasets to evaluate on standard measurement metrics.

The models to be compared are:

- Encoder-decoder
- Attention mechanism
- Dense Captioning
- Deep Multimodal Similarity Model
- Reinforcement Learning

The benchmark datasets comprise:
- Flicker8k
- Flicker30k
- MSCOCO

The metrics used for evaluation are:

* BLEU 1-4
* METEOR 
* CIDEr 
* ROUGE-L


I have tabulated the performance of each:

| Dataset | Model | BLEU-1 | BLEU-2 | BLEU-3 | BLEU-4 | METEOR | ROUGE-L | CIDEr |
|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|
| | [CNN-LSTM](https://www.kaggle.com/blackcanary/image-caption-flicker8k) | 0.530076 | 0.286551 | 0.197607 | 0.94241 | | | |
| | CNN-LSTM with Attention | | | | | | | |
| Flicker8k | DenseCap | | | | | | | |
| | DMSM | | | | | | | |
| | Reinforcement Learning | | | | | | | |
| | | | | | | | | |
| | [CNN-LSTM](https://www.kaggle.com/blackcanary/image-caption-flicker30k-w-o) | | | | | | | |
| | CNN-LSTM with Attention | | | | | | | |
| Flicker30k | DenseCap | | | | | | | |
| | DMSM | | | | | | | |
| | Reinforcement Learning | | | | | | | |
| | | | | | | | | |
| | CNN-LSTM | | | | | | | |
| | CNN-LSTM with Attention  | | | | | | | |
| MSCOCO | DenseCap | | | | | | | |
| | DMSM | | | | | | | |
| | Reinforcement Learning | | | | | | | |
