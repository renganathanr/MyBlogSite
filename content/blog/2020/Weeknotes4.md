---
title: "Week4-20200614"
date: 2020-06-24T10:01:34-04:00
categories: ["RIT","Weeknotes","Web Development"]
---
In this week, I learned less amount of things related to web development. Last week I created a basic todo webapp in order to perform its primary purpose and found many unknown Flask syntaxes in it. So I learned those unknowns and debug my webapp.
# Debugging
## 1. Identify and show a warning message if empty string entered into task content form
In first when I created the app by following the Youtube tutorial - [Learn Flask for Python - Full Tutorial.](https://www.youtube.com/watch?v=Z1RJmh_OqeA), there is a bug that allows users to enter an empty string and save it. But when you look at it, there is no meaning if you entered nothing in the task content. So my brother teached me to use print statement debugging to identify and fix it using appropriate actions.
## 2. Refresh/reload using browser
Whenever I changed some content in my stylesheet, it does not reflect immediately in my browser. But if I changed some content in my app.py file, it automatically reload and reflect the changes in the browser. Then my brother instructed me what is the issue. There exists differences while you made changes in py file and stylesheets. The browsers have caches that only detects content changes even if you reload the browser using F5 or ctrl+R or manually pressing refresh button in the browser. For that you instruct the browser to reload without the cache using `shift+reload` options in the browser.

Then I watched some movies and learned some of SQLite database basics.