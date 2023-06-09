## An Introduction to Natural Language in Python using spaCy

Based on a tutorial at https://colab.research.google.com/github/DerwenAI/spaCy_tuTorial/blob/master/spaCy_tuTorial.ipynb#scrollTo=nEzq2vNoUJz5

In this assignment we will create data from natural language text. We'll use spaCy to identify people, organizations and places mentioned in the State Department cables that we used in an earlier assignment. Here are the steps:

1. Use a Colab notebook to download the cables from October 1973 and run Spacy to find the named mentions in the actual body of each message. To do this you will need to remove message headers and other formatted text that is also present in the msgtext field.
2. Then run coreferee to resolve nominal and pronominal references and create mention chains.
3. Then count the number of references to each unique entity two ways: (1) direct mentions of the named entity, and (2) any reference to a coreference chain that contains that entity.
4. Create an excel spreadsheet in which you provide two sorted lists showing the most commonly referenced entities, in decreasing order of mentions or references, as counted in step 3.

Upload your spreadsheet and a link to the Colab notebook that you used to assemble the raw data that you used to compute those statistics to ELMS.
