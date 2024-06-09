## JWT and User Authentication

8. **Describe the user registration logic in your project. Provide a pseudo-code workflow from the registration request to storing the user in the database.**
<p>

The new user registers by going to 'POST/register/Register' under "Login and Registration".<br>
Click the "Try it out" button in the top right hand corner.<br>
Enter the new user information and click the "Execute" button below.
<p>

<br>Pseudo-code workflow from the registration request to storing the user in the database.

Register User:

[../app/routers/user_routes.py](../app/routers/user_routes.py)

![user_routes_UserService_register_user.png](../screenshots/homework02/08/user_routes_UserService_register_user.png)
<p>

<br>Add New User to Database:

[../app/services/user_service.py](../app/services/user_service.py)

![user_service_register_user_create.png](../screenshots/homework02/08/user_service_register_user_create.png)
<p>

![user_service_create_add_new_user.png](../screenshots/homework02/08/user_service_create_add_new_user.png)
<p>

<br>[Back to answer.md](../answer.md)
