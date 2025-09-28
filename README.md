# Library Management System – Use Case Exam Question

## Client Software Requirement
You are tasked with developing a software application for managing a **library system**.  
The system will handle multiple types of items that can be borrowed by users.  
Each item will have unique characteristics, but all items will share common behaviors such as **borrowing**, **returning**, and **checking availability**.  

### Item Types
- **Book**
- **Magazine**
- **DVD**

---

## Functional Requirements
1. **Borrowing Items**  
   Each item should have a method that allows users to borrow it.

2. **Returning Items**  
   Each item should have a method to return it.

3. **Check Availability**  
   Each item should have a method to check if it is currently available.

4. **Late Fee Calculation**  
   Different items should have different methods to calculate late fees.

5. **Overdue Notification**  
   The system should notify users when an item is overdue.

---

## Design Requirements (OOP Principles)
1. **Inheritance**  
   Define common behaviors for all items in the library system.

2. **Encapsulation**  
   Hide internal details such as borrower information and due dates.

3. **Polymorphism**  
   Allow different items to implement methods differently (e.g., late fee calculation).

4. **Abstraction**  
   Use abstract classes or interfaces to define a common structure for item types.

---

## Your Task
Design the system using **Object-Oriented Programming (OOP)** principles and provide the following:

1. **Class Diagram (UML)**  
   Show all classes and their relationships (inheritance, interfaces, etc.).

2. **Code Implementation**  
   Implement the required classes and methods in Python (or another OOP language).

3. **Explanation**  
   Clearly explain how each OOP pillar (**Inheritance, Encapsulation, Polymorphism, Abstraction**) is applied in your solution.
