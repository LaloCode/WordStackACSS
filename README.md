This is the starter code for the WordStack workshop. 
This workshop is part of the Applied CS with Android course:

http://g.co/cswithandroid

Check the website for detailed instructions on how to implement this activity.

Version 1.0

# Word Stack Activity
My solution for the Word Stack activity in the Applied CS Skills Google course, had a lot of fun with this one and learned a lot!

## Rules
The app for this workshop is a single-user word game called WordStack. The idea of the game is to try to separate out two words
of the same length whose letters have been scrambled (but the order of the letters has been preserved).

For example, 'cat' and 'dog' might get scrambled in many ways but 'c' will always come before 'a' and 'a' will always come before 't'. Similarly, 'd' will always come before 'o' and 'o' will always come before 'g'. So we get permutations like:

    cdaotg
    cadogt
    catdog
    dogcat
    dcoagt
    ...

But never 'actdog' ('a' is out of order) or 'coatdg' ('o' out of order).

## TO DO
Implement one of the suggested extensions in the future
