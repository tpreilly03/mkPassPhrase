mkPassPhrase

mkPassPhrase provides a way to generate a pass phrase consisting of a number of words (as many as you can reliably remember) selected from a list of 32,768 words via a 5 digit index. The 5 digit index is constrained such that each digit must be in the range of 1 to 8 inclusive. This range restriction allows for using five eight-sided dice (5d8) as a way to generate a truly random selection from the word list.

Procedure:

	1. Obtain 5d8 dice at your local gaming store.
	2. Roll the five dice and arrange them in a line without looking.
	3. Use the five digits in order as input to the mkPassPhrase command:

		%> mkPassPhrase -d 53728
		dividend

	4. Repeat this for as many words as you think you can remember. Minimally
	   five words, but six or seven would be better. Ten words is doable. You
	   can think of it as two five word pass phrases.
	5. Optionally, include a space or different single characters from above
	   the numbers on your keyboard as separators between the words when
	   forming your pass phrase to make it even stronger.