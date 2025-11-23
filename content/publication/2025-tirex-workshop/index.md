---
title: "TiRex: Zero-Shot Forecasting Across Long and Short Horizons"
date: 2025-06-01
publishDate:  2025-06-01
authors: ["**Andreas Auer**, Patrick Podest, Daniel Klotz, Sebastian Böck, Günter Klambauer, Sepp Hochreiter"]
publication_types: ["2"]
abstract: "In-context learning, the ability of large language models to perform tasks using only examples provided in the prompt, has recently been adapted for time series forecasting. This paradigm enables zero-shot prediction, where past values serve as context for forecasting future values, making powerful forecasting tools accessible to non-experts and increasing the performance when training data are scarce. Most existing zero-shot forecasting approaches rely on transformer architectures, which, despite their success in language, often fall short of expectations in time series forecasting, where recurrent models like LSTMs frequently have the edge. Conversely, while LSTMs are well-suited for time series modeling due to their state-tracking capabilities, they lack strong in-context learning abilities. We introduce TiRex that closes this gap by leveraging xLSTM, an enhanced LSTM with competitive in-context learning skills. Unlike transformers, state-space models, or parallelizable RNNs such as RWKV, TiRex retains state-tracking, a critical property for long-horizon forecasting. To further facilitate its state-tracking ability, we propose a training-time masking strategy called CPM. TiRex sets a new state of the art in zero-shot time series forecasting on the HuggingFace benchmarks GiftEval and Chronos-ZS, outperforming significantly larger models including TabPFN-TS (Prior Labs), Chronos Bolt (Amazon), TimesFM (Google), and Moirai (Salesforce) across both short- and long-term forecasts."
featured: true
publication: "Workshop on Foundation Models for Structured Data @ ICML 2025 [Spotlight - Oral]"
links:
  - icon_pack: ai
    icon: arxiv
    name: Paper
    url: 'https://openreview.net/pdf?id=cWrbpOZGRa'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://github.com/NX-AI/tirex'
  - icon_pack: fab
    icon: square-binary
    name: Model (HuggingFace)
    url: 'https://huggingface.co/NX-AI/TiRex'
---