# PGR103-exam
This was the exam on Object Oriented Programming spring 2021. This was not a grade exam only pass or not pass because of COVID. I asked the lecturer and he said it would have been a A if it would have been graded (A-F)

##Background
An English gym teacher at a primary school in Norway has become very tired of not having control over
the sports equipment used in the teaching. She therefore plans to get this sorted out.
Initially, she has given priority to gaining control of balls and tennis rackets. These will be
constantly gone and they need some maintenance. Balls constantly need refilling of air, and
the table tennis rackets need to have the coating on the outside of the racket changed. It is planned to incorporate
several types of sports equipment eventually.
She has now given all balls and table tennis rackets a unique ID (drawn directly on the ball / racket). She
has also had some cabinets installed where these are to be stored. She has made a list (equipment.txt) that
contains information on all sports equipment (balls and table tennis rackets). Sports equipment in
the gym teacher's system has some common features:
- A unique id
- A location that indicates in which cabinet the ball / racket is to be stored
- Information about the equipment must be replaced (because it is damaged or lost)

For balls, she wants to store the type of ball in question (foot, hand, basketball or volleyball).
She also wants to know if the ball needs to be refilled with more air - that is, needs to be inflated.
For table tennis rackets, she wants to know if the racket needs to change coating.
As you can see from the inventory list (equipment.txt), all this information is now registered in a file.
An explanation of the contents of the file can be found in Appendix 1.

##Task 1
Create a class that is responsible for being able to read equipment information from a file. When reading from file it should
create objects that represent the balls and table tennis rackets. The class must include one
public method that can return the objects loaded from file. You have to figure out for yourself which classes you need
make to be able to represent the balls and the table tennis rackets. It is expected that you use inheritance.
You will need this method that returns the objects (read from file) in the next task. If you did not get
to create objects based on the information in the file, then you should create a new method that creates equipment objects without loading information from the file. In that case, keep your code where you tried to read from the file.

##Task 2
Write a few words about how you can test whether the method that returns the objects in problem 1 works
as intended.

##Task 3
Create a class that offers three public methods:
- printBallsNeedingMoreAir: The method should print information about which balls need
to be inflated.
- printEquipmentNeedingToBeReplaced: The method should print information about which equipment
which must be replaced.
- printTableTennisRacketsNeedingNewPad: The method should print which table tennis rackets
which must change coating.
The methods should use the objects read from file to perform their action. It is therefore expected that
you use the class you created in problem 1 to read in information about the equipment before the methods are called.

##Exercise 4
Create a program that tests whether the class you created in Exercise 3 works as intended. The program
shall call on all the three methods described in problem 3.
What to deliver
All source code in your project (ie all .java files).
A text document that answers task 2.
A screenshot of the result when you run your program (Exercise 4).

Good luck!
