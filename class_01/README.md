# NLP: A Primer

## 🔖 NLP in the Real World

### Core applications:

         * Email platforms, such as Gmail, Outlook, etc., use NLP extensively to provide a range of product features, such as spam classification, priority inbox, calendar event extraction, auto-complete, etc.

         * Voice-based assistants, such as Apple Siri, Google Assistant, Microsoft Cortana, and Amazon Alexa rely on a range of NLP techniques to interact with the user, understand user commands, and respond accordingly.

         * Modern search engines, such as Google and Bing, which are the cornerstone of today’s internet, use NLP heavily for various subtasks, such as query understanding, query expansion, question answering, information retrieval, and ranking and grouping of the results, to name a few.

         * Machine translation services, such as Google Translate, Bing Microsoft Translator, and Amazon Translate are increasingly used in today’s world to solve a wide range of scenarios and business use cases. These services are direct applications of NLP.
     
### Other applications:![image](https://github.com/user-attachments/assets/b84702fa-9a18-4912-8998-a554ea27ad1f)


         * Organizations across verticals analyze their social media feeds to build a better and deeper understanding of the voice of their customers.

         * NLP is widely used to solve diverse sets of use cases on e-commerce platforms like Amazon. These vary from extracting relevant information from product descriptions to understanding user reviews. Chapter 9 covers these in detail.

         * Advances in NLP are being applied to solve use cases in domains such as healthcare, finance, and law. Chapter 10 addresses these.

         * Companies such as Arria [1] are working to use NLP techniques to automatically generate reports for various domains, from weather forecasting to financial services.

         * NLP forms the backbone of spelling- and grammar-correction tools, such as Grammarly and spell check in Microsoft Word and Google Docs.

         * Jeopardy! is a popular quiz show on TV. In the show, contestants are presented with clues in the form of answers, and the contestants must phrase their responses in the form of questions. IBM built the Watson AI to compete with the show’s top players. Watson won the first prize with a million dollars, more than the world champions. Watson AI was built using NLP techniques and is one of the examples of NLP bots winning a world competition.

         * NLP is used in a range of learning and assessment tools and technologies, such as automated scoring in exams like the Graduate Record Examination (GRE), plagiarism detection (e.g., Turnitin), intelligent tutoring systems, and language learning apps like Duolingo.

         * NLP is used to build large knowledge bases, such as the Google Knowledge Graph, which are useful in a range of applications like search and question answering.
           

### NLP Tasks:

         * Language modeling: This is the task of predicting what the next word in a sentence will be based on the history of previous words. The goal of this task is to learn the probability of a sequence of words appearing in a given language. Language modeling is useful for building solutions for a wide variety of problems, such as speech recognition, optical character recognition, handwriting recognition, machine translation, and spelling correction.

         * Text classification: This is the task of bucketing the text into a known set of categories based on its content. Text classification is by far the most popular task in NLP and is used in a variety of tools, from email spam identification to sentiment analysis.
  
         * Information extraction: As the name indicates, this is the task of extracting relevant information from text, such as calendar events from emails or the names of people mentioned in a social media post.
  
         * Information retrieval: This is the task of finding documents relevant to a user query from a large collection. Applications like Google Search are well-known use cases of information retrieval.
  
         * Conversational agent: This is the task of building dialogue systems that can converse in human languages. Alexa, Siri, etc., are some common applications of this task.
  
         * Text summarization: This task aims to create short summaries of longer documents while retaining the core content and preserving the overall meaning of the text.
         * Question answering: This is the task of building a system that can automatically answer questions posed in natural language.
  
         * Machine translation: This is the task of converting a piece of text from one language to another. Tools like Google Translate are common applications of this task.
  
         * Topic modeling: This is the task of uncovering the topical structure of a large collection of documents. Topic modeling is a common text-mining tool and is used in a wide range of domains, from literature to bioinformatics.
  
 
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-2.png)

### Approaches to NLP
  * Machine Learning for NLP
  * Deep Learning for NLP

### Machine Learning for NLP
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-8.png)

![image](https://github.com/user-attachments/assets/b24886ae-c581-4dfd-a5a5-c579b8f6dc6b)
![image](https://github.com/user-attachments/assets/9de79b1c-21c1-4183-bb85-754bd126ed2f)
![image](https://github.com/user-attachments/assets/50db3193-3b18-4d56-9d08-79f7798debec)

Machine learning techniques are applied to textual data just as they’re used on other forms of data, such as images, speech, and structured data. Supervised machine learning techniques such as classification and regression methods are heavily used for various NLP tasks. As an example, 

         * an NLP classification task would be to classify news articles into a set of news topics like sports or politics.
         
         * regression techniques, which give a numeric prediction, can be used to estimate the price of a stock based on processing the social media discussion about that stock. 
         * unsupervised clustering algorithms can be used to club together text documents.

![image](https://github.com/user-attachments/assets/40b01c75-9f28-45ab-995c-68a79c12b121)
![image](https://github.com/user-attachments/assets/0482cbc1-9558-42d9-986d-b7e99ce8fa15)


#### 1. Naive Bayes
Naive Bayes is a classic algorithm for classification tasks [16] that mainly relies on Bayes’ theorem (as is evident from the name). Using Bayes’ theorem, it          calculates the probability of observing a class label given the set of features for the input data. 

#### 2. Support vector machine
The support vector machine (SVM) is another popular classification [17] algorithm. The goal in any classification approach is to learn a decision boundary that acts as a separation between different categories of text (e.g., politics versus sports in our news classification example). This decision boundary can be linear or nonlinear (e.g., a circle). An SVM can learn both a linear and nonlinear decision boundary to separate data points belonging to different classes. 
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-11.png)

#### 3. Hidden Markov Model
The hidden Markov model (HMM) is a statistical model [18] that assumes there is an underlying, unobservable process with hidden states that generates the data—i.e., we can only observe the data once it is generated. An HMM then tries to model the hidden states from this data. 
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-12.png)

#### 4. Conditional random fields
The conditional random field (CRF) is another algorithm that is used for sequential data. Conceptually, a CRF essentially performs a classification task on each element in the sequence.

### Deep Learning for NLP

#### The Perceptron
In 1957, the first implementation of a biologically inspired machine learning component was realized: Rosenblatt’s perceptron. This device, implemented on physical hardware, allowed the processing of visual stimuli represented by a square 400 (20 by 20) array of photosensitive cells. The weights of this network were set by electromotors driving potentiometers. The learning part of this perceptron was based on a simple one-layer neural network, which effectively became the archetype of neural networks
![image](https://github.com/user-attachments/assets/2ecfe2ae-33c0-46cc-975e-31efd3efc402)
![image](https://github.com/user-attachments/assets/db7cb006-8f4e-4c47-a1af-52a31a7281b1)



#### 1. Recurrent neural networks
A sentence in any language flows from one direction to another (e.g., English reads from left to right). Thus, a model that can progressively read an input text from one end to another can be very useful for language understanding. Recurrent neural networks (RNNs) are specially designed to keep such sequential processing and learning in mind. RNNs have neural units that are capable of remembering what they have processed so far. This memory is temporal, and the information is stored and updated with every time step as the RNN reads the next word in the input.
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-13.png)

#### 2. Long short-term memory
Despite their capability and versatility, RNNs suffer from the problem of forgetful memory—they cannot remember longer contexts and therefore do not perform well when the input text is long, which is typically the case with text inputs. Long short-term memory networks (LSTMs), a type of RNN, were invented to mitigate this shortcoming of the RNNs. LSTMs circumvent this problem by letting go of the irrelevant context and only remembering the part of the context that is needed to solve the task at hand. This relieves the load of remembering very long context in one vector representation. LSTMs have replaced RNNs in most applications because of this workaround.
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-14.png)

#### 3. Convolutional neural networks
Convolutional neural networks (CNNs) are very popular and used heavily in computer vision tasks like image classification, video recognition, etc. CNNs have also seen success in NLP, especially in text-classification tasks. One can replace each word in a sentence with its corresponding word vector, and all vectors are of the same size (d) (refer to “Word Embeddings” in Chapter 3). Thus, they can be stacked one over another to form a matrix or 2D array of dimension n ✕ d, where n is the number of words in the sentence and d is the size of the word vectors. This matrix can now be treated similar to an image and can be modeled by a CNN. The main advantage CNNs have is their ability to look at a group of words together using a context window. For example, we are doing sentiment classification, and we get a sentence like, “I like this movie very much!” In order to make sense of this sentence, it is better to look at words and different sets of contiguous words. CNNs can do exactly this by definition of their architecture. 
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-15.png)

#### 4. Transformers
Transformers [28] are the latest entry in the league of deep learning models for NLP. Transformer models have achieved state of the art in almost all major NLP tasks in the past two years. They model the textual context but not in a sequential manner. Given a word in the input, it prefers to look at all the words around it (known as self-attention) and represent each word with respect to its context. For example, the word “bank” can have different meanings depending on the context in which it appears. If the context talks about finance, then “bank” probably denotes a financial institution. On the other hand, if the context mentions a river, then it probably indicates a bank of the river. Transformers can model such context and hence have been used heavily in NLP tasks due to this higher representation capacity as compared to other deep networks.
![figure](https://github.com/practical-nlp/practical-nlp-figures/raw/master/figures/1-16.png)

## 🔖 NLP Python Libraries

         * PyTorch
         
         * Gensim
         
         * Spacy
         
         * NLTK

## 🔖 Models Evaluation

Consider an anti-spam model that predicts whether a received email is spam or not and automatically sends spam emails to a junk folder. One simple measure of evaluating performance is accuracy:
![image](https://github.com/user-attachments/assets/92e27b2a-9bb6-43c4-9116-e48728bf10c8)
![image](https://github.com/user-attachments/assets/61ba3478-89e8-4a6b-8e0e-4471f08eaf29)


