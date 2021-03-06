# Data Science and Text Mining for Historians with Python
By Kaspar Beelen and Luke Blaxill

⚠️ **Warning** ⚠️  Still Under construction

These lectures are part of the Text Mining and Statistics course for Historians. For an overview of the full course content go [here](https://lukeblaxill.wixsite.com/website-1).

Run all on Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main)

## Unit 0: Intro and Setup

**Lecture 0: [How to access Notebooks on Binder](introduction.md)**

# Course 1: Text Mining in Python

## Unit 5: Python, the Basics

**Lecture A: [Introduction to the  course](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=1_-_Introduction.ipynb)**

We start with a brief introduction to the aims and principles of this course: why should a historian bother to learn a programming language for analysing textual and other types of data? Why Python (notebooks) in particular? We also discuss what to expect from this course (and what not?) and give an overview of the skills you will obtain. 


**Lecture B: [Basic Python, a gentle introduction](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=2_-_Values_and_Variables.ipynb)**

This notebook starts with a gentle introduction to the basic elements of the Python syntax. We discuss how to create and manipulate variables, and demonstrate common operations. Some topics are more extensively discussed in 'break out' notebooks or in external documentation.

**Lecture C: [Text and String Methods](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=3_-_Text_and_String_Methods.ipynb)**

Finally, we move on from more fundamental syntax to working with actual text data. In this notebook, we introduce 'string methods', which are Python tools for processing and manipulating text files. We also demonstrate how to open and read text files (at scale).

## Unit 6: Text Processing and Corpus Exploration

**Lecture A: [Processing Texts](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=4_-_Processing_texts.ipynb)**

This lesson introduces core Python objects such as lists and dictionaries that you will need when processing text files. We discuss the application of Natural Language Processing tools to historical documents. More precisely, we show how to use the NLTK and SpaCy to splitting a text into tokens and analyse the grammatical structure of a sentence with part-of-speech tagging.

**Lecture B: [Corpus Selection](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=5_-_Corpus_Selection.ipynb)**

In this notebook, we introduce techniques for selecting relevant information from large data sets. We discuss how to filter and select information based on their metadata as well as textual content. The strategies covered here allow you to select documents that are relevant to your research question and build question-specific subcorpora,

**Lecture C: [Corpus Exploration](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=6_-_Corpus_Exploration.ipynb)**

After building a subcorpus, you need tools to explore and analyse the texts meaningfully. We focus on a wide range of tools provided by the Natural Language Toolkit, such as concordance or Keyword in Context (KWIC), collocation analysis and feature selection. We use reports written by Victorian Medical Officers of Health as a case study.

**Lecture D: [Trends over Time](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=7_-_Trends_over_time.ipynb)**

The last notebook in the text mining series focuses on studying discursive trends over time. The goal of this notebook is to understand the changing content of British political manifestos.

# Course 2: Statistics in Python

## Unit 5: Explorative Data Analysis

**Lecture A: [Exploring DataFrames with Pandas (Part I)](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=8_-_Data_Exploration_with_Pandas_I.ipynb)**

This notebook introduces the Pandas library and explores tools for working programmatically with tabular data in. We have a closer look at realistic and complex metadata derived from the British Library catalogue and demonstrate how you can refine and reorganise information with the goals of studying trends over time.

**Lecture B: [Exploring DataFrames with Pandas (Part II)](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=9_-_Data_Exploration_with_Pandas_Part_II.ipynb)**

This notebook uses  "synthetic" demographic data about age and gender in late Victorian London. We discuss different types of variables and strategies for visualising distributions. We proceed with summarising information using descriptive statistics, such as mean and median. From a historical point of view, we investigate whether men are generally younger than women in late-Victorian London.

## Unit 6: Hypothesis Testing

**Lecture A: [Distributions and Hypothesis Testing](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=10_-_Hypothesis_Testing.ipynb)**

In this section, we move from descriptive to inferential statistics. We assess the statistical 'significance' of the gendered differences observed in the previous notebook (on descriptive statistics). We pursue a data-driven and intuitive approach to significance testing. First, We "bootstrap" confidence intervals and then explore permutation for hypothesis testing.

## Unit 7: Regression

**Lecture A: [Correlation and Linear Regression](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=11_-_Linear_Regression.ipynb)**

This session has a closer look at modelling the relation between different variables. The first notebook (click here) discusses how to compute and interpret correlation coefficients and then continue with a gentle introduction to linear regression. The goal is to understand variation in lifespans in late-Victorian London. We try to understand if residents in more affluent boroughs tend to live longer?

**Lecture B: [⚠️Generalised Linear Models ⚠️](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/main?labpath=12_-_Generalised_Linear_Models.ipynb)**

The second notebook on linear regression turns to more advanced techniques: Generalised Linear Models (GLMs). We use GLMs to model and predict count outcomes. We explore two case studies in detail: a) gender bias in university applications and b) gender and participation in the British House of Commons.

## Unit 8: Machine Learning (⚠️ Under construction ⚠️) 

Lecture A: [Supervised Classification](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/4-tables?labpath=13_-_Supervised_Learning.ipynb)

Lecture B: [Topic Modelling](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/4-tables?labpath=14_-_Topic_Modelling.ipynb)

Lecture C: [Word Vectors](https://mybinder.org/v2/gh/kasparvonbeelen/ghi_python/4-tables?labpath=15_-_Word_Vectors.ipynb)








