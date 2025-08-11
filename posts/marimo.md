---
title: Marimo
author: Simone Massaro
date: 10 Aug 2025
---

# Marimo first impressions

I started to experiment with Marimo because I wanted to try a reactive notebook, that for basic data analysis seems an interesting idea.

You can check all about Marimo at [marimo.io](https://marimo.io)

What I like:

- the UI is polished
- it suggest to autoinstall missing packages and uses uv!

What I don't like:

- cannot redefine variables. I have developed the habit that a notebook cell needs to be idempotent, which means that I can rerun it as many times and it still gives the same result. This does mean I can modify variables there, the most common use case is adding a column to a dataframe. With marimo I can't do that and I need to come up with new variable names.
- doesn't support star imports
- the ui of the dataframe seems that sometimes doesn't sync with the data

overall it looks pretty nice, I should definitely keep playing with it.
