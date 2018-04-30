# NeuralNetworks
Performance Analysis of a Neural Net using TensorFlow

The main purpose of this project is to present the analysis and performance of a Neural Network on a specified dataset, by segregating the input dataset into a fixed number of outputs.
The dataset that shall be put to use is the 20 newsgroups dataset, which comprises of approximately 20,000 newsgroup posts that fall under 20 topics. 

This data is split into two subsets, training data and testing data. The dataset is often used for the purpose of experiments of text analysis techniques making use of machine learning, clustering, and natural language processing. 
The file in question is a .csv file that contains a reference to the id of the document the news article has been fetched from and the newsgroup, or the title it is associated under. 
The dataset is free of duplicate messages. 

Each newsgroup has 4 headers: Newsgroup, Document, From and Subject.
Each newsgroup and document ID can be checked against the list present in the .csv file. 
The neural networks analysis includes testing different configurations of neurons in the inner layers of the network to check the learning capacity of the algorithm being used. 
For the purpose of this project, 40 neurons are being used in the inner layer, but depending on computational capacity and needs of the application, the number of neurons is scalable. 

Different configurations shall be used to see how the depth of the layer shall affect the learning ability and speed. 
Configurations being used are: (10, 4), (20, 2), (8, 5) and (5, 8). 
The representation is of the form (l, b) where b is the depth of the neural network. So, by theory as the depth of the network increases, the learning should get harder but if the algorithm is correctly tweaked results should improve as the number of layers increase. 

The task is to find an optimal configuration that would be an apt tradeoff for speed and accuracy of the algorithm performance.

There are three folders in this:

a) Output 20

b) Output 6

c) Output 3

As mentioned earlier, the task is to segregate those 20 topics into a fixed number of outputs based on categorisation of choice.

So, output 20 refers to the input being sorted into 20 outputs. It ocntains code for four configurations: 10 * 4, 20 * 2, 8 * 5 and 5 * 8
Likewise, output 6 refers to sorting into 6 categories and output 3 refers to sorting into 3 categories.
