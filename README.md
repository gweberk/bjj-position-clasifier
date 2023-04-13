# BJJ positions helper

Final project for the Building AI course

## Summary

Brazilian Jiu Jitsu it's a really difficult sport to learn.
The main idea of the project is to build a map of positions and the options to attack or defend in each one.
This can improve the learning process of everyone's who wants to learn this art. This map is going to act like
a recommendation system in a learning website.


## Background

In the process of learning, it's difficult to know what alternatives are available, so it's useful to make 
a map with possible movements in each position to attack (if we are in advantage) or to defend. And depending 
on the situation, on things like where the opponent has his weight on, one movement could be 
better than another.


## How is it used?


This project consists in a learning website. It has a lot of learning resources pre-charged. 
They show and teach a simple movement or position. Movements could be an attack or defense in a 
custom position. Also, there are available championships videos.
By video based detection, the system can learn positions, the possible movements and defenses.
By the belt of the competitor in the video, it could know the technique's level.  

At the right of each leaning video, there are recommendations of another learning videos divided in 
attack or defend category and with a mark (the belt's color) to know its complexity.
At the right of each championship's videos, depending on what's happening on the video, could appear the 
link to the learning video of that movement.


## Data sources and AI methods

The learning videos can come from a learning academy. The competition videos can be found online with 
an open license.

Additionally, only a part of the learning video (when they show the movement, 
not all the explanation) should be used for train the AI.

Uploading competition's videos, them should be preprocessed to analyze the time and recognize the movement.
The relationship between them should be saved, and the sequence of movements too.

## Challenges

* Detecting players when they are interlocked in a complex way.
* The new movements or variants that always appears in the matches.
* Keep the system simple to help the learning process.

## What next?

* Distinguish player one from two in all the competition.
* Adding an automatic score in competition's videos.
* Detecting the technique's level with the belt color.
* Real time movement recommendation.

## Acknowledgments

* https://www.youtube.com/@HispaFight
* https://dl.acm.org/doi/10.1145/3552437.3555707
