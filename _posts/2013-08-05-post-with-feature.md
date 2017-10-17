---
layout: post
title: Philosophy of Data Midterm Colin and Toby




---

Colin (theory): As social media becomes more and more of a driving force in our lives, it can seem that it is impossible to keep track of all that is going on. We designed our project around this problem. Hashtags work as a label for tweets, identifying them and grouping tweets about the same thing together. In sending a random hashtag to you every day, we hope to expose the repetition of themes that Trump’s tweets, and in future iterations of the project the tweets of other celebrities, have. For example, trump uses the hashtag “Drain The Swamp” 57 times. That means at least 57 tweets from the limited set of tweets we have from Trump are about his plans to get rid of corruption in Washington. There are other common hashtags such as “Crooked Hillary”, “MAGA”, and “America First” that appear extemley frequently. If we are to develop this project further, it would be interesting to send the hashtags or even entire tweets of those people in Trump’s circle along with Trump’s tweets to see the similarities. 

Toby (code):
We used a couple different previous blocks of code to make this program. We took a script that automatically sends emails from a previous class and added to it some of the code from the search history exercise. Here’s what the code does:
  Imports the necessary pre-written functions  (smtplib, csv, random)
  Creates a function that reads the csv file of Trump hashtags and puts each into an array. Then, it selects a random item          from this array and returns it. This is the mostly code from the search history exercise, and we added the random return      element.
  Creates a server and logs into a gmail account (specifically, delightfulTestingBoy, an account I made for this script           previously). 
  Calls the random hashtag function to get a message to send, and then sends it to an email address inputted into the code. Steps 3 and 4 are from the previous email script.
  We could expand this code in a couple ways:
  Prompt the user to log into their own email
  Prompt the user to input a destination email
  Get more complicated text to send than short hashtags
  Pick out some emails in advance (of political figures or celebrities or something) and prompt the user to choose one to send    the emails to
  Send multiple emails at once (like… thirty of them)
We encountered a few issues while working on the code, but solved them. Here they are:
  The code was demanding an infinite number of indents, and it turned out to be a problem with the file itself. We’d moved the      file from one folder to another, and that seemed to have upset the file. By copy+pasting the code into a clean file, it         worked fine.
  The .csv file of Trump tweets is pretty big but had a ton of blank lines in it. Getting rid of them by hand was tedious and     awful. We did some research and found out how to use find/replace in TextEdit to get rid of all the empty lines.
  A variety of small errors that were solved by googling them/inputting them into stack overflow/talking through the code out     loud and looking a bit like a maniac. 
