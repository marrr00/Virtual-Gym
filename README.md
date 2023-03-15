<h1 align="center">
<img src="https://image.flaticon.com/icons/svg/2527/2527955.svg" width="20%" height="20%">
</h1>
<h3 align="center">
MERN STACK V-GYM - Software Engineering immersive <a href="https://generalassemb.ly/" target="__blank">General Assemply</a>
</h3>



## :computer: MERN Stack Project

### Integrate Backend with Frontend using API
we create API in the Backend, then we called the API in the frontend 

### Example of creating and calling the API :
### Creating API in the backend 
 open  route/user.route.js file 
 find line number 7 
 $ // this code create Post API to signup new user 
 $ // ** note: user data stored in the database schema located in /models/user.model.js
 $router.post("/signup", async (req, res)

### Call created API in the frontend
open  /frontend/src/Components/User/Signup.jsx
find line number 13
$ // this code call API signup
$ .post("http://localhost:5000/api/users/signup", this.state)
