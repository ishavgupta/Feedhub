
# FeedHub

# 1. Methodology 

o I have implemented a friend recommendation system in python using collaborative filtering.
o There are basically two methods for recommending friends to a user based on their common
friends and influence of number of friends.
o To find the potential friends we will measure them using the ‘score’ metric where a higher score would
mean that user is a better candidate for being friend.
o We will then test the recommendation system accuracy by removing the friendship edges of all friends in
the Facebook data and then compute which method gives the most similar recommendations to that of the
original data.
* We would perform many trails of randomly chosen users from the data to compute accuracies.
© A subset map of friendship of the users will be displayed using edges and nodes in the form of graphs in
python.

![image](https://user-images.githubusercontent.com/55930740/208229738-0442dfdf-e8d8-4cf3-b056-57b3b0729737.png)



# 2. Description

![image](https://user-images.githubusercontent.com/55930740/208229853-ba6d7fea-0a7b-436b-bec0-a38947e5f443.png)

![image](https://user-images.githubusercontent.com/55930740/208230171-fcdb4f3a-8a43-440c-8f7d-62818c1713ff.png)


# 3. Input/Output



Created a graph named facebook from the Facebook data in file facebook-links.txt.

Print the number of nodes and the number of edges in your facebook graph. The output should be:

Facebook nodes: 63731
Facebook edges: 817090
The facebook-links.txt file is courtesy of the Max Planck Institute for Software Systems. Here is a slightly clarified version of the documentation for this file:

  File facebook-links.txt contains a list of all of the user-to-user links from the Facebook New Orleans networks. These links are undirected on Facebook.

  Format: Each line contains two numeric user identifiers, meaning the second user appeared in the first user's friend list, and the first user appeared in the second            user's friend list. Finally, the third column is a UNIX timestamp with the time of link establishment (if it could be determined, otherwise it is '\N').

A Unix timestamp is the number of seconds since January 1, 1970.


# 4. Live Link 

https://bit.ly/feedhub-demo-project


# 5. Screenshot of the interface

![image](https://user-images.githubusercontent.com/55930740/208229441-20fa2b7c-d622-4349-a7dc-0fb44d0fa31e.png)

![image](https://user-images.githubusercontent.com/55930740/208229449-46a660fa-00d9-41fa-b185-10fb52896f2f.png)

![image](https://user-images.githubusercontent.com/55930740/208229474-e13aff67-a9b2-454c-9f9e-df8e48a1d42d.png)

![image](https://user-images.githubusercontent.com/55930740/208229487-d85cb452-d8e7-4ff6-aacf-63ccefa1b9af.png)


