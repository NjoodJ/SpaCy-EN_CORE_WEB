# EN_CORE_WEB

![image](https://github.com/NjoodJ/SpaCy-s-trained-pipelines-EN_CORE_WEB-/assets/93571826/b52e6585-5f3f-4c6b-817c-9dd7454bc4af)

The en_core_web model is a pre-trained English language model provided by spaCy. It is designed to be a compact and efficient model while still delivering reasonably accurate results for common natural language processing (NLP) tasks. The model incorporates several linguistic features, including tokenization, part-of-speech tagging, dependency parsing, named entity recognition, and lemmatization. It also includes pre-trained word vectors that capture semantic relationships between words. While the en_core_web model may not offer the same level of comprehensiveness as larger models, it is suitable for a wide range of NLP applications in English and serves as a practical choice for basic linguistic analysis and entity recognition tasks.

## The model is divided into types:  

|  Type             |  Size             | 
|-------------------|-------------------|
|   en_core_web_sm  |   (Small) 12 MB   |
|   en_core_web_md  |   (Medium) 40 MB  |
|  en_core_web_lg   | (Large) 560 MB    |

## The code displays a task, such as:

|  Task                         |  Description                            | 
|-------------------------------|-----------------------------------------|
| Tokenization                  |   Segment text into tokens              |
|Named Entity Recognition       | Detect and label named entities    	    |
|Part-of-speech (POS) Tagging   | Assign part-of-speech tags              |
|Dependency Parsing             | Assign dependency labels                |
|Lemmatization                  |  Assign base forms                      |
|Sentiment segmentation         |Divide the opinions into specific aspects|


### 1-Tokenization
The input text is divided into individual tokens, which can be words, punctuation marks, or other meaningful units. This step ensures that the text is properly segmented for further analysis.
 ![image](https://github.com/NjoodJ/SpaCy-s-trained-pipelines-EN_CORE_WEB-/assets/93571826/b4079c26-aa6e-4ca8-8697-946cc89cd973)

 ### 2-Named Entity Recognition
Named Entity Recognition identifies and classifies named entities in text, such as names of persons, organizations, locations, dates, and more. It can be useful for information extraction, entity linking, and other applications.
![image](https://github.com/NjoodJ/SpaCy-s-trained-pipelines-EN_CORE_WEB-/assets/93571826/8e756c04-ced6-449a-af4b-296ffcc8da9b)


### 3-Part-of-speech (POS) Tagging
Each token is assigned a grammatical label or tag, such as noun, verb, adjective, etc. This step helps in understanding the role and function of each word in the sentence.
![image](https://github.com/NjoodJ/SpaCy-s-trained-pipelines-EN_CORE_WEB-/assets/93571826/0234ca0f-5699-4a49-8dc7-5fd86cb70512)

### 4-Dependency Parsing
The model analyzes the syntactic structure of the sentence and assigns dependency labels to each token. These labels describe the grammatical relationships between words, such as subject, object, modifier, etc., forming a dependency tree representation.
![image](https://github.com/NjoodJ/SpaCy-s-trained-pipelines-EN_CORE_WEB-/assets/93571826/110e3242-1ba1-4463-b6e1-da40b204e290)

### 5-Lemmatization
The model determines the base or dictionary form (lemma) of each word, considering different grammatical variations. This process helps in reducing words to their root form, facilitating tasks like word matching and analysis.
![image](https://github.com/NjoodJ/SpaCy-s-trained-pipelines-EN_CORE_WEB-/assets/93571826/cc666cc4-a976-41a7-b8e0-7066e84e6404)

### 6-Sentiment segmentation
The goal of sentiment segmentation is to understand the sentiment associated with various aspects or entities mentioned in a piece of text, such as product features, service attributes, or specific topics.
![image](https://github.com/NjoodJ/SpaCy-s-trained-pipelines-EN_CORE_WEB-/assets/93571826/157e58be-43c7-499d-a504-40595429e0f8)

## Conclusion:
Depending on your specific use case, you can leverage the model's pre-trained linguistic features to efficiently perform a wide range of NLP tasks, like Information Extraction, Text Classification, Chatbot Development, Text Analytics, Visualization, etc.

## Reference:
1.	https://spacy.io/usage/models
2.	https://spacy.io/models/en#en_core_web_sm
3.	https://blog.logrocket.com/guide-natural-language-processing-python-spacy/#spacy




