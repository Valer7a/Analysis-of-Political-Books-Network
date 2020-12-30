# Analysis-of-Political-Books-Network
In this project it has been faced the analysis of a network in which the nodes are books regarding US Politics, sold by the online bookseller "Amazon.com". In particular, it is an heterogenous net with three types of books: conservative, liberal and neutral. These alignments were assigned separately by Mark Newman based on a reading of the descriptions and reviews of the books posted on Amazon. Edges represent frequent co-purchasing of books by the same buyers, as indicated by the "customers who bought this book also bought these other books" feature on Amazon.

The aim of the project is to understand the clusters of the net and to reproduce the network itself, looking at the probability of two books being linked if they were of the same or different type. Moreover, we will compare other quantities describing the two nets as the _mean degree_, the _assortativity_ or _clustering coefficient_, trying to understand how much the constructed net is comparable to the real one. 

To reproduce the net, it has been used the Barabasi-Albert model with a little modification on the number of links that are given to a node when introduced into the net. This number is not always constant, but an integer random number in [2,7].

To obtain similar results, we see that we need a very high probability that a not neutral book is connected to another one of the same type, instead a very lower one is needed for books of the opposite type. Moreover, the connection is asymmetric in the probabilities. For example, the probability of a neutral node to be connected to the other types is set as 0.4, instead the probability of a liberal or conservative node to be connected to a neutral one is 0.009.

Slides summarize the processes and results.

The reported data "polbooks1.txt" can be found on: http://www.orgnet.com/, V. Krebs, unpublished.
