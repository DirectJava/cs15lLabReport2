PART 1:
Note: This one image may be temporary, more will be coming soon as I will work things out.
![image](https://user-images.githubusercontent.com/122843554/234185001-c3f28a2d-bafd-47be-a29f-800b79131edf.png)
The methods in my code are called handler2, because there's already already another handler in use for NumberServer.java. That method does the job of keeping track of the URL and prints the result if there are any attempts of trying to insert a new message.

The relevant arguments to those methods are any type of strings or just no strings at all. The values of any relevant fields in the class would be any strings that is typed out.

Unfortunately, I was unable to answer this question becasue I am having trouble modifying the String Server2, which helps the website builds its URL. This will all be changed when things are sorted out.

PART 2: 
After the committing the code, this photo shown below are before and after the changes...
![image](https://user-images.githubusercontent.com/122843554/233913329-760ab345-b06c-40b2-b855-8a430a7a1bf3.png)

With that in mind, a failure-inducing input would be any list that has been inputted into the test cases. The reason that input is failure-inducing is because once I insert the list of numbers, the ArrayExamples.java file has one of the variables that is not correctly stated in the method body. So when the loop runs, the list of numbers that are added to the test are stated as a new variable and then there's another variable that pops up which confuses java and is unable to produce the desired results. As far is non-inducing failures go, there are none for this code.
![image](https://user-images.githubusercontent.com/122843554/233916032-e83eb766-b7b6-4f14-afd6-9f612f0c8498.png)

The picture above is the output I received before editing the code. The symptom here is one of the elements in the testReversedAgain class has one of the actual outputs different compared to the expected output. Once my groupmates and I discussed and worked on the issue, it turns out that one of the methods used for ArrayExamples has its variable that's either undeclared, in wrong orientation, or was missing some crucial parts to complete teh body. After we fixed the code, all of the tests ended up passing.

PART 3: Labs from week 2 or 3 is very interesting and exciting because I learned about the cool implementation technique from the website that I didn't know before. Basically, the website is created by the codes and URLs being meshed together to form a website that works together. For example, I changed the query or path in order to increment the number that is shown on the website. 
