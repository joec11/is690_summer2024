## Security Practices

10. **How do you ensure the security of user passwords in your project? Discuss the hashing algorithm used and any additional security measures implemented.**
<p>

The security of user passwords can be ensured in the project by using a hashing algorithm. Hashing is one-way which means that the hashed value of the data can not be reversed. When the user enters their password into the login form, the password is given to a hashing algorithm that converts the text into a special string that must match the hashed password value of the user stored in the database in order to authenicate the user into the system.
<p>

[../app/services/user_service.py](../app/services/user_service.py)

![user_service_hash.png](../screenshots/homework02/10/user_service_hash.png)

The hash_password function uses the bcrypt hash algorithm.
<p>

<br>[Back to answer.md](../answer.md)
