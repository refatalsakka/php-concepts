<h1 align="center">
<br>
  <a href="https://github.com/refatalsakka/php-concepts"><img src="https://github.com/refatalsakka/php-concepts/blob/main/php-concepts.webp" alt="Gguide to PHP concepts" width=200" /></a>
  <br>
  <br>
  PHP concepts, from basic to advanced.
  <br>
  <br>
</h1>

## Introduction <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/427/427735.png">

Welcome to the "PHP Concepts" repository, a comprehensive collection of essential PHP topics and concepts designed to deepen your understanding of the language. Inspired by the popular repository [33-js-concepts](https://github.com/leonardomso/33-js-concepts) by Leonardo Moura, this project follows the structured format pioneered by him. Our goal is to provide concise explanations and curated resources for mastering PHP development. Whether you're a novice seeking to grasp the fundamentals or an experienced developer looking to expand your knowledge, you'll find valuable articles and videos covering a wide range of PHP concepts. From basic data types and control structures to advanced topics like memory management and opcode optimization, each concept is explained in a clear and straightforward manner. Explore this repository to enhance your PHP skills and consider contributing to make it even better!

## Community <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/11511/11511262.png">
Feel free to contribute! This repository thrives on community involvement. Whether you have new articles and videos to share, spot errors that need fixing, or want to suggest improvements, your contributions are highly valued. Join us in making "PHP Concepts" the go-to resource for PHP developers worldwide. Let's learn and grow together <img align="center" width="20px" height="20px" src="https://cdn-icons-png.flaticon.com/512/7398/7398227.png">

## Table of Contents <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3079/3079998.png">
   
- [Basics and Foundations](#1-data-types-and-variables)
  - [1. Data Types and Variables](#1-data-types-and-variables)
  - [2. Control Structures (If, Loops)](#2-control-structures-if-loops)
  - [3. Functions and Scope](#3-functions-and-scope)
  - [4. Arrays and Array Functions](#4-arrays-and-array-functions)
  - [5. String Manipulation Functions](#5-string-manipulation-functions)
  - [6. Error Handling with Exceptions](#6-error-handling-with-exceptions)
- [Intermediate Concepts](#7-classes-and-objects)
  - [7. Classes and Objects](#7-classes-and-objects)
  - [8. Visibility (Public, Private, Protected)](#8-visibility-public-private-protected)
  - [9. Constructors and Destructors](#9-constructors-and-destructors)
  - [10. Inheritance](#10-inheritance)
  - [11. Interfaces](#11-interfaces)
  - [12. Abstract Classes](#12-abstract-classes)
  - [13. Traits](#13-traits)
  - [14. Static Methods and Properties](#14-static-methods-and-properties)
  - [15. Namespaces](#15-namespaces)
  - [16. Type Declarations](#16-type-declarations)
  - [17. Anonymous Functions and Closures](#17-anonymous-functions-and-closures)
  - [18. Type Hinting and Return Types](#18-type-hinting-and-return-types)
  - [19. Regular Expressions (PCRE)](#19-regular-expressions-pcre)
  - [20. Variable Handling Functions](#20-variable-handling-functions)
- [Advanced Features and Functional Programming](#21-generators)
  - [21. Generators](#21-generators)
  - [22. Magic Methods](#22-magic-methods)
  - [23. Late Static Bindings](#23-late-static-bindings)
  - [24. Reflection API](#24-reflection-api)
  - [25. Iterators](#25-iterators)
  - [26. Dependency Injection](#26-dependency-injection)
  - [27. Sessions and Cookies](#27-sessions-and-cookies)
  - [28. File Handling and Streams](#28-file-handling-and-streams)
  - [29. PHP Standard Recommendations (PSR)](#29-php-standard-recommendations-psr)
  - [30. Object Cloning and Serialization](#30-object-cloning-and-serialization)
- [PHP 8 Features and Modern Practices](#31-attribute-annotations-php-8)
  - [31. Attribute Annotations (PHP 8)](#31-attribute-annotations-php-8)
  - [32. Constructor Property Promotion (PHP 8)](#32-constructor-property-promotion-php-8)
  - [33. Union Types (PHP 8)](#33-union-types-php-8)
  - [34. Match Expressions (PHP 8)](#34-match-expressions-php-8)
  - [35. Nullsafe Operator (PHP 8)](#35-nullsafe-operator-php-8)
  - [36. Weak Maps (PHP 8)](#36-weak-maps-php-8)
  - [37. Named Arguments (PHP 8)](#37-named-arguments-php-8)
  - [38. Mixed Type (PHP 8)](#38-mixed-type-php-8)
  - [39. Enums (PHP 8.1)](#39-enums-php-81)
  - [40. Fibers (PHP 8.1)](#40-fibers-php-81)
  - [41. Readonly Properties and Classes (PHP 8.1)](#41-readonly-properties-and-classes-php-81)
  - [42. Intersection Types (PHP 8.1)](#42-intersection-types-php-81)
- [Performance and Internals](#43-just-in-time-compilation-jit)
  - [43. Just-In-Time Compilation (JIT)](#43-just-in-time-compilation-jit)
  - [44. Preloading](#44-preloading)
  - [45. Weak References](#45-weak-references)
  - [46. Memory Management](#46-memory-management)
  - [47. Zval and Reference Counting](#47-zval-and-reference-counting)
  - [48. Opcode Cache](#48-opcode-cache)
  - [49. Zend Engine Internals](#49-zend-engine-internals)
  - [50. Symbol Table](#50-symbol-table)
  - [51. Garbage Collection](#51-garbage-collection)
  - [52. Request Lifecycle](#52-request-lifecycle)
  - [53. Extension Development](#53-extension-development)
  - [54. Streams and Network Programming](#54-streams-and-network-programming)
  - [55. Session Handling Internals](#55-session-handling-internals)
  - [56. PHP-FPM (FastCGI Process Manager)](#56-php-fpm-fastcgi-process-manager)
  - [57. Interned Strings](#57-interned-strings)
  - [58. Abstract Syntax Tree (AST)](#58-abstract-syntax-tree-ast)
  - [59. Compilation and Execution](#59-compilation-and-execution)
  - [60. Server API (SAPI)](#60-server-api-sapi)
  - [61. Persistent Connections](#61-persistent-connections)
  - [62. PHP Standard Library (SPL) Internals](#62-php-standard-library-spl-internals)
  - [63. Dynamic and Static Scoping](#63-dynamic-and-static-scoping)
  - [64. Type System](#64-type-system)
  - [65. Function and Method Resolution](#65-function-and-method-resolution)
  - [66. Security Mechanisms](#66-security-mechanisms)
  - [67. PHP Binary Protocols](#67-php-binary-protocols)
  - [68. Profiling](#68-profiling)
  - [69. Network Internals](#69-network-internals)
  - [70. Connection Pooling](#70-connection-pooling)

---

## 1. Data Types and Variables

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Data Types in PHP](https://www.scaler.com/topics/php-tutorial/data-types-in-php)
- [PHP 8.0: News in Data Types (2/4)](https://blog.nette.org/en/php-8-0-news-in-data-types)
- [PHP 8 - Type System Improvements](https://www.infoq.com/articles/php-8-type-system-improvements)


### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Variables In PHP | Procedural PHP Tutorial For Beginners | PHP Tutorial | mmtuts](https://www.youtube.com/watch?v=DiEfNQsapbc&t=2s&ab_channel=DaniKrossing)
- [PHP Data Types - Typecasting Overview & How It Works - Full PHP 8 Tutorial](https://www.youtube.com/watch?v=KH4MmQsCDuw&ab_channel=ProgramWithGio)
- [PHP Variable and Data Type Tutorial](https://www.youtube.com/watch?v=FLs6rAVQWs0&ab_channel=DaniKrossing)

**[⬆ Back to Top](#table-of-contents-)**

---

## 2. Control Structures (If, Loops)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Control Structures in PHP: Conditional Statements and Loops](https://medium.com/@olivia.j.01101001/control-structures-in-php-conditional-statements-and-loops-8255be58c87f)
- [PHP Control Structures](https://www.scaler.com/topics/php-tutorial/control-structures-in-php/)
- [PHP Control Structures and Loops: if, else, for, foreach, while, and More](https://code.tutsplus.com/php-control-structures-and-loops--cms-31999t)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Conditions & Control Structures in PHP](https://www.youtube.com/watch?v=OlvCP8kHjvs&ab_channel=DaniKrossing)
- [Control Structures in PHP - Conditional Statements - if/else](https://www.youtube.com/watch?v=PUWrc6vzRMw&ab_channel=ProgramWithGio)
- [How to Use and Create Loops in PHP](https://www.youtube.com/watch?v=g7h5ndxKV9U&ab_channel=DaniKrossing)

**[⬆ Back to Top](#table-of-contents-)**

---

## 3. Functions and Scope

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Functions](https://www.javatpoint.com/php-functions)
- [PHP Tutorial - PHP Functions Scope](http://www.java2s.com/Tutorials/PHP/Language_Basics/0280__PHP_Function_Scope.htm)
- [PHP Variables Scope](https://www.scaler.com/topics/php-tutorial/variable-scope-in-php/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [How To Create Functions In PHP](https://www.youtube.com/watch?v=ba1rulfNhLk&ab_channel=ProgramWithGio)
- [Scopes in PHP for Beginners](https://www.youtube.com/watch?v=YIM6OLBMyY8&ab_channel=DaniKrossing)
- [How to Create Your Own Function in PHP](https://www.youtube.com/watch?v=uOLGQ9ZoOSc&ab_channel=DaniKrossing)

**[⬆ Back to Top](#table-of-contents-)**

---

## 4. Arrays and Array Functions

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Arrays](https://www.geeksforgeeks.org/php-arrays/)
- [PHP Array Functions](https://www.w3schools.com/php/php_ref_array.asp)
- [64 PHP Array Functions & Constants to Bookmark](https://blog.hubspot.com/website/php-array-functions)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [How to Create Arrays in PHP | Indexed & Associative Arrays](https://www.youtube.com/watch?v=D7mqV-p1kEc&ab_channel=DaniKrossing)
- [Arrays & Array functions](https://www.youtube.com/watch?v=nR6bdjr2hxQ&ab_channel=TheCodeholic)
- [PHP Array Functions (Playlist)](https://www.youtube.com/playlist?list=PLfZdD6t4BR8O-TulLw0WnmUZkE0v5RhNh)

**[⬆ Back to Top](#table-of-contents-)**

---

## 5. String Manipulation Functions

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP String Functions](https://www.w3schools.com/php/php_ref_string.asp)
- [String Manipulation in PHP](https://www.scaler.com/topics/php-tutorial/string-manipulation-in-php/)
- [Explain some string functions of PHP](https://www.geeksforgeeks.org/explain-some-string-functions-of-php/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [String Manipulation in PHP](https://www.youtube.com/watch?v=2TXxgwmcm8k&ab_channel=Codemy.com)
- [Strings & String functions](https://www.youtube.com/watch?v=HTEP3LC0ppk&ab_channel=TheCodeholic)
- [PHP 101 - String Functions](https://www.youtube.com/watch?v=SLYSb_IWNTw&ab_channel=Freeskills)
- [Ultimate Guide to the Most Useful String Functions in PHP](https://www.youtube.com/watch?v=YSmieMzKrSo&ab_channel=AMIRKAMIZI)

**[⬆ Back to Top](#table-of-contents-)**

---

## 6. Error Handling with Exceptions

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Exceptions](https://www.php.net/manual/en/language.exceptions.php)
- [PHP Try Catch: Basics & Advanced PHP Exception Handling Tutorial](https://stackify.com/php-try-catch-php-exception-tutorial/)
- [Modern Error handling in PHP](https://netgen.io/blog/modern-error-handling-in-php)
- [PHP 8.0: Expressions can now throw Exceptions](https://php.watch/versions/8.0/throw-expressions)
- [PHP 8.0 : throw as an expression](https://phpbackend.com/blog/post/php-8-0-throw-expression)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Error Handling & Error Handlers - Full PHP 8 Tutorial](https://www.youtube.com/watch?v=rQntgj7yink&ab_channel=ProgramWithGio)
- [OOP Error Handling In PHP - Exceptions & Try Catch Finally Blocks - Full PHP 8 Tutorial](https://www.youtube.com/watch?v=XQ5Pd-6Hnjk&ab_channel=ProgramWithGio)
- [How to Log Errors in PHP | PHP Error Reporting and Debugging](https://www.youtube.com/watch?v=EoP5PqvoLHg&ab_channel=DaniKrossing)

**[⬆ Back to Top](#table-of-contents-)**

---

## 7. Classes and Objects

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP OOP - Classes and Objects](https://www.w3schools.com/php/php_oop_classes_objects.asp)
- [PHP Objects and Classes](https://www.scaler.com/topics/php-tutorial/class-and-object-in-php/)
- [How to create and use PHP Classes and Objects](https://reintech.io/blog/how-to-create-and-use-php-classes-and-objects)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Object Oriented PHP Tutorials (Playlist)](https://www.youtube.com/playlist?list=PL0eyrZgxdwhypQiZnYXM7z7-OTkcMgGPh)
- [PHP Classes & Objects - Typed Properties - Constructors & Destructors](https://www.youtube.com/watch?v=6FW72q5fIx8&ab_channel=ProgramWithGio)
- [OOP In PHP | Object Oriented Programming In PHP](https://www.youtube.com/watch?v=JSX0HMYgtvc&ab_channel=Simplilearn)

**[⬆ Back to Top](#table-of-contents-)**

---

## 8. Visibility (Public, Private, Protected)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Visibility](https://www.php.net/manual/en/language.oop5.visibility.php)
- [PHP OOP - Access Modifiers](https://www.w3schools.com/php/php_oop_access_modifiers.asp)
- [What is the difference between public, private, and protected in PHP?](https://www.geeksforgeeks.org/what-is-the-difference-between-public-private-and-protected-in-php/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Object Oriented PHP - Access Modifiers](https://www.youtube.com/watch?v=NGYX-v5oDQs&ab_channel=NetNinja)
- [What is the difference between public, private, and protected php7](https://www.youtube.com/watch?v=fK4m1J8Req0&ab_channel=ZarxBiz)
- [Using Public, Private and Protected Variables](https://www.youtube.com/watch?v=Vuz_Gp2KNpY&ab_channel=CASMANWHAT)

**[⬆ Back to Top](#table-of-contents-)**

---

## 9. Constructors and Destructors

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Constructors and Destructors](https://www.php.net/manual/en/language.oop5.decon.php)
- [PHP | Constructors and Destructors](https://www.geeksforgeeks.org/php-constructors-and-destructors/)
- [PHP Constructors and Destructors](https://www.tutorialspoint.com/php-constructors-and-destructors)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Constructors and Destructors in OOP PHP](https://www.youtube.com/watch?v=ToomaGjgqBw&ab_channel=DaniKrossing)
- [Object Oriented PHP - Constructors](https://www.youtube.com/watch?v=Dh9ETygs-pA&ab_channel=NetNinja)
- [Constructors and Destructors in PHP](https://www.youtube.com/watch?v=CFBx0kHpnjw&ab_channel=TheCodeholic)

**[⬆ Back to Top](#table-of-contents-)**

---

## 10. Inheritance

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP OOP - Inheritance](https://www.w3schools.com/php/php_oop_inheritance.asp)
- [Inheritance in PHP: Understanding Inheritance With Examples](https://www.simplilearn.com/tutorials/php-tutorial/inheritance-in-php)
- [What is Inheritance in PHP?](https://www.geeksforgeeks.org/what-is-inheritance-in-php/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Object Oriented PHP - Inheritance](https://www.youtube.com/watch?v=mRMFQP_98oo&ab_channel=NetNinja)
- [Inheritance for beginners - OOP in PHP](https://www.youtube.com/watch?v=UWtB1srbixc&ab_channel=TheCodeholic)
- [Composition vs Inheritance in PHP With Practical Examples - Full PHP 8 Tutorial](https://www.youtube.com/watch?v=djd9zdlzyuA&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 11. Interfaces

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Interface](https://www.phptutorial.net/php-oop/php-interface/)
- [Interfaces](https://www.php.engineer/interfaces)
- [PHP Interfaces Explained](https://alexwebdevelop.com/php-interfaces/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Interface](https://m.youtube.com/watch?v=QQvbpJ4kARA)
- [Php Interface Tutorial - How and When to use Interfaces](https://m.youtube.com/watch?v=3B0KWx8gpuM)
- [PHP Interfaces & Polymorphism](https://m.youtube.com/watch?v=zebHZeQhIR4)

**[⬆ Back to Top](#table-of-contents-)**

---

## 12. Abstract Classes

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP: Abstract Classes and Interfaces](https://www.w3schools.com/php/php_oop_classes_abstract.asp)
- [UNDERSTANDING ABSTRACT CLASSES AND METHODS IN PHP](https://jamiegrand.co.uk/understanding-abstract-classes-and-methods-in-php/)
- [Abstract vs Interfaces Classes in PHP](https://rifatcse09.medium.com/abstract-vs-interfaces-classes-in-php-47067351c519)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Abstract Classes - Tutorial for Beginners](https://m.youtube.com/watch?v=52frlN8webg)
- [Abstract Classes in OOP PHP | Abstract Explained](https://www.youtube.com/watch?v=Eu7l8utquGY&ab_channel=DaniKrossing)
- [Abstract classes, abstraction in PHP - OOP in PHP](https://www.youtube.com/watch?v=EyY3BVPJXtI&ab_channel=TheCodeholic)

**[⬆ Back to Top](#table-of-contents-)**

---

## 13. Traits

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP OOP - Traits](https://www.w3schools.com/php/php_oop_traits.asp)
- [PHP Traits Explained](https://alexwebdevelop.com/php-traits/)
- [Everything about Traits in PHP.](https://medium.com/@edouard.courty/everything-about-traits-in-php-857c101b774d)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [OOP PHP | What is Traits and Why we need it](https://www.youtube.com/watch?v=npPnXEjMZ0Y&ab_channel=Bitfumes)
- [PHP traits in depth with examples - OOP in PHP](https://www.youtube.com/watch?v=eeqa3nHI5mI&ab_channel=TheCodeholic)
- [PHP Traits - How They Work & Drawbacks - Full PHP 8 Tutorial](https://www.youtube.com/watch?v=PMruqUC4Qpc&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 14. Static Methods and Properties

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP OOP - Static Properties](https://www.w3schools.com/php/php_oop_static_properties.asp)
- [PHP Static Properties and Methods](https://www.tutorialspoint.com/php-static-properties-and-methods)
- [PHP Static Methods and Properties](https://www.phptutorial.net/php-oop/php-static-methods/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Static Properties And Methods In OOP PHP](https://www.youtube.com/watch?v=L9jLxuLAAIY&ab_channel=DaniKrossing)
- [Static properties and methods in PHP - OOP in PHP](https://www.youtube.com/watch?v=JXs7tHUmxvc&ab_channel=TheCodeholic)
- [OOP PHP | Static Methods and Properties](https://www.youtube.com/watch?v=9byWxRUHqp0&ab_channel=Bitfumes)

**[⬆ Back to Top](#table-of-contents-)**

---

## 15. Namespaces

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Namespaces](https://www.w3schools.com/php/php_namespaces.asp)
- [PHP | Namespace](https://www.geeksforgeeks.org/php-namespace/)
- [A Complete Guide to PHP Namespaces](https://www.thoughtfulcode.com/a-complete-guide-to-php-namespaces/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Namespace Tutorial - Full PHP 8](https://www.youtube.com/watch?v=Jni9c0-NjrY&ab_channel=ProgramWithGio)
- [PHP namespaces 1/10: What is a namespace in PHP?](https://www.youtube.com/watch?v=lNaWD7kRBC8&ab_channel=DaveHollingworth)
- [Everything about PHP namespaces - OOP in PHP](https://www.youtube.com/watch?v=0SZW-wBY_WI&ab_channel=TheCodeholic)

**[⬆ Back to Top](#table-of-contents-)**

---

## 16. Type Declarations

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Type declarations](https://www.php.net/manual/en/language.types.declarations.php)
- [Benefits Of Type Declarations In PHP](https://kiptookorir.medium.com/benefits-of-type-declarations-in-php-531dfe56b295)
- [How PHP Type Declarations Actually Work](https://dev.to/robdwaller/how-php-type-declarations-actually-work-1mm5)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Type Declarations In OOP PHP](https://www.youtube.com/watch?v=0MYqGSplVQs&ab_channel=DaniKrossing)
- [PHP Type Declarations](https://www.youtube.com/watch?v=Ig0NbYTStxo&ab_channel=DaveHollingworth)
- [Return Type Declarations](https://www.youtube.com/watch?v=W8mbkPSLGBI&ab_channel=GaryClarke)

**[⬆ Back to Top](#table-of-contents-)**

---

## 17. Anonymous Functions and Closures

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [A Beginner's Guide to Closures and Arrow Functions in PHP](https://ashallendesign.co.uk/blog/a-beginner-s-guide-to-closures-and-arrow-functions-in-php)
- [PHP and Closures: Anonymous Functions and Variable Scoping](https://reintech.io/blog/php-and-closures-anonymous-functions-and-variable-scoping)
- [The power of Anonymous functions (Closures) in PHP](https://steemit.com/php/@hvonsteemit/the-power-of-anonymous-functions-closures-in-php)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Anonymous Functions](https://www.youtube.com/watch?v=kUs8bAaab70&ab_channel=DinoCajic)
- [Anonymous Functions & Closures](https://www.youtube.com/watch?v=soITzMQmycw&ab_channel=EsotericTech)
- [Variable, Anonymous, Callable, Closure & Arrow Functions In PHP](https://www.youtube.com/watch?v=7_FOIxYLF-s&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 18. Type Hinting and Return Types

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Reducing Errors With Type Hinting in PHP](https://www.honeybadger.io/blog/php-type-hinting/)
- [Type hint in PHP function parameters and return values, properties and constants](https://mlocati.github.io/articles/php-type-hinting.html)
- [PHP 8.0 feature focus: type improvements](https://platform.sh/blog/php-80-feature-focus-type-improvements/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Example: Why We Need PHP Return Types](https://www.youtube.com/watch?v=bx7O65je0Mc&ab_channel=LaravelDaily)
- [Type Declarations In OOP PHP | Type Hinting In PHP](https://www.youtube.com/watch?v=0MYqGSplVQs&ab_channel=DaniKrossing)
- [Type Hinting - Object Oriented PHP](https://www.youtube.com/watch?v=UxkPNTr6Vqo&ab_channel=GaryClarke)

**[⬆ Back to Top](#table-of-contents-)**

---

## 19. Regular Expressions (PCRE)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Regular Expressions](https://www.w3schools.com/php/php_regex.asp)
- [PHP | Regular Expressions](https://www.geeksforgeeks.org/php-regular-expressions/)
- [PHP Regular Expressions](https://www.javatpoint.com/php-regular-expressions)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Regular Expressions (RegEx) in 100 Seconds](https://www.youtube.com/watch?v=sXQxhojSdZM&ab_channel=Fireship)
- [PHP Regular Expressions Tutorial](https://www.youtube.com/watch?v=wnu4febXKx0&ab_channel=CleverTechie)
- [Functions Using Regular Expressions](https://www.youtube.com/watch?v=In5NBIRfMrQ&ab_channel=DaniKrossing)

**[⬆ Back to Top](#table-of-contents-)**

---

## 20. Variable Handling Functions

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Variable handling Functions - php.net](https://www.php.net/manual/en/ref.var.php)
- [PHP Variable Handling Functions - Tutorials point](https://www.tutorialspoint.com/php/php_variable_handling_functions.htm)
- [PHP Variable Handling Functions - php.org](https://php.org/php-variable-handling-functions/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Variable Handling function In PHP](https://www.youtube.com/watch?v=94L7x35s9wA&ab_channel=ProgramSnippets)
- [PHP Data Types and Variable Handling Functions](https://www.youtube.com/watch?v=n2oWBRTeDyg&ab_channel=CleverTechie)

**[⬆ Back to Top](#table-of-contents-)**

---

## 21. Generators

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Generators overview](https://www.php.net/manual/en/language.generators.overview.php)
- [PHP — Generators](https://medium.com/@erlandmuchasaj/php-generators-b26e98025a50)
- [PHP Generators](https://www.tutorialspoint.com/php-generators)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Tutorial: Generators and Iterators - Quick Guide](https://www.youtube.com/watch?v=dTnis2_jIPs&ab_channel=DeskNook)
- [PHP Generators Explained](https://www.youtube.com/watch?v=xH3snMmgDWg&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 22. Magic Methods

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [What are magic methods and how to use them in PHP ?](https://www.geeksforgeeks.org/what-are-magic-methods-and-how-to-use-them-in-php/)
- [PHP Magic Methods - PHP Tutorial](https://www.phptutorial.net/php-oop/php-magic-methods/)
- [PHP Magic Methods - Tutorials point](https://www.tutorialspoint.com/php-magic-methods)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [What Are PHP Magic Methods & How They Work](https://www.youtube.com/watch?v=nCxnzj83poQ&ab_channel=ProgramWithGio)
- [PHP Magic Methods (Playlist)](https://www.youtube.com/playlist?list=PLNuh5_K9dfQ0jQOX35XnGV0Fivekm695G)

**[⬆ Back to Top](#table-of-contents-)**

---

## 23. Late Static Bindings

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Late Static Bindings - php.net](https://www.php.net/manual/en/language.oop5.late-static-bindings.php)
- [Late Static Binding - PeachPie](https://docs.peachpie.io/api/Late-Static-Binding/)
- [What is Late Static Bindings in PHP ?](https://www.geeksforgeeks.org/what-is-late-static-bindings-in-php/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [OOP PHP | Late Static Binding](https://www.youtube.com/watch?v=MxRrCV_3VSQ&ab_channel=Bitfumes)
- [Level up Your PHP Skills: Mastering Late Static Binding](https://www.youtube.com/watch?v=7wBP1-Fsxaw&ab_channel=var_dump)
- [What Is Late Static Binding & How It Works In PHP](https://www.youtube.com/watch?v=4W5t8g3Rp_0&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 24. Reflection API

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Reflection](https://www.php.net/manual/en/book.reflection.php)
- [Reflection in PHP](https://dev.to/po0q/reflection-in-php-2dj3)
- [Introduction to PHP Reflection API](https://medium.com/tech-tajawal/introduction-to-php-reflection-api-4af07cc17db4)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Reflection API: Reflection Class ](https://www.youtube.com/watch?v=3uaPBYG4eeQ&ab_channel=Codecourse)
- [Dependency Injection Container With & Without Reflection API Autowiring](https://www.youtube.com/watch?v=78Vpg97rQwE&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 25. Iterators

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [The Iterator interface](https://www.php.net/manual/en/class.iterator.php)
- [Modern PHP Developer - Iterator](https://startutorial.com/view/modern-php-developer-iterator)
- [Iterator in PHP](https://refactoring.guru/design-patterns/iterator/php/example)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [What are PHP Iterators?](https://www.youtube.com/watch?v=NVN0FPRxQMs&ab_channel=Dr.AdamNielsen)
- [PHP Iterators & Iterable Type - Iterate Over Objects](https://www.youtube.com/watch?v=QFPP9B-Q3zM&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 26. Dependency Injection

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Understanding Dependency Injection](https://php-di.org/doc/understanding-di.html)
- [Building a Simple Dependency Injection Container in PHP](https://medium.com/@khalidzeiter/building-a-simple-dependency-injection-container-in-php-db3a397283ae)
- [Playing with dependency injection in PHP](https://allanmacgregor.com/posts/dependency-injection-php)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Dependency Injection & DI Containers](https://www.youtube.com/watch?v=igx3bIl1T_c&ab_channel=ProgramWithGio)
- [Dependency Injection in PHP | Create a Service Container from Scratch](https://www.youtube.com/watch?v=TqMXzEK0nsA&ab_channel=DaveHollingworth)
- [What is Dependency Injection PHP - in 5 Minutes](https://www.youtube.com/watch?v=38zitS5EgW0&ab_channel=DailyTuition)

**[⬆ Back to Top](#table-of-contents-)**

---

## 27. Sessions and Cookies

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Managing Sessions and Cookies in PHP](https://reintech.io/blog/managing-sessions-cookies-php)
- [What are the difference between session and cookies in PHP ?](https://www.geeksforgeeks.org/what-are-the-difference-between-session-and-cookies-in-php/)
- [Difference Between Session and Cookies in PHP](https://www.shiksha.com/online-courses/articles/difference-between-session-and-cookies-in-php-blogId-144431)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Session and Cookies in PHP](https://www.youtube.com/watch?v=jort8_4U-88&ab_channel=DaniKrossing)
- [Sessions & Cookies tutorial](https://www.youtube.com/watch?v=lhpqakrebiI&ab_channel=TheCodeholic)
- [PHP Sessions & Cookies - Output Buffering - Headers Already Sent Warning](https://www.youtube.com/watch?v=6vM-9ou1ARo&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 28. File Handling and Streams

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP File Handling: Read, Write, and Upload Files](https://reintech.io/blog/php-file-handling-read-write-upload-files)
- [Streams - php.net](https://www.php.net/manual/en/book.stream.php)
- [PHP - File Handling - Tutorials point](https://www.tutorialspoint.com/php/php_file_handling.htm)
- [PHP File Handling - Javatpoint](https://www.javatpoint.com/php-file)
- [A Guide to Streams in PHP: In-Depth Tutorial With Examples](https://stackify.com/a-guide-to-streams-in-php-in-depth-tutorial-with-examples/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Working With File System In PHP](https://www.youtube.com/watch?v=p7F2GgVxHc0&ab_channel=ProgramWithGio)
- [PHP File Tutorial | File in PHP | PHP File Handling Tutorial](https://www.youtube.com/watch?v=e7NvwnWaOZw&ab_channel=edureka%21)
- [How To Handling Files In PHP | file handling | php file handling](https://www.youtube.com/watch?v=x6Db-_1tD8E&ab_channel=HeavyCoding)

**[⬆ Back to Top](#table-of-contents-)**

---

## 29. PHP Standard Recommendations (PSR)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Standards Recommendations (PSRs)](https://reintech.io/term/php-standards-recommendations-psrs)
- [PHP Standards Recommendations](https://www.php-fig.org/psr/https://medium.com/@bramahendramahendra1/introduction-to-psr-php-standard-recommendations-and-how-to-use-them-f70c0b2daf16)
- [Introduction to PSR (PHP Standard Recommendations) and How to Use Them](https://medium.com/@bramahendramahendra1/introduction-to-psr-php-standard-recommendations-and-how-to-use-them-f70c0b2daf16)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Coding Standards, Autoloading (PSR-4) & Composer](https://www.youtube.com/watch?v=rqzYdHdyMH0&ab_channel=ProgramWithGio)
- [PHP PSR (Playlist)](https://www.youtube.com/playlist?list=PLxmMgFQn_JhIo1jysxaMOohDrZB37yCVH)

**[⬆ Back to Top](#table-of-contents-)**

---

## 30. Object Cloning and Serialization

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Object Cloning](https://www.php.net/manual/en/language.oop5.cloning.php)
- [Serializing objects - objects in sessions](https://www.php.net/manual/en/language.oop5.serialization.php)
- [What is serialization in PHP](https://dev.to/inspector/what-is-serialization-in-php-2dd1)
- [PHP Object Cloning](https://www.tutorialspoint.com/php-object-cloning)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP - Object Cloning & Clone Magic Method](https://www.youtube.com/watch?v=vLmIoy6Bnog&ab_channel=ProgramWithGio)
- [PHP Serialize Objects & Serialize Magic Methods](https://www.youtube.com/watch?v=Jnm2m_Iw5CI&ab_channel=ProgramWithGio)
- [PHP Serialization Tutorial | Serialize and Unserialize PHP Objects](https://www.youtube.com/watch?v=hTm4FyFDh40&ab_channel=GaryClarke)

**[⬆ Back to Top](#table-of-contents-)**

---

## 31. Attribute Annotations (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8: Attributes](https://stitcher.io/blog/attributes-in-php-8)
- [PHP 8.0: Attributes](https://php.watch/versions/8.0/attributes)
- [PHP 8.0 feature focus: Attributes](https://platform.sh/blog/php-8-0-feature-focus-attributes/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Attributes - Simple Router With Attributes](https://www.youtube.com/watch?v=I7WJa-he5oM&ab_channel=ProgramWithGio)
- [PHP Attributes 50 Minute Tutorial](https://www.youtube.com/watch?v=oSo4xbP6ZYo&ab_channel=GaryClarke)

**[⬆ Back to Top](#table-of-contents-)**

---

## 32. Constructor Property Promotion (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.0: Class constructor property promotion](https://php.watch/versions/8.0/constructor-property-promotion)
- [PHP 8: Constructor property promotion](https://stitcher.io/blog/constructor-promotion-in-php-8)
- [PHP 8 Constructor Property Promotion: Simplifying Class Definitions with Examples](https://timjwilliams.medium.com/php-8-constructor-property-promotion-simplifying-class-definitions-with-examples-6039ea2f09b7)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP 8's Constructor Property Promotion in Magento 2.4.4](https://www.youtube.com/watch?v=I960JDkmXY0&ab_channel=MarkShust)
- [PHP 8 Constructor Property Promotion Explained](https://www.youtube.com/watch?v=OQybCaMch2M&ab_channel=AMIRKAMIZI)
- [Constructor Property Promotion - Nullsafe Operator](https://www.youtube.com/watch?v=T1PbFz-o6kw&ab_channel=ProgramWithGio)

**[⬆ Back to Top](#table-of-contents-)**

---

## 33. Union Types (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.0: Union Types](https://php.watch/versions/8.0/union-types)
- [A Guide to Union Types in PHP 8: Examples, Best Practices, and Benefits](https://mderis.medium.com/a-guide-to-union-types-in-php-8-examples-best-practices-and-benefits-d51c292f5f54)
- [PHP 8 Union types](https://www.geeksforgeeks.org/php-8-union-types/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP 8 Union Types Explained](https://www.youtube.com/watch?v=Tv7X2uTM0XU&ab_channel=AMIRKAMIZI)
- [Php 8 - Union Types](https://www.youtube.com/watch?v=64RDCMwe85g&ab_channel=Laratips)

**[⬆ Back to Top](#table-of-contents-)**

---

## 34. Match Expressions (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.0: Match Expressions](https://php.watch/versions/8.0/match-expression)
- [PHP 8: match or switch?](https://stitcher.io/blog/php-8-match-or-switch)
- [PHP match Expression](https://www.geeksforgeeks.org/php-match-expression/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Match Expression - Match vs Switch](https://www.youtube.com/watch?v=jCUyvHUKSmE&ab_channel=ProgramWithGio)
- [Php 8 - Match Expression](https://www.youtube.com/watch?v=iioTbh6y4iw&ab_channel=Laratips)
- [Match in PHP 8.0](https://www.youtube.com/watch?v=5RI2VA5KB2c&ab_channel=PHPAnnotated)

**[⬆ Back to Top](#table-of-contents-)**

---

## 35. Nullsafe Operator (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8: the null safe operator](https://stitcher.io/blog/php-8-nullsafe-operator)
- [PHP 8.0: Null-safe operator](https://php.watch/versions/8.0/null-safe-operator)
- [Mastering Null Safety in PHP 8: A Comprehensive Guide to Using the Null Safe Operator](https://medium.com/@prevailexcellent/mastering-null-safety-in-php-8-a-comprehensive-guide-to-using-the-null-safe-operator-47835ba1140b)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP 8 Null Safe Operator Explained](https://www.youtube.com/watch?v=BW2xSQz-98U&ab_channel=AMIRKAMIZI)
- [Php 8 - Nullsafe Operator](https://www.youtube.com/watch?v=iI1OVTPCc2o&ab_channel=Laratips)

**[⬆ Back to Top](#table-of-contents-)**

---

## 36. Weak Maps (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8 Weak Maps and Practical Use Cases](https://php.watch/articles/practical-weakmap)
- [PHP 8.0 feature focus: Weak maps](https://platform.sh/blog/php-80-feature-focus-weak-maps/)
- [PHP 8.0: WeakMaps](https://php.watch/versions/8.0/weakmap)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP WeakMap Explained ](https://www.youtube.com/watch?v=zDKnI_YKCDc&ab_channel=ProgramWithGio)
- [Exploring Weakmaps - Front Line PHP](https://www.youtube.com/watch?v=-lFyHJqzfFU&ab_channel=SPATIE)

**[⬆ Back to Top](#table-of-contents-)**

---

## 37. Named Arguments (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8: named arguments](https://stitcher.io/blog/php-8-named-arguments)
- [PHP 8: The joy of named arguments](https://dev.to/po0q/php-8-the-joy-of-named-arguments-1nhn)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP 8 Named Arguments: Practical Example](https://www.youtube.com/watch?v=QjH9ObFH90M&ab_channel=LaravelDaily)
- [PHP Function Parameters - Named Arguments - Variadic Functions & Unpacking](https://www.youtube.com/watch?v=I9XkWyets9w&ab_channel=ProgramWithGio)
- [PHP 8 Named Arguments Explained](https://www.youtube.com/watch?v=ZZvs-0QkUwM&ab_channel=AMIRKAMIZI)

**[⬆ Back to Top](#table-of-contents-)**

---

## 38. Mixed Type (PHP 8)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.0: New mixed pseudo type](https://php.watch/versions/8.0/mixed-type)
- [PHP 8 News: Union Types and Mixed Types](https://dev.to/xxzeroxx/php-8-news-union-types-and-mixed-types-l0h)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP 8 Mixed Data Types](https://www.youtube.com/shorts/z39aKyfFi7s)

**[⬆ Back to Top](#table-of-contents-)**

---

## 39. Enums (PHP 8.1)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.1: Enums - php.watch](https://php.watch/versions/8.1/enums)
- [PHP 8.1: Enums - stitcher.io](https://stitcher.io/blog/php-enums)
- [Use PHP 8.1 Enums](https://developer.shopware.com/docs/resources/references/adr/2023-05-16-php-enums.html)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP 8.1 - Enum](https://www.youtube.com/watch?v=Pl5bZpQycmg&ab_channel=Laratips)
- [PHP Enums With Practical Examples](https://www.youtube.com/watch?v=5Cgio2OfOYk&ab_channel=ProgramWithGio)
- [Enum PHP 8.1 Classes in Laravel: Practical Example](https://www.youtube.com/watch?v=uEBHJVK-Ibg&ab_channel=LaravelDaily)

**[⬆ Back to Top](#table-of-contents-)**

---

## 40. Fibers (PHP 8.1)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.1: Fibers](https://php.watch/versions/8.1/fibers)
- [Php 8.1 New Features — Fibers](https://kvnc-inc.medium.com/php-8-1-new-features-fibers-49744f84c151)
- [PHP Fibers: A practical example](https://aoeex.com/phile/php-fibers-a-practical-example/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Fibers & Asynchronous Under 11 Minutes](https://www.youtube.com/watch?v=Db-GFBGyD4w&ab_channel=DeskNook)
- [Learn how to use Fibers in PHP 8.1](https://www.youtube.com/watch?v=gRRqAET3h20&ab_channel=LionelTheTechLead)
- [Learn how to use Fibers in PHP 8.1](https://www.youtube.com/watch?v=3DiKvpC9TL8&ab_channel=Techweber)

**[⬆ Back to Top](#table-of-contents-)**

---

## 41. Readonly Properties and Classes (PHP 8.1)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.1: Readonly Properties](https://php.watch/versions/8.1/readonly)
- [PHP Readonly Properties: How to Use Them](https://alexwebdevelop.com/php-readonly-properties/)
- [Readonly Classes in PHP: A Useful Addition to Readonly Properties](https://doganoo.medium.com/readonly-classes-in-php-a-useful-addition-to-readonly-properties-4457b27a9f16)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Readonly classes in PHP 8.2](https://www.youtube.com/watch?v=2cyJq08q6xE&ab_channel=PHPAnnotated)
- [Readonly properties in PHP 8.1](https://www.youtube.com/watch?v=qoObkWJdBu0&ab_channel=AmitMerchant)
- [Readonly properties and classes in PHP 8](https://www.youtube.com/watch?v=8I9NYAIivj4&ab_channel=Coder)

**[⬆ Back to Top](#table-of-contents-)**

---

## 42. Intersection Types (PHP 8.1)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.1: Intersection Types](https://php.watch/versions/8.1/intersection-types)
- [PHP 8.1 : Pure intersection types](https://phpbackend.com/blog/post/php-8-1-pure-intersection-types)
- [How and When to Use PHP’s Pure Intersection Types](https://doganoo.medium.com/how-and-when-to-use-phps-pure-intersection-types-2189aa8359c1)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP 8.2: Intersection Types](https://front-line-php.com/videos/617766993-intersection-types)

**[⬆ Back to Top](#table-of-contents-)**

---

## 43. Just-In-Time Compilation (JIT)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP 8.0: JIT](https://php.watch/versions/8.0/JIT)
- [JIT Compiler in PHP](https://medium.com/developers-keep-learning/jit-compiler-in-php-655d690f976c)
- [PHP 8.0 feature focus: Just-in-Time compilation](https://platform.sh/blog/php-80-feature-focus-just-in-time-compilation/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Just In Time (JIT) Compilers - Computerphile](https://www.youtube.com/watch?v=d7KHAVaX_Rs&ab_channel=Computerphile)
- [How to enable JIT OR Just In Time Compilation in PHP8 | What is Just In Time Compilation](https://www.youtube.com/watch?v=Jm2NeaIlmU8&ab_channel=Shakzee)
- [JIT(Just In Time Compilation) VS interpreter in PHP | JIT VS interpreter performance Test in PHP8](https://www.youtube.com/watch?v=ccldTJJ4coI&ab_channel=Shakzee)

**[⬆ Back to Top](#table-of-contents-)**

---

## 44. Preloading

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Preloading in PHP 7.4](https://stitcher.io/blog/preloading-in-php-74)
- [Preloading your PHP 7.4 project in one line](https://medium.com/swlh/preloading-your-php-7-4-project-in-one-line-9ede756f292c)
- [https://blog.blackfire.io/php-preloading-and-performance-impact.html](https://blog.blackfire.io/php-preloading-and-performance-impact.html)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Preloading in PHP 7.4](https://www.youtube.com/watch?v=aScXoYm-2CE&ab_channel=CitrusApps)
- [PHP OPCache, Realpath Cache and Preloading - Jachim Coudenys - PHP UK 2020](https://www.youtube.com/watch?v=R5Okt1EX3_4&ab_channel=PHPUKConference)

**[⬆ Back to Top](#table-of-contents-)**

---

## 45. Weak References

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Weak References](https://php7explained.com/4.3.19-weak-references.html)
- [The WeakReference class](https://typeoverflow.com/developer/docs/php/class.weakreference)
- [PHP WeakReference class](https://www.tutorialspoint.com/php-weakreference-class)

**[⬆ Back to Top](#table-of-contents-)**

---

## 46. Memory Management

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Memory management](https://www.php.net/manual/en/mysqlnd.memory.php)
- [11. PHP Memory Management](https://www.zend.com/resources/php-extensions/php-memory-management)
- [Memory management¶](https://www.phpinternalsbook.com/php7/memory_management.html)
- [8 questions to the PHP memory usage](https://medium.com/@serhii.shkarupa/8-questions-to-the-php-memory-usage-e49ae105bade)
- [Memory Management with PHP](https://www.informit.com/articles/article.aspx?p=516587&seqNum=2)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Tech Talk: Memory Usage in PHP - Dealing with Arrays](https://www.youtube.com/watch?v=l6lq_RJtozA&ab_channel=AcroCommerce)
- [Benoit Jacquemont - Hunting down memory leaks with PHP Meminfo - phpday 2019](https://www.youtube.com/watch?v=NjIlKlFImlo&ab_channel=GrUSP)

**[⬆ Back to Top](#table-of-contents-)**

---

## 47. Zval and Reference Counting

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Reference Counting Basics](https://www.php.net/manual/en/features.gc.refcounting-basics.php)
- [Details of PHP 7.4 Reference Counting of Zvals](https://stackoverflow.com/questions/72309477/details-of-php-7-4-reference-counting-of-zvals)
- [PHP Object-Caching and Reference Counting](https://externals.io/message/27539)

**[⬆ Back to Top](#table-of-contents-)**

---

## 48. Opcode Cache

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Unlocking Faster Execution with PHP OpCode Caching for PHP Performance](https://accesto.com/blog/php-opcode-caching/)
- [Opcode Caching](https://www.drupal.org/docs/7/managing-site-performance-and-scalability/caching-to-improve-performance/opcode-caching)
- [How to Install and Configure OPcache With Your PHP App](https://www.cloudways.com/blog/integrate-php-opcache/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP Performance I: Everything You Need to Know About OpCode Caches](https://www.youtube.com/watch?v=lcNbp3qkTqo&ab_channel=engineyardcloud)

**[⬆ Back to Top](#table-of-contents-)**

---

## 49. Zend Engine Internals

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Zend engine](linhttps://www.phpinternalsbook.com/php7/zend_engine.htmlk)
- [PHP and Zend Engine Internals](https://phpbuilder.com/php-and-zend-engine-internals/)
- [How zend engine compile php codes or How php compiler works?](https://stackoverflow.com/questions/5377370/how-zend-engine-compile-php-codes-or-how-php-compiler-works)

**[⬆ Back to Top](#table-of-contents-)**

---

## 50. Symbol Table

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [What is the Symbol Table?](https://www.tutorialspoint.com/what-is-the-symbol-table)
- [Symbol Table](https://www.javatpoint.com/symbol-table)

**[⬆ Back to Top](#table-of-contents-)**

---

## 51. Garbage Collection

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [What Is Garbage Collection in PHP And How Do You Make The Most Of It?](https://tideways.com/profiler/blog/what-is-garbage-collection-in-php-and-how-do-you-make-the-most-of-it)
- [Better Understanding PHP’s Garbage Collection](https://www.sitepoint.com/better-understanding-phps-garbage-collection/)
- [Garbage Collection Statistics](https://xdebug.org/docs/garbage_collection)

**[⬆ Back to Top](#table-of-contents-)**

---

## 52. Request Lifecycle

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [HTTP — Request Lifecycle](https://spiral.dev/docs/http-lifecycle/current/en)
- [The PHP Request Life Cycle](http://php.find-info.ru/php/016/ch20lev1sec5.html)

**[⬆ Back to Top](#table-of-contents-)**

---

## 53. Extension Development

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Writing PHP Extensions](https://www.zend.com/resources/writing-php-extensions)
- [PHP Extension - Create a Simple Extension and Set Up Development Environment](https://bogomolov.tech/php-extension-development/)
- [Create PHP7 Extension, The Easy Way!](https://medium.com/tech-tajawal/introduction-to-php7-extension-cd802b8ecc1c)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Your first PHP extension - Christian Rades](https://www.youtube.com/watch?v=j9L8x_6rT_E&ab_channel=PHPUKConference)

**[⬆ Back to Top](#table-of-contents-)**

---

## 54. Streams and Network Programming

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [A Guide to Streams in PHP: In-Depth Tutorial With Examples](https://stackify.com/a-guide-to-streams-in-php-in-depth-tutorial-with-examples/)
- [My Experience with PHP](https://phillipnb.wordpress.com/2011/06/01/php-and-network-programming/)
- [Understanding Streams in PHP](https://www.sitepoint.com/understanding-streams-in-php/)

**[⬆ Back to Top](#table-of-contents-)**

---

## 55. Session Handling Internals

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Session Handling on Heroku](https://devcenter.heroku.com/articles/php-sessions)
- [The SessionHandler class](https://www.php.net/manual/en/class.sessionhandler.php)
- [Session Handling](https://phpdoctest.github.io/en/book.session.html)

**[⬆ Back to Top](#table-of-contents-)**

---

## 56. PHP-FPM (FastCGI Process Manager)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [FastCGI Process Manager (FPM) ¶](https://www.php.net/manual/en/install.fpm.php)
- [PHP-FPM: The Future of PHP Handling](https://www.plesk.com/blog/various/php-fpm-the-future-of-php-handling/)
- [PHP-FPM Performance Tuning: A Detailed Guide to Optimizing Your Web Applications](https://www.cloudways.com/blog/php-fpm-on-cloud/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [All you need to know about FastCGI Process Manager (FPM)](https://www.youtube.com/watch?v=hEXBgQ71rvE&ab_channel=DanielPersson)

**[⬆ Back to Top](#table-of-contents-)**

---

## 57. Interned Strings

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Internals Book](https://www.phpinternalsbook.com/php7/internal_types/strings/zend_strings.html)
- [How opcache works](https://www.npopov.com/2021/10/13/How-opcache-works.html)
- [Checking OPcache, RealPath Cache, PCRE Cache and OPcache Interned Strings Buffer with Blackfire](https://blog.blackfire.io/cache-information.html)
- [Nextcloud 23.02 OPcache interned strings buffer](https://help.nextcloud.com/t/nextcloud-23-02-opcache-interned-strings-buffer/134007)

**[⬆ Back to Top](#table-of-contents-)**

---

## 58. Abstract Syntax Tree (AST)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Abstract Syntax Tree](https://phpstan.org/developing-extensions/abstract-syntax-tree)
- [PHP RFC: Abstract syntax tree](https://wiki.php.net/rfc/abstract_syntax_tree)
- [Unlocking the Power of PHP with the Abstract Syntax Tree (AST)](https://aminshamim.xyz/unlocking-the-power-of-php-with-the-abstract-syntax-tree-ast-6951a3de2919)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [What Is An Abstract Syntax Tree, With WealthFront Engineer Spencer Miskoviak](https://www.youtube.com/watch?v=wINY109MG10&ab_channel=newline)
- [PHP UK Conference 2018 - James Titcumb - Climbing the Abstract Syntax Tree](https://www.youtube.com/watch?v=AEfkYUjEuSs&ab_channel=PHPUKConference)
- [Understand Abstract Syntax Trees - ASTs - in Practical and Useful Ways for Frontend Developers](https://www.youtube.com/watch?v=tM_S-pa4xDk&list=PLw5h0DiJ-9PCWamtYU7X220dlBSU94BdD&ab_channel=newline)

**[⬆ Back to Top](#table-of-contents-)**

---

## 59. Compilation and Execution

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Code Execution Flow](https://webkul.com/blog/php-code-execution-flow/)
- [How does PHP interpreter works, How PHP is executed on server, PHP script execution explained step by step](https://medium.com/@mimranisrar6/how-does-php-interpreter-works-how-php-is-executed-on-server-php-script-execution-explained-step-663a8cd05df6)
- [How a PHP interpreter works](https://www.droptica.com/blog/how-php-interpreter-works/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Ok, I made C compiler in PHP (c.php Ep.01)](https://www.youtube.com/watch?v=Yi6NxMxCFY8&ab_channel=TsodingDaily)
- [The PHP Process Explained](https://www.youtube.com/watch?v=6QGskEOIS9E&ab_channel=LeighCotnoir)
- [How PHP Works](https://www.youtube.com/watch?v=wKn-GIFTo4E&ab_channel=PHPTrainingDotCom)

**[⬆ Back to Top](#table-of-contents-)**

---

## 60. Server API (SAPI)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [What is SAPI and when would you use it?](https://stackoverflow.com/questions/9948008/what-is-sapi-and-when-would-you-use-it)
- [Requests, responses and the PHP SAPI](https://sabre.io/http/sapi/)

**[⬆ Back to Top](#table-of-contents-)**

---

## 61. Persistent Connections

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP, MySQL, and persistent connections](https://kylewoodward.com/current/php-mysql-and-persistent-connections/)
- [Persistent Database Connections](https://www.php.net/manual/en/features.persistent-connections.php)
- [Persistent DB Connections - Yea or Nay?](https://stackoverflow.com/questions/50303/persistent-db-connections-yea-or-nay)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Should I close my MySQL connections in PHP?](https://www.youtube.com/watch?v=dO6rmygN38g&ab_channel=TechTalkofDan)
- [Persistent Connections (Pros and Cons)](https://www.youtube.com/watch?v=XxM8BZuaKi4&ab_channel=HusseinNasser)

**[⬆ Back to Top](#table-of-contents-)**

---

## 62. PHP Standard Library (SPL) Internals

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [THE STANDARD PHP LIBRARY (SPL)](https://web.archive.org/web/20230918193820/https://benramsey.com/articles/standard-php-library/)
- [A quiet peek through the PHP Standard Library (SPL)](https://medium.com/@noob.dev/a-quiet-peek-through-the-php-standard-library-spl-0e85f625e256)
- [An Introduction to SPL, the Standard PHP Library](https://www.slideshare.net/slideshow/an-introduction-to-spl-the-standard-php-library/1403211)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Mark Baker - Standard PHP Library](https://www.youtube.com/watch?v=-IltUmcqj5A&ab_channel=PHPUSERGROUPDRESDENe.V.)
- [The Standard PHP Library - Intermediate PHP](https://www.youtube.com/watch?v=N-hLIREo6Mg&ab_channel=alijafari)

**[⬆ Back to Top](#table-of-contents-)**

---

## 63. Dynamic and Static Scoping

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Static and Dynamic Scope](https://learnloner.com/static-and-dynamic-scope/)
- [Variable scope](https://www.php.net/manual/en/language.variables.scope.php)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [Static and Dynamic Scoping (Part-1)](https://www.youtube.com/watch?v=L53nqHCSSFY&ab_channel=NesoAcademy)
- [Static and Dynamic Scoping (Part-2)](https://www.youtube.com/watch?v=DeGfInd5BPY&ab_channel=NesoAcademy)
- [Static and Dynamic Scoping (Part-3)](https://www.youtube.com/watch?v=-7Hz3iriV6w&ab_channel=NesoAcademy)
- [Static and Dynamic Scoping (Part-4)](https://www.youtube.com/watch?v=kqWP26CdhB8&ab_channel=NesoAcademy)

**[⬆ Back to Top](#table-of-contents-)**

---

## 64. Type System

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Type System](https://www.php.net/manual/en/language.types.type-system.php)
- [Everything you need (and don't need) to know about PHP's type system](https://thephp.website/en/issue/php-type-system/#type-operations-in-php )
- [PHP 8 - Type System Improvements](https://www.infoq.com/articles/php-8-type-system-improvements/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP's type system dissected? - George Peter Banyard](https://www.youtube.com/watch?v=LUydbYBzjAk&ab_channel=PHPUKConference)

**[⬆ Back to Top](#table-of-contents-)**

---

## 65. Function and Method Resolution

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Scope Resolution operator in PHP](https://www.geeksforgeeks.org/scope-resolution-operator-in-php/)
- [PHP: The Scope Resolution Operator (::)](https://eleni.blog/2013/02/03/php-the-scope-resolution-operator/)

**[⬆ Back to Top](#table-of-contents-)**

---

## 66. Security Mechanisms

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [8 Best PHP Security Practices You Should Know](https://wpwebinfotech.com/blog/php-security/)
- [PHP Security 5: PHP Security Tips](https://www.acunetix.com/websitesecurity/php-security-5/)
- [Ultimate PHP Security Best Practices](https://www.cloudways.com/blog/php-security/)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [PHP website security & Hacking prevention (Playlist](https://www.youtube.com/playlist?list=PLY3j36HMSHNVaHbm5gf302PjGAmYZKZv1)
- [PHP Security (Playlist)](lihttps://www.youtube.com/playlist?list=PL2407F4EE0530B251k)

**[⬆ Back to Top](#table-of-contents-)**

---

## 67. PHP Binary Protocols

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Alpari BinaryProtocol library](https://github.com/alpari-tech/binary-protocol)
- [Binary parsing with PHP](https://igor.io/2012/09/24/binary-parsing.html)

**[⬆ Back to Top](#table-of-contents-)**

---

## 68. Profiling

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [3 PHP Profiler Types and Why You Need All of Them](https://stackify.com/php-profilers/)
- [PHP Profiling: How to Find Slow Code](https://stackify.com/php-profiling-find-slow-code/)

---

## 69. Network Internals

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [PHP Internals Book](https://www.phpinternalsbook.com/)
- [Internals](https://wiki.php.net/internals)

---

## 70. Connection Pooling

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/1864/1864984.png" alt="Articles"> Articles

- [Improve PHP Application Performance With Database Connection Pooling](https://medium.com/@dollyaswin/improve-php-application-performance-with-database-connection-pooling-a93a5e372fce)
- [Database connection Pooling PHP-CP Introduction](https://topic.alibabacloud.com/a/database-connection-pooling-php-cp-introduction_1_34_30018797.html)

### <img align="center" width="30px" height="30px" src="https://cdn-icons-png.flaticon.com/512/3074/3074767.png" alt="Videos"/> Videos

- [How to reduce latency with Connection Pools](https://www.youtube.com/watch?v=YM1I-uf_k-o&ab_channel=CockroachDB)
- [PHP : Connection pooling in PHP](https://www.youtube.com/watch?v=ZrJqhT_UtBg&ab_channel=HeyDelphi)
- [MySQL : php connection pooling mysql](https://www.youtube.com/watch?v=XlTuZF1PgKY&ab_channel=HeyDelphi)

---