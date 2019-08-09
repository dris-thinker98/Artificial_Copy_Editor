# Artificial_Copy_Editor

The task is to create the model (artificial copy editor), understand it in problem - solution basis:
Problem: 
1)  A model in which if i input a paragraph then it remove all the grammatical mistakes of the paragraph.

2) Furthermore user can further transform the paragraph into writing style of any author's of his choice. kind of author filters so if a third person will read it then it feels like the author wrote this paragraph. 

Creation:
Author filter: every author has its unique style of writing for example Kafka, Mark Twain etc so the author filter is the model can be trained by the writings of any famous author(user selects or use as input) then use this trained model to change any para or article written by the user. 

For example I like the writings of Shakespeare so I use his book/literary-pieces as input to train my model then now I can use this trained model to change my article or paragraph. 


#AI_Model
The first part of the AI model uses the approach of the concept of Natural Language Processing (NLP). Thus this AI model extensively uses the Python NLP libraries such as: SpaCy (excellent library for splitting into sentences, tokenizing sentence, generating POS tags and determiners), NLTK (helps in tokenizing, visualizing sentence structure tree, has huge collection of data corpus), language_check (great spelling-correction library with extensive support for simple grammar suggestions, punctuation errors), pattern (a CLiPS product which helps in conjugating verbs and thus helps form the correct structure of the verb based on the tense, person, number, mood) and sympound (another spelling correction algorithm-based library which also accepts dictionary).

The second part of this AI model is designed to take the corrected input text paragraph or sentence and convert it into the writing style of different famous authors. In order to do this the AI model utilizes the simple text-generator tool that taps into the writing style of various authors from their literary pieces and either generates their own text paragraph (non-existent in the original corpora) in the style of the concerned author or converts a given input text to the literary style.
