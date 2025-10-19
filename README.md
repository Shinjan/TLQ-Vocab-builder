Web-App that can be used to learn vocabulary.

How to play:

1. Go to this url: https://shinjan.github.io/TLQ-Vocab-builder/
2. To load an existing set of words you can download "tlq_sets.json" available in this repo and import it in the app in "All Sets" tab. You can create a similar one  and import that as well. This is only needed once till the cahce is cleared.
3. Start Learning and taking Quizes
 

About the files:

*index.html*: - Teach, Learn and Quiz is a web app for learning vocabulary. Which has following 3 modes:

* Teach Mode: You can add words into the app. It would be stored in localStorage and would be persistent only on a local brower till the cache is not cleared. Alternatively, a json file with word set can be loaded as well

* Learn Mode: Words stored in set(s) will be displayed as a flashcard with meaning and a sentence usage

* Quiz Mode: Student will be present with challenges like word completion, meaning matching etc. for them to test their learning skill at

*tlq_sets.json*: A Json format data file that can be imported into the app to load word set(s). Similarly words loaded in the set can be exported out. It's best to add the word into the set
