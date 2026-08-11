# Card Shuffling and Markov Chains

<img width="1361" height="762" alt="image" src="https://github.com/user-attachments/assets/b31509ba-df1b-40a9-9e42-00136b1735f6" />


This repository contains a mathematical modeling project focusing on the efficiency of different card shuffling techniques. The project was implemented in **Python** and take part of the module **Introduction to research** during my Double Degree in Mathematics and Economics at University Paris-Saclay

We had an oral of one hour with a jury, including a presentation of the results and a precise question-and-answer session. We based our project on the researches of Persi Diaconis

This project was made with Astrid CARBELO and Selima KLIBI, our goal was to work on Markov Chains and further our knowledges in Probability to an usual situation as playing cards. 

## Project Overview

The main goal of this analysis is to determine the precise number of shuffles required to achieve a perfectly "random" deck of cards. The project models card shuffling as a sequence of permutations using **Markov Chains**


[📖 Click here to read the full report in french (PDF)](https://github.com/mehdi-belhamiti/Card-Shuffling-Markov-Chains/blob/main/Projet%20Battage%20de%20Cartes%20-%20Maths.pdf)

### Key Concepts Explored :

* **Insertion Shuffle** : Modeling the transition probabilities and finding the stationary distribution (uniform measure).
* **Variation Distance** : Measuring how close the deck distribution is to a perfectly uniform distribution after $n$ shuffles
* **Mixing Time** : Demonstrating that for a deck of $N$ cards, it takes approximately $N \log (N$) shuffles to reach a well-mixed state (around 360 shuffles for 52 cards using insertion)
* **Riffle Shuffle** : Analysis of the most common shuffling method, showed it is highly efficient and requires only about 8 to 9 shuffles for a 52-card deck

<img width="1628" height="811" alt="image" src="https://github.com/user-attachments/assets/eefe58b2-0d30-4f03-9bf4-ec864f0dc265" />


## Technologies

* **Python**
* **Mathematics and Probabilities** : Markov Chains, Transition Matrices, Total Variation Distance and Euler-Mascheroni constant
