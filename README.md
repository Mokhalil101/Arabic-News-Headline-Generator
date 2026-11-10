
# Arabic News Headline Generator

## Models

- SimpleRNN Encoder-Decoder
- LSTM Encoder-Decoder

## Architecture

Seq2Seq without Attention.

## Evaluation

- BLEU-1
- BLEU-2
- BLEU-4
- ROUGE-1
- ROUGE-2
- ROUGE-L
- Inference Time

## Directory Structure

models/
    simple_rnn_best.pt
    lstm_best.pt

vocabulary/
    stoi.pkl
    itos.pkl
    vocab_metadata.json

results/
    training_history.json
    evaluation_metrics.json
    model_comparison.csv
    predictions.csv

config/
    model_config.json
