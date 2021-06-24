# Grammer-Error-Correction

Grammatical errors are of the many differing types, including articles or determiners, prepositions, noun form, verb form, subject-verb agreement, pronouns, word choice, syntax, punctuation, capitalization, etc. Of all the error types, determiners and prepositions are among the foremost frequent errors made by learners of English.[1]. the main focus of this project is to correct errors in spellings, determiners, prepositions & action verbs using B.E.R.T as a language representation model. Bidirectional Encoder Representations from Transformers (B.E.R.T) is meant to pretrain deep bidirectional representations from unlabelled text by jointly conditioning on both left and right context altogether layers. As a result, the pre-trained B.E.R.T model are often finetuned with only one additional output layer to make state-of-the-art models for a good range of tasks, like question answering and language inference, without substantial task specific architecture modifications. 

Specifically, for task associated with GEC, we arrange to hump without the utilization of any annotated training, and just depend upon the language knowledge captured by the B.E.R.T Masked Language Model (MLM).

## Software requirements 
All the code is in the Google collab file.
No separate installation of library is required as the code handles it internally.
