Analyzing Harry Potter movies dataset using Pyspark

In this project we use an existing Harry Potter movies dataset to gain some more insights about the movie franchise by performing EDA and validating the three hypothesis to understand the book to movie adaptation, character development and factors determining the revenue and budget.
Following are 3 hypothesis that we will try validate:

Hypothesis 1: Adaptation of book chapters into movies: With this data we explore which movies condense the most book chapters within 1 hour of runtime and which are the top 2 and bottom 2 most densed movie chapter. We also try to draw a correlation between the revenue and the number of chapters per 1 hour of runtime.

Hypothesis 2: Character arc and Character development: Besides the golden trio, Luna Lovegood and Neville Longbottom & Draco Malfoy are the 3 members that are beloved by many. In this section we explore the number of dialogues and the number of words these the characters have over the course of the series. For comparison, we also add in the same statistics for Ginny Weasley, another member and a prominent side character to see the contrast.

Hypothesis 3: Factors that determine the movies budget and their revenue. We try to analyze budget level based on:
*   The number of dialogues (less dialogue, more actions and actions are more costly to make)
*   The number of places appear for the first time( more places more set needs to be built, but if the set is reused from the previous movies, no additional budget needed)
*   The movie length (the longer it is, the more shots needed to be taken) We also add in the revenue for each movie to see if there is any correlation between the revenue and the above factors.

