## JWT and User Authentication

7. **Decode the following JWT and explain its contents:**
   - Token: `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJqb2huLmRvZUBleGFtcGxlLmNvbSIsInJvbGUiOiJBRE1JTiIsInVzZXJfaWQiOiJjZGY4M2QzZi0zNzQ5LTRjZGQtOTRlYS1hNTVjZmMwNDhkMGYiLCJleHAiOjE3MTc2MTY4MjAuMjIwNzA5fQ.ANS8PgUiwPCmOvnZLYTCy_5WzLyhCDOx8aF4xu-Kaz8`
   - Use [jwt.io](https://jwt.io/) to decode and explain the contents.
<p>

<br>
<b>Decoded</b><br>

- HEADER: ALGORITHM & TOKEN TYPE<br>

      {
         "alg": "HS256",
         "typ": "JWT"
      }

   | Key | Description |
   |----------|----------|
   | alg | the signature or the encryption algorithm used |
   | typ | the token type |
<br>

- PAYLOAD: DATA<br>

      {
         "sub": "john.doe@example.com",
         "role": "ADMIN",
         "user_id": "cdf83d3f-3749-4cdd-94ea-a55cfc048d0f",
         "exp": 1717616820.220709
      }

   | Key | Description |
   |----------|----------|
   | sub | the subject of the token |
   | role | the authorization status of the subject |
   | user_id | the unique id of the subject |
   | exp | the expiration time of the token |
<p>

<br>[Back to answer.md](../answer.md)
