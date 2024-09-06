# Exercise List on Object-Oriented Programming, Inheritance, and Libraries in Python

## 1. Creating a Simple Class
Create a class called `Dog` with the attributes `name` and `age`. Access these attributes;

## 2. Class with Method
Create a class called `Car` with the attributes `manufacturer`, `model`, and `year`. Create a method that returns this information;

## 3. Simple Inheritance
Create a class `Vehicle` that has the attribute `year`. Then, create a derived class `Bicycle` that has a `run()` method to show the message `"The bike is running"`. Create an object/instance of type `Vehicle` and another of type `Bicycle`. What happens when you try to access the `year` attribute and the `run()` method in both cases? Why does this occur?;

## 4. Using `super()`
Create a class `Animal` that has the attribute `__weight` and a method `info()` that returns the animal's weight. Then, create a class `Dog` that inherits from `Animal`. The `Dog` class should have the attribute `__paws` and should override the `info()` method, returning the number of paws in addition to the weight. Use `super()` to call the parent class's method inside the `Dog` class;

## 5. Checking Object Type
Create an object of the `Dog` class and use the `type()` function to check the type of the object;

## 6. Checking Instance of Class
Create two classes: `Person` and `Student`, where `Student` inherits from `Person`. Create an instance of `Student` and verify if it is an instance of both `Student` and `Person` using `isinstance()`. Also use `issubclass()` with `Student` and `Person`;

## 7. Class Attributes and Methods
Check if the `list` class has the methods `append` and `drop`;

## 8. Using the `os` Module
List the directories of the previous folder from where the Python code is being executed;

## 9. Importing Numpy Modules
Implement a function that uses `numpy` to generate a matrix of random numbers and display their values;

## 10. Importing and Using Pandas
Implement a program that uses `pandas` to create a DataFrame with data from a list of dictionaries and display it;

## 11. Importing and Using Random
Create a program that uses the `random` module to generate a random integer between 1 and 100;

## 12. Using the `datetime` Module
Check what the date will be 10 days after the current code execution time;

## 13. Using the `re` Module
Remove all punctuation from a string using `re`;

## 14. Magic Method `__str__()`
Create a class `Book` with the attributes `title` and `author`. Override the `__str__()` method to return a formatted string when printing the object;

## 15. Multiple Inheritance
Create two classes `Animal` and `Aquatic`. Create a third class `Dolphin` that inherits from both and implements specific methods/attributes;

## 16. Using `dir()` to Check Attributes and Methods
Create an instance of any class and use the `dir()` function to list its methods and attributes;