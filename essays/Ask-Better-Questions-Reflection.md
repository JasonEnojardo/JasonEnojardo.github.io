---
layout: essay
type: essay
title: "Ask Better Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Smart Questions
  - Better Responses
---

## What About Asking Smart Questions?

  In this essay I will compare questions asked in a smart manner versus one asked in a not so smart manner and we'll see the types of responses each of the questions yield. To start off let's define what's the smart way to ask a question that will most likely yield a helpful response and not get you criticized. The first thing you should do when you have a problem is to try and find the solution yourself by searching the web, such as using search engines like google, to find websites, forums, or other FAQ's [1]. It's most likely you are not the only one who has come across the issue you're having. So most likely someone else has already posted a similar question to the one you're thinking of in a forum or FAQ and has gotten pointers or the answer you're looking for. By doing this you're taking the time to narrow down your issue and get closer to finding a solution and even if you don't this will help you formulate a more concise question that will show who you're asking that you've already taken the time to try and develop a solution yourself and are willing to help yourself [1]. you also want to make sure you describe the issue you’re having like how the issue is occurring and inform the steps you've already taken to try and solve your problem [1]. You also want to describe the environment the issue is occurring in that way others can narrow down solutions in their response quicker and not have to ask what version of the application the issue you're experiencing on [1]. Also make sure to write clearly and without grammatical errors [1]. 
  
  As we might expect a not so smart question is one where someone has an issue and decides to ask about it rather than spend the time to first look for a solution themselves [1]. Also, if your issue is with code, it's not good to just dump the whole code when posting your questions especially if you have hundreds of lines of code [1]. What you should do is post the portion you're having issues and explicitly state what line it's on along with a detail on why you think it’s happening with what you've done to debug it and post supporting code for the portion that has the issue.

## This Is You Ask Smart Questions

  Looking around on StackExchance I found a question that has most of the properties necessary for a smart question. This question asks [How do you push MongoDB objects into a global array without it overwriting?](https://stackoverflow.com/questions/65987065/how-do-you-push-mongodb-objects-into-a-global-array-without-it-overwriting). The issue they think they're having is a scoping issue. So, this person is having an issue with MongoDB and essentially, they are trying to make a program that searches for a specific person which is an object, and, in this object, it has an array of friend’s names. They want to take all the friends names and put it in a new array that is essentially the results of their friends’ name. But the issue they're having is due to the for loop in their code because at the end of the loop all the data stored in the new array gets deleted. So, this is a pretty good question because they explicitly say what they think the issue is and provide the step process as to how they developed the code. So, it seems they have already tried what they can to find their own solutions. The comments received from the community was essentially that the way the path they were using to develop the program was wrong and they should use MongoDB's aggregation pipeline and provided with a sample code to follow.

  Here is another question I found that doesn't follow the properties on how to ask a smart question. This question asks [Weird adb logs, I get a lot of these logs](https://stackoverflow.com/questions/75277489/weird-adb-logs-i-get-a-lot-of-these-logs). Aside from the question all they posted was a couple lines of error codes and didn't explicitly say those were error codes and didn't explain what has caused these errors to occur, didn't provide the steps they took to find a solution themselves, didn't even provide sample code, and didn't even explain what they are trying to do. So, one of the responses was to "Please clarify your specific problem or provide additional details to highlight exactly what you need. As it's currently written, it's hard to tell exactly what you're asking.".

## Smarter the Questions, Smarter the Engineer

  Based on these two examples I understand now why it is important that when you ask questions make sure you tried to answer it yourself so you’re not wasting someone else's time where you could've just looked it up yourself and when you do research the issue yourself you gain a better understanding as to why you have this issue. That way you can make a more precise question and explain what you've done to try and remedy a solution yourself. This way you're showing the person you're asking that you have at least attempted to solve it and want to help yourself develop a solution rather than let someone else do it for you.

## References

[1] E. S. Raymond, R. Moen, E. Mitchell, and M. Ramendik, “How To Ask Questions The Smart Way,” How to ask questions the smart way, http://www.catb.org/esr/faqs/smart-questions.html (accessed Sep. 7, 2023). 
