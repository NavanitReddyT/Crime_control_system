# Crime_control_system

This is a C++-based application designed to provide a streamlined system for managing and reporting crimes. The system facilitates two main user types: Public users and Authority users. Public users can sign up to report incidents, specifying details such as case type, location, and description. These incident reports are dynamically stored as individual text files in the system's designated folder. Authority users, on the other hand, can sign in to search and view these reports using keywords, which are matched against both filenames and file content. The system implements several key features, including user authentication, dynamic memory allocation, file handling, and keyword-based search functionality.

Features: Public Users:

Can sign up with valid credentials (name, phone number, and password). Can sign in to report incidents, categorized by type, location, and detailed description. Reports are saved as text files named using the case type, location, and reporter's name for easier identification. Authority Users:

Can sign in using predefined credentials. Can search for incident reports by entering keywords, which are matched against filenames and file content. Found reports can be opened and read directly from the system. File Handling:

All reports are stored as individual text files in a folder named C++ Project. User credentials are securely saved in a file named public_users.txt. Validation:

User input (name, phone number, and password) is validated during the sign-up process. Case type and location inputs are sanitized to create valid filenames. Technologies and Concepts: This project leverages several core C++ features and concepts:

Object-Oriented Programming (OOP): Classes and inheritance are used to define Public and Authority users. Dynamic Memory Allocation: A dynamically resizing array is used to manage public user accounts. File Handling: Incident reports and user data are managed using file input/output streams. Namespace and Standard Library: Utilizes modern C++17 features such as std::filesystem for file and directory management. Validation: Custom validation functions ensure input accuracy for user credentials.

Usage Instructions: Public User Workflow: Select Sign Up to create an account. Log in using Sign In to report an incident. Provide the case type, location, and description of the incident. Select the emergency level (e.g., high or normal priority).

Authority User Workflow: Log in using predefined credentials. Search for reports using a keyword. View the list of matching reports and open the desired file.

Crime-control-system/README.md at main · Gnana-Prudhvi-Rasamsetti/Crime-control-system
