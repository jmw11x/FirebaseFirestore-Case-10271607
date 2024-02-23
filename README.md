Folder contains a new project configured that I made today (same error) 

Project ID : firestoremcve
Project number : 653252239666

You can firebase serve and it is all ready inside folder.

You can view data without creating an account and also with creating an account there is a button for both on the root index page.

I have not included persistant cache on this repo. 

Problem Statment: Safari is not displaying data at all with defaut settings for onSnapshot method while on other browsers data loads normally.
  =>To see this issue view either of the pages at 
    1) /Users/data.html (logged in) 
    2) or at /Users/noauthdata.html on local server (edit firestore.rules from if request.auth != null to if true to revoke auth privlages)
