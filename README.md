# Text_Summarization - Extractive_Method

## Steps implemented :
* Construct a text corpus. 
* The text corpus is passed through the sentence tokenizer. List of sentences in the paragraph is formed.
* Ordered indexing of the sentences is performed, where the key is the sentence and the value is the order at which it occurs in the paragraph.
* The list of sentences after tokenizing is passed through the TF-IDF vectorizer.
* The sentences are scored . This is done by adding all the weights of the words in that particular sentence.
* Sentence re-organizing is done, where the sentences with high score are considered, re-arranged in the order they occur, and words are picked up in order , to get the summary.
* Finally the summary is printed.
