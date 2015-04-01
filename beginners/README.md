# Learning JavaScript Study Group at Delphic

These are the files needed for the JS Study Group. The curriculum for this group is based off of the "How to Learn JavaScript Properly" blog post on [http://javascriptissexy.com](javascriptissexy.com).

## Prerequisites

* A basic knowledge of HTML / CSS

## Resources

* Create an account on [Cloud9](https://c9.io/), follow instructions for [Setting Up Your Workspace](#setting-up-your-workspace)
* Create an account on [CodeAcademy](http://www.codeacademy.com)
* Use Google Chrome or Firefox
* [Meetup Assignments](#meetup-assignments)

## An Important Message
To get the most of this study guide, type out code examples that you find in the book in your browser console to see first-hand what it does. You can also try to modify the code and see what the results you get.

## <a id="#setting-up-your-workspace"></a>Setting Up Your Workspace

## <a id="#meetup-assignments"></a>Meetup Assignments

**Note**- **We will be meeting every other week.**

**For each meetup:**
* If needed, complete assignments in your cloud9 workspace.
* Make note of something you found interesting or you didn't understand to discuss with the group.

### Meetup 1

**Making a Website with HTML and CSS (if applicable); Read Intro to JavaScript**

1. Codecademy.com: If you do not already know HTML and CSS, complete the [Web Fundamentals](http://www.codecademy.com/tracks/web) Track on Codecademy.
2. Codecademy.com: Then follow the [Make a Website](http://www.codecademy.com/skills/make-a-website) track to make your first little website, using what you learned above.
3. *Beginning JavaScript*: Read Chapter 1 (Introduction to JavaScript and the Web) and Chapter 2 (Data Types and Variables).


### Weeks 3 & 4 - April 30th

1. *Beginning JavaScript*: Read Chapter 3 (Decisions, Loops, and Functions).
2. Codecademy.com: Work through the [JavaScript Track](http://www.codecademy.com/tracks/javascript) on Codecademy. Specifically, work through these sections: "Introduction to JavaScript," "Functions," "‘For' Loops in JavaScript," "‘While' Loops in JavaScript," and "Control Flow."
3. *Beginning JavaScript*: Read Chapter 4 (Common Mistakes, Debugging, and Error Handling).


### Weeks 5 & 6 - May 7th

**Learn JavaScript Objects, the Browser Object Model (BOM), and Events; Learn jQuery**

1. *Beginning JavaScript*: Read Chapter 5 (JavaScript — An Object- Based Language).
2. JavaScriptIsSexy.com: Read the article, [JavaScript Objects in Detail](http://javascriptissexy.com/javascript-objects-in-detail/)
3. Codecademy.com: Work through the last three sections of the Codecademy JavaScript track: "Data Structures," "Objects 1," and "Objects 2."


### Weeks 7 & 8 - May 14th

1. *Beginning JavaScript*: Read Chapter 6 (Programming the Browser).
2. *Beginning JavaScript*: Read Chapter 15 (JavaScript Frameworks), and stop just after you complete this section: "Digging Deeper Into jQuery".
3. Codecademy.com: Work through the entire [jQuery Track](http://www.codecademy.com/tracks/jquery) on Codecademy.

### Weeks 9 & 10 - May 28th

**HTML Forms and Frames; JavaScript Strings; Build Your First Interactive Website**

1. *Beginning JavaScript*: Read Chapter 7 (HTML Forms: Interacting with the User).
2. *Beginning JavaScript*: Read Chapter 8 (Windows and Frames).
3. *Beginning JavaScript*: Read Chapter 9 (String Manipulation).
4. *Beginning JavaScript*: Read Chapter 10 (Date, Time, and Timers).
5. *Beginning JavaScript*: Read Chapter 11 (Storing Information: Cookies).
6. Codecademy.com: Now, make your first cool website. Work through the entire [Make an Interactive Website](http://www.codecademy.com/skills/make-an-interactive-website) track on Codecademy.


### Weeks 11 & 12 - June 11th

**JavaScript "this," Variable Scope, and Hoisting, the DOM, JavaScript XML, and AJAX**

1. JavaScriptIsSexy.com: Read the post [JavaScript Variable Scope and Hoisting Explained](http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/)
2. JavaScriptIsSexy.com: Read the post [Understand JavaScript's "this" With Clarity, and Master It](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)
3. *Beginning JavaScript*: Read Chapter 12 (Dynamic HTML and the W3C Document Object Model).
4. *Beginning JavaScript*: Read Chapter 14 (Ajax).


### Week 13 & 14 - June 25th FINAL WEEKS OF WORK!!!!

**Build a Real-World JavaScript Quiz Application**

At this juncture, you have learned enough to build a solid JavaScript web application. Don't proceed any further until you can successfully build this application I describe below. Don't be afraid to ask questions on Stack Overflow, and do reread sections of the book to properly understand the concepts.

You are building a JavaScript quiz web application (you will use HTML and CSS as well) that will function as follows:

* It is a simple quiz that has radio button choices, and it will show the quiz taker his or her score upon completion.
* The quiz can show any number of questions and any number of choices.
* Tally the user's score and display the final score on the last page. The last page will only show the score, so remove the last question.
* Use an array to store all the questions. Each question, along with its choices and correct answer, should be stored in an object. The array of questions should look similar to this (Notice that only one question is in this example array; you will add many questions):

var allQuestions = [{question: "Who is Prime Minister of the United Kingdom?", choices: ["David Cameron", "Gordon Brown", "Winston Churchill", "Tony Blair"], correctAnswer:0}];

* Dynamically (with document.getElementById or jQuery) remove the current question and add the next question, when the user clicks the "Next" button. The Next button will be the only button to navigate this version of the quiz.
* You can ask for help in the comments below or preferably on Stack Overflow. You will likely to get a prompt and accurate answer on Stack Overflow.


### Final Meetup - July 9th

1. Go over final reading / assignments
2. Study Group Celebration Postmortem!!!!
3. Discuss Pros and Cons of the Group