# CS 61B Spring 2026 OH Simulation

Hi! Welcome to the CS 61B OH simulation! During this stage, we
want to see how you help students in a 1-1 office hours style
situation.

# What to Expect 

During the 10-15 minute simulation, one of the interviewers will
be acting as a student in office hours who requires assistance on
a hash maps assignment. The student will have a partial
implementation, so your goal is identify where the student is
struggling and assist them! The goal is not to find the most bugs,
but to help the student learn as much as they can.

There are no required materials for you to prepare other than
thinking about the questions in the email. But, if you
would like to
get an idea of what the interview might look like, the skeleton
code for the assignment is provided in this repository and an
assignment spec is given below.

During the interview, you
will be working on this simulation with
your interviewer's computer, but here are instructions if you
would like to try the assignment locally on your own computer!
Let us know if you have any questions by replying to the email
(cs61b@berkeley.edu).

# Tips 

During this interview, we're looking to see how you interact with
and assist students! A couple of tips to keep in mind:
- The goal is to best help the student with what they're
struggling on. Keep in mind what their major misconceptions
seem to be!
- Equip students with skills that they can keep for the f
uture.
- For example, taking a student's computer and fixing their
errors won't help them learn!
- Treat the student how you
would like to be treated when you
ask for help!

# Setting Up the Assignment 
1. Check that you have Git and Java installed on your
computer. If not, follow the instructions in this section [here](https://fa25.datastructur.es/homeworks/hw01/)!
2. We will be using the IntelliJ IDE during this exercise. You can
install IntelliJ through [these instructions](https://www.jetbrains.com/idea/download/?section=mac).
3. Clone the `library-fa25` repository with the instructions
listed [here](https://fa25.datastructur.es/homeworks/hw01/#task-5-cloning-repositories).
4. Clone this repository.
5. Open the project in IntelliJ and follow the Assignment
Workflow steps to prepare your setup.
6. At this point, you should be ready to work on the
assignment! To quickly check, you should see green buttons
in the test files under the tests directory. Clicking on these
buttons should allow you to run the tests!

# Spec

In this assignment, you’ll work in `RedBlackTree.java`.

## File Structure 

`RedBlackTree.java`: This file ontains three main operations to ensure a balanced tree, rotateRight, rotateLeft, and colorFlip. 

`TestRedBlackTree.java`: This file contains tests. You do
not need to modify this file, but understanding how some of the
tests work could be usef
ul!

# Background Information

*The instructions are a summarized version of this semester's [HW 10](https://fa25.datastructur.es/homeworks/hw10/)! We are following Left-Leaning Red Black Trees as discussed in [lecture](https://docs.google.com/presentation/d/1eITMp5V1yqEpfzRzK7cdD2Dq9GWdxEDd3kdrm5Zgm8k/edit?slide=id.g213d1cb6cd3_0_146#slide=id.g213d1cb6cd3_0_146). Note that though the edges are colored in lecture, we are representing nodes as colored here for a simpler implementation.*

*There is also a RBTreeNode provided within `RedBlackTree.java` that tracks the color of each node, T item, and its correspond left and right RBTreeNodes.* 


