## Security-Service API

### This is a personal project.
> Using this to build experience working with Spring Security.

### Overview:

- In this program i'm getting my hands dirty with JWT.
- I'm assigning each registered user an Access + Refresh Token.
 
- They then use their access token as a Bearer to get Authorization.
- If their token expires, they can use the refresh token to get a new token.

---

### Login
> I've already registered a few users. Here i'm logging in with one of them and getting an access + refresh token.

---

![Screenshot (13)](https://user-images.githubusercontent.com/81378094/139023469-acc19afb-e7a3-4034-a60c-799a0c8ffd89.png)

---

### Access Denied
> Trying to get access without authorization.

---

![Screenshot (14)](https://user-images.githubusercontent.com/81378094/139024055-ec77981f-9864-4ff7-838c-e4ed397db33a.png)

---

### Access Denied
> Trying to get access by providing a fake Bearer token.

---

![Screenshot (3)](https://user-images.githubusercontent.com/81378094/139024428-023fc3d5-bf8a-4feb-a6b8-429f180f72b8.png)

---

### Access Granted
> Providing the correct Bearer Token and getting access to a list of all the users + their roles in the database.

---

![Screenshot (31)](https://user-images.githubusercontent.com/81378094/139025390-f239282c-257a-4bd7-b504-f2bd0787652e.png)

---

### Token Expired
> The user no longer has access to the application.

---

![Screenshot (32)](https://user-images.githubusercontent.com/81378094/139026442-6a852b77-0115-4614-acee-500e0f391a12.png)

---

### Refreshing token
> Using the refresh token to generate a new token, giving the user access to the application again.

---

![Screenshot (33)](https://user-images.githubusercontent.com/81378094/139026890-df1552e4-75ea-4b8e-ba56-cd56da55c90f.png)

---
