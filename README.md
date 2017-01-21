# Week1 weekend homework
For your weekend homework, please choose one of the built in functions from the list below. Explain what the function does, provide at least one example of the use of the function and be prepared to present this topic on Monday.

```zip
type
sorted (bonus question: what is the difference between sort and sorted?) 
slice
setattr and getattr
ord
char
set
map
iter
```
In addition, as a group, please answer the following questions:
```What is a function? What is a method? What is the difference (if any) between a function and a method?
```

FAQs:
1. Can I choose more than one topic?
Yes! But you must choose at least one.

2. Do setattr and getattr count as one topic?
Yes.

3. What do we do after we answer the group question?
Pick a representative to present it on Monday.

4. If I get picked as the group representative, do I still have to pick a function to explain?
Yes.

5. How do I pick which topic I want to do?
```
import random

topics=set()
while len(topics) != 10:
	topics.add(random.choice(dir(globals()['__builtins__'])))
```
(This is actually a joke, don't literally do this. I mean you can, but you can just pick whichever topic(s) you'd like)

6. How long does the presentation have to be?
It’s a 5 minute or less presentation. You don’t have to present exactly five minutes worth of material but we’re capping it at 5 minutes to try to get you in the habit of explaining yourself succinctly.

7. What do I do if I have questions?
Ask! Or slack any of the TAs or Billy

TL;DR - HW is to choose and explain a built in function from the list provided. Get together as a group and answer the questions about functions and methods. Be ready to explain your chosen topic(s) on Monday.
