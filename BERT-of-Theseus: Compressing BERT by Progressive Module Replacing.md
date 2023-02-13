# BERT-of-Theseus: Compressing BERT by Progressive Module Replacing

#### credit source: https://aclanthology.org/2020.emnlp-main.633.pdf


### Intro
BERT-of-Theseus: Compressing BERT by Progressive Module Replacing" provides a novel approach for compressing large language models, and presents new insights into the trade-off between model size and accuracy in the field of natural language processing.

| Command | Description |
| --- | --- |
| Topic |BERT-of-Theseus: Compressing BERT by Progressive Module Replacing |
| Problem | 1. The size and computational cost of large language models like BERT are challenging to handle, especially when deploying in resource-constrained environments such as mobile devices or edge computing systems.|
|  |2. The challenge of reducing the size and computational cost of large language models while maintaining their accuracy and ability to generalize to new data.|
|  |3. The need for a method that balances the trade-off between model size and accuracy, making it possible to deploy large language models in resource-constrained environments while maintaining their performance. |
| Objective | Proposing a method for compressing BERT through the use of progressive module replacing, which allows for reducing the size of the model while maintaining its accuracy and performance on various natural language processing tasks. The authors aim to find a balance between model size and accuracy, making it possible to deploy large language models in resource-constrained environments while maintaining their performance.|
| Solution  | They proposed the progressive module replacing method works by gradually replacing the original BERT modules with smaller, computationally efficient modules, while maintaining the overall performance of the model. The method is designed to be done in a step-by-step manner, allowing the model to be fine-tuned after each replacement to ensure its performance is maintained.
|  | 1. Train the original BERT model on a large-scale dataset to obtain the baseline performance.|
|  | 2. Replace the original BERT modules with smaller, computationally efficient modules while keeping the overall architecture of the model intact.|
|  | 3. Fine-tune the model with the new, smaller modules on the same large-scale dataset to evaluate its performance.|
|  | 4. Repeat steps 2 and 3 until the desired level of compression is achieved.|
| Limitation | Show strong performance in NLP tasks, including named entity recognition, part-of-speech tagging, dependency parsing, and text classification. The pre-trained models have strong language coverage and the toolkit's architecture is flexible and easily customizable. |
| Conclusion and Future work | Focus on improving performance, expanding language coverage, optimizing resource efficiency, and developing advanced models for specific tasks. The authors believe Stanza is a significant step forward in NLP research and toolkit development. |

### Set Up Environment

