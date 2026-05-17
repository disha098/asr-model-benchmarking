# ASR Model Benchmarking

This project compares modern Automatic Speech Recognition (ASR) models for noisy real-world audio applications. The models were evaluated using transcription accuracy, inference speed, memory usage, and deployment feasibility.

## Models Evaluated
- Whisper Small
- Faster-Whisper Small
- Whisper Tiny

## Dataset Used
- LibriSpeech (test-clean subset)

## Evaluation Metrics
- Word Error Rate (WER)
- Inference Time
- Memory Usage

## Technologies Used
- Python
- OpenAI Whisper
- Faster-Whisper
- Transformers
- JiWER
- Kaggle Notebook

## Conclusion
Based on the benchmarking results, Faster-Whisper Small provided the best balance between transcription accuracy and inference speed, making it suitable for real-time customer support applications.
