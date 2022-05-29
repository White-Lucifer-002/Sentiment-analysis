+ This model predicts the sentiment of whether it is,
	- Positive
	- Negative
	
	based on the text/comments/tweets given as input.


+ LSTM used for implementation of the sentiment analysis.


+ When giving a new input it needs to be cleaned and lemmatized like in the script[cells: 13 and 16] to predict the nature of the comment 
  like good/bad or positive/negative.


+ The new input can be supplied to the model like say,
	- input = "Hi I #ram don't like this type of scenery at @redhills https://fhdte.guc.vu #comment"
	- clean it[ of urls and special characters using regular expression ]
		 - "Hi I ram don't like this type of scenery at redhills"
	- lemmatize = "Hi I ram dont like type scenery redhills"
	- model => input => output = negative



