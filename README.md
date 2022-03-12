# Sentiment-Analysis
Sentiment Analysis with TensorFlow

# First Training Values And Results 

I trained my model using TensorFlow with Python language. I have 25,000 comments for training and 25,000 comments for testing from a dataset compiled from the comments from the movies on Imdb.
![image](https://user-images.githubusercontent.com/78434833/158013904-f211e8ca-9cdb-41ee-a1c0-a6920af58ae9.png)

The validation split value I set is 0.2 .
![image](https://user-images.githubusercontent.com/78434833/158013917-46f81ace-3ef8-4b06-aead-9f06dd3adeeb.png)

Python libraries I use for training: 

•	tensorflow 

•	os

•	shutil

•	numpy 

•	re

•	string

•	TextVectorization

•	matplotlib.pyplot

At the end of the training, it was seen that our model was 87% successful in sentiment analysis.
![image](https://user-images.githubusercontent.com/78434833/158013930-56e02443-ecd1-42e7-b17e-32f74d05269b.png)

Parameters:

batch_size:	32

seed:	42

validation_split:	0.2

max_features:	10000

sequence_length:	250

embedding_dim:	16

Dropout:	0.2

Dense:	1

Epochs:	10

I trained my model using the above parameters. The graphs of the results I got are as follows:
![image](https://user-images.githubusercontent.com/78434833/158013944-b6e52b5c-5cc3-46a2-8297-2e581c0124cd.png)
![image](https://user-images.githubusercontent.com/78434833/158013952-138dfabf-22d6-427f-a077-4919af50b24d.png)

By looking at these graphs, the training of our model goes towards memorizing the data the longer it gets.  Therefore, I decided to retrain my model by changing the parameters. By looking at the graph, we can say that the graph starts to change after the 6th Epochs value. That's why I realized that I should pay attention to these values. 


# Second Training Values And Results 

I trained my model using TensorFlow with Python language. I have 25,000 comments for training and 25,000 comments for testing from a dataset compiled from the comments from the movies on Imdb. 

![image](https://user-images.githubusercontent.com/78434833/158013987-9b812171-c716-4f01-bbe1-6db89a421000.png)

The validation split value I set is 0.2 .

![image](https://user-images.githubusercontent.com/78434833/158013994-228badc6-a2a0-48a4-983a-3c71b880c694.png)

Python libraries I use for training:

•	tensorflow 

•	os

•	shutil

•	numpy 

•	re

•	string

•	TextVectorization

•	matplotlib.pyplot

•	keras

•	drive

At the end of the training, it was seen that our model was 86% successful in sentiment analysis.
![image](https://user-images.githubusercontent.com/78434833/158014024-da80b8df-b7be-4d8f-b7af-59b74d0b2fcb.png)

Model summary:
![image](https://user-images.githubusercontent.com/78434833/158014032-47b75254-ba31-4af1-901b-578dfe30e274.png)

Parameters:

batch_size:	32

seed:	42

validation_split:	0.2

max_features:	10000

sequence_length:	250

embedding_dim.	16

Dropout:	0.2

Dense:	1

Epochs:	6

I trained my model using the above parameters. The graphs of the results I got are as follows:
![image](https://user-images.githubusercontent.com/78434833/158014046-b0e96dd1-6c1a-463b-81c8-46c670046782.png)

![image](https://user-images.githubusercontent.com/78434833/158014049-0289c402-c59e-48ad-9d68-162c4005de53.png)

As a result of the second training, I realized that it was the right decision to change the Epochs value. The success value of our model was 87% while it was 86%. But this value is small enough to be ignored. It is also important for us that the training phase also yields healthier results. 






