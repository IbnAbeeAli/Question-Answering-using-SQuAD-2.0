# Question-Answering-using-SQuAD-2.0
#### "In this project, we try to implement the task of question answering using various transformers models"

## Question Answering Types:

### 1. Reading Comprehension:
#### In this type of question answering, the question plus, the context in which the answer of the question has to be in; is provided.


### 2. Open Domain:
#### In this type of question answering, the answer is not usually in the context:
#### In such type of scenarios, we have:
   ### Open Book:
 #### Model has access to an external source of data. Internet, Documents etc.

### Closed Book:
 #### All information must be encoded in the model parameters.


 # Our Focus: ODQA: Open Domain Question Answering
 ### Model Types:

 #### 1. Retreiver:
 ##### Provided the question, use that question to retreive a set of context from external data source.

 #### 2. Reader:
 ##### Takes the question, also gets context from external data source and takes a span of text from the context and gives the answer from the context

 #### 3. Generator:
 ##### Takes the place of our reader model. Take a question, generates the answer without needing external source. In some, we use an external source and then produce the answer    