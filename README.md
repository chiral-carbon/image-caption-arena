Comparing the performance of different image captioning models on benchmark datasets to evaluate on standard measurement metrics.

The models to be compared are:

- Encoder-decoder
- Compositional
- Dense Captioning
- Deep Multimodal Similarity Model
- Reinforcement Learning

The benchmark datasets comprise:
- Flicker8k
- Flicker30k
- MSCOCO

The metrics used for evaluation are:

* BLEU 1-4
* METEOR score
* CIDEr score


I have tabulated the performance of each:

| Dataset | Model | BLEU-1 | BLEU-2 | BLEU-3 | BLEU-4 | METEOR | CIDEr |
|:--------|:--------|:--------|:--------|:--------|:--------|:--------|:--------|
| | CNN-LSTM | 53.0076 | 28.6551 | 19.7607 | 9.4241 | | |
| | CNN-LSTM with Attention | | | | | | |
| Flicker8k | DenseCap | | | | | | |
| | DMSM | | | | | | |
| | Reinforcement Learning | | | | | | |
|--+--+--+--+--+--+--+--|
| | CNN-LSTM | | | | | | |
| | CNN-LSTM with Attention | | | | | | |
| Flicker30k | DenseCap | | | | | | |
| | DMSM | | | | | | |
| | Reinforcement Learning | | | | | | |
| | | | | | | | |
| | CNN-LSTM | | | | | | |
| | CNN-LSTM with Attention | | | | | | |
| MSCOCO | DenseCap | | | | | | |
| | DMSM | | | | | | |
| | Reinforcement Learning | | | | | | |
