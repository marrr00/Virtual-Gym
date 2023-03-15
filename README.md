


## :computer: MERN Stack Project


### Integrate Backend with Frontend using API
we create API in the Backend, then we called the API in the frontend 

### Example of creating and calling the API :
### Creating API in the backend 
 open  ``` route/user.route.js ``` file 
 at line number 7 
 
 ```javascript
 // this code create Post API to signup new user 
 // ** note: Data stored in the database schema located in /models/user.model.js
 router.post("/signup", async (req, res)
```
### Call created API in the frontend
open  ``` /frontend/src/Components/User/Signup.jsx ``` file
at line number 13
 ```javascript
// this code call API signup
.post("http://localhost:5000/api/users/signup", this.state)
```
