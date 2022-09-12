# 66 Days Of Data | Log

### Day 5: September 11, 2022

**Today's Progress**:
- Worked on submodules to copy repos I've worked on during this challenge, into my 66-days-of-data repo
  - I'll continue to work on this to clone other repos into my 66-days-of-data repo to track all the projects and progress dedicated to this round of the challenge
- Still working with GH Pages. I need to figure out how to configure the DNS between GH Pages to my personal domain: http://www.veroanalytic.com/
- Continued working on analysis of Monkeypox cases worldwide. A few observations:
  - The U.S has the highest reported cases by 3x
  - Germany and Italy have the highest hospitalizations
  - Italy leads the group at 2.2% of cases leading to hospitalization
- Worked on cleaning up the "Symptoms" classification of Monkeypox
  - There are a lot of inconsistencies in the data, so I am attempting to transform similar named symptoms into a shared category to be able to better illustrate which symptoms are most prevalent when contract Monkeypox
    - Used regex to match to the particular symptoms
- Did more data cleaning of the Monkeypox dataset. In particular, I worked on conforming similar symptoms to a standardized naming convention.
  - Flu-like symptoms and different forms of skin lesions/ulcers are prevalent.


**Thoughts:**
Spent several hours, in different chunks throughout the day. I am really enjoying doing data analytics in VS Code (Jupyter Notebooks).

I do need to come back and continue my studies of "Automating the Boring Stuff with Python", but for now it will have to "remain on the shelf" so to speak.


**Link to work:**
- GitHub 66-days-of-data repo: https://github.com/veroanalytic/66-days-of-data
- GitHub monkey-pox-analysis: https://github.com/veroanalytic/monkey-pox-analysis.git
- GH Page: https://veroanalytic.github.io/



### Day 4: September 10, 2022

**Today's Progress**:
- Decided to skip a head a few chapters, and currently reviewing chapter 9, "Reading and writing files"
  - Learned about the pathlib module, and how it is better practice to use forward slashes in your code, even when working in Windows because it will allow your code to be able to run on other operating systems like macOS and Linux
- Conducted analysis on a worldwide dataset of Monkeypox cases, and the timeline of cases being reported
- Set up GitHub Pages for the first time. I will be using this to host a custom domain.

**Thoughts:**
I enjoyed working within Jupyter Notebooks again. It's definitely been a while. I think I'll continue working on the analytics portion of Python programming instead of the conceptual studying.


**Link to work:**
- GitHub monkey-pox-analysis: https://github.com/veroanalytic/monkey-pox-analysis.git

---
### Day 3: September 9, 2022

**Today's Progress**:
- Still continuing with Lists from "Automating the Boring Stuff with Python". This feels like a long chapter lol.
  - Reviewed tuples, and converting types with the list() and tuple() function
  - Clarified that variables do not necessarily store values, but they store 'references' to values. These references are stored in the computers memory (think a container or box)
  - Noted the id() function that returns the identity of the variable reference
  - Worth noting again, list methods like append() modify 'in-place'. So if my_list = ['cat', 'dog'] and has an ID of 123, if I run my_list.append('squirrel'), my_list is modified in place, and still contains the same reference ID of 123
- ** placeholder until I resume my studies. maybe after work
  - Studying has continued after dinner, where I learned that when using copy() and deepcopy() functions, you are creating an actual duplicate copy of a mutable value like a list; you are not just copying the reference of the list. Meaning the variable holding the original list, and the variable holding the copied list are independent of each other
  - Followed the code to create a 'Conway's Game of  Life' short program. Honestly it's over my head right now, but I'll have this saved away to refer to if needed.



**Thoughts:**
Unexpectedly woke up at 6 am, but instead of trying to force myself to go back to sleep, I decided to get up and have an early start to my studies.

This has been a goal for myself for a while to be able to wake up early and code/study before work. Here's hoping I can do this consistently and make it a habit.

**Thoughts: Late night**
I may make the decision to jump around in the chapters for Automating the Boring Stuff with Python. Conceptually, there's a lot of information, but pertaining to what I want to accomplish at my job, I don't think I need all of the details that are being depicted in some of the chapters.

I may start hopping around more towards chapters relating to actual automation, and then retroactively go back at chapters to understand any concepts. I think this will help it stick better.


**Link to work:**
- GitHub About Me: https://github.com/veroanalytic
- GitHub auto-boring-stuff repo: https://github.com/veroanalytic/auto-boring-stuff.git

---
### Day 2: September 8, 2022

**Today's Progress**:
- Updated my GitHub overview page with an About Me: README.md file. I used a generator to get the template, but will continue to alter it as needed.
- Still continuing with lists from "Automating the Boring Stuff with Python"
  - Reviewed list methods like append() and insert()
  - Also learned about the enumerate function
- ** putting a place holder here because I will resume studies after the gym :D
- Got back from the gym and continued more through my review of lists
  - practiced list methods such as remove(), sort(), passed keyword arguments within these methods like sort(reverse=True), to sort in descending order.
  - Went over sequence data types: lists, strings, range objects returned by the range() function and tuples are considered sequence data types. Meaning they can be indexed, sliced, and used in for loops with len() or with in and not in operators.


**Thoughts:**
I'm feeling impatient and want to get through these chapters that are of review for me and to the later chapters dealing with actual Python automation.

But I little by little, there are additional things that I'm picking up that I either forgot, or never learned during my initial pass at learning Python.

This is a marathon not a sprint, so I will continue to take it slower but with consistency.

**Thoughts after the gym:** I think I like this routine.
- Finish work
- Have dinner
- Study for a bit, digesting food, and record #66daysofdata challenge
- Go to gym
- Continue studying until tired

We'll see if I can keep this up.


**Link to work:**
- GitHub About Me: https://github.com/veroanalytic
- GitHub auto-boring-stuff repo: https://github.com/veroanalytic/auto-boring-stuff.git

---
### Day 1: September 7, 2022

**Today's Progress**:
- Created 66-days-of-data repo to track progress on this challenge.
- Used Git to clone the remote repo down to my local repo. Pushing changes back to GitHub through Git as well.
- Continuing Chapter 4 of "Automating the Boring Stuff with Python", which is focused on lists.
  - Working with lists:
    - Created a variable and assigned it as an empty list []
    - Followed that with a while loop that breaks out of the loop of an empty string is entered
    - Otherwise it continues iterating and allows for more inputs which gets outputted in a for loop
    - File name 'allMyCats2_ch4.py' in the auto-boring-stuff.git repo

**Thoughts:**
I took quite a long break from my last round of #66daysofdata. I'm riding this wave of motivation to reestablish this as a habit. My primary goal for this round is to increase my skills with Python.

**Link to work:**
- GitHub to the auto-boring-stuff repo: https://github.com/veroanalytic/auto-boring-stuff.git
