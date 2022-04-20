# Class-10-Blog
Describe one thing you're learning in class today. Why do you think it will be important in your future web development journey?

    I learned that classes make "new data types" and a constructor is "what do you want to execute when the object is created".



Can you offer a use case for the new arrow => function syntax?

     Function expressions are best for object methods; arrow methods are best for callbacks or methods like, map, reduce, or forEach.



How does this new syntax differ from the older function signature, function nameFunc(){}, both in style and functionality?



Explain the differences on the usage of foo between function foo() {} and const foo = function() {}

    Function foo() {} is the Normal Function or Function Declaration and var foo = function() {} is a Anonymous Function or Expression Function or in simple words, it many also be illustrated that it is variable inside which a function is wrapped up.



What advantage is there for using the arrow syntax for a method in a constructor?
    The arrow syntax reduced lots of code and makes the mode more readable.



Can you give an example for destructuring an object or an array?
    Destructuring Objects
    Destructuring is especially useful for unpacking data from objects. For example, let’s say we have a movie app filled with movie objects like so:

If we want to pull individual values from this object, we could do this:

const title = movie.title
const country = movie.country

Or, using the destructuring syntax we could do this instead:
const {title, country} = movie
console.log(title, country) // 'Star Wars', 'United States'
JavaScript will take the variables declared on the left-hand side and match them to the corresponding values within the chosen destructured object!


Explain Closure in your own words. How do you think you can use it? Don't forget to read more blogs and videos about this subject.
    A closure is a function having access to the parent scope, even after the parent function has closed.
