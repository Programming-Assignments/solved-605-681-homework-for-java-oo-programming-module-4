Download Link: https://assignmentchef.com/product/solved-605-681-homework-for-java-oo-programming-module-4
<br>
<strong>Assignment:</strong>

This homework will have you create some Java classes and subclasses.

Each concrete class must have a toString() method defines that prints out its attributes. These objects are not desgined to be the most efficient or consistent objects (some throw exceptions for bad arguments, some go to defaults). Instead, I want to see how you handle different input cases. Don’t try to over-analyze the problems. Even if I don’t specify how to handle bad input, <em>use common sense</em>! You should always handle bad input somehow, do not throw runtime exceptions! Don’t assign values to a variable that don’t make sense ANYWHERE in your code (example, don’t set the number of engines on an aircraft to a negative number!).

Make sure that attributes are not publicly accessible!

Also, you need to review the <u>Coding Guidelines</u> which explain acceptable ways to format your source code. Please use these in all future homeworks.

<strong>Step 1</strong>:Define an interface Contact

<ol>

 <li>That has the following methods (notice that some are for type String, this means you’ll have to convert them to int’s)</li>

 <li>getLength/setLength (int)</li>

 <li>getSpeed/setSpeed (int)</li>

 <li>setSpeed(String)</li>

 <li>getName/setName (String)</li>

 <li>getType/setType (String) (This is an arbitrary string label for anything of class Contact)</li>

</ol>

<strong>Step 2</strong>: Define an abstract class Ship that implements the Contact Interface. The methods in contact should be defined (no longer abstract, but they can be overriden later on).

<strong>Step 3</strong>: Define a class Destroyer that subclasses Ship

<ol>

 <li>that has the following attributes and get/set methods. Supports int and String setNumberMissiles() arguments. If the String argument of setNumberMissiles() encounters a parsing error, set the numberMissiles to 2.</li>

 <li>numberMissile</li>

</ol>

<table width="768">

 <tbody>

  <tr>

   <td width="643">1 of 1</td>

   <td width="125">9/14/18, 11:08 PM</td>

  </tr>

 </tbody>

</table>

<strong>Step 4</strong>: Define a class Submarine that subclasses Ship

<ol>

 <li>that has the following attributes and get/set methods. Supports int and String setNumberTorpedos() arguments. If the String argument of setNumberTorpedos() encounters a parsing error, set the numberTorpedos to 2</li>

 <li>numberTorpedos</li>

</ol>

<strong>Step 5</strong>: Define an abstract class Aircraft that implements the Contact Interface. This class should also contain a getAltitude/setAltitude(int) method.

<strong>Step 6</strong>: Define a class P3 that extends the Aircraft abstract class

<ol>

 <li>That has the following attributes and get/set methods. Not string method is necessary for this one, just handle integers for the accessor (get) and modifier (set) methods.</li>

 <li>numberEngines</li>

</ol>

<strong>Step 7</strong>: In a test class:,

<ol>

 <li>Create 2 Destroyers</li>

 <li>Create 2 Submarines</li>

 <li>Create 2 P3s</li>

 <li>Make a collection of Destroyers (you select the type of Collection)</li>

 <li>Make a collection of Submarines (you select the type)</li>

 <li>Make a collection that holds all Ships</li>

 <li>Make a collection that holds all Contacts</li>

</ol>

You get to pick the names and values for the classes above.

<strong>Step 8</strong>: Print out the list of Contacts to System.out.println(). You should override the toString() method to return something “meaningful” for each class. Again, no hard requirements, just use a little common sense (i.e. print out more than the name).

Note: Use defensive programming whenever you can, for example, none of your methods should let the user set the number of items to a negative number.

You can choose what the constructors set these parameters to in your classes (they can be defaults or you can provide them). Typically, you try to exercise your code as much as possible in a test case so try a bit of each.

In the Test class, again, you can choose what values you wish to assign to the test cases.

Also, in your test class, you should exercise your execption handling case for the submarine by setting the number of torpedoes in one of your submarine classes to the string “Foo”.


