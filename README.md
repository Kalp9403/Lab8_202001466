## <pre>             IT 314 - Software Engineering </pre> 
### Lab 8 : Unit Testing with JUnit
### Student Name : Kalp Pandya
### Student ID: 202001466

<h3 align="center" >
  <b>Lab Exercises</b>
</h3>
<br/>
1. I created a new Java project in eclipse with name <b>Lab8</b> and created a package inside it with name <b>mypackage</b>

![image](https://user-images.githubusercontent.com/77287821/233029175-367810f4-956d-4a8a-ac9f-5209d9547f90.png)


2.I then created a class with name <b>Boa</b> and then added the given code inside it.
![image](https://user-images.githubusercontent.com/77287821/233030808-22d5c9ee-5336-4a22-b503-c97158144143.png)


3.Then I created a JUnit test file for the Boa Class with name <b>BoaTest</b>
![image](https://user-images.githubusercontent.com/77287821/233030951-9f13aac1-a60b-4216-b357-a9147e9707f1.png)

4.Then I modified the setUp method to initialize the variables.

5.Then I also implemented tests for the given two functions <b>testIsHealthy()</b> and <b>testFitsInCage()</b>.
  ![image](https://user-images.githubusercontent.com/77287821/233031388-2d7ed35f-0fef-4c43-8c3d-75ab98c73559.png)
For testing thee fitsInCage() function, there is no need to write tests for both jen and ken objects as the function is same for both and the output of test cases depends only whether the given lenght is greater than,less than or equal to actual length of object.The behaviour will be similar in both cases.

6.Then I ran the Junit test file and all the tests are passed.There are no red bars in the output.
![image](https://user-images.githubusercontent.com/77287821/233036803-be8c0390-ef86-4d73-9277-4e85555f43bd.png)
It can be seen that 2 out of 2 test cases have been passed. 

7.Then I added a new method to the Boa class with name <b>lenghtInInches()</b> to get the length in inches.
![image](https://user-images.githubusercontent.com/77287821/233037826-f7459d32-e1ca-4a32-98b3-5d99617ddfc6.png)
As the length of the Boa is given in feet, to convert it into inches, I had multiplied length with 12 and returned the value.

8.Then I wrote another test case for this new method and ran the 3 test cases together. 
![image](https://user-images.githubusercontent.com/77287821/233038501-4963e088-a680-4d34-a138-b7264e6ddbde.png)

Thus, test cases have been written for the given Boa class and all the three methods have been tested with required Junit test cases.
