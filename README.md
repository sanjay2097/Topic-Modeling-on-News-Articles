# Topic-Modeling-on-News-Articles

![image](https://user-images.githubusercontent.com/98027899/173231212-09a279e0-b101-48ab-9a6a-c3b54e6c91df.png)

### Objective :

### In this project, we used Latent Dirichlet Allocation, an unsupervised machine learning algorithm for a document of more than 2200 BBC News Articles. We were provided with a wide variety of topics ranging from law,government,sports,entertainment and technology so we built a LDA model capable of classifying these topics into groups. 
### LDA is a generative probability model, which means it attempts to provide a model for the distribution of outputs and inputs based on latent variables. This is opposed to discriminative models, which attempt to learn how inputs map to outputs.

![Schematic-of-LDA-algorithm](https://user-images.githubusercontent.com/98027899/172631337-af60f022-4229-4021-aa4f-a9a4e09758ba.png)


### You can use LDA for a variety of tasks, from clustering customers based on product purchases to automatic harmonic analysis in music. However, it is most commonly associated with topic modeling in text corpuses. Observations are referred to as documents. The feature set is referred to as vocabulary. A feature is referred to as a word. And the resulting categories are referred to as topics.

![image](https://user-images.githubusercontent.com/98027899/173231931-e370b963-d27d-40e1-a8f2-3a689729c6c4.png)

### Project Files:
* News Articles.zip : This file contains the dataset used for this project.It includes 2200 news articles grouped into categories.
* Topic Modeling on News Articles - This is a power point presentation file of a project. It includes various visualaized plots of EDA using Seaborn and Matplotlib. The result chart of various implemented algorithms.
* Topic Modeling on News Articles.ipynb - This file includes Features description, exploratory data Analysis, data preprocessing and implemented LDA.

![image](https://user-images.githubusercontent.com/98027899/173231931-e370b963-d27d-40e1-a8f2-3a689729c6c4.png)

### Project Details :

### Unprocessed Data
![Screenshot 2022-06-12 170913](https://user-images.githubusercontent.com/98027899/173231539-730ef6b8-04fb-43ef-a42b-e092f9bec53d.png)

### Processed Data
![Screenshot 2022-06-12 170900](https://user-images.githubusercontent.com/98027899/173231991-14166ee2-c6d1-4574-ad09-01e349b94460.png)

### Distribution of topics
![download](https://user-images.githubusercontent.com/98027899/173231572-00b4c18f-9464-4bdb-8678-d082d17ad86f.png)

### Average word count for each topic
![download (3)](https://user-images.githubusercontent.com/98027899/173231596-149c394c-38e4-49d5-b281-1344e8f80d92.png)

### Most frequent word distribution
![download (3)](https://user-images.githubusercontent.com/98027899/173231612-de9a4ecd-38a1-49bd-9741-6f9af4fab636.png)

### WordCloud of most frequent words
![download (2)](https://user-images.githubusercontent.com/98027899/173231626-29a4d368-897f-4507-a70b-9e9290cabdf9.png)

### Coherence score for number of topics
![download (4)](https://user-images.githubusercontent.com/98027899/173231663-36f332de-5939-4aef-8f93-9218b5ed8111.png)

![image](https://user-images.githubusercontent.com/98027899/173231939-896f5cc3-9e20-4caf-93ce-054f38c869fc.png)

### Model References :
* LDA: https://towardsdatascience.com/latent-dirichlet-allocation-lda-9d1cd064ffa2
* Topic Modeling: https://towardsdatascience.com/topic-modeling-and-latent-dirichlet-allocation-in-python-9bf156893c24

![image](https://user-images.githubusercontent.com/98027899/173231939-896f5cc3-9e20-4caf-93ce-054f38c869fc.png)

### Conclusion :

### We made improvement in classifying the topics.Initially we were provided with 5 major topics but using the LDA model we have further classified into major subtopics thus ensuring reliability in choosing a topic.We have clustered the given categories into 10 major sub-categories for which we have acieved coherence score of 60%.

![image](https://user-images.githubusercontent.com/98027899/173231943-189b13a0-97cc-4de1-a570-f911cb62a2ac.png)


### Scope :

### Topic modelling applications cover a range of use cases, here are a few real-world examples: Annotation , eDiscovery , Content recommendation , Search engine optimization , Word sense disambiguation etc.This project provides an approach to use topic modelling for classifying various documents which can further be used in supervised learning models to make recommendations for topics.Furthermore, we can use both kinds of information to build a NLP model in the future.

![image](https://user-images.githubusercontent.com/98027899/173231945-91a27802-7df3-41c1-b245-59e27c8ffd31.png)

### Credits :
* Sanjay Yadav | Data Scientist

![image](https://user-images.githubusercontent.com/98027899/173231939-896f5cc3-9e20-4caf-93ce-054f38c869fc.png)


### References :

https://cbail.github.io/SICSS_Topic_Modeling.html

https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf
