Language generation models have emerged as a cornerstone of natural language processing (NLP), 
enabling machines to produce human-like text based on given inputs. These models are designed 
to learn patterns, structures, and semantics from textual data, empowering them to generate 
coherent and contextually relevant sentences. Applications of language generation models span a 
wide range, including chatbots, automated content creation, translation systems, and more. 
In this project, we focus on developing and training two distinct architectures for language 
generation: a custom Transformer-based model and a Recurrent Neural Network (RNN) model 
using a bidirectional Long Short-Term Memory (Bi-LSTM) network. Each architecture offers unique 
advantages in handling the complexities of language modeling. Transformers, with their attention 
mechanisms, excel at capturing long-range dependencies in text, while Bi-LSTMs leverage 
sequential processing to effectively learn contextual information from both past and future states. 
The dataset for this project was meticulously curated through web scraping from the Higher 
Education Commission (HEC) and Government of Pakistan websites. This diverse and domain
specific dataset provides a rich foundation for training models tailored to generate relevant and 
meaningful text. To further enhance the performance, we incorporated both custom vector 
embeddings derived from the dataset and pre-trained GloVe-200 embeddings, which offer a robust 
representation of words by encoding semantic and syntactic relationships. 
Evaluation of the trained models was performed using standard metrics, including accuracy and 
BLEU scores. These metrics provide insights into the models' ability to generate text that aligns 
closely with the input context and ground truth, ensuring the generated output is both syntactically 
correct and semantically relevant. 
This work not only demonstrates the potential of combining custom data with advanced 
architectures but also underscores the value of leveraging pre-trained embeddings in achieving 
superior performance in language generation tasks.

We have used the dataset which we scrapped in our assignment 1 and made embeddings of it in 
assignment 2. We used the website  
1. Higher education Commission (HEC) 
2. Govt of Pakistan 
We merged our data sets and made a CSV file of it. 
