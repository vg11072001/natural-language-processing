# Natural Language Processing 
[![image](https://github.com/vg11072001/natural-language-processing/assets/67424390/e1ca118e-a247-4139-b530-0ac15432188f)](https://mm.tt/map/2792478423?t=1mrN2j2FB1)

* github.com/graykode/nlp-tutorial
* github.com/TrainingByPackt/Deep-Learning-for-Natural-Language-Processing


### Resources 
* CS224n: Natural Language Processing with Deep Learning
  * https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ
  * https://youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z
  * Material - http://web.stanford.edu/class/cs224n/index.html#schedule 
  * https://aman.ai/cs224n/
  * [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/)
* Natural Language Processing Specialization on Coursera (offered by deeplearning.ai)
  * https://github.com/amanjeetsahu/Natural-Language-Processing-Specialization 
  * https://aman.ai/coursera-nlp/
  * https://github.com/vg11072001/coursera-natural-language-processing-specialization
* https://github.com/vg11072001/NLP-with-Python 
* Codes in NLP, Deep Learning, Reinforcement Learning and Artificial Intelligence: https://github.com/RubensZimbres/Repo-2017/
* [Awesome Deep Learning for Natural Language Processing (NLP)](https://github.com/brianspiering/awesome-dl4nlp#table-of-contents)
* https://www.deeplearning.ai/resources/natural-language-processing/
* https://course.fast.ai/Lessons/lesson4.html


![image](https://user-images.githubusercontent.com/67424390/209301541-3866b696-3aaf-498b-b0e9-304615dacfa0.png)

## Step 1
![image](https://user-images.githubusercontent.com/67424390/209412930-4dcf4114-bd4b-450f-90f3-246e2254fb17.png)

## Step 2
![image](https://user-images.githubusercontent.com/67424390/209435353-c6b766dd-bbea-430e-ae48-9266434c7117.png)

## PI
* https://www.kaggle.com/code/tanulsingh077/deep-learning-for-nlp-zero-to-transformers-bert 
* https://towardsdatascience.com/building-nlp-powered-applications-with-hugging-face-transformers-9f561effc84f & https://github.com/jackmleitch/EssayCompanion
* https://huggingface.co/welcome
* https://odsc.medium.com/12-most-popular-nlp-projects-of-2022-so-far-e11cd01e9a8
* Reasearch papers - https://machinelearningmastery.com/applications-of-deep-learning-for-natural-language-processing/

## Reading Materials

- [Link](https://substack.com/@kartiksinghal/note/c-70239045)
5 landmark papers in NLP that significantly moved the needle

These are 5 of my favorite papers that brought a step function change in natural language understanding. Anyone looking to learn NLP should read these, or at least some articles about them:

A unified architecture for natural language processing: deep neural networks with multitask learning (ronan.collobert.com/pub… ) : This paper was the first to show how a single neural network architecture could learn task-specific word embeddings and apply them to multiple NLP tasks, such as part-of-speech tagging, chunking, and named entity recognition. Before this, word embeddings existed mostly as a concept but weren’t widely used across multiple tasks.

Efficient Estimation of Word Representations in Vector Space (ronan.collobert.com/pub…) : This paper introduced Word2Vec model, which efficiently learns word embeddings by utilizing continuous bag-of-words (CBOW) and skip-gram architectures to capture semantic relationships between words. Word2Vec was the first major model to be scalable and widely used in industrial applications. It sparked a wave of X2Vec models (e.g., Doc2Vec, Tweet2Vec, Graph2vec), where various types of data were transformed into vector representations, further expanding the application of embedding techniques.

Attention is all you need (ronan.collobert.com/pub…) : Who could forget this paper? :)  It introduced the Transformer model, which eliminated the need for recurrence by relying entirely on self-attention mechanisms to model relationships between tokens in a sequence. This dramatically improved performance and efficiency in NLP tasks and laid the foundation for LLM models.

BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (ronan.collobert.com/pub…) : This introduced BERT, the first LLM model based on deep bidirectional Transformers, pre-trained on vast amounts of text and fine-tuned for various NLP tasks setting a new standard for transfer learning.

Language Models are Few-Shot Learners (ronan.collobert.com/pub…) : This paper introduced GPT-3, the largest language model (at the time) capable of performing tasks with minimal fine-tuning or task-specific data. It demonstrated the power of few-shot learning and essentially began the shift away from the need for task-specific trained models.

Of course, the list is much longer, and there are many other milestone papers in NLP. Which ones are your favorites? I'd love to hear your thoughts!
## Categories of NLP:

* **Text Preprocessing**: Cleaning, tokenization, stemming, lemmatization, stop word removal, spell checking, etc.
* **Text Representation**: Bag-of-words, TF-IDF, word embeddings (Word2Vec, GloVe), contextual embeddings (BERT, ELMO), etc.
* **Syntax and Grammar**: Parsing, part-of-speech tagging, syntactic analysis, dependency parsing, constituency parsing, etc.
* **Semantics**: Named entity recognition, semantic role labeling, word sense disambiguation, semantic similarity, etc.
* **Text Classification**: Sentiment analysis, topic modeling, document categorization, spam detection, intent recognition, etc.
* **Information Extraction**: Named entity extraction, relation extraction, event extraction, entity linking, etc.
* **Machine Translation**: Neural machine translation, statistical machine translation, alignment models, sequence-to-sequence models, etc.
* **Question Answering**: Document-based QA, knowledge-based QA, open-domain QA, reading comprehension, etc.
* **Text Generation**: Language modeling, text summarization, dialogue systems, chatbots, text completion, etc.
* **Text-to-Speech and Speech-to-Text**: Automatic speech recognition (ASR), text-to-speech synthesis (TTS), voice assistants, etc.
* **Text Mining and Analytics**: Topic extraction, sentiment analysis, trend detection, text clustering, opinion mining, etc.
* **NLP Evaluation Metrics**: Precision, recall, F1-score, accuracy, BLEU score, ROUGE score, perplexity, etc.

## NLP application involves several steps

* **Define the Problem**: Clearly define the objective of your NLP application. Determine the specific task you want to perform, such as sentiment analysis, text classification, or named entity recognition.

* **Data Collection:** Gather a dataset that is relevant to your problem. This dataset should be labeled or annotated with the target labels or annotations you want to predict.

* **Data Preprocessing**: Clean and preprocess the dataset to prepare it for model training. This step may include removing unnecessary characters or symbols, handling missing data, tokenizing text, removing stop words, and performing other text normalization techniques.

* **Data Exploration and Analysis:** Perform exploratory data analysis (EDA) to gain insights into the dataset. Visualize the data, analyze its statistical properties, and understand the distribution of different classes or labels.

* **Feature Engineering:** Extract relevant features from the text data to represent it in a format suitable for machine learning algorithms. This may involve techniques such as bag-of-words, TF-IDF, word embeddings, or contextual embeddings.

* **Model Selection:** Choose an appropriate machine learning or deep learning model for your task. Consider the nature of your problem, the size of your dataset, and the available computational resources. Common models used in NLP include logistic regression, support vector machines (SVM), recurrent neural networks (RNN), and transformer models.

* **Model Training:** Split your dataset into training and validation sets. Train your chosen model on the training set using appropriate algorithms and optimization techniques. Tune hyperparameters to improve model performance. Monitor the training process to avoid overfitting.

* **Model Evaluation:** Evaluate the trained model using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, or area under the ROC curve. Assess its performance on the validation set to understand its generalization capabilities.

* **Model Fine-tuning:** If the performance of the model is not satisfactory, consider refining the model architecture, adjusting hyperparameters, or applying techniques such as regularization to improve performance.

* **Model Testing:** Once you are satisfied with the model's performance, evaluate it on a separate, unseen test dataset to assess its real-world performance. Ensure that the test dataset is representative of the data your model will encounter in production.

* **Deployment:** Deploy the trained model into a production environment. This may involve integrating the model into an application or creating an API to serve predictions. Ensure the necessary infrastructure and resources are in place to support the deployment.

* **Monitoring and Maintenance:** Continuously monitor the performance of the deployed model and collect feedback from users. Regularly retrain or update the model as new data becomes available or the requirements change.
