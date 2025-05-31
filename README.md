Hindi Text Summarization using Deep Learning

A complete implementation of a **Sequence-to-Sequence (Seq2Seq)** model with attention (optional) for summarizing Hindi news articles. Built using **PyTorch** and basic **NLP preprocessing techniques**, the model generates concise summaries from long Hindi texts.

---

## Features

-  Processes and summarizes **Hindi-language** news content
-  Implements a **Seq2Seq architecture** with Encoder-Decoder LSTM
-  Dynamic **vocabulary creation** with `<PAD>`, `<UNK>`, `<SOS>`, `<EOS>` tokens
-  Includes **tokenization, padding, and batching**
-  Loads and runs saved models for inference
-  Interactive input + summary generation with `generate_summary()` method

---

##  Core NLP Concepts Used

| Concept         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Tokenization    | Splitting sentences into individual Hindi tokens                           |
| Vocabulary      | Created from token frequencies and includes special tokens                 |
| Padding         | Ensures all input sequences are of fixed length                            |
| Embeddings      | Words are converted to dense vectors for learning                          |
| Seq2Seq Model   | Encoder-decoder architecture for translation-style summarization           |
| LSTM            | Captures temporal dependencies in both encoder and decoder                 |
| `<UNK>/<PAD>`   | Handles unknown words and aligns input shapes
