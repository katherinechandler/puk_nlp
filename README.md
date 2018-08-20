# puk_nlp
nlp analysis of anthony bourdain's parts unknown

look at parts_unknown_initial_exploration.ipynb for main analysis

Project Overview:

I’m doing an analysis of the transcripts of the TV show Parts Unknown. This is an unsupervised classification task, and I hope to perform some clustering to identify similar episodes and/or locations. The broad analyses I will do here are: 

1) do some preliminary exploration of the words used in each episode; maybe make a few figures from this

2) perform topic modeling; so far I have used NMF from the sklearn decomposition module
	
3) use k-means to identify natural groupings in the episode themes

4) use libraries of positive and negative words to assign a score to each episode. not hoping for anything amazing here, but might be an interesting exercise.


Progress:

1) I’ve completed the topic modeling portion and am getting ready to start parts 3 and 4 of the analysis

2) the topics generated were interesting. The data isn’t labeled well yet (sorry!!) but categories emerged for locations/episodes including the following:
	a) former USSR states 
	b) former colonies
	c) asian countries
	d) middle eastern countries
	e) conflict zones
	f) southern europe and economic crisis

3) I made a heat map of the topics by episode; I need to format this better to make some conclusions about it


Specific Questions:

1) didn’t get great results with LDA for topic modeling; got much better results with NMF; what are some reasons for this?

2) I got better results doing NMF using the sklearn countVectorizer + TFIDFtransformer than I did using the TFIDFvectorizer. Is this a valid approach?

3) what are some pit-falls of k-means? If I don’t get the same classes as my ’topics’, how do I explain this?

4) can you recommend any libraries of positive/negative associated words?
