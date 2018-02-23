---
layout: post
title:      "Object Orienated programming"
date:       2018-02-22 22:44:12 -0500
permalink:  object_orienated_programming
---


Some people may wonder what is Object oriented programming? Why do we use it, and how do classes work in it? Also how do objects work in Ruby and Javascript? 
So to start what is OOP? It is a way of programming that makes code easier to understand. Rather than worrying about the logic and actions required to do something we can work with objects. 
So what is an Object? An object is either user or predetermined code that does or defines an action. Allowing the user to create objects that execute an action the user wishes to get done. Some languages allowing the creation of objects easier than others. 
One OOP that I have been working with a lot is Javascript in this language pretty much everything is an object. Even classes which is a new concept to emerge in Javascript is nothing but a object with properties that are either defined or come predefined. To declare a class in JS6 you can declare a class and inside you can declare methods that the class has. Here is an example.

```
class Dog {
	constructor(name,age,breed){
		this.name = name;
		this.age = age;
		this.breed = breed;
	}
	bark(){
		return "woof!"
	}
}
```
In JS6 you directly declare a class if you wish for it to take any parameters you must put a constructor that takes the parameters and sets them equal to properties so the object has new properties, and you can also declare methods within the class giving the class different methods to be called upon. At the end of the day though in Javascript a class is just a glorified Object and fancy function. To instantiate a new object for the object Dog or class Dog you declare it as

`var variable = new Dog('name', 'age', 'breed')`

Here is how you create new instances of the object Dog. So you can just declare a variable and set it equal to a 'new' instance of the object and that copy's its properties to the new object you declared, because an variable is just an object. 


Another OOP language that I've worked with is Ruby. Now Ruby is more Object oriented than Javascript one way is classes mean more and are an actual object vs Javascript when it's more of just a function/variable object.  To create a class in Ruby you type 

`"class "Name" 
end"`

it is as simple as that to create a class and adding methods to the class is as easy as typing "def "name"".  To call it you would type Name.name and it would output the action you defined. To instantiate a new instance of Name you would simply say variable = Name.new("parameters if any") doing this copies the methods of the class to the new instance of it called variable. 

I have mentioned instance of class objects and you may be wondering what it is. An instance is a seperate object that simply copies the original properties and method of the class to a new object therefore a new instance of the object class. So an instance is not a class but a copy of the class a in a way its own object.

I hope all this information can be helpful and look forward to sharing more as i learn.

