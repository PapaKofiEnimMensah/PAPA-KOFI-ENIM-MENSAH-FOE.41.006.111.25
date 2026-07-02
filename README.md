# Inheritance - UMaT Management System

This repository contains Python examples and a Jupyter Notebook demonstrating **Object-Oriented Programming (OOP) inheritance** concepts, based on Week 4 of EL 162/234 (Object-Oriented Programming) by Dr. Matthew Cobbinah.

## 📚 Contents
- **Simple Inheritance**  
- **Inheriting Attributes**  
- **Extending Parent Classes**  
- **Constructor Inheritance (explicit & super)**  
- **Method Overriding**  
- **Calling Parent Methods with super()**  
- **Method Resolution Order (MRO)**  
- **UMaT Management System Case Study**  

## 🏫 Case Study: UMaT Management System
The case study models different types of people on campus:
- **Person**: Base class with common attributes (name, age).  
- **Student**: Inherits from Person, adds student ID and `enroll_course()`.  
- **Lecturer**: Inherits from Person, adds employee ID and `teach_course()`.  

Demonstrates:
- Use of `super()` for cleaner initialization.  
- Method overriding (`display_info()` in Student).  
- Unique methods for each role. 
