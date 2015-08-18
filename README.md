## Preparation

We use [ipython notebook](http://ipython.org/notebook.html) and [RISE](https://github.com/damianavila/RISE) to hold the training meterials. You should install them before you view the meterial in your local platform.

To view the presentations, just switch to the project directory, and execute `ipython notebook` in command line.

## Python Basic Training

### Outline

1. 9:30 ~ 9:40
    * build up group (pair)
    * duplicate notebook
    * ipython basic
1. 9:40 ~ 9:50
    * Setup Python develop environment
        * Install Python (2 vs 3)
        * Choose an editor
        * Choose an interactive shell
1. 9:50 ~ 10:00
    * "Hello World"
1. 10:00 ~ 10:20
    * Use python as a calculator
        * int, float
        * +, -, *, /, %, **
1. break
1. 10:30 ~ 11:00
    * Format your letter
1. 13:00 ~ 14:00
    * Find out valid LAN ip addresses
        * ==
        * if - else
        * for
1. break
1. 14:10 ~ 15:20
    * Get most active users from nginx access log
        * list
        * tuple
        * dict
        * set
        * list comprehension
        * set comprehension
        * dict comprehension
1. 15:30 ~ 16:40 (break before practice)
    * Find fatest mirror
        * subprocess
        * multi-threading, multi-processing (*)
1. 16:40 ~ 17:00
    * Zen of Python
1. 17:00 ~ 17:10
    * feedback

### Retrospective

1. `Find out valid LAN ip addresses` waste a lot of time on the definition of LAN ip range.
    * add LAN ip definition in the question
1. `Get most active users from nginx access log` stuck on sorting problem.
    * add doc link of `sorted` function
    * remove question 2, split question 1 into two steps, first step get the ip and count, second step, sorting.
1. `Discussion` seems meaningless.
1. Classroom need to be restructed, cycle is not good for it.
1. waste a lot of time on notebook cloning
    * add instruction into slides
1. few feedback
1. pair programming in the morning is not good
    * in the morning, everyone should finish the practice
    * in the afternoon, switch to pair mode
1. `Download content from website` is not in the same line as other practices
    * change it to `find fatest mirror`
1. somebody seems tired in the last practice, how to reschedule the practices?

## Python Intermediate Training

### Outline

1. Introspection
1. Functional programming
    * map-reduced
    * read_int
1. Unit Testing and TDD
    * use cyber-dojo http://cyber-dojo.org/
    * use TDD to implement read_int
    * bowling game
1. Iterator and Generator
    * mock command line system
1. Run in parallel
    * batch downloading tool
    * Multi threading
    * Multi processing
    * Gevent
        * BBS like chating service
1. Design patterns
    * Mixin
    * Singleton
    * Decorator
1. Regrex Expression (?)
1. Meta Class (?)
