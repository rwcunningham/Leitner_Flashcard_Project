Presentation Video: https://youtu.be/tM6zGvhNMnE

Leitner Flashcard System: A Smarter Way to Learn

Flashcards are a great way to memorize large sets of information. But how do your organize your flashcards to learn most optimally? One solution is to use something called a "Leitner System" to arrange your flashcards in an order that optimizes learning. Leitner Systems use "spaced repetition" to quiz you at optimal intervals. 

https://en.wikipedia.org/wiki/Leitner_system

----

This program allows you to import cards, go through them in quiz mode and organizes it according to the rules of the Leitner System. It also generates the study plan that tells you which boxes to study on which days. 

How to use:
To use the system, you will need to place 2 files in your directory

Create your cards in a JSON file structured like this: 

[
{
    "question": "lata",
    "answer": "tin",
    "box_location": 1
},
{
    "question": "deletrear",
    "answer": "spell",
    "box_location": 1
}
]

Create a user settings csv file like this:

username,num_boxes,plan_len_days,current_day
Robobob,4,31,2

You can set the username, number of boxes you want to use, the number of days you have to study, and how many days into your study plan you are

Now launch the program and follow the menu options. You can view your study plan, you can add or delete cards, edit user settings in addition to running the quiz mode.

Besides that, it should be pretty striaghtforward to use if you just follow the menu. 

