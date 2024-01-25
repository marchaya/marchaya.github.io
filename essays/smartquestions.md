---
layout: essay
type: essay
title: "The Art of Asking Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2024-01-25
published: true
labels:
  - Software Engineering
  - Learning
---

<img width="300px" class="float-start pe-3" src="../img/ICS314/smartQ.png">

## Smart Questions
Asking smart questions is important, not only to the individual asking the question, but to the community as well. Introducing problems without known solutions can bring attention to new or overlooked issues. By attempting to find solutions, software engineers contribute not only to the community but also to their own skill development. It would help future strugglers who encounter the same issue to find your question, and might also aid those answering by uncovering new knowledge on the topic. However, one of the most important distinctions between smart and not-smart questions is the amount of effort put into finding a solution on your own beforehand. Including the thought process you took to attempt to find a solution will give more context on where to start and what the questioner is asking.

## Smart Example
A smart question on StackOverflow illustrates this well. It asks, "Why is processing a sorted array faster than processing an unsorted array?" The individual who posted this question provides a base code example of where their curiosity originated. The question includes an example, detailing the execution times for both sorted and unsorted arrays. In their pursuit of an answer, they even tested their code in Java, suspecting a language or compiler anomaly, and observed similar results. With all the context displayed, they give their final thoughts on why it may be and ask, "My first thought was that sorting brings the data into the cache, but that's silly because the array was just generated. What is going on? Why is processing a sorted array faster than processing an unsorted array? The code is summing up some independent terms, so the order should not matter."

## Smart Answer
The most upvoted answer directly addresses the query: "You are a victim of branch prediction fail." From there, they go on to explain what branch prediction is with an analogy using train tracks. The answerer then applies this analogy to coding, mirroring its structure for easy understanding. They continue to focus on the main issue and bring attention to the "culprit." The answerer then asks, "What can be done?" and proceeds to give a simple solution to the problem. They clearly outline which code to replace and also provide the replacement code. Their solution is followed up with time results comparing the old code vs the updated code in a table, clearly demonstrating that their solution works.

## Not-So-Smart Answer...
An example of a poorly framed question is titled "Cant define another class," lacking both descriptiveness and proper punctuation. The question merely copies the error message received, providing little context or background for the issue at hand. The post states, "i tried a new class to tha admin page And was expecting it to operate with zero issues and load the offer class." This is understandably downvoted with no answers. Without considering the poor question structure, it is obvious that the individual did not do much research, as indicated by the lack of context. This also makes it difficult for anyone to answer the question accurately.

In conclusion, the way questions are asked in a technical community like StackOverflow can significantly impact the quality and efficiency of the answers received. Smart questions, characterized by clear context, thorough research, and well-thought-out queries, not only facilitate effective problem-solving but also contribute to the collective knowledge and efficiency of the community.
