# BERT-of-Theseus: Compressing BERT by Progressive Module Replacing

#### credit source: https://aclanthology.org/2020.emnlp-main.633.pdf


### Intro
BERT-of-Theseus: Compressing BERT by Progressive Module Replacing" provides a novel approach for compressing large language models, and presents new insights into the trade-off between model size and accuracy in the field of natural language processing.

| Command | Description |
| --- | --- |
| Topic | Stanza: A Python Natural Language Processing Toolkit for Many Human Languages |
| Challenge | 1. The lack of easy-to-use and accessible NLP libraries for different languages and domains. The need for faster and more efficient NLP models for large-scale text processing. |
|  | 2. The requirement for more flexible and extensible NLP toolkits that can be easily customized for different NLP tasks and domains. |
|  | 3. The need for NLP toolkits that are built on top of modern machine learning frameworks, such as PyTorch, to leverage the latest developments in deep learning and other NLP techniques. |
| Feature method | Stanza works by converting raw text input into a structured representation and using the structured representation to perform NLP tasks. The toolkit leverages the latest developments in deep learning and other NLP techniques, and is designed to be flexible, extensible, and compatible with different programming languages and platforms. |
| Limitation | Stanza not being state-of-the-art in every NLP task, limited language coverage, high computational resource requirements, and potential performance issues with small or domain-specific data. |
| Result | Show strong performance in NLP tasks, including named entity recognition, part-of-speech tagging, dependency parsing, and text classification. The pre-trained models have strong language coverage and the toolkit's architecture is flexible and easily customizable. |
| Conclusion and Future work | Focus on improving performance, expanding language coverage, optimizing resource efficiency, and developing advanced models for specific tasks. The authors believe Stanza is a significant step forward in NLP research and toolkit development. |

### Set Up Environment
To install the Stanza library in your Python environment, you can run the following command:

pip install stanza

To set up the environment and download necessary models, use the following code:

 import stanza
 stanza.download("en")
 nlp = stanza.Pipeline("en")

This will download the English models and set up a pipeline to process text in English. You can replace "en" with any other supported language code to process text in a different language.

### Language Support
Afrikaans, Albanian, Arabic, Armenian, Bengali, Bosnian, Bulgarian, Burmese, Cantonese, Catalan, Croatian, Czech, Danish, Dutch, English, Esperanto, Estonian, Finnish, French, Galician, Georgian, German, Greek, Gujarati, Hebrew, Hindi, Hungarian, Icelandic, Indonesian, Irish, Italian, Japanese, Javanese, Kannada, Kazakh, Korean, Kurdish, Latvian, Lithuanian, Macedonian, Malay, Malayalam, Maltese, Maori, Marathi, Mongolian, Nepali, Norwegian, Persian, Polish, Portuguese, Punjabi, Romanian, Russian, Serbian, Sinhalese, Slovak, Slovenian, Spanish, Swedish, Tamil, Telugu, Thai, Turkish, Ukrainian, Urdu, Uzbek, Vietnamese, and Welsh