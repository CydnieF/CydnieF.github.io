# **CS-499 ePortfolio**



## **Introduction**


   Hello, my name is Cydnie Fisher. I began my process of obtaining my bachelor’s in computer science from SNHU in June of 2023 and will complete it in December of 2024. This page serves to demonstrate how my understanding of software design and engineering, algorithms and data structure, and databases has increased during my time here at SNHU.  


## **Professional Self-Assessment**

   When I began my bachelor's in computer science I had very little knowledge regarding developing code and creating projects. SNHU has allowed me to become confident in my programming abilities by providing me with knowledge in the most commonly used programming languages and back-end and front-end development. This has allowed me to feel prepared to enter the workforce. Submitting assignments to my ePortfolio also allows me to begin my career journey with plenty of completed assignments that showcase my competency in programming. 
   
   While I completed my degree online, a collaborative environment was still fostered through the usage of discussion posts, where I would post my initial post, respond to some of my classmates, and read their responses to my post. These discussion posts often aligned with the topics used for the assignments, which would allow me to think about the topic at hand from the perspective of my classmates. While there wasn’t direct communication with stakeholders, every assignment came outlined with specific requirements that needed to be met, and feedback would be provided by the professor if these requirements weren’t met. This mimics communicating with stakeholders to determine program requirements and if those requirements have been met.
   
   I have also learned about how to communicate in a professional manner, software design and engineering, algorithms and data structures, databases, and security. My ability to communicate in a professional manner is evident in my code review where I analyze previous code and discuss how to improve it. It is also evident in this write-up where I discuss my growth and my enhancement process for all three categories. My understanding of software design and engineering is evident in my first enhancement where I demonstrate my knowledge in both Java and Python. My understanding of algorithms and data structures is evident in my second enhancement category where I increased the efficiency of my data structure. Finally, the third enhancement category showcases my understanding of databases and security where MongoDB was implemented as well as role-based access control. Overall, this write-up, my code review, and the three enhancement categories demonstrate a diverse understanding of the most important concepts in computer science. 

    
# **Code Review**
   In the following code review, I begin by analyzing the code that I previously wrote in a clear and professional manner. I discuss code functionality, what was done right or wrong, and how I will implement necessary changes to ensure I meet all of the required course outcomes. In doing so, I meet the following course criteria:
	 
   • Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts

[Code Review](https://youtu.be/h_LfBpZaTKY)

# **Enhancement One: Software Design and Engineering**

Artifact Description:

   The artifact I chose for the first enhancement category is the final project for IT145 Foundations in App Development. This artifact was written in Java in February of 2023 a search and rescue company, Grazioso Salvare. This application allows them to intake new animals, reserve animals for rescue missions, and print lists of animals based on animal type and reserve status. Once an animal is reserved, it can be sent out on a rescue mission to save humans from dangerous, and potentially life-threatening, situations. 

Why This Artifact Was Selected:

   This artifact was one of the first programs I completed during my bachelor’s degree. I feel that I have grown a lot as a developer since then, and enhancing this program was an excellent way to demonstrate this growth. This program showcases some of the essential concepts in programming: handling user input, storing data entered by the user, and accurately returning the data to the user. While it functions per the requests of the initial requirements, there was still plenty of room for improvement. This program lacked proper data validation and error handling, had redundant code, leftover comments and methods used for testing, and undescriptive comments. I also wanted to use this program to showcase my understanding of Java and Python by converting the program.
 
Artifact Improvement and Skills Showcased:

   The first enhancement I made was converting the program from Python to Java. This was done without losing any functionality, which demonstrates a mastery of both languages. I also implemented robust data validation and error handling, showcasing my ability to create a program that appropriately handles errors as they occur, without disrupting the program. This was done through the addition of helper functions used to verify that the correct values are entered by the user. I also removed redundant code through the use of helper functions that are called upon when needed, removed any unnecessary code, and enhanced the descriptiveness of the comments. These changes demonstrate my ability to create a scalable and easy to maintain program. 
   
Course Outcomes Met:

By completing this enhancement, I have met the following course outcomes:

   • Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science. 
   o Python is a widely known language with easy to understand syntax. Converting the program to Python broadens its accessibility and promotes an inclusive, collaborative environment. Removing unnecessary comments and adding more descriptive ones instead increases the readability of the code, making the program easier to understand, even for people with limited experience in coding. 
 
Reflecting on the Enhancement Process

   I began the enhancement process by converting the program from Python to Java. This gave me some difficulties due to the majority of my courses focusing on Java and C++. I found myself having to reference previous work to remind myself of proper Python Syntax. This was also the case when incorporating data validation and error handling. Utilizing helper functions to remove redundant code, removing unnecessary code, and enhancing the descriptiveness of the comments was straightforward and therefore did not cause any issues. 
 

### **Repository Link**

- [Enhancement One Repository](https://github.com/BrettSoden/EnhancementOne-Software-Design-and-Engineering)


# **Enhancement Two: Algorithms and Data Structures**

Artifact Description:

   The artifact I chose for the second enhancement category is the final project for IT145 Foundations in App Development. This artifact was written in Java in February of 2023 for a search and rescue company, Grazioso Salvare. This application allows them to intake new animals, reserve animals for rescue missions, and print lists of animals based on animal type and reserve status. Once an animal is reserved, it can be sent out on a rescue mission to save humans from dangerous, and potentially life-threatening, situations. I will continue to build off the work completed in the first enhancement category. 

Why This Artifact Was Selected:

   The original artifact showcases a basic understanding in data structures, with room for improvement. Animals and their perspective attributes are stored in an array list, which has a runtime complexity of O(n) when iterating through the array list to search for animals. Since this is commonly completed within the program, I wanted to decrease the runtime complexity. I also noticed that the original artifact did not take appropriate measures to ensure the same animal wasn’t added into the system more than once. If the animal shared the same name as another animal, it couldn’t be added into the system. This isn’t practical since animals don’t always have unique names.  
 
Artifact Improvement and Skills Showcased:

   The first enhancement I made was switching the data structure from an array list to a dictionary and implementing unique IDs. This unique ID is assigned to the animal as they are first entered into the system and can be used to find them when searching through the dictionary. These changes subsequentially reduce the runtime complexity when iterating through the data structure from O(n) to O(1), therefore increasing the efficiency of the program. This demonstrates an in-depth understanding of data structures and algorithms. I also reworked how duplicate animals were determined. Instead of the program assuming that if an animal shares the same name, it is the same animal, the program now compares all attributes. Lastly, I implemented a helper function that is called upon when reserving an animal previously unreserved in the system. This helper function ensures that if two animals of the same type share the same name, the intended animal is marked as reserved. 
 
Course Outcomes Met:

By completing this enhancement, I have met the following course outcomes:

   • Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices.  

   o Replacing the array lists with dictionaries, and incorporating unique IDs to search through the dictionary, decreased the runtime complexity from O(n) to O(1), and therefore increased the efficiency of the program using algorithmic principles. Incorporating a way for the program to ensure that the same animal can’t be added more than once increases data handling, following computer science practices. Furthermore, ensuring that the appropriate animal is reserved when multiple animals of the same animal type share the same name increases data handling. 
 
Reflecting on the Enhancement Process:

   I began the enhancement process by implementing dictionaries instead of array lists. This process was straightforward, but it did require me to rework how animals were added into the system and searched for. I then incorporated unique IDs, which required me to research how to do so automatically, without help from the user. I then moved on to implementing the helper function used to determine if an animal is already in the system. I initially compared all attributes, without realizing that comparing the unique IDs would result in all animals being deemed as new. This required me to rewrite the function so it would avoid comparing the unique IDs. When further testing my program, I discovered that if two animals shared the same name when reserving animals, the first animal found would be automatically reserved. To mitigate this, I altered the reserve animals function so that it would display all of the animals with the same name and allow the user to choose the appropriate animals. 


### **Repository Link**

- [Enhancement Two Repository](https://github.com/BrettSoden/EnhancementTwo-Algorithms-and-Data-Structure)


# **Enhancement Three: Databases**

Artifact Description:

   The artifact I chose for the first enhancement category is the final project for IT145 Foundations in App Development. This artifact was written in Java in February of 2023 for a search and rescue company, Grazioso Salvare. This application allows them to intake new animals, reserve animals for rescue missions, and print lists of animals based on animal type and reserve status. Once an animal is reserved, it can be sent out on a rescue mission to save humans from dangerous, and potentially life-threatening, situations. 

Why This Artifact Was Selected:

   The original artifact stored animals in array lists, which would clear their data once the program ended. This would be very inefficient for a company that would need to continually use this data. I chose this artifact so I could implement a database, which would continually store the animals, making the program significantly more useful. I also realized that the original program only implemented create and read functionality. I wanted to increase the usefulness of the program by also implementing update and delete functionality, completing CRUD. I also noticed that there was no security, so I wanted to implement role-based access control, which will ensure that only users with specific roles can alter the database. Lastly, when the data was output to the user, it was output as a list which is hard to navigate. I wanted to mitigate this by implementing a dashboard. 
 
Artifact Improvement and Skills Showcased:

   I began this enhancement process by implementing MongoDB and completing the rest of the CRUD functionality in a manner that allowed it to interact with MongoDB rather than a data structure. I closely followed the steps taken to implement MongoDB in my previous database class, CS340. While this was relatively straightforward, I initially ran into an issue where each time I ran the program, the data within the JSON file would be added back into the database, resulting in duplicate data. This was mitigated by ensuring that the program would check for duplicate data when importing data. Creating a functioning database with CRUD functionality showcases my understanding of databases. I then created a dashboard that can be used to better visualize and sort through data. This showcases my ability to use innovative techniques to increase the functionality of a program. Lastly, I implemented role-based access control to limit user functionality based on their role. This showcases my ability to increase the security of a program.
 
Course Outcomes Met:

By completing this enhancement, I have met the following course outcomes:

   • Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.

   o Using MongoDB instead of storing animals in an array list, and completing the implementation of CRUD functionality increases the value of my application. Animal data is now persistent once the program ends, and can now be updated or deleted as needed.
 
   o Utilizing a dashboard for data visualization allows the user to interact with the data in a more practical way. 
 
   • Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.

   o Security of the program has been enhanced by implementing role-based access control. This ensures users can only access the CRUD functionality that they have access to, inhibiting certain users from altering the data within the database. 	



### **Repository Link**

- [Enhancement Three Repository](https://github.com/BrettSoden/Enhancement-Three-Databases)

### **GitHub Pages Link**

- [CS-499 ePortfolio](https://brettsoden.github.io/)
