# Team-Project-26

## PROPOSAL 1

### Problem Statement:
This project seeks to detect Parkinson disease (PD) by analysis in proportion to the keystroke dynamics of the patient. It also aims to design a product by a people-centric design methodology.

### Abstract:
Accurate diagnosis is critical and remains founded on clinical grounds as no specific diagnostic test is available so far. This urges to bring the solution for detection of Parkinson's disease as early as possible with good accuracy and low cost. Thus, our project aims to detect parkinson's disease using keystroke dynamics. Information of keystroke dynamics is given to a trained model and it outputs whether the user suffers with parkinson’s disease or not with good accuracy. Model will be trained using machine learning concepts.

### Approach:
Database Selection and Schema design
Mongodb -> Flexible Design, Scalable, Used To handle Big data

### Interface And UI Design
Web Application

### Collecting Data From user
Using Python Library
Pynput
Records Hold time
Flight time
Latency
Form the Key strokes

### Data Analysis
Python Libraries for data processing (Pandas, Numpy, etc.)

### Persona:
End-User can be anyone testing laboratory, person,etc. Using this application it can be determined if a person has Parkinson disease or not.

### Dataset link:
https://www.kaggle.com/c/parkinsons-detection/data




## Proposal 2 

### Problem Statement:
Search Engine for optimal scanning of bulk scanning of documents and text data.
 
### Abstract:
 Since these days we are surrounded by a massive amount of unstructured data in form of text documents & news articles etc. and extracting information from it becomes a very hard task. And a lot of time is wasted in manually going through these docs to extract useful content. We intend to solve this problem using NLP, machine learning, flask web components and react UI.
We are trying to solve this problem by replicating the search engine mechanism. It will be a web app that would query the existing database of records of return the ones that are highly relevant as a response to the query. We will be using BBC new dataset as our source of truth on top of which we will perform clustering into the five given categories of the existing documents, namely: business, entertainment, politics, sport or tech. Any request will undergo a classification to identify the category of records to be returned and top K (say) records that are similar to the query semantics will be returned as a list, which could individually be viewed on the separate web page.
 
### Approach:
1. 	Initializing initial clusters on BBC news dataset using the k-Means clustering algorithm.
2. 	Query processing component
a. 	Processing the input query by performing stemming and lemmatization on the query
b. 	Vectoring the query using Words-To-Vec embedding.
c. 	Performing classification of the existing query & sampling a batch of records of that category to identify the top 10/15 records that have the highest similarity to the query to return as search response.
3. 	Web component: interacting with the system to query & view records easily.
a. 	Flask: web components for handling requests and responding with appropriate repose.
b. 	React: for query interface, rendering of contents of documents.

### Persona:
End-User: One who wishes to collect some relevant information can enter this query that most aptly describes the requirement as a natural language sentence, can get the most relevant set of records in a highly organized manner.
 
### Dataset link:
https://www.kaggle.com/c/learn-ai-bbc/overview


## Proposal 3

Disturb At My Condition 

### Problem Statement:
In this topic we propose a simple mobile application that acts as a notification manager. It has a filtering mechanism to show the user notifications which have certain keywords the user is actively waiting for and blocks the rest to reduce distraction.

### Abstract:
One study found that people receive, on average, 63.5 notifications per day. Whether you follow a notification or not, your train of thought will inevitably be interrupted by your noticing, processing, and determining whether or not to respond to the notification. Recent estimates find that while each task switch might waste only 1/10th of a second, it can add up to a 40% productivity loss if you do lots of switching in a day.

The design of the application will help to streamline all notifications via a single application and also give the power to the user to choose what he wants to get distracted by and still not miss out on important announcements.

### Approach:
1. Find different applications (Facebook, Whatsapp, Instagram, Gmail) that have given access to developers to access the Notifications API. Create and obtain access codes for  all such relevant sites and find a suitable protected way of storing them.
2. We aim to create a mobile application using React Native in which the user will be able to do a SSO on the application and will help us to access certain identifiers of the user on the particular application. The user will also be able to set certain keywords for example “test”, ”assignment”,”vacancies”,”internships”.
3.At every given interval the API calls will be made to obtain any new notifications and if the content of the notification has any of the keywords in it only then will a push-notification be generated to the user.
4.A NoSQL database can be maintained to store a certain number of the notifications.

### Persona:
Smart-phone users looking to minimize distractions via push notifications.

### Dataset:
Not Applicable



