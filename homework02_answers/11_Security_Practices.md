## Security Practices

11. **Explain the difference between hashing and encoding. Provide examples from your project where each is used:**
    - **Hashing:** Example and explanation with code
    - **Encoding:** Example and explanation with code
<p>

<br>Hashing algorithms are one-way functions that produce a hashed value of the data that can not be reversed which provides additional security.<br>
An example of when to use a hashing algorithm is when storing passwords (hashed passwords).

[../app/services/user_service.py](../app/services/user_service.py)

![user_service_hash.png](../screenshots/homework02/10/user_service_hash.png)
<p>

<br>Encoding is reversible, used to represent data in a specific format when the data is being transmitted or stored, but does not provide security.<br>
An example of when to use encoding is when generating a JWT token for a user login.

[../app/routers/user_routes.py](../app/routers/user_routes.py)

![user_routes_login_create_access_token.png](../screenshots/homework02/11/user_routes_login_create_access_token.png)

[../app/services/jwt_service.py](../app/services/jwt_service.py)

![jwt_service_create_access_token.png](../screenshots/homework02/11/jwt_service_create_access_token.png)
<p>

<br>[Back to answer.md](../answer.md)
