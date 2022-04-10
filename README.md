# Assignment-operator-
in here I can write about my project info righ?
reviewed 1x time
Hi I’m Pilotaskar. In this document we’ll review: JavaScript essentials by Lawrence (udemy course)

CourseLink:https://www.udemy.com/course/javascript-essentials/learn/lecture/4275898#overview

Road map:
This color mark is Theme
This color mark is I don’t understand
This color mark is I understand but not expert
This color mark is I know this as an expert


Introduction
1. Introduction
We’ll learn what is the object
Manipulating object and date is important
2. What is Javascript?
Let’s look at the history of this language
This language created by Brandon Aik in 1995
It was created in 10 days
At that moment the development code name was “Mocha”
Brandon liked this language because it’s simple and easy to use
That’s why JavaScript is easy to use today
Then it was called Livescript
Then it was renamed to JavaScript
Then Microsoft called JScript
ECmaScript EC5 2009
Now EC6
You can visit ECmascript website to get some info https://www.ecma-international.org/


3. How Javascript Works
Your computer understands machine code 010101
Browser has three main program
The first program is the DOM pausa. This takes our HTML code and converts it into a structured page that we can visually see
The next program is CSS pasa. It will take our CCS code and then and then it will make sure our document layout rendered correctly
We say for HTML and CCS together “Rendering Engine”
And also we have JavaScript engine for that brauser (for ex: firefox says for it Spider Monkey, Google chrome has V8 Engine, Safari has Nitro, EA has Chakra )
These all shows our code understandable to client side
 Engine JIT Compilers (Just in Time) 010101
.js is human readable code, but computer take is as a 01010

4. Javascript Console
Console.log is a simple text interface. 
Command prompt or terminal also called console window.
We like  consoles as a programmer. Because it has input and output.
So does JavaScript have its own console. Yes.
This console allows you to type JavaScript commands. JIT takes it and returns back to the console's human-readable format.
And also the console is very good for debugging.
you can see errors etc.
https://avelx.co.uk/ this is Lawrence's website.
How to go to the console window.

5. Objects in Javascript
People think objects are very hard. But it is very-very simple. 
Your program only contains Nouns, Adjectives and Verbs. That’s it.
World is also an object oriented world.
Each object has -properties or nouns.
Let’s take an apple for example.
Apple has nouns like width: height: color: weight: but not enough to describe apple.
You also need adjectives as well.“red”.These called properties. 
Next we also need verbs. Verbs are performing actions . This is a function.Ex eat: throw: 
When a function within an object it is still a function but we call it a Method. 
When we say Method this is an object containing a function. That’s it. That’s how easy.
If you don’t understand objects you can’t understand any programming language.
Next level is the embedded object. It’s just an object that contains an object. { {} }
So you can call it a hierarchy of objects. Because we have a subobject and the main parent object. 
Hierarchy is objects within objects. 
Encapsulation is just grouping data together.





6. Javascript Syntax 
Syntax is a program that is written.
For example HTML has its own style. That is syntax.
And What is API? API is “Application Programming Interface”
Every language has its own API. What is it?
An API is simply a collection of functions and also properties. 
Let’s have a look at this. We have a window in JavaScript. It has many functions. These are set up by JIT. This is the JavaScript API. 
JQuery API. 
The JIT compiler also has its own API. Otherway you cannot write a program. 
And then you can create your own API. Own library. 
Embedded JQuery API



Basic Syntax
7. Primitive Data
Quotation marks in JavaScript “”
Backslash with quotation mark \”
Mix and match ‘“”’, “‘’”
Numbertype whole integers and float
Boolean (without quotation mark)
Null and undefined are also Primitive types. Don’t forget it. 
Null is completely empty. 
Undefined doesn't assign anything assigned.
NaN is also a primitive data type, don't forget it. 

8. Variables, Constants & Assignment
Create a new variable var and assign and give a value
var name; name is one box. It’s a memory address. It’s a symbol. The name is variable. 
var name = “Askarbek”. = is assign. Now Askarbek is assigned to the box (name). 
Try to keep your box name. Don’t put a number, symbol and spaces. 
Don’t create a variable with a number or string. Just keep it simple. And don’t put a space between.
You can create a blank variable box and it returns undefined. Later on you can reassign it .Undefined is waiting for your variable to be assigned. Undefined is just an empty box. 
JavaScript is a loosely typed language. For example you can create a string and then you can change that string to the num, object, array or boolean etc. 
Variable constant. You can’t create a variable with an empty box with const. You can’t change the const later. This is good for security reasons. 
You can’t assign a new value. 



9. Arithmetic Operators & BODMAS
Operator & javascript operators from mdn
BODMAS (PEDMAS)
Complex expression math.pow() (Teksherip kordum. Githubga da attym.https://github.com/pilotaskar/Math.pow-.git )
Modules division %




10. Assignment Operators (Arithmetic type operators)
Assignment operator +=, -=, *=, /= 
Assignment operator %=, **= https://github.com/pilotaskar/Assignment-operator-.git
Two separate strings with plus operators
Polymorphism, 10 + Askar = “10Askar”
String +=


11. Code Editors & Debugging
Code editor “Brackets”
Basic markup and script tag
Write JavaScript inline
Console log and Console window
Why does the script stay on bottom
You can log out with console log string, number, boolean, null
console log variable
Console log all together (“string”, 10.11, true, false, null, num);

12. Functions or Subroutines
Parameters and argument
Subroutine

13. Objects & Arrays
Object
Properties
Method
Array
Zero index
Car object
Key name 
Property
Array literal

14. Embedding Objects & Arrays
Car hierarchy
Embed object in to the array
Multiple piston objects
Arrays can embed object
Method in object
Method in Array

15. Member Access
Member access with dot syntax
Drive method
Computed member access

16. Computed Member Access
Computed member access
Run execution contact
Write a statement inside of array brackets
You can use algebra in math
Dynamically fetch array 3
Access with [“make”]
car[“engine”][“pistons”][1][“maker”];
envoke subroutine
Target a variable
car [“en” + “gine”]
Mix and match with dot

17. Member Creation, Assignment & Deletion
Delete object for string
car.make = “ford”;
car.make += 200;
car[“speed”] *= 2;
car.engine = { newengine: “new”}
car.drive = “drive”;
car.model = “v60”;
car.color; => undefined; car.color = “red”; is good
stop method
car.engine.stop = function() {return “stop engine;”};
car.color = null;
delete car.color:
delete car.stop;

18. Array Modification
array[0] = “new string”;
array[0] += “concat”;
array[5] = “new string”;
array [20] = 2020; x14 null
array[“test”] = “test”; array.test2 = “test2”;
array.length
array.shift(); delete
array.pop(); delete
array.unshift( “string”, 20, 20.22, function(){}, {}, [] ); add
array.push(200, 300, “string” );
array.splice (2 , 2); delete
array.splice (1, 0, “hello”, “world”, 200); add
array.splice(2, 2, “world200”); replace

19. Callable Objects
callable object  inside object
Envoke callable object
embed object inside of object
var obj = { embedded: {} };
function concat( name )
You can embed arrays inside of arrays object inside of arrays
callable object nested inside of another
Invoke like concat
return concat(fullname);
name({firstname: “Lawrence”, lastname: “Turton”})
return fullname.firstname + fullname.lastname;
var obj = function(){}
name(function(){})
name( function() { return “embed”;});
return fullname;
console.log(name(function() { return “embed”;}))
executive by parenthesis embed


20. Memory Hoisting
Hoisting is lift up
Looking symbol name
Looking for other type of symbol name
It takes the symbol name and lift up (hoist)
It is going to line by line
console.log(myName, printName())hasn’t created yet
var myName; undefined 
console.log (a); var a = 100;
console.log (a, embed()); var a = 100; function embed () { return “hello”;}

21. Scope & Closures
engine.headGasket.pots[0]; (scope)
function have scope
callable object add() embedded function
return 100
runExpression(); 100
a + b also 100
but the callable object is different
Execution Stack
You have two execution contact runExpression(); and add();
First runExpression created a=10
second add(); function does not delete a=10. it leaves. it is closure
add() function also creates b=90
so return a + b is 100
Garbage Collection
runExpression(); b is not defined 
it does not run add execution contact
it create a = 10;
add(); is just added to stack
But all we have in the table is a=10
b has not been created
it just pushes onto the stack add() function
symbol b hasn't been created
Therefore we get this error
First run this execution contact and then run add() execution contact
it just adds to the stack 
for example two add(90) add(20)
runExpression 100 30 
Execution Stack or Main Thread
Outer execution Environment

22. Inferred Globals & Scope
Window object is the highest level object
They can access anywhere from the script
Globally accessible object called engine
invoking add();
conclude where this memory pointer is
first look inside 
If not found look outside
It will find it here
RunExpression(); it will find engine
What happens if console.log(a);
What happens if var engine = “String Engine”
It didn’t go up.
But globally the engine is still here
We didn’t change the global engine
If we created a window object and runExpression callable object
we can also change the global scope engine
very-very careful just create engine = “New String”
You can create with var or const and it will not change the global
What will happen if we write test = “New String”
 clobbered the global scope
point test;


23. This Context
This Look at this
Pointing something
However we have this word set up on memory
First of all this by default pointing window object
And then it can change 
So how it will change
Let’s look at property first of all
object.prop;
It’s again a window object;
array[0] this keyword again
the callable object allows you to change this
For example we have a method: 
object.method now not window object
array[1]();
global(); just pointing the window object
global(); standard function subroutine
global.call( object )
call is object in JavaScript
You can also can assign this = global forex’
This execution contact will be this
global.call( object ) runs this code in the console
Now we changed this which 
new global(); now this interesting
the new keyword coming first
What it will do
new says I literally want a blank object
new global();
you can use call method
global(); is by default window object
object.embed.method();
object.embed.method.call( array );
new object.embed.method();
console.log (‘from global’, this)
function sub(){console.log(‘from sub, this’)}
sub();


24. Constructors
constructor Function(){}
Why do you need constructor
function Apple() {return object;}
We are creating many objects from this construction
That’s why we have constructor function
Let’s make capital letter constructor function
function Apple (x, y, color, score)
and this execution contact
with constructor function you use the new keyword
new Apple();
we want new context 
this.x = x;
this.y = y;
this.color = color;
this.score = score;
return this;
but it returns this by default. You can not write
Let’s add some arguments
new Apple(10, 20, “red”, 200);
But there is little bit issue
var apple1 = {}
now you can start making more copies
we created one function but each instance is unique
One construction house, one factory


25. Prototype
We don’t need the same verbs like eat(), throw()
It’s a just copy
We need to attach a prototype object in our constructor
JavaScript automatically searches prototype
Every apple object linked that prototype object
 Now I have just one eat() method one throw() method
This saves a lot of memory
JavaScript is very good using prototype
Prototype are sharable objects
What about this, this is also so important
It will connect automatically with prototype
Apple1.eat();


26. Constructors with Prototype
Let’s look at our existing project
Let’s put them on prototype objects
This is our constructor function
You can see the prototype object in console window object
Apple.prototype = {}
apple1.eat();
apple2.eat();
apple3.eat();
I can also change the prototype now. Apple.prototype.eat = function() {return “new apple eaten!!!!”}
but now all the prototypes are the same like “new apple eaten!!!”
Now I want to use “This”
This is contractual words and it needs contact
I’m gonna change the eat() method
eat : function () {return this;}
apple2.eat();
how is this method being invoked
This is so important to understand this contact
is this a contraction with prototype or apple2?
Answer is it is pointing apple2
Because that object is initial invocation
Now this contact goes up instant contact
I can change unique level
They use a prototype and this 
if you wanna take a look apple1
you can only modify prototypes of the construction themselves
Dynamically linked prototype you can actually access
eat: “New Prop” It's a little bit of a problem
because it goes and finds an eat symbol and stops there so it does not  go even prototype


Comparison & Conditional Execution
27. Comparison Operators
10 == 10; true
10 == 100; false 
“hello” == “hello”; true;
“hello” == “Hello”; false;
10.5 == 10.5; true
10.5 == 10.43; false
null == null; true
undefined == undefined; true
true == true; true
false == false; true
false == true; false
NaN is primitive data type
NaN == NaN; false
polymorphism 10 + “10”; “1010”
null == undefined; true
10 == “10”; true
null === undefined false
10 === “10”; false
null != null; false
null != undefined; false
10 != 100; true
10 != “10”; false
10 !== “10”; true
null !== undefined; true
10 > 100; false
10 > 1; true
“hello” > “hello”; false
 “hellooo” > “hello”; true
10 >= 10; true 
10 < 100; true
10 < 1; false
10 <= 10; true

28. If Statements

29. For & For In Loop's
for (var index in classRegister){console.log( classRegister [index])}

30. Let ES6
let & const
let is respect that block
const also respect the scope
I don’t want my symbol globally accessible
let and const respect to the private but var didn’t
var respect only scope of function but it doesn’t respect for for loops and if statement


DOM Manipulation
31. Understanding the Document Object Model
Document object model
window object is also advocate
nodes are like leaves of the tree
document also object like window object
child nodes
document.childNodes[1].childNodes[2]; this is not a good way to access
we’ll use CCS selectors
32. Targeting DOM Element’s
document; is a global variable
document.getElementByTagName(‘p’);
document.getElementById(‘hello’);
dir (document.getElementById(“hello”)); it shows me as an object
document.getElementsByClassName(‘pClass’);
What about CCS selectors
document.querySelectorAll(‘#hello’);
Queryselectorall is always return array
document.querySelectorAll(‘.pClass’);
document.querySelectorAll(‘#hello’, .pClass);
document.querySelectorAll(‘ p[data-content=”123”], body > h1.pClass > span ’);

33. Changing Element's Content's
Why script putting bottom
console.log(document.getElementById(‘hello’));
console.dir(document.getElementById(‘hello’));
(document.getElementById(‘hello’).innerText = “new world”;
(document.getElementById(‘hello’).innerText += “order”;
var pHello = document.getElementById(‘hello’);
why innerhtml and innertext
pHello.outerHTML = 
pHello.outerTEXT = 
document.querySelectorAll(‘h1 span’)



34. Changing Element Style's
var el = document.getElementById(‘style’);
el.style.backround = “blue”;
el.style.color = “white”;
el.width = “200px”;
el.style.cssText = “ backround: blue; color:white; width: 200px”;
el.style.cssText += “ height: 200px;”;
console.log(getComputedStyle (el));
javascript style is not a computed style
!important 

35. Event Handlers
Event listener
document.getelementByName(‘cars’);
All clicks begin with on
onclick = “console.log(‘you clicked me’)”
var select = document.getElementByName(‘cars’)[0];
select.onclick = function(event){} call back function
console.log(event);
select.addEventListener(‘click’, function (event));
select.removeEventListener(‘click’, symbolName);
call back function doesn’t need a name
ClickCallback(event)



36. Create & appendChild & insertBefore method's
var element = document.createElement(‘div’);
element.style.cssText = “width:200px; height:200px; background:blue;”;
element.onclick = function(){ alert (‘hello’);};
document.body.appendChild( element );
Let’s create 2 more div elements manually
So now we have three different divs
Can we do our div element that created by javascript before manual div 
var target = document.getElementById(‘yellow’);
document.body.insertBefore( element, target );

37. Final Project 
When I click to set button I want to run the function
function set(){ alert (‘clicked’);}
document.getElementById(‘set’).addEventListener(‘click’, set);
let  elements = document.getElementByName(‘cssProperty’); console.log(elements)
for (i = 0; i < elements.length; i++){console.log(i);}
console.log(elements[i].value)
console.log(elements[index].getAttribute(‘id’));
bul projecti maidalap chyk i zhakshylap uiron

Final Overbiew
38. Conclusion & Goodbye
39. Bonus Lecture: Discount Courses

