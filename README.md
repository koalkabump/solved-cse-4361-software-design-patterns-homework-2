Download Link: https://assignmentchef.com/product/solved-cse-4361-software-design-patterns-homework-2
<br>
5/5 - (1 vote)

<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">1 Introduction</span>

This individual homework requires the student to modify homework 1 design and implementation. The en- hancement requirements are as follows:

2

3

1.

2. 3.

The software shall have a Hello-World button in addition to the Box and Circle buttons. The behavior of this button is the same as the Box and Circle buttons except that it draws a “Hello world” string in the drawing area. You decide the font and font size of the string.

The software shall support undo and redo. This requires you to add another two buttons to the button jpanel. You are required to apply the command pattern to support this functionality.

Apply the adapter pattern, if you had not done so in homework 1, to convert the various Java listener interfaces that you use to the interface of the controller. The Java listener interfaces may include an action listener’s actionPerformed(…) method, or a mouse listener’s mousePressed(…) method, etc. That is, each of the five buttons will have its own action listener, and the mouse pressed event will also have its own mouse listener. These listeners will adapt their respective listener interfaces to the respective methods of the controller.

You may have done so for homework 1. If so, you just reuse your solution and apply it in homework 2.

What Needs to be Done and Submit?

This homework requires the student to do the following:

1. 2.

3. 4. 5.

Modify your domain model according to the new enhancement requirements.

Extend your design sequence diagram (DSD) to accommodate the new requirements and apply the com- mand and adapter patterns. The patterns you applied in homework 1 must still be applied in homework 2. Use UML stereotype or UML note to show the patterns applied.

Modify your design class diagram, which must be derived from the modified design sequence diagram and modified domain model. Use UML stereotype or UML note to show the patterns applied.

Modify your Java implementation to support the new requirements and patterns applied. Provide com- ments in your code to show all of the patterns applied.

Compile and run your application. Arbitrarily add a few circles, boxes, and/or hello-world strings, as well as click the Undo and Redo buttons in between the drawing actions to test your software. Produce and submit screen shots to show the working of your software.

How To Submit

To be announced by the TA before the deadline.