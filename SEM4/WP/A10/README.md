# Assignment10

Develop a web application based on ASP .NET.

Documentation can be found at:
1) http://www.cs.ubbcluj.ro/~forest/wp
2) http://www.w3schools.com/aspnet
3) http://www.w3schools.com/ajax
All web pages should be accessible only if the user logs in using a username and a password (create a session each time a user logs in, and destroy the session when the user logs out). Have in mind the user experience when you implement the problem:

add different validation logic for input fields
do not force the user to input an ID for an item if he wants to delete/edit/insert it; this should happen automatically (e.g. the user clicks an item from a list, and a page/modal prepopulated with the data for that particular item is opened, where the user can edit it)
add confirmation when the user deletes/cancels an item
do a bare minimum CSS that at least aligns the various input fields
Problems
Solve the same problem you got for the PHP lab, but using the ASP .NET technology. In addition to the specification for the PHP lab, your application must implement user authentication and ask the user to authenticate himself/herself prior to actually using the web application (based on an username and password saved in the database).
