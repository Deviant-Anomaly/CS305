# CS305
* Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?


  Artemis Financial is a consulting company that assists others in setting up financial plans. Their goal was to modernize security on their existing application, address current security vulnerabilities and mitigate appropriately.

  
* What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely?

  
  I believe I did well when it came to the certificate generation and the implementing a checksum, as I noticed on my ending dependency check that many of the certificate and validation issues I saw the first time were no longer present. It is important to think of security when you start working and throughout because a secure application will save a lot of time and money if you mitigate risks before they have a chance to happen. You spend less time and money implementing security measures in the beginning than you would later on after having to recover from an attack.


* What value does software security add to a company’s overall well-being?

  
  Software security now can definitely be a large factor in working with a company. You want to make sure whoever you are doing electronic business with is not going to leak your identifying information or financial information. A company that has good software security is seen as more trustworthy, and the clients working with that company are satisfied, maintaining Artemis' reputation as a valuable company. 


* Which part of the vulnerability assessment was challenging or helpful to you?


  I think the biggest challenge for me what sorting through the dependency checks for false positives. It can be very overwhelming to look at and is pretty time consuming when you aren't completely sure if a certain vulnerability was false.

  
* How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?


  I added a plug-in for the OWASP dependency check to the pom.xml file, which will automatically update newly introduced vulnerabilities when the scanner is run. In the future, I plan to use this in my own projects to implement SAST.


* How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?


  I made sure there were no errors in the code so the project was able to run as intended. After refactoring, I ran another dependency check post-build to make sure no new problems were added to the project due to my input.

  
* What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  Learning security basics is definitely a good skill to have, I did really enjoy learning how to improve upon an existing program and how to find issues within a program. This would be a valuable skill to show employers as it shows I have experience working with legacy programs, and the value to myself is now knowing how to screen my own projects for security vulnerabilities.
