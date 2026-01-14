# assignment-answers

 Section 0: Candidate Details

Full Name: Abhishek Goswami  
Email Address: abhishekgoswami8791@gmail.com 
College / Company Name: Dewan VS Institute of Engineering & Technology 
GitHub Profile URL: https://github.com/abhishekgo87
Internship Batch / Group Name:  Mern Stack Developer / Mern and Pern fullstack Internship 


 Section 1 Git & GitHub

 1. Difference between Git and GitHub ?

Git is a distributed version control system used to track code changes locally on a computer.  
GitHub is a cloud-based platform that hosts Git repositories and helps developers collaborate, share code, and manage projects online.



 2. Explain git clone, git pull, and git fetch
    
git clone: Creates a local copy of a remote repository.
git pull: Fetches changes from the remote repository and merges them into the current branch.
git fetch: Downloads changes from the remote repository but does not merge them automatically.


3. What is a merge conflict and how do you resolve it?
   
A merge conflict occurs when Git cannot automatically merge changes because the same lines of code were modified differently.  
To resolve it, we manually edit the conflicting files, choose the correct changes, remove conflict markers, and then commit the resolved version.



 4. Difference between git merge and git rebase ?
    
git merge combines branches and creates a new merge commit.
git rebase moves commits from one branch onto another, creating a linear and cleaner commit history.



 5. What is .gitignore and why is it important?
     
.gitignore is a file that tells Git which files or folders should not be tracked.  



6. GitHub Repository link for this assessment
    
https://github.com/abhishekgo87/assignment-answers



 Section 2: MySQL & PostgreSQL

 1. Difference between MySQL and PostgreSQL ?
    
MySQL is a popular relational database mainly used for web applications and is known for its speed and simplicity.  
PostgreSQL is an advanced relational database that supports complex queries, custom data types, and follows SQL standards more strictly.



 2. What is a primary key and a foreign key?
    
A primary key is a column that uniquely identifies each record in a table and cannot contain NULL values.  
A foreign key is a column that creates a relationship between two tables by referring to the primary key of another table.



 3. Difference between WHERE and HAVING clause ?
    
The WHERE clause is used to filter rows before grouping the data.  
The HAVING clause is used to filter groups after the GROUP BY operation.



 4. Difference between DELETE and TRUNCATE ?
    
DELETE removes selected rows from a table and can be rolled back if used with a transaction.  
TRUNCATE removes all rows from a table quickly and cannot be rolled back.



 5. What is database normalization?
     
Database normalization is the process of organizing data into multiple related tables to reduce redundancy and improve data integrity.



6. Explain INNER JOIN, LEFT JOIN, and RIGHT JOIN
    
 INNER JOIN returns only the matching records from both tables.
 LEFT JOIN returns all records from the left table and matching records from the right table.
 RIGHT JOIN returns all records from the right table and matching records from the left table.

Section 3: React Fundamentals


1. What is React and why is it used?
   
React is a JavaScript library used to build user interfaces, especially single-page applications. It helps in creating reusable components and makes the UI fast and interactive by efficiently updating only the required parts of the page.

2. Difference between state and props
   
State is used to store data that can change inside a component and is managed by the component itself.
Props are used to pass data from a parent component to a child component and are read-only.

3. What are React hooks?
   
React hooks are special functions that allow functional components to use features like state and lifecycle methods. Hooks make the code cleaner and reduce the need for class components.

4. Explain useEffect with an example
   
useEffect is a React hook used to perform side effects such as data fetching, updating the DOM, or setting timers. It runs after the component renders.




Section 4: TypeScript Basics

1. What is TypeScript and why is it used?

   TypeScript is a superset of JavaScript that adds static typing. It helps developers catch errors at compile time, improves code readability, and makes large applications easier to maintain.

2. Difference between any and unknown
   
   The any type disables type checking and allows any operation without errors.
   The unknown type is safer because it requires type checking before performing operations on the value.

3. What are interfaces in TypeScript?
   
   Interfaces are used to define the structure of an object. They help ensure that an object follows a specific shape, which improves consistency and type safety in the code.

4. What is type inference?
   
   Type inference is a feature where TypeScript automatically determines the data type of a variable based on the value assigned to it, without explicitly specifying the type.

5. Explain optional and readonly properties

   Optional properties are marked with ? and may or may not be present in an object.
   Readonly properties cannot be changed after the object is created.

6. Share your TypeScript code or GitHub link

   https://github.com/abhishekgo87/frontent-learning/tree/master/next-js/first

 



Section 5: General Web Development

1. What is a REST API?
   
   A REST API is a way for a client and a server to communicate with each other using HTTP requests. It is commonly used in web applications to send and receive data in a simple and structured manner.

2. Difference between PUT and PATCH
   
   PUT is used when we want to update the complete data of a resource.
   PATCH is used when only a small part of the data needs to be updated instead of the whole resource.

3. What is CORS?
   
   CORS  is a browser security feature that controls whether a website can access resources from another domain. It helps protect users from unauthorized or harmful requests.

4. Difference between SQL and NoSQL databases
   
   SQL databases store data in tables with fixed schemas and are best suited for structured data.
   NoSQL databases are more flexible, do not rely on fixed tables, and are commonly used for large or changing datasets.

5. Explain MVC architecture
    
   MVC is a design pattern that helps organize application code.
   The Model manages data and logic, the View is responsible for displaying the user interface, and the Controller handles user actions and connects the Model with the View.



