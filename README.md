# Kottans frontend course

 ## **Task 0**

Learning these materials helped me to systematize my knowledge about Git and GitHub.
Before that I've learned them through watching disjointed screencasts, googling and reading manuals.
Sarah's 'concept map' really helps me to understand it better.

Also performing tasks forced me to learn some new commands. Even not only from this materials,
such as: `git commit --amend`, `git rebase --interactive HEAD~n`, `git push --force`, etc.  
_upd from "GitHub & Collaboration" course: rebase is bad while collaborating when you've already 
pushed the commits you want to rebase._  

Git and GitHub are very powerful developer tools.

 ## **Task 1**

- [Linux Command Line Basics (screenshot)](/task_1/Linux_Command_Line_Basics.png)
- [Configuring Linux Web Servers (screenshot)](/task_1/Configuring_Linux_Web_Servers.png)
- [Networking for Web Developers (screenshot)](/task_1/Networking_for_Web_Developers.png)

I think more then 90% of information in these courses was totally new for me.

- [HTTP: The Protocol Every Web Developer Must Know - Part 1](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)

_new:_ list of status codes in server responds  
_surprised:_ that 'The request and response messages are mostly the same, except for the first line and message headers'  
_to use:_ at least one of the named server-side frameworks  

- [HTTP: The Protocol Every Web Developer Must Know - Part 2](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155)

_new:_ Identification and Authentication  
_surprised:_ persistent and parallel connections which are default in HTTP/1.1  
_to use:_ Cache Control Headers 

 ## **Task 2**

- [Version Control with Git (screenshot)](task_2/Version_Control_with_Git.png)

This course better explains Git. Especially branching, merging and undoing changes.  
PS: And a funny phrase to my vocabulary - _"easy-peasy"_ :P  

- [GitHub & Collaboration (screenshot)](task_2/GitHub_n_Collaboration.png)

From this course I've got better explanation of how tricky the `git rebase` command is. And what is the order of a collaboration.  

 ## **Task 3**

- [HTML and CSS Syntax (screenshot)](task_3/HTML_and_CSS_Syntax.png)

I'm glad that I've already passed most of one of the proposed extra materials - [htmlacademy (screenshot)](task_3/htmlacademy.png)  

 ## **Task 4**

- [Responsive Web Design Fundamentals (screenshot)](task_4/Responsive_Web_Design_Fundamentals.png)

_new:_ responsive patterns  
_surprised:_ responsive images and optimization  
_to use:_ flexbox  

 ## **Task 5**

- [Intro to JavaScript (screenshot)](task_5/Intro_to_JavaScript.png)

_new:_ the difference between arguments and parameter of a function  
_surprised:_ hoisting variables and functions to the top of a scope  
_to use:_ convention for naming variables and properties  

 ## **Task 6**

- [Object-Oriented JavaScript (screenshot)](task_6/Object-Oriented_JavaScript.png)

_new:_ good explanation of `this`: _only the moment of call time influences how 
the parameter this will get bound!_  
by using a `new` keyword, function is going to run in a special mode called _Constructor Mode_
Which adds two lines at the beginning and at the end:  
```javascript
var Constructor = function(arg) {
    (this = Object.create(Constructor.prototype);)
    ...
    (return this;)
}
```
_surprised:_ I was surprised that it is widely accepted bad technique 
binding prototypes by running 
```javascript
Subclass.prototype = new Superclass()
``` 
instead of 
```javascript
Subclass.prototype = Object.create(Superclass.prototype)
``` 
_to use:_ pseudoclassical pattern in object-oriented JavaScript  

- frontend-nanodegree-arcade-game [repo](https://github.com/val-fom/frontend-nanodegree-arcade-game), 
[demo](https://val-fom.github.io/frontend-nanodegree-arcade-game/)  

 ## **Task 7**

- [Offline Web Applications (screenshot)](task_7/Offline_Web_Applications.png)

_new:_ Service worker, IndexedDB, Cache - all this was new for me. Also I had a good practice with Promises.  
_surprised:_ how many instruments on a browser side a developer has for improving user experience.  
_to use:_ Offline First approach, for sure.  
