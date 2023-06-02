| Model                   | Use Cases                                                   | Documentation                                              | Python Code                                                  |

|-------------------------|-------------------------------------------------------------|------------------------------------------------------------|--------------------------------------------------------------|

| Bag-of-Words (BoW)      | Text classification, sentiment analysis, basic feature extraction         | [Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html)         | `from sklearn.feature_extraction.text import CountVectorizer`\n`vectorizer = CountVectorizer()`\n`X = vectorizer.fit_transform(corpus)` |

| TF-IDF                  | Information retrieval, document similarity, text classification             | [Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)             | `from sklearn.feature_extraction.text import TfidfVectorizer`\n`vectorizer = TfidfVectorizer()`\n`X = vectorizer.fit_transform(corpus)` |

| Word2Vec                | Word embeddings, word similarity, document clustering                     | [Documentation](https://radimrehurek.com/gensim/models/word2vec.html)                    | `from gensim.models import Word2Vec`\n`model = Word2Vec(sentences, size=100, window=5, min_count=1, workers=4)` |

| GloVe                   | Word embeddings, document classification, sentiment analysis, word analogy   | [Documentation](https://nlp.stanford.edu/projects/glove/)   | - |

| FastText                | Text classification, language identification, entity recognition              | [Documentation](https://fasttext.cc/docs/en/unsupervised-tutorial.html)               | - |

| LSTM (Long Short-Term Memory)       | Sequence labeling, sentiment analysis, named entity recognition     | [Documentation](https://pytorch.org/docs/stable/generated/torch.nn.LSTM.html)     | - |

| GRU (Gated Recurrent Unit)         | Sequence modeling, language modeling, speech recognition         | [Documentation](https://pytorch.org/docs/stable/generated/torch.nn.GRU.html)         | - |

| Transformer             | Machine translation, language modeling, question answering         | [Documentation](https://pytorch.org/docs/stable/generated/torch.nn.Transformer.html)         | - |

| BERT (Bidirectional Encoder Representations from Transformers)       | Text classification, named entity recognition, question answering     | [Documentation](https://huggingface.co/transformers/model_doc/bert.html)     | - |

| GPT (Generative Pre-trained Transformer)          | Text generation, story completion, language translation      | [Documentation](https://huggingface.co/transformers/model_doc/gpt.html)      | - |

| RoBERTa                  | Text classification, named entity recognition, sentiment analysis      | [Documentation](https://huggingface.co/transformers/model_doc/roberta.html)      | - |

| XLNet                    | Sequence classification, question answering, natural language inference  | [Documentation](https://huggingface.co/transformers/model_doc/xlnet.html)  | - |

| ALBERT                   | Text classification, named entity recognition, sentiment analysis  | [Documentation](https://huggingface.co/transformers/model_doc/albert.html)  | - |

| T5 (Text-To-Text Transfer Transformer)         | Text summarization, question answering, language translation     | [Documentation](https://huggingface.co/transformers/model_doc/t5.html)     | - |

| SBERT (Sentence-BERT)    | Semantic search, sentence similarity, text clustering          | [Documentation](https://www.sbert.net/docs/)          | - |

| XLM (Cross-lingual Language Model)       | Cross-lingual document classification, machine translation        | [Documentation](https://huggingface.co/transformers/model_doc/xlm.html)        | - |

| ELMO (Embeddings from Language Models)       | Contextual word embeddings, sentiment analysis, text classification     | [Documentation](https://www.tensorflow.org/api_docs/python/tf/keras/layers/ELMoEmbedding)     | - |

| Flair                   | Named entity recognition, part-of-speech tagging, text classification    | [Documentation](https://flair.ai/docs/)    | - |

| ULMFiT (Universal Language Model Fine-tuning)      | Transfer learning, text classification, sentiment analysis     | [Documentation](https://docs.fast.ai/text.html)     | - |

| BioBERT                 | Biomedical text mining, named entity recognition, relation extraction   | [Documentation](https://github.com/dmis-lab/biobert)   | - |

| ELECTRA                 | Text classification, sentiment analysis, natural language understanding   | [Documentation](https://github.com/google-research/electra)   | - |

| DistilBERT              | Text classification, named entity recognition, question answering    | [Documentation](https://huggingface.co/transformers/model_doc/distilbert.html)    | - |


