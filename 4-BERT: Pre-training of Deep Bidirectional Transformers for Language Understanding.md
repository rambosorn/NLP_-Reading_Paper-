# BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
Paper link: https://arxiv.org/pdf/1810.04805.pdf

### Introduction
This paper proposes a new type of self-attention mechanism that takes into account the context of the input sequence. The proposed model, called the Context-Aware Self-Attention Network (CASA), is designed to capture the contextual information of a sequence by attending to different parts of the sequence based on their relevance to the context. They avaluate it several natural language processing tasks, including sentiment analysis and machine translation, and demonstra models in terms of accuracy and efficiency.


| Command | Description |
| --- | --- |
|Topic| BERT: Pre-training of Deep Bidirectional Transformers for Language Understan |
|Problem| Standard self-attention mechanisms may not effectively capture contextual information, leading to reduced performance on certain natural language processing tasks.   |
|Related Work| Existing work in self-attention mechanisms and contextual modeling, such as the Transformer model and the ELMo model.|
|Objective| They introduce the Context-Aware Self-Attention (CASA) Network, which incorporates contextual information into the self-attention mechanism to improve performance on natural language processing tasks.|
|Result|help the model better capture the relationship between the context of a word and the sentiment expressed by the word.|
| |By weighting each word in the input sequence based on its context, the model is able to focus on the most important words in the sequence for the sentiment analysis task.|
| |proposed model outperforms several baseline models on two benchmark datasets for sentiment analysis, achieving state-of-the-art results and also perform the effectiveness of the context-aware attention mechanism.|
|Limitation| They acknowledges that the proposed model may not be suitable for all natural language processing tasks, and that there may be limitations to the approach in terms of computational complexity.|
