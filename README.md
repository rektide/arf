# arf

> Abort, retry, or fail web terminal

http://arf.anomal.istic.us

I was curious to see what it would be like to write a mini "terminal" program on the web. 

I wrote a quick interface that asks the age old question, abort retry or fail, and gives you a keyboard or touch-friendly way of answering. Users then have to confirm their selection. Denying will continue the session, enabling further input, confirming will submit & show an acceptance text.

# Assorted Notes

## Loadable dictionary

The text dictionary is loadable. Going to `/arf.html?pirate` for example will load the "pirate" dictionary that will show in the prompts.

## Static

This entire app is one html page with the embedded. At the same time, it does submit a HTML form via the default `GET` method, so my server can log response.

I thought this might be fun to use this project as a part of a short talk on event-sourcing, by developing a small daemon that can watch these logs.



