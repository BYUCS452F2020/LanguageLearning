# SeroLanguage

Language learning application 

E-Book type language learning application, inspired by Google e-book service.

The application will provide elevated level learning materials as an e-book with quizzes, vocab, and other study features.

- Front End

The android platform using Java. 

E-Book will be displayed as a Web Text(HTML) by using android webview. 

It will be 5 different levels and each chapter will have 30 chapters. (select level to access to chapters)

Each chapter has a chapter quiz.

The quiz will be designed based on 'spaced repetition(https://en.wikipedia.org/wiki/Spaced_repetition)' to maximize memorization for necessary vocab.

- Back End

post: Back end will decide which data will be stored in the database. Mostly quiz related data will be stored, because spaced repetition requires calculation based on data and frequency. 

get: check and calculate priority based on the response from the database and return.

- Database

NoSQL (have not decided which type will be proper yet, however, I think key-value type will be useful).

Store calculated quiz data as a key-value pair of Chapter and the list of the quiz.



