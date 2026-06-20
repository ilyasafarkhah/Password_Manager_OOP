# Password_Manager_OOP
Password Manager (OOP Project)
A command-line password manager built in Python to practice object-oriented
programming concepts. This project was built during my first month of
self-studying programming, as part of a multi-year plan to work as a
programmer in Germany.
Features
Add a new password entry (username, site, password)
Automatically updates the entry if the same username + site already exists
(instead of creating a duplicate)
Search for an entry by username (exact match)
Delete an entry by username
Password validation (minimum 8 characters), enforced through a property setter
Concepts practiced
Classes and objects
@property / setters for validation
Name mangling (__password) for encapsulation
Avoiding common bugs like mutating a list while iterating over it,
and creating duplicate entries on repeated calls
Example usage
Python
Possible improvements
Persist data to a file (JSON) instead of keeping it only in memory
Hash/encrypt passwords instead of storing plaintext
Add a simple CLI menu for interactive use
Project context
This is one of the early portfolio projects from my first month learning
Python, focused on solidifying OOP fundamentals before moving on to more
advanced topics.