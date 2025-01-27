This Java program implements a Library Management System that allows users to manage a collection of books effectively. Built using the Java programming language, the program leverages Object-Oriented Programming (OOP) principles such as encapsulation, modularity, and abstraction. It provides functionality for adding books, searching for books by title or author, checking out books, returning books, and maintaining data persistence by saving and loading the library's state to and from a file. The system uses the Book class to represent individual books with attributes like title, author, and checkout status, while the Library class manages a collection of books using Java's ArrayList. The program ensures encapsulation by using private fields and public getter and setter methods to manage book attributes. To handle data persistence, it utilizes Java’s file-handling capabilities, including PrintWriter to save book data (title, author, and checkout status) to a file (library.txt) and Scanner to load data from the file, reconstructing the library collection during startup. The program also uses Java's Scanner class for user input and provides a menu-driven interface for users to perform various actions interactively. This menu allows users to add new books, search for books by keywords, check out books if available, and return books to update their availability. Each operation is handled seamlessly, and appropriate feedback is provided to guide the user. When the program exits, it automatically saves the library's current state to ensure data continuity between sessions. Overall, the program demonstrates how Java's robust standard library and OOP features can be used to create practical, interactive applications with data persistence and user-friendly functionality.