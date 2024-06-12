Objective: The objective of this project is to create a Java program that allows users to store and manage contact information efficiently. The program provides a user-friendly interface for adding, viewing, editing, and deleting contacts.

Key Features:

Add Contact: Users can add new contacts by entering the contact's name, phone number, and email address.

View Contacts: Users can view the list of all stored contacts. This feature allows users to quickly access contact information.

Edit Contact: Users can edit existing contacts by specifying the contact's name and entering new details such as the updated name, phone number, and email address.

Delete Contact: Users can delete contacts from the contact list by specifying the name of the contact they want to remove.

Persistent Storage: The program stores contacts in a text file (contacts.txt) to ensure that contact information is retained between program executions. This allows users to maintain their contact list across multiple sessions.

Implementation Details:

The project is implemented in Java programming language.
Contact information is stored as objects of the Contact class, which encapsulates attributes such as name, phone number, and email address.
The ContactManager class acts as a controller for managing contacts. It provides methods for adding, viewing, editing, and deleting contacts, as well as loading and saving contacts from/to the text file.
User interactions are handled through a simple command-line interface. Users can choose options from a menu displayed in the console.
The program utilizes file I/O operations to read from and write to the contacts.txt file for persistent storage of contact information.
Usage:

Users run the program (ContactManager.java) in a Java runtime environment.
Upon execution, users are presented with a menu of options to perform various actions such as adding, viewing, editing, or deleting contacts.
Users can choose an option by entering the corresponding number.
The program performs the selected action and provides feedback to the user accordingly.
Contact information is stored in the contacts.txt file, allowing users to access their contact list across multiple sessions.
