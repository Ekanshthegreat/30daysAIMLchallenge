![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/day1ibm.png)

watched an IBM lecture on AI ML 

![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/day1aws.png)

learnt what AGI is: 

Deep Learning: an AI discipline that focuses on training neural networks with multiple hidden layers to extract and understand complex relationships from raw data


Generative artificial intelligence: is a subset of deep learning wherein an AI system can produce unique and realistic content from learned knowledge
its trained with massive data sets.

Natural language processing (NLP): is a branch of AI that allows computer systems to understand and generate human language. language data into simple representations called tokens and understand their contextual relationship

Computer vision:  technology that allows systems to extract, analyze, and comprehend spatial information from visual data. Self-driving cars use computer vision models to analyze real-time feeds from cameras and navigate the vehicle safely away from obstacles. Deep learning technologies allow computer vision systems to automate large-scale object recognition, classification, monitoring, and other image-processing tasks.


![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/day1ibm2.png)

GPT: generative Pre Trained Transformed is LargeLanguageModel

Learnt some fun stuff about the history of LLM's
starting with ELIZA model...didnt have much progress until google released in 2017 a research paper on Transformers architecture which allowed GPT 1 to be built with high number of parameters


![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/llms.png)


How do LLM's work: Tokenization -> then vector embeddings -> then placed in vector databases (which are optimized for retrieval of vectors)
so now they can see which words are related to other words based on their embeddings. 
-> Transformations


data pre processing before feeding in and training. nvidia building hardware for these

RLHF - reinforcement learning human feedback

Finetuning - take raw models and then finetune for better usecases


![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/cloudflare.png)

Learnt how inference is the AI model in action.

![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/cloudflare2.png)
Learnt about the types of ML models, types of training parameters and how to use them: Amazon ML model

![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/domino.png)
![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/aws.png)

Also learned what all to keep in mind when training the model, and how splitting and shuffling is important



word embedding very important for nlp - for text classification - spam detection etc
transformers use contextual based embedding - better for NLP tasks
![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/day1ibm3.png)
Embedding is the process of creating vectors using deep learning. An "embedding" is the output of this process — in other words, the vector that is created by a deep learning model for the purpose of similarity searches by that model.

A vector database determines what other data (represented as vectors) is near your input query. This allows you to build different use-cases on top of a vector database, including:

Semantic search, used to return results similar to the input of the query.
Classification, used to return the grouping (or groupings) closest to the input query.
Recommendation engines, used to return content similar to the input based on different criteria (for example previous product sales, or user history).
Anomaly detection, used to identify whether specific data points are similar to existing data, or different.
![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/4.png)

Was supposed to continue reading this but got confused about how an RAG works and learnt that it queries a database or some knowledge source and utilizes that information parses it to an LLM and then gets the resposne. 
![Screenshot](https://github.com/Ekanshthegreat/30daysAIMLchallenge/raw/main/Screenshots/rag.png)


The step-by-step workflow resembles the below:

A developer converts their existing dataset (documentation, images, logs stored in R2) into a set of vector embeddings (a one-way representation) by passing them through a machine learning model that is trained for that data type.
The output embeddings are inserted into a Vectorize database index.
A search query, classification request or anomaly detection query is also passed through the same ML model, returning a vector embedding representation of the query.
Vectorize is queried with this embedding, and returns a set of the most similar vector embeddings to the provided query.
The returned embeddings are used to retrieve the original source objects from dedicated storage (for example, R2, KV, and D1) and returned back to the user.

also learnt why some metric distance types are better optimizaed for certain types eg words retrieval vs images


#############################################################################


Now the fun stuff - going to develop a custom AI agent - watching this - https://www.youtube.com/watch?v=MOyl58VF2ak

AI agent developer fine tune to use in production

AI automations cant handle edge cases
AI based agents automation - grant agent automonmy to handle edge cases - agent retreieves context only when it is needed



