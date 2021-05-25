![BFH Banner](https://trello-attachments.s3.amazonaws.com/542e9c6316504d5797afbfb9/542e9c6316504d5797afbfc1/39dee8d993841943b5723510ce663233/Frame_19.png)
# Project Name
Our Project, 'Event Portal for Your College' using Python (Django) named VEA MESM(Virtual Event Assistant) allows a user to create a unique account (can call membership) and register for events. They can see their past attendance and upcoming events. We have provided a search bar in case the user requires assistance. Not only the user can register for events according to their choice from the event section, but they can also get all information on the event they registered for. The uncomplicated and manageable overall structure of the portal along with its color combination brings out a familiar feeling to the users, hence able to catch-up the portal settings pretty fast. Admin users can permit student users if they need to host an event. Admins can also monitor all the users and manage the user's status. The login and sign-in for the users are done in such a way that security issues are reduced and only admin can access their information if needed. Our Virtual Event Portal is a user-friendly and reliable one at that.
## Team members
1. Ashik Muhammed K N [https://github.com/poppy1006]
2. Muhammed A J [https://github.com/muhammedaj2002]
3. Steffy Senson [https://github.com/SteffySenson]
## Team Id
BFH/recqez40HH6WWA4sc/2021
## Link to product walkthrough
https://drive.google.com/drive/folders/1QGHIFHLIp8wmKsZQUHr1_bnOASa9viXm?usp=sharing
## How it Works ?
Overall Structure [https://app.dbdesigner.net/designer/schema/419953]
1. Step 1: For admins, we can log in after creating a superuser, and for users, first register for an account, then log in.
2. Step 2: Separate pages are set for Admins and Student Users. In navigation bar, a Dashboard, Users tab, All Events tab, and Registration tab, is set for Admins, and All Events tab, Members, Create Events and Profile tab is set for Student Users.
3. Step 3: Admins can see the number of Total Events, Events Completed, and Upcoming Events along with the last created 5 Students, Events, and Registration in the dashboard. Whereas the users can see their number of Total Events, Events Completed, and Upcoming Events along with all their Registered Event details. User can register for events and can see all the members of the club portal.
4. Step 4: Admins have the permission to create Users and Events and give Users permission for creating events if necessary.
5. Step 5: If a user forgot his/her password, he or she can select the forgot password option on the login page and thus reset their password by entering through the link sent to his/her registered mail.
6. Step 6: Admins can view the details of Student Users and Events and update or delete them if necessary.
## Libraries used
Frontend - HTML(Bootstrap)
Backend - Python (version - 3.9.5), Django (version - 3.2.3)
## How to configure
$ pip install requirements.txt
$ heroku open
$ heroku run python manage.py runserver
Admin User name: muhammed
Admin password: muhammed@123
Or Create Superuser for Admin-->$heroku run python manage.py createsuperuser
## How to Run
$ python manage.py runserver