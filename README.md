# Class and Prototype inheritance exercises in Javascript

* Create a class called `Person` which accepts the name of a person as a string, and his/her age as a number.
  * The `Person` class should have a method called `describe()` which returns a string with the following syntax: "name, age years old". 
  * So for example, if John is 19 years old then the function describe() of his object will return "John, 19 years old".
* Create another class object called` Teacher` derived from the `Person` class.
    * Implement a *static method* called `instruction()` which returns a string like: "How much teach would a teacher teach if a teacher could teach teach?"
    * Implement an *instance method* called `teach()` which receives a string called subject
      * It should print out a statement like: "Foo teaches subject bar"
