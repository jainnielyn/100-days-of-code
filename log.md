# 100 Days Of Code - Log

*Background: Received BS Computer Science in 2011, cum laude. However, due to some circumstances, did not go into tech. Currently working full-time, but realized coding is what I **really** want to do!*

---
#### Goals:
- Refresh basic computer science knowledge (by completing **Harvard's CS50 course**). *Will not* be uploading code for this (no cheating!).
- Create own projects
---

### Day 1: November 8, Thursday

**Today's Progress**: Successfully implemented 2 out of 3 exercises in **problem set 4** of CS50 (whodunit and resize less).

**Thoughts** This course is really challenging! I am surprised at the level of complexity they teach supposedly beginners. On the other hand, it's also really rewarding when you finally get it 100% right! 

**Link(s) to work**
1. [Twitter update](https://twitter.com/jainnielyn/status/1060529654849773568)

### Day 2: November 9, Friday

**Today's Progress**: Coded recover exercise. This completes pset4!!

**Thoughts** Had a tough time understanding pointers (* and &) and fopen/fwrite/fread. 

**Link(s) to work**
1. [Documentation](http://www.cplusplus.com/reference/cstdio/fwrite/)


### Day 3: November 10, Saturday

**Today's Progress**: Watched lecture for **week 5** of CS50. Learned more about pointers in C, and some intro to linked lists.

**Thoughts** I understand malloc, but it hasn't really sunk in. Maybe when I start using it...


### Day 4: November 11, Sunday

**Today's Progress**: A little relaxed on a Sunday, but still watched the short videos pre-coding exercises.

**Thoughts** Excited to use data structures, linked lists, queues and stacks!


### Day 5: November 12, Monday

**Today's Progress**: Completed all short videos of week 5 (data structures). Started looking over **problem set 5**, speller.

**Thoughts** Somehow, even after completing problem sets 1 through 4, whenever I go through the next specifications, it feels daunting. "Omg this is so difficult."


### Day 6: November 13, Tuesday

**Today's Progress**: Reviewed all .c and .h files to understand the basic structure given, answered questions for pset 5.

**Thoughts** It wasn't that difficult after all! Mood is important, when I'm tired my brain rejects having to understand code (anything, really), and then negative self talk happens. Will enforce sleeping early more, and be more understanding when unforeseen circumstances prevent me from doing so.


### Day 7: November 14, Wednesday

**Today's Progress**: Started working on function load for speller. Decided to use a trie data structure for word lookup time optimization.

**Thoughts** Still confused about how pointers in a trie work and how to use them in code, but Google has been good help. Videos of other people implementing tries shed some light as well.


### Day 8: November 15, Thursday

**Today's Progress**: Completed load, check and size for speller!

**Thoughts** Still confused with working with pointers for a trie, but understanding it a little better.


### Day 9: November 16, Friday

**Today's Progress**: Completed unload, fixed some bugs! Now the output of my code is the same as the staff solution! Valgrind reports some bytes "still reachable" though...

**Thoughts** Hit a bump on unload using recursion, but remembered that there *should (normally)* be only 2 cases - if this is the last node in the branch, "delete me" or "delete lower node." It was a *eureka!!* moment!


### Day 10: November 18, Sunday

**Today's Progress**: Working on the valgrind memory leak. 4:30pm: Finally!!! Fixed memory leak and got 100% on speller! 

**Thoughts** What does "still reachable" even mean?! Knowledge gap cleared on recursion!! Realized I was still missing something in recursion. "Delete everybody else, ***then delete me.***" So added lines for deletion of node after it deletes the lower nodes.


### Day 11: November 19, Monday

**Today's Progress**: Watched a part of CS50 lecture on HTTP.

**Thoughts** Great, David explains the basics of the web well.
