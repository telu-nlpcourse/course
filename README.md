# course
# Preamble
This repository contains the lecture slides and course description for the Natural Language Processing course offered in 2017/2018 2nd term at the Telkom University. 

This is an introductory course on natural language processing. The NLP topic deals with the interaction between human and computer, and the ultimate goal is that computer could understand the command delivered in human natural language. The biggest challenge in processing natural language is ambiguity. Ambiguity found in each level of language complexity, from the lexical until pragmatic level. This course objective includes the student ability to design and evaluate a system that is based on lexical, syntactic, and semantic level of language processing, and to design - implement - evaluate an NLP based system for a real problem.

# References

- Jurafsky, David, and James H. Martin. Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics and Speech Recognition. Upper Saddle River, NJ: Prentice-Hall, 2000. ISBN: 0130950696..
  Second Edition: http://www.deepsky.com/~merovech/voynich/voynich_manchu_reference_materials/PDFs/jurafsky_martin.pdf
  
  Third Edition (draft): https://web.stanford.edu/~jurafsky/slp3/
- http://www.nltk.org/book/


This course is organised by Said Al Faraby and delivered by Ade Romadhony.

# Lecturer
* Ade Romadhony

# Timetable
## Lectures
Lectures are held in KU3.09.17 room on Tuesdays, 08:30-11:00. Each meeting will contains three sections:

1. Student presentation, 15-30', each student will be given chance to deliver a part of the topic of the week using their own style.
2. Course material presentation by lecturer, 30-45'.
3. Hands-on on paper-pencil based exercise or live programming.

# Lecture Materials
## 1. Lecture 1 - Introduction
This lecture introduces the course and motivates why it is interesting to study language processing.

[[slides]](course/01_Lecture_Intro.pdf)

### Weekly Assignments
Python and NLTK introduction.
[[description]](course/PythonIntroduction_NLP.pdf) Please do the exercise and answer the questions on no. 6 and 7!

## 2. Lecture 2 - Language Modeling
This lecture introduces the concept of Language Modeling (LM), the definition and the computation of LM probability component (unigram, bigram, likelihood), LM development process, and LM evaluation.

I used slide from Jurafsky and Manning NLP course, which can be found in https://web.stanford.edu/~jurafsky/NLPCourseraSlides.html

### Weekly Assignments
Building simple Language Model and the application: Poetry Generator.
[[description]](https://github.com/telu-nlpcourse/assignment/tree/master/01_language_modeling) 

## 3. Lecture 3 - POSTagging
This lecture introduces the POSTag of words and the method on assigning POSTag to words.

[[slides]](course/03_POSTagging.pdf)

### Reading Materials
[[Part-of-Speech-Tagging]](https://web.stanford.edu/~jurafsky/slp3/10.pdf) 

### Weekly Assignments
TODO

## 4. Lecture 4 - POSTagging & Hidden Markov Model (HMM)
This lecture introduces the HMM method for assigning POSTag to words in a sentence.

[[slides]](course/Lecture%203b%20HMM%20for%20PoS%20Tagging.pdf)

### Reading Materials
[[Hidden-Markov-Models]](https://web.stanford.edu/~jurafsky/slp3/9.pdf) 

[[POSTagging with HMM - Neubig's Tutorial]](http://www.phontron.com/slides/nlp-programming-en-04-hmm.pdf) 

[[POSTagging-Algorithm-inclduing-Viterbi]](http://www.inf.ed.ac.uk/teaching/courses/inf2a/slides/2012_inf2a_L16_slides.pdf) 

[[HMM Based POSTagger for Bahasa Indonesia]](https://www.researchgate.net/publication/209387036_HMM_Based_Part-of-Speech_Tagger_for_Bahasa_Indonesia) 

### Weekly Assignments
MyPOSTagger

## 5. Lecture 5 - Context Free Grammar, Syntactic Parsing

[[slides]](course/Lecture%204a%20CFG.pdf)

### Reading Materials
[[Syntactic Parsing]](https://web.stanford.edu/~jurafsky/slp3/12.pdf) 


## 6. Lecture 6 - Probabilistic CFG, CKY Algorithm

[[slides]](course/Lecture%204b%20PCFG-CYK.pdf)

### Reading Materials
[[Statistical Parsing]](https://web.stanford.edu/~jurafsky/slp3/13.pdf) 
[[CYK Parsing Algorithm]](https://courses.engr.illinois.edu/cs373/sp2009/lectures/lect_15.pdf) 

## 7. Lecture 7 - Parser Evaluation, Lexicalized PCFG, Dependency Parsing Introduction

[[slides]](course/07_Syntactic%20Parsing%20%E2%80%93%20Part%20III.pdf)

### Reading Materials
[[Dependency Parsing]](https://web.stanford.edu/~jurafsky/slp3/14.pdf) 

## 8. Lecture 8 - Semantic Similarity: Vector Semantic
### Reading Materials
[[Vector Semantic]](https://web.stanford.edu/~jurafsky/slp3/slides/vector1.pdf) 
[[Dense Vector]](https://web.stanford.edu/~jurafsky/slp3/slides/vector2.pdf) 

## 9. Lecture 9 - Word Sense Disambiguation
### Reading Materials
[[Intro and Similarity]](https://web.stanford.edu/~jurafsky/slp3/slides/Chapter18_introandsimilarity.pdf) 
[[Word Sense Disambiguation]](https://web.stanford.edu/~jurafsky/slp3/slides/Chapter18.wsd.pdf) 

## 10. Lecture 10 - Text Classification
### Reading Materials
[[Text Classification using Naive Bayes]](https://web.stanford.edu/~jurafsky/slp3/slides/7_NB.pdf) 

## 11. Lecture 11 - NLP Applications: Information Extraction, Question Answering System
### Reading Materials
[[Information Extraction]](https://web.stanford.edu/~jurafsky/slp3/21.pdf)
[[Question Answering System]](https://web.stanford.edu/~jurafsky/slp3/28.pdf) 


# Assessment & Scoring
The information of assesment and scoring is available on the Course Introduction slide.

# Acknowledgements
This course page is created using the template from Oxford Deep Learning for NLP course page https://github.com/oxford-cs-deepnlp-2017/lectures.
