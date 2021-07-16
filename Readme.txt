Name: Ali Iftakhar 
 
Perplexity of Unigram: Infinity 
Perplexity of Bigram: Infinity 
Perplexity of Smoothened Bigram: inf
ANSWER TO QUESTION 1 
I think the worst performance by far, came from the Unigram model. Since there is no dependency of the word to the prior word, we cannot hope to achieve a good prediction. It is unfortunate though that I wasn't aware to get number values for perplexity 
 
ANSWER TO QUESTION 2 
I think smoothing definitely helped with the overall performance. For unigram and bigram when we had a 0 probability sentence, it ruined the entire perplexity calculation. Sadly, my probabilities even with smoothing were so low that I wasn't able to get a finite number answer for Smoothened Bigram as well. I'm not sure what I did wrong.