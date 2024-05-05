## Lab Assignment 6 Dependency Inversion
The NEU Library offers a variety of resources, including books, theses, capstones, internet access, journals, and newspapers.

Currently, the Student object has methods like borrowBook(), borrowJournal() with a parameter of title, which directly depend on specific resource types.

To adhere to the Dependency Inversion Principle (DIP) and ensure flexibility for future changes (such as introducing audio books or e-journals), we need to refactor the program while maintaining SOLID principles. The goal is to create a robust system that can seamlessly accommodate new resource types in the future.

Your solution should not violate other SOLID principles.

## UML DIAGRAM 
![image](https://github.com/frenchMontajes/Lab-Assignment-7/assets/130640700/53802fd1-d2cb-4574-841c-829a55efe2fd)