Download Link: https://assignmentchef.com/product/solved-cs2028-lab-4-inheritance-polymorphism-and-abstract-classes
<br>
The objective of this Lab is to examine Inheritance, Polymorphism and Abstract classes.

<strong>Task 1:  </strong>Create a base class that will be used as the basis for the remainder of the lab.

<ol>

 <li>Create a new project. You can name this whatever you like.</li>

 <li>Design a class to abstractly model games. You may want to read the entire assignment before starting this task.

  <ol>

   <li>Include at least 2 attributes along with getters and setters for the attributes.</li>

   <li>Create a default constructor and an overload constructor allowing you to set values for all attributes.</li>

   <li>Define a virtual function called Play that prints out “Let’s play”. Define a non-virtual function called Winner that prints out the string “Not Yet”.</li>

   <li>Create the implementation code for the above functions as required.</li>

  </ol></li>

 <li>Include in the submission how each member will be available in derived classes (i.e. not available, available if not overridden, etc…). Complete this before moving on to task 2.</li>

</ol>




<strong>Task 2:  </strong>Create 2 classes that inherit from this class.

<ol>

 <li>Create a class for board game and video game that inherits from Game.</li>

 <li>Board game should have the following features:

  <ol>

   <li>Play should be defined as printing out “Role the dice.”</li>

   <li>Winner should be defined as printing out “Dancing time.”</li>

   <li>Add 1 additional attribute to the board game class. Include a getter and setter.</li>

  </ol></li>

 <li>Video game should have the following features:

  <ol>

   <li>Play should be defined as printing out “Mash the buttons.”</li>

   <li>Winner should be defined as printing out “Winner music”</li>

   <li>Add 1 additional attribute for the video game class (different from the board game class). Include a getter and setter.</li>

  </ol></li>

 <li>Include in the submission what version of the derived class members will be available in instances of the derived class and in instances of the derived class declared as the base class type. Complete this before moving on to task 3.</li>

</ol>

<strong>Task 3:  </strong>Test the classes.

<ol>

 <li>Create a program that tests the classes.

  <ol>

   <li>Prompt the user for which class to create and values to set the attributes for that class. Include the option to create a board game or video game as a game.  This may look like:</li>

  </ol></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="432">Press 1 for an instance of game.Press 2 for an instance of board game.Press 3 for an instance of video game.Press 4 for an instance of a board game declared as a gamePress 5 for an instance of a video game declared as a game</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Call the “Play” and “Winner” functions from the instance created in step a.</li>

 <li>Create a function outside of classes that accepts a game as a parameter. This function should call the Play and Winner functions of the input parameter.</li>

 <li>Call the function from step c.</li>

 <li>Ask the user if they wish to continue. If so, loop to step a.</li>

</ol>

<ol start="2">

 <li>Use your test program to test all member functions and ensure the class is working correctly.</li>

 <li>Include in the lab report a screen shot(s) of the output of a test. Include a discussion of how the actual results compared with the expected results from Task 2.</li>

</ol>


