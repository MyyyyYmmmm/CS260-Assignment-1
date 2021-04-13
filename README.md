# CS260-Assignment-1
C++ Programming 


Assignment 1 (C++ Programming)  
Yoshiko Murakami (X00503764)  
Linn-Benton Community College  
CS260  
April 12, 2021  





## **Assignment 1 details:**

1.	GitHub repo, create a folder for assignment1 and a README file in that folder,  
2.	In your README file (feel free to include labeled drawings!) explaining what a program could do to model a bag of marbles, with a list of properties (variables) and behaviors (methods), including at least:  
    1.	some way of representing marbles (what makes up a marble in this program?),  
    2.	a way to add new marbles into the bag (how do we interact with marbles and add them into the bag?),  
    3.	a way to remove a marble out of the bag (perhaps a random marble taken out of the bag?),  
    4.	a few ways that we could use to show that our implementation should be working correctly (tests),  
        (perhaps you start with an empty bag, put a marble in with some known values, then you pull the marble out and verify that it has the same values, perhaps you try to pull a marble out of an empty bag, perhaps you try to add 3 billion marbles... maybe you do not have to go that high or maybe your solution is smart enough to deal with this)  
3.	implement your bag of marbles in a program as simply as possible!
4.	test our implementation in a driver file with our tests (a driver file is just the file we would use to launchour program). 
Note: This assignment is intended to get you thinking about how simple your implementations could be, to make sure your programming environment is set up properly, and to get you thinking about how we store data in different structures.
5.      Submit a link to your repo to Moodle as a reminder to us to grade your work  







## **Assignment 1 (C++ Programming)**  

Let's consider this information, suppose that a person has a bag that can hold up to 1000000000 marbles. Secondly, suppose that person needs to add and take out marbles from the bag. In such a case, it is necessary to note that a bag of marble and marble can be perceived as real-life entities; therefore, classes can solve this problem. In C++, classes are vital, and they contribute immensely to Object-Oriented Programming (OOP). A class can be referred to as a user-defined data type, encompassing data member and member functions (Study Tonight, 2021). The former and the latter alludes to the variables and functions, respectively. Class instance creation assists in accessing these data members and the functions. One example of a class is a bird, and in this class, every bird is capable of flying and has a beak. In this example, flying and a beak are some of a bird class's behaviors and characteristics, respectively. 
Correspondingly, a class alludes to a blueprint used to define data members and member functions. These characteristics are common for every single object of a certain class (Study Tonight, 2021). It's not mandatory to define functions only within the class, but they also are defined outside a given class. In C++ programming, OOP features, such as inheritance and encapsulation, centers on the classes. A single program can have numerous objects of a given class (Toso & Resende, 2015). For the nonce, let's say that marble lacks behavior and has only properties. In this way, marble can be represented as a class or a structure. Even though a class and a structure are considered the same, the latter is utilized mostly to represent group-associated data. In this context, marble is utilized as a structure. From the provided problem, it is apparent that the bag encompasses several properties and behaviors. Following this development, a class can be used to implement the bag of marbles.  
  
At this moment, the marble bag contains up to 1000000000 elements. The number of these elements is great, and it is impossible to hold all these marbles. Therefore, the minimum number of marbles that the bag can contain is zero while the maximum is 1000000000. At the moment, it is better not to allot memory for 1000000000 elements. Then, the bag can enlarge to accommodate more marbles. This enlargement is implemented through a dynamic array. The dynamic array concept is underpinned by alteration of array size when the program is running (Savitch et al., 2015). In the sample code, the initial array is set to 3 for demonstration; however, an individual can alter that value. The following is the Labelled diagram designed by sketchpad online tool:  
  
 ![Assignment1](https://user-images.githubusercontent.com/59652655/114492321-3d102000-9bcd-11eb-8702-ca63bb88e780.png)
 
 

## References  
Savitch, W. J., Mock, K., Msanjila, S., & Muiche, L. (2015). Problem Solving with C++  
	Pearson.  
Study Tonight (2021). Introduction to C++ Classes and Objects   
	https://www.studytonight.com/cpp/class-and-objects.php  
Toso, R. F., & Resende, M. G. (2015). A C++ application programming interface for biased  
	random-key genetic algorithms. Optimization Methods and Software, 30(1), 81-93  


