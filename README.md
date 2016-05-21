# make-mamma-happy
 
 Make Mamma Happy App is a side project I will be working on outside of NSS that was almost chosen as my final capstone project.  Motivation for this app came about as I have an expecting wife who is always adding additional tasks to my busy schedule.  This is more than just a simple to do list as I will be incorporating Twillio API for notifying my wife via text (SMS) to update her on the status or completion of the tasks at hand.  This will also hopefully prevent as many back and forth texts/discussions from our hectic lives when away from home.

Features
-User can assign tasks to self or to other registered user
-User can set reminders and upload before and after pictures if needed
-Upon completion of the assigned task a text/sms will be sent notifying the assignee that the task has been completed so they know real time when it has been done
-Can send alerts/reminders from the app itself where you don't feel like your significant other is nagging 

Implementation
-Back end
     -Using ASP.NET MVC
    -set tasks, task due date (prioritization), location, urgent checkboxs
    -Oauth using Google but will also prompt first time user for telephone number if they wish to receive updates via text/sms
    -Using DateTime would also like to set up future automated reminders 

-Front End
    - HTML, JS, Jquery, Bootstrap, and Angular framework
        -Login page directing you to app dashboard
        -app dashboard will allow for you to choose options such as:  search/connect/invite other users, assign tasks, mark tasks as complete, review completed tasks, review pending tasks, and "my account" feature to update phone/text preferences.
