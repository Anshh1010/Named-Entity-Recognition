# Named-Entity-Recognition


Named Entity means anything that is a real-world object such as a person, a place, any organisation, any product which has a name.   
For example – “My name is Anshh, and I am a Machine Learning Student”. In this sentence the name “Anshh”, the field or subject “Machine Learning” and the profession “Student” are named entities.

In Machine Learning Named Entity Recognition (NER) is a task of Natural Language Processing to identify the named entities in a certain piece of text.  

The dataset contains 45279 sentences, each having the description of each word in the sentence, describing whether it's a verb, noun etc.    

<img width="429" alt="Screenshot 2023-01-06 at 9 00 10 PM" src="https://user-images.githubusercontent.com/72307339/211043755-858e934d-84fe-427a-a856-827703be88af.png">. 

##  Libraries used  
Pandas   
Numpy    
Sklearn    
Tensorflow     
Keras  
Spacy   

##  Process
We're training a Neural Network for this task, so we have to make some modifications to the data so that it fits into the network.  
We've applied One Hot Encoding to this data and used padding. The network has 4 main layers, that are:  
Embedding Layer   
Bidirectional LSTM   
LSTM       
Time Distributed Layer  

<img width="585" alt="Screenshot 2023-01-06 at 9 41 17 PM" src="https://user-images.githubusercontent.com/72307339/211051692-e9e05b0a-c218-45a0-95f4-2d0e7724e8a2.png">   
This is how the working model looks      

<img width="1092" alt="Screenshot 2023-01-06 at 9 43 24 PM" src="https://user-images.githubusercontent.com/72307339/211052091-1e727c05-b8cb-42a7-892f-48c60dc177db.png">  

Thank you!

