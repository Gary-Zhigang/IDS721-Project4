[![CircleCI](https://circleci.com/gh/noahgift/functional_intro_to_python.svg?style=svg&circle-token=d3ccec4d9ec6d4f1052ec528e22dc26554502cde)](https://circleci.com/gh/noahgift/awslambda)

# IDS721-Project4

This is the individual project4 for the course IDS721. In this project, I plan to use AWS Lambda to implement a basic serverless data engineering system that leverages an NLP technique called POS (Part-of-Speech) Tagging for its functionality.

## POS Tagging Introduction

POS (Part-of-Speech) Tagging is a process in NLP that involves marking each word in a text with its corresponding grammatical category, such as noun, verb, adjective, adverb, etc. This helps to identify the role each word plays in a sentence and provides a more structured representation of the text. POS tagging is typically performed using statistical models, such as HMMs or CRFs, that are trained on annotated corpora. The information obtained from POS tagging can be used for a variety of NLP tasks and can help to analyze the grammatical structure of a text and extract important information.

<img src="https://1.bp.blogspot.com/-spGNcdlw7g4/XHY5fS25uVI/AAAAAAAABqY/63lfyQFHkl4rf1ls0vvLIBRRc8TEsBZvgCLcBGAs/s1600/Capture.PNG" alt="Your image description" width="800" height="300">

## What I did so far

I finished the basic build and deploy of AWS lambda, and in the future I will implement the POSTagging feature and complete the whole project

***AWS Lambda***

<img src="https://github.com/Gary-Zhigang/IDS721-Project4/blob/main/images/p2.png" alt="Your image description" width="800" height="600">

***Test Result***

<img src="https://github.com/Gary-Zhigang/IDS721-Project4/blob/main/images/p2.png" alt="Your image description" width="800" height="300">

## Build and Deploy

1.  `sam init`
2.  `sam build`
3.  `sam deploy --guided`

