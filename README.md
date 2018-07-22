# webdo
A web based todo list with api so it can be used by any client ever, and eventually the terminal. Probably will be written in python/react.

## Motivation

I'm creating this because I've been trying to set up taskwarrior server for way
too long, and I've just resigned to believe it's an pile of garbage not worth
fixing. So in true open source fasion i'm gonna try to write something better. 

## Goals

This project should be as cross platform as possible. It should work well on 
mobile, desktop, and most importantly have terminal integration somehow.
Security will not be a priority (at least in the beginning) because I just
wanna get something working, and I'm not that worried about someone reading
my "buy more anime posters" todo task. However, the project will not allow
itself to be run as root, because remote execution on root is something really 
really damn bad. I'll write a script to like make installing as a new user easy, 
so nobody accidentally installs it as themselves or whatever

So basically: 
 * Security: Defend against remote execution, todo list privace IDGAF
 * Speed: Hack it out, don't think too hard. We can always rewrite if it becomes
a pile of shit. Duplicate rather than abstract unless spaghetti appears. 
 * Start with api in mind. Should be lightweight and fast. 


## Branching model

I'm pushing to master. If you want something merged submit a PR. If it's not
garbage I'll probs just give you push access to master after that. You should
also push to master. 
