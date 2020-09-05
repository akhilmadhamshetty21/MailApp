# MailApp

## Part A: Login  
The requirements are as follows:  
1. The user should provide their email and password. The provided credentials should be used to authenticate the user 
using the provided login api. Clicking the “Login” button should submit the login information to the api to verify the user’s credentials.  
a) If the user is successfully logged in then start the Chat Screen, finish the Login
Screen, and save the token in Shared Preferences.
b) If the user is not successfully logged in, then show a toast message indicating
that the login was not successful.
2. Clicking the “Sign Up” button should start the Signup Screen, and finish the login Screen.

## Part B: SignUp  
Create the Signup screen with the following requirements:
1. Clicking the “Cancel” button should finish the Signup Screen and start the Login Screen.  
2. The user should provide their first name, last name, email, password and password
confirmation. Preform the required validation(the given password and the repeated
password must match). Clicking the “Sign Up” button should submit the user’s
information to signup API.  
a) If the signup API is not successful, It will display an error message indicating the error
message received from the api.
b) If the signup API is successful, then store the returned token in the shared
preferences, and display a Toast indicating that the user has been created. Then
start the Chat Screen and finish the Signup Screen.

## Part C: Inbox  
This is the home screen which displays the list of emails:    
1. There should be two ImageViews/Buttons: (i) Create New Email, and (ii) Logout.  
2. Clicking on Create New Email button, It should take you to Create New Email screen.  
3. Clicking on the Logout button (top-right) should log you out and take you to the
Login Screen.  
4. In between two ImageButtons, there should be a TextView to display the username.  
5. The email list should be implemented using RecyclerView. Each item in the list
should have three things:  
      1.  TextView with Subject. It should display only the first line. If the sentence
          exceeds the limit of the line, end it with three dots.  
      2.  TextView with DateTime. Display the date when the email was created.  
      3.  An ImageView/Button with Delete icon.   
6. Clicking on any of the item in the RecyclerView should open the Display Mail Screen.  
7. Clicking on the Delete ImageView should call the Delete API and delete the particular message from Inbox.

## Part D: Create New Email (25 Points)
Clicking on Create New Email ImageView should take you to Create New Email Screen.
Please follow the instructions:
1. You should get the users using the Users API, and add them in a Spinner (Drop Down). Every item in the Spinner should display “FirstName LastName.”  
2. You have to select the user you want to send the email to.  
3. Next, you need to display an EditText to get the subject.  
4. And, display a multiline EditText for the message.  
5. Finally, a Send button to send. 
6. Clicking on the Send button should call Add API and send the message. Display a Toast saying that the message  
is sent, and finish the activity.
7. Clicking on Cancel button should finish the activity.  

## Part E: Display Mail (5 Points)
Design the UI yourself that contains:  
1. Sender Name.  
2. Subject.  
3. Message.  
4. Created at.  
5. A Close button to finish the Activity.
