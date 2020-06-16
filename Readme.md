# Vocab with corpus probablity
	# This uses two most important things:-
1 The probability of  word occuring in the corpus(After removing the stopwords and other things)\n
2 The model which takes the probability from the new testing Set\n
	<h2> Now for each testing text file</h2>
1 Remove stop words and then\n
2 Finds the word into the corpus and assign probablitiy
3 Then if not found from the document what is the probability of that word in doc
4 Assigning them that probability\n
5 As each important word occurs less than in  a word in spam  mail\n
6 so Probability of each spam word is more\n
7 Hence ham word is less\n
# Note Laplace smoothing is also done
