# Correo


2021F COMP-3415-FA/FDE - Software Engineering Computer Science

Implementation
Android Messenger Application “Correro”


Project Members:

0888211 Dmitriy Chuyko
0904737 Arjun Omanakuttan
0903202 Roshith K. Ramesh
0874768 Zhijie Zhang


# 1, Glossary:

Application - foremost layer that is used to install the applications in the devices.
Application Framework - It is the third layer. It serves the services to the
application layer in the form of java classes.
Activity - Activity is an application component that provides a screen with which
users can interact in order to do something
Codeline - Codeline contains the release of a software product. It consists of one
or more branches from one or more repositories, all of which are often under active
development at once.
Debugging - Debugging requires finding and fixing errors in Android platform
code, either in features or their tests.

GIT - The source control tool used by Android that historically operated on a
single Git repository.

GIT Repository - Sometimes referred to as a project, this is a portion of the
codebase representing a particular component or type of device

Layout Resources - An XML file that describes the layout of an Activity screen.
Resources- Nonprogrammatic application components that are external to the
compiled application code, but which can be loaded from application code using a
well-known reference format.

Repo - A wrapper around Git to allow easier operations on multiple Git
repositories. It aggregates and manages the many Git repositories as a singular
checkout or codebase.

Theme - A set of properties (text size, background color, and so on) bundled
together to define various default display settings.

URI - URI (uniform resource identifier) strings as the basis for requesting data in a 
content provider (such as to retrieve a list of contacts) and for requesting actions in
an Intent (such as opening a Web page in a browser).

View - An object that draws to a rectangular area on the screen and handles click,
keystroke, and other interaction events. A view is a base class for most layout
components of an Activity or Dialog screen (text boxes, windows, and so on).



# 3. (a): Screenshot of Successful scenarios

![Login](https://user-images.githubusercontent.com/71609080/145503399-33946f1a-1eea-461f-b42c-e990ff6ba139.jpg)

![Signup](https://user-images.githubusercontent.com/71609080/145503407-d64452da-db28-4c65-a486-0e937221ee7f.jpg)

![Users](https://user-images.githubusercontent.com/71609080/145503418-85a44faf-0178-4466-b592-73b48af8a951.jpg)

![Chatroom](https://user-images.githubusercontent.com/71609080/145503350-9591b838-f302-4124-a162-ee10b28ad1fe.jpg)


# Scenario 1) Log- In


This is the very first scenario where the First time user can go to create a new

Correro account or the existing user can log in into the chat.
If the User Inputs the incorrect Email, or Password than the system will display
error messages (screenshots below).
Screenshot of Email error
Screenshot of Password Error
Session log displayed in the Firebase 

#Scenario 2) Registration (creating Account)

This is one of the scenarios that is utilized the first-timers. After clicking on “Don’t
have account?” button, the user will be send to this credential creation screen,
where the user can register his ID and password.
Scenario 3) Selecting Chat room
Here the user can select the chatroom that they are currently participating in.
Below is the button for when the user wants to create a new chat room.
Screenshots of New Chat room creation


Creation of new chat
Firebase Realtime Database log
Scenario 4 and 5) Sending/Receiving chat and uploading emoji
Here the User can start chatting with other users that have access to this chat.
Aside from sending and receiving messages, the user can add emojis that will be
sent alongside the message, or just emoji independently.
Screenshot of the Firebase Realtime database of the chat that was used


# 3. (e) User Manual:


Step 1: Run the code and initiate the Log-in Scenario. If you are a first-time user,
go to Step 2. Existing users can proceed to Step 3


Step 2: Click on the “Don’t have an Account?”. This will lead you to the
Authentication screen, where you can register for the Correro app. Input all the
necessary fields.


Step 3: Enter the Email and Password that was used to create the Firebase
Registration and access the Correro app.


Step 4: Upon successful log-in, you will be sent to the Chat selection screen. Here,
you can select the chat room that you are participating in. If you do not have any
chat rooms available or wish to create a new one, Simply Press on the “Create A 
New Chatroom” button. This will display a screen where you can enter your new
chat room name.


Step 5: Once you have enter into your chatroom, you can type in the message you
wish to send. After you finish typing, just simply press Send.

# 3. (e) Git/SVN links
https://github.com/aomanaku/Correo
