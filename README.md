# The-Last-"Asshole"-Sucker 
## Yes, that's what it said its name is.
### A chat bot based on reddit comments, slow to respond and difficult to hold a conversion with.

```
You: hi
Bot:snitch.
You: cringe
Bot:Chuck Norris can breach a gap.
You: cat
Bot:horse
You: she liked it
Bot:Did somebody say [π](http://hardnphirm.wordpress.com/2007/05/07/5/)?
You: what's your name
Bot:"Asshole."
Bot:The Last Sucker
You: what's your gender
Bot:"Asshole."
Bot:The Last Sucker
```
<br>
<br>
<br>
# Credits
This chatbot uses a small subset of the [comments made available by /u/Stuck_In_the_Matrix](https://www.reddit.com/r/datasets/comments/3bxlg7/i_have_every_publicly_available_reddit_comment) as it's dataset.
Specifcally all the reddit comments for the month of October 2007. The chatbot is quite slow, taking up to a minute to respond on my i3 processor.
<br>
<br>
It works by finding the similarity between the text given to it and all the comments in it's dataset.
It then finds the most similar comment that has replies and prints out the highest rated reply.
The larger the dataset the better the replies, but longer the response time.
<br>
# How To Use
Run it using 
```
python3 The_Last_Sucker.py
```
