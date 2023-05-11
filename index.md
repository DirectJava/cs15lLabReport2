PART 1:
Here is my code for StringServer:
![image](https://user-images.githubusercontent.com/122843554/235336281-593d9000-763d-49df-bdfe-819120e01660.png)
Inside the class, Handler2, the method that I have is "handleRequest", which takes in a path such as "/", "add-message", or "add-message?s=<string>" to produce the webpage that displays the string I put in the path. Relevant arguments are any strings from a single character to a big long sentence and the only relevant field here is the "String phrase = ' ' ", which helps take in any string. The vaule of any relevant fields of the class change by adding a string into "add-message?s=<string>" to produce another string on the screen. Here's one example: 
  ![image](https://github.com/DirectJava/cs15lLabReport2/assets/122843554/7a01566d-fad2-4f16-8746-711cc3cc78c0)

  
  In the second image below, the method is exactly the same as the prevous example. Relevant arguments to both the class and methods are still numbers, strings, and characters. As long as I add the message "add-message" in the URL, the webpage will still display the string that I typed. The values can be changed by either inserting another string or something else that will print out an error message. Here's another example:
  ![image](https://user-images.githubusercontent.com/122843554/235337207-81baa448-8209-48a1-a1fe-6b9e506ae287.png)

PART 2: 
After the committing the code, this photo shown below are before and after the changes...
![image](https://user-images.githubusercontent.com/122843554/233913329-760ab345-b06c-40b2-b855-8a430a7a1bf3.png)

With that in mind, a failure-inducing input would be any list that has been inputted into the test cases. The reason that input is failure-inducing is because once I insert the list of numbers, the ArrayExamples.java file has one of the variables that is not correctly stated in the method body. So when the loop runs, the list of numbers that are added to the test are stated as a new variable and then there's another variable that pops up which confuses java and is unable to produce the desired results. As far is non-inducing failures go, there are none for this code.
![image](https://user-images.githubusercontent.com/122843554/233916032-e83eb766-b7b6-4f14-afd6-9f612f0c8498.png)

The picture above is the output I received before editing the code. The symptom here is one of the elements in the testReversedAgain class has one of the actual outputs different compared to the expected output. Once my groupmates and I discussed and worked on the issue, it turns out that one of the methods used for ArrayExamples has its variable that's either undeclared, in wrong orientation, or was missing some crucial parts to complete teh body. After we fixed the code, all of the tests ended up passing.

PART 3: Labs from week 2 or 3 is very interesting and exciting because I learned about the cool implementation technique from the website that I didn't know before. Basically, the website is created by the codes and URLs being meshed together to form a website that works together. For example, I changed the query or path in order to increment the number that is shown on the website. 
