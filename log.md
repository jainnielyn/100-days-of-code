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


### Day 11 & 12: November 19-20, Mon-Tue

**Today's Progress**: Watched CS50 lecture on HTTP (lecture 6).

**Thoughts** Great, David explains the basics of the web well.


### Day 13 & 14: November 21-22, Wed-Thu

**Today's Progress**: Watched CS50 shorts on HTTP. Watched lecture 7 on dynamic programming.

**Thoughts** Good easy explanation on how the web works. HTML and CSS are old friends. Yale instructor was confusing in explaining dynamic programming, but a resource for easier understanding is: https://www.youtube.com/watch?v=We3YDTzNXEk


### Day 15: November 23, Fri

**Today's Progress**: Watched CS50 lecture on Python.

**Thoughts** Huh. Python is easier than C!


### Day 16: November 25, Sun

**Today's Progress**: Watched CS50 lecture on Python, continued.

**Thoughts** Python seems interesting!


### Day 17: November 26, Mon

**Today's Progress**: Watched CS50 shorts on Python.

**Thoughts** Want to see how the actuals would be - if it's indeed easier. It's definitely a slightly different way of thinking (like loops are slightly different).


### Day 17-19: November 27-29, Tue-Wed

**Today's Progress**: Working on pset6, converting .c files to .py.

**Thoughts** Got quite busy so didn't have much time to code recently. Gained a new understanding of how to code for loops in python. They are indeed quite different than C or Java!


### Day 20: November 30, Fri

**Today's Progress**: Completed converting credit.c to credit.py

**Thoughts** Ugh, the user input checking was running circles around me. Decided not to use cs50's library of "get_string" but did my own validation instead to learn more. It took longer than expected, haha! But now I gained a new understanding. I like how there are built in string methods(?) where you could easily get the first or last x number of characters!


### Day 21: December 1, Sat

**Today's Progress**: Started converting caesar.c to caesar.py... and finished!

**Thoughts** So in C it took some getting used to having the chars as integers, but easier to shift them. Now in python, it takes some getting used to having a character as an actual character. Got analysis paralysis thinking about the best way to add a key per character, so will continue tomorrow.
Had another crack at it after a break, and completed it using the string library! (and a pythonic solution, I hope?)


### Day 22: December 2, Sun

**Today's Progress**: Completed converting vigenere into python.

**Thoughts** Python is really handy! Makes coding easier!


### Day 23: December 3, Mon

**Today's Progress**: Coded lines and sentences for similarities exercise. (Comparing 2 files together and comparing by line or by sentence)

**Thoughts** Oh, after the time spent understand all the files in the set, coding the actual functions was quicker than I expected! 


### Day 24: December 4, Tue

**Today's Progress**: Finished similarities (less)! Starting on similarities (more).

**Thoughts** Similarities (less comfortable) was a little too easy, so will also work on the more comfortable version!


### Day 25-26: December 5-6, Wed-Thu

**Today's Progress**: Completed distances and index.html for similarities (more comfortable). Also part of matrix.html.

**Thoughts** It took me a while to figure out how to work with tuples in a 2D matrix (Imagining it gets a little complicated), also because the CS50 explanation is not crystal clear. Good thing there was that youtube video that explained edit distance better. For matrix.html, I can now print the costs of the matrix. I only need to print string a and b at the top row and leftmost column.


### Day 27: December 10, Mon

**Today's Progress**: Watched SQL lecture

**Thoughts** Familiar territory! I found SQL easy in college.


### Day 28: December 11, Tue

**Today's Progress**: Watched SQL shorts. Read specifications for CS50 finance.

**Thoughts** Wow, much difficult...


### Day 29: December 12, Wed

**Today's Progress**: Completed register function, started with quote function... completed quote function! Started with buy function.

**Thoughts** This problem set is pretty challenging! Confused with how python and SQL and Jinja all come together, makes progress slower.


### Day 30: December 13, Thu

**Today's Progress**: Completed buy function.

**Thoughts** Starting to get the hang of python + SQL! Still don't like Jinja though.


### Day 31: December 14, Fri

**Today's Progress**: Worked on index, just need to display the cash and total portoflio value in a format...

**Thoughts** Hello 'group by' syntax in SQL! I meet you again.


### Day 32: December 15, Sat

**Today's Progress**: Completed index. Started with sell.

**Thoughts** Turns out the format functionality is in the jinja documentation! Cool, almost done with the functionality in this problem set. Will need to go back and make it optimal later.


### Day 33: December 16, Sun

**Today's Progress**: Completed sell, and fixed formatting of dollar amounts in index.

**Thoughts** Was putting off writing the nitty gritty code for updating the stock amounts, as I knew it was going to be a little complicated. There are many transactions for each symbol bought, with differing amounts. So subtracting the amount of stocks the user wants to sell can be a little tricky. (What if there are 10 lines for the stock, and one line could be greater than/less than/equal to the sell amount of shares) But I was able to do it easier than I expected! Trick was to be well rested, and utilize pseudocode!


### Day 34: December 17, Mon

**Today's Progress**: Implemented history 2/3 of the way.

**Thoughts** Before coding I took some time to think of the "best" approach then did sample cases on paper (which would highlight the algorithm) - doing it on paper *first* really helps a lot!


### Day 35: December 18, Tue

**Today's Progress**: Completed history!

**Thoughts** Yay!! *happy dance* The bulk of the work was configuring the SQL structure, then it was easy peasy to code the html template with Jinja. Learned Jinja's ternary operator (e.g. 'Update' if Case else 'Continue')


### Day 36-38: December 19-21, Wed-Fri

**Today's Progress**: Added a way to change password.

**Thoughts** Ran into multiple issues when running check50, but eventually worked it all out! Now I'm 5/5 for both style and correctness!


### Day 39: December 22, Sat

**Today's Progress**: Ran checks, revised code and completed CS50 finance!

**Thoughts** Yay!!


### Day 40-41: December 24-25, Mon-Tue

**Today's Progress**: Watched lecture on Javascript

**Thoughts** Learned a bit of JS a while back, but it feels like the Python knowledge overwritten it in my mind, haha. It still seems familiar though, I would only need to code to bring it back!


### Day 42: December 26, Wed

**Today's Progress**: Watched Javascript shorts

**Thoughts** I really like how CS50 shorts teaches you more about the subtopics (versus getting one of the Udemy courses - I feel like they don't explain it well enough.)


## 2019
### Day 43: January 2, Wed

**Today's Progress**: Read through mashup, problem set 8

**Thoughts** Okay, I got overwhelmed. Javascript was understandable enough, but this pset seemed like alien language. Had a bout of imposter syndrome and didn't look at it for a few days.


### Day 44: January 7, Mon

**Today's Progress**: Created a table for places

**Thoughts** How do you eat an elephant? One bite at a time. Hesitantly, I read the pset again slowly... and discovered that the first thing to do was create a table. Ah, not alien language!


### Day 45: January 8, Tue

**Today's Progress**: Completed articles and search from application.py, and configure from scripts.js.

**Thoughts** Whew... ok, it doesn't need an Einstein brain. Now I think, am I really learning? I had to google to find out I needed to use request.get.args. Also, doesn't CS50 give too much to the students? But then again, it wasn't meant to be a hardcore course; just an intro - so it makes sense. I guess I am still in the imposter syndrome phase...


### Day 46: January 9, Wed

**Today's Progress**: Fixed issue from yesterday, infobox now shows news.

**Thoughts** The reason why this was happening yesterday is because going through the lookup takes about 4s, and I had infobox open before it could retrieve the news. So I nested infobox open, now it has to wait for the lookup function to complete before opening the window. I know, 4s is forever in today's standards, but it's good enough. For now.


### Day 47: January 10, Thu

**Today's Progress**: Completed remove markers for CS50 mashup! Completed some kata from codewars, levelled up to [7 gyu](https://www.codewars.com/users/jainnielyn).

**Thoughts** This marks the end of CS50 course for me! Yay~ There's actually a "final project" where you think of something to use what you've learned with, but I took CS50 just to refresh myself with coding, so I'm finished with it. After doing some kata on [codewars](https://www.codewars.com), I realized I need to learn more... JavaScript?


### Day 48: January 11, Fri

**Today's Progress**: Watched some videos and completed some challenges on [coderbyte](https://coderbyte.com/course/learn-javascript-in-one-week). Completed up to lesson 9 on [regexone](https://regexone.com/).

**Thoughts** Coderbyte, learn JS in one week. The basics I already knew (variables, functions, loops). Hit a snag on regular expressions, again. I've been encountering it from katas too. This is what I'm going to learn next. I like regexone because each lesson is bite-sized and easy to understand, plus there's a little exercise to solidify the knowledge. You could also see their solution (hopefully after you complete the exercise), and compare to yours.


### Day 49: January 12, Sat

**Today's Progress**: Completed the rest of the lessons [regexone](https://regexone.com/). Tried some regexone exercises. Did 1 kata in codewars.

**Thoughts** Ah, I think I know regex a bit now! Regexone's exercises are really difficult though? I wish it were gradually difficult instead. Did a kata to make me feel better about myself haha.


### Day 50: January 13, Sun

**Today's Progress**: Completed exercises from w3resource.

**Thoughts** Found a website with better difficulty of exercises, although it's actually for making python code to test for certain regex, I just check my answer against the regex portion of the code. It's not interactive like regexone, but it will do. So far, so good. I'm not stumped how to solve anything yet, though sometimes I miss one character in my solution.


### Day 51: January 14, Mon

**Today's Progress**: Did some more exercises from w3resource.

**Thoughts** Their solutions aren't really accurate! Also, I think I have a good grasp of regex more or less even though I can't do the complex exercises from regexone yet. Onto the next topic!


### Day 52: January 16, Wed

**Today's Progress**: Started **Responsive Web Design curriculum** from [freecodecamp](https://learn.freecodecamp.org/).

**Thoughts** I plan to make a vacation scheduler web app as a personal project, so I thought this would come in handy. Also, web work has a low barrier of entry, so it would be easy enough to find things to do for people as practice. Finished HTML portion in a blur, that was easy.


### Day 53: January 17, Thu

**Today's Progress**: Finished basic CSS portion. Started Applied Visual Design portion.

**Thoughts** Still mostly easy, as I've learned these before. Applied Visual Design was easy at the start, then becomes more complex. Some of these things I don't know about, so learning some new things. Hopefully they stick as the little exercises are a little too much spoonfeeding.


### Day 54: January 18, Fri

**Today's Progress**: Finished Applied Visual Design portion.

**Thoughts** The latter portion took me a while. It would have been easy if I just read the spec and did as was instructed, but I want to actually understand what I'm doing, so I understand the idea first and let it sink into my brain.


### Day 55: January 19, Sat

**Today's Progress**: Started with "Applied Accessibility" portion.

**Thoughts** It's amazing to see how the internet has been modified to be inclusive to all kinds of people. I haven't really thought about how people with eye or hearing defects use the internet. I am glad there are tools put in place for them so they can use the internet as well. But, I don't think I'll remember all of these... at least I'll remember there's tags for certain things, even if I don't remember the syntax. Easily Google-able. 


### Day 56: January 20, Sun

**Today's Progress**: Completed the accessibility portion, completed "Responsive Web Design Principles". Started "CSS Flexbox Challenges".

**Thoughts** There's lots of cool things in HTML5 now!


### Day 57: January 21, Mon

**Today's Progress**: Completed CSS flexbox. Started a website using a template for someone.

**Thoughts** That's a lot of new things. CSS flexbox is a great handy tool to use instead of divs. Hope I remember these properties!


### Day 58: January 22, Tue

**Today's Progress**: Added another page to the website. Almost done with CSS flexbox from freecodecamp.

**Thoughts** I realize, I don't like front end design. I would still like to finish it though, as it would be a waste if I don't since I'm so close to completing this course from freecodecamp (and that virtual certificate!). Also, the next section is actually for creating projects, so it would be good experience.

After this course, I will start working on my projects. My goal is 3 projects completed by July/August, study for interviews, then start applying by September/October.

Project idea #1: Vacation scheduler - User inputs places s/he wants to visit, code figures out optimized way to go about it (taking into account opening hours, close days, weather and usual time people spend in the area), and spits out day/time schedule.

Project idea #2: A crawler of some sort - I've always wanted to try my hand at crawlers. Initial idea is creating a list of restaurants with lunch specials around the user indicated zip code(?). Useful for work lunches, discovering new restaurants.

Project idea #3: None yet


### Day 58: January 23, Wed

**Today's Progress**: Completed CSS flexbox portion in freecodecamp. Completed CSS grid portion. Completed part 1 of web design projects, Tribute Page.

**Thoughts** That was interesting... it was great to finally apply the things I've learned! I may not remember syntax of things, but since I know there are various ways to do things, it's easily solved by my friend Google.

Also, for project #2: Realized that scripting does not work this way. One actually needs a website where things are, and then model a template that would extract data. I've changed my mind to pull data from [slickdeals](https://slickdeals.net/) into a .csv file, for Amazon arbitrage use (?).

Met with the President of [Philippine American Chamber of Commerce (PACC)](https://www.philamchamberny.org/) to offer IT-related help. Looking forward to "real world" projects!

**Link** [See my tribute page](https://codepen.io/jainnielyn/full/GzgBzL)


### Day 59: January 24, Thu

**Today's Progress**: 

**Thoughts** 

**Link** 
