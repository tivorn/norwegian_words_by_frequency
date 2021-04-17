#  Norwegian words by frequency

### About

Prioritization is an important task in vocabulary acquisition, therefore a word list by frequency empower language learners to narrow their focus
into these most common words.

To compose this document the Universal Dependencies Treebank was used, which consists of 14,791 unique words and 15,696 sentences. 

The lexical unit chosen was the lemma. Furthermore, the "words" were ranked according to their frequency of appearance. They were also classified into classes as following the equation below:

$$\lfloor 0.5 - log_2(\frac{Frequency \ of \ a \ given \ word}{Frequency \ of \ most \ common \ word}) \rfloor$$

### References

[Universal Dependencies](https://universaldependencies.org/)

[UniversalDependencies/UD_Norwegian-Bokmaal](https://github.com/UniversalDependencies/UD_Norwegian-Bokmaal/tree/master)

[Word lists by frequency - Wikipedia](https://en.wikipedia.org/wiki/Word_lists_by_frequency)