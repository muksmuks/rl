---
layout: post
title:  "Creating dictionary as a lambda function"
date:   2022-05-01 15:16:00 +0530
categories: [python]
---


In python, lambda function are anonymous function which can perform a small task.
A dictionary can be defined as a lambda function.


```python
digit_to_english = lambda t : {0:"Zero", 1:"One"}[t]
```

We can invoke it as a function
```python
digit_to_english(0)
```

The output would be 'One'

