---
layout: essay
type: essay
title: "Being Standard"
# All dates must be YYYY-MM-DD format!
date: 2024-09-26
published: true
labels:
  - Engineering
  - Programming
---



When writing your programs, you might be able to understand the thought process and what is being achieved with a mere glance. Maybe after not seeing the program for a while but upon taking the time to skim through the lines of code you could remember what is happening. Who is to say that another programmer who has never seen your code before would be able to understand it? Maybe their coding style clashes with yours.

To avoid these bits of miscommunication, we have coding standards. Coding standards are guidelines, conventions, and practices that help ensure code is readable, consistent, and maintainable throughout time. Some of these standards include naming conventions, formatting, and documentation. Coding standards should be practiced by any developer, even if they fly solo.

## Telling a Story

There are many different companies, each with their coding standards. For example, the standards for Google differ from the standards for Microsoft. These differences show what each company values more in the clarity of their code. Regardless of their differences, they all aim to make code that makes sense. When I was learning how to write programs, my professor had an intriguing quote. 

“Your code should tell a story.”

My interpretation of the quote is to write your code in a meaningful and clear way. Anyone should be able to read your code and understand what the code is trying to achieve. This includes naming your variables or functions in ways that make clear what their purpose is, aligning text to improve readability, and using macros to get rid of “magic numbers”.

## The Linter's Complaints

To help coders keep their code clean and adhere to coding standards, they make use of linters. A linter is a formatting tool that will scold you for not writing your code to standard. This includes smaller details such as spacing, or larger details such as the order in which functions or variables appear in your code. 

In the past week, I have been working with ESLint with my Typescript programs. While I do not agree with some spacing details the linter likes to yell at me for, I have not had much of a bad experience with the linter itself. It can get annoying when the linter is throwing a hissy-fit in the middle of typing out your function, but it calms down once it sees you are doing things properly
