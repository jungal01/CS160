Problem Solving with Algorithms and Data Structures
===================================================


Setting up Your Environment
---------------------------

* Since we are in Olin 112 please bring  your laptops to class
* Make sure you register for cs160fall16 at http://interactivepython.org
* Download and install the latest `PyCharm <https://www.jetbrains.com/pycharm/download/>`_ on your computer
* Python's `unittest documentation <https://docs.python.org/3.5/library/unittest.html>`_

Weekly Goals
------------

* Week of August 31

  * Python Review -- Shakespear and his Monkeys
  * Write a new MSDie class which can represent more than numbers on each side.  *Hint:* The constructor should take a list of values as a parameter.
  * A pythonic way of protecting data ``properties``
  * Add a Cup Class that can roll multiple dice.
  * Algorithms for Random Numbers

    * algorithm 1: middle-Square
    * algorithm 2: Multiplicative Linear Congruential Generators
    * algorithm 3: Fibbonacci

  * What makes for a good pseudorandom number generator?

  * Assignment:  Do practice1 for Friday
  * Assignment:  Do practice2 for Monday


* Week of Sept 5

  * Discussion and finishing up Random lab -- Hand in on Wednesday
  * Introduce Algorithm Analysis ideas

* Week of

  * Questions on part 1 of the crazy 8 assignment

    * Making attributes read only
    * See here for `visualization:  <http://www.pythontutor.com/visualize.html#code=import+random%0Aimport+collections%0A%0Arandom.seed(42%29%0A%0Aclass+MSDie%3A%0A++++def+__init__(self,+num_sides%29%3A%0A++++++++self.num_sides+%3D+num_sides%0A++++++++self.__value+%3D+random.randrange(num_sides%29+%2B+1%0A%0A++++def+getValue(self%29%3A%0A++++++++return+self.__value%0A%0A++++def+roll(self%29%3A%0A++++++++self.__value+%3D+random.randrange(self.num_sides%29+%2B+1%0A++++++++return+self.__value%0A%0A%0AmyDie+%3D+MSDie(6%29%0A%23print(myDie.__value%29%0Aprint(myDie.getValue(%29%29%0AmyDie.__value+%3D+9%0Aprint(myDie.__value%29%0A%23print(myDie.getValue(%29%29&mode=display&origin=opt-frontend.js&cumulative=false&heapPrimitives=false&textReferences=false&py=3&rawInputLstJSON=%5B%5D&curInstr=15>`_
    * A "Fancy" python trick for making simple read only classes

  * Finish up finding the longest sequence
  * Inheritance
  * Discuss and start part 2 of Crazy 8's
  * More on Big-O analysis  -- Read Chapter on Analysis

* Week of

  * Anagram Detection Algorithms And Big-O
  * Stacks -- Read Stacks, Queues and Lists
  * Friday - Brad is at SIGCSE in Memphis
  * Be ready to try your Player classes Monday March 7


* Week of

  * Introducing the Queue
  * Airplane boarding simulator
  * Crazy 8's Tournament?
  * Project 2:  Word Ladders  (Queues of Stacks!!?!)
  * Lists and their implementation

* Week of

  * Finish linked list implementation
  * Compare our implementation with Python's implementation
  * Wednesday exam

    * Chapters 1 - 3
    * Classes - implementing a simple class
    * Big O notation and algorithm analysis
    * Queues
    * Stacks
    * Linked lists


* Week of

    * Compare Python implementation of lists with our linked lists
    * Recursion - Read Recursion through the Three Laws section
    * Recursive Trees


* Week of

    * The end of the world, with towers of Hanoi
    * State Space Problems and recursion
    * Start the `water jug project <https://github.com/bnmnetp/CS160/blob/master/08_Recursion/waterjug.rst>`_ - Due
    * Searching algorithms

* Week of

    * Hash Functions and making hash tables
    * Sorting
    * You are responsible for the entire sorting and searching chapter

* Week of

    * Finish sorting
    * Introduction to Trees   -- Read the sections on tree representations
    * Compression with Trees
    * Guest lecture on Wednesday

* Week of

    * Tree Traversals
    * Finish up compression example
    * Binary Search Trees, add nodes


* Week of

    * Binary Search Trees, deleting a node
    * Introduction to Graphs and Graph representations
    * Friday is Research Symposium Day

* Week of

    * Breadth First Search
    * Depth First Search
    * Dijkstra's Algorithm
    * Review
