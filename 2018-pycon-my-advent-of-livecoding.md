# The Advent of Livecoding

## Submitted by

Joel Grus

## Description

[Advent of Code](http://adventofcode.com) is a 25-day, 25-part programming challenge each December. This year I livecoded my attempts to solve each problem and posted the videos to YouTube. I expected that it would be a fun challenge, and that people might find it valuable to watch me fumble through the problem-solving process.

What was surprising was how valuable I found it. Over those 25 days I learned a lot about livecoding, about problem-solving, about expertise and stupid mistakes, about time management, about communication, about data modeling, about success, about failure, and of course about Python.

In this talk I'll share the lessons I learned and teach you how livecoding will make you a better programmer.

## Audience

This talk is for anyone who wants to improve their coding skills and Python skills. Beginners will find valuable the structured modeling approach I developed over the 25 days, as well as the stories of all the stupid mistakes I (a very experienced Python developer) made when put on the spot. Experienced programmers will find valuable the systematic mistakes I made and the bad programming habits I discovered in myself.

Anyone with basic programming knowledge should be able to benefit from the talk. As mentioned above, Python beginners will get different value out of it than Python experts, but it should be interesting and useful for both groups. Hopefully it will lead people to introspect some of their programming habits and build better ones.

## Outline

* (1 minute) about me
* (1 minute) about Advent of Code
* (1 minute) about livecoding
* (21 minutes) there are 25 Advent of Code problems, I plan to spend ~50 seconds on each one: (10 seconds the problem, 10 seconds the solution, 30 seconds "what I learned") (50 seconds * 25 problems = 1250 seconds = 21 minutes). Here's a rough overview of the "what I learned"s

** Day 1: the `zip(xs, xs[1:])` trick
** Day 2: n^2 algorithms are sometimes OK
** Day 3: simplify before coding
** Day 4: Pythonic anagram finding
** Day 5: when to slice-copy your input lists
** Day 6: itertools
** Day 7: recursive data structures
** Day 8: data modeling with NamedTuples
** Day 9: state machines
** Day 10: immutable state machines
** Day 11: make sure to run `mypy`!
** Day 12: finding your inner graph problem
** Day 13: when to simulate and when not to
** Day 14: reusing interview whiteboard problems
** Day 15: understanding bit arithmetic
** Day 16: looking for shortcuts
** Day 17: recognizing special cases
** Day 18: knowing when to throw it all out and start over
** Day 19: hiding your error checking inside abstractions
** Day 20: sometimes it's ok to just guess
** Day 21: cache your work
** Day 22: using sparse representations
** Day 23: learning to fail
** Day 24: using tuple sorting to your advantage
** Day 25: putting it all together

* (5 minutes) grand overall lessons
* (1 minute) thanks!

# Additional notes

I have given a lot of talks, a few representative ones are:

* Livecoding Madness: Let's Build a Deep Learning Library (ODSC West 2017)
* Using AI to Answer Science Questions (Southern Data Science Conference 2017)
* Fizz Buzz in Tensorflow (PyData Chicago 2016)
* Learning Data Science Using Functional Python (PyData Seattle 2015)

I have never given this talk before.

Here is a YouTube playlist of all the livecoding videos: https://www.youtube.com/playlist?list=PLeDtc0GP5IClpoQ6ZnsIk8nzNHaoR76hh

Here is the repo of all the solutions: https://github.com/joelgrus/advent2017

I also plan to write up a blog post about this, but I haven't yet. (The Advent of Code just ended a couple of days ago.)
