# Analyzing Hacker News Posts

## Introduction
Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

Users submit `Ask HN` posts to ask the Hacker News community a specific question. Likewise, users submit `Show HN` posts to show the Hacker News community a project, product, or just generally something interesting.

## Dataset
You can find the data set [here](https://www.kaggle.com/hacker-news/hacker-news-posts), but the dataset have been reduced from 300,000 rows to approximately 20,000 rows (available in the repository) by removing all submissions that didn't receive any comments and then randomly sampling from the remaining submissions. (Courtesy: Dataquest)

## Problem Statement
- Do `Ask HN` or `Show HN` receive more comments on average?
- Do posts created at a certain time receive more comments on average?

## Conclusion
Let's answer the questions 
**Do `Ask HN` or `Show HN` receive more comments on average?**

`Ask HN` posts received 14 comments per post as compared to `Show HN` posts that received 10 comments per post.

**Do posts created at a certain time receive more comments on average?**

Yes. `Ask HN` posts posted between 15:00 and 16:00 EST receied most number of comments.
