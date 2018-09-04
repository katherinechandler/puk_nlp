# puk_nlp

Project Overview:

1) still working on my NLP clustering project

2) created a more robust list of stop words to make analysis cleaner
	- identified words used more than 10 X per episode (average) and added to stop words list

3) also made a secondary stop words list that included location names and nationalities
	- I noticed that lots of the topics identified just contained place names, so I wanted to see if I 
	could identify more general topics by removing place names and references to specific nationalities
	- I still get similar topics but the key words are interesting

4) did a cosine similarity followed by heat mat to identify locations most similar to a given location

5) k-means elbow test is not converging; I’ve read that this doesn’t necessarily mean there aren’t clusters, but perhaps K-means is not a good model for this data
	- discuss reasons why

5) considering doing network analysis rather than clustering to visualize relationships
	- any insight on this?