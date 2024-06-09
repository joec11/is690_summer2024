## JWT and User Authentication

9. **Detail the steps involved in the user email verification process. Provide a pseudo-code workflow from sending a verification email to activating the user's account.**
<p>

A user email is verified by going to 'GET /verify-email/{user_id}/{token} Verify Email' under "Login and Registration".<br>
Click the "Try it out" button in the top right hand corner.<br>
Enter the new user_id (id) and the token (verification_token) and click the "Execute" button below.
<p>

<br>Pseudo-code workflow from sending a verification email to activating the user's account.

Verify Email:

[../app/routers/user_routes.py](../app/routers/user_routes.py)

![user_routes_verify_email.png](../screenshots/homework02/09/user_routes_verify_email.png)
<p>

<br>Update User Email Verified Status in Database:

[../app/services/user_service.py](../app/services/user_service.py)

![user_service_verify_email_with_token.png](../screenshots/homework02/09/user_service_verify_email_with_token.png)
<p>

<br>[Back to answer.md](../answer.md)
