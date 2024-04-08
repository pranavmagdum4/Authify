# Authify
# Description
This project implements user authentication and registration
features using JSON Web Tokens (JWT) in a full-stack application 
built with Node.js, Express.js, React.js, and MySQL. 
The primary focus is on enhancing security by 
mitigating common web vulnerabilities such as Cross-Site Scripting (XSS) 
and Cross-Site Request Forgery (CSRF) attacks.

## Installation

### Backend (Node.js/Express + MySQL)

1. Clone the repository to your local machine:

```bash
git clone <repository-url>
```    

2.Navigate to the backend directory:

```bash
cd backend
```

3.Install dependencies:

```bash
npm install
```

4.Configure the environment variables:

Create a .env file in the root of the backend directory.
Add the required environment variables (e.g., database connection details, JWT secret).

5.Start the backend server:

```bash
nodemon index
```

### Frontend (React.js)
1. Navigate to the frontend directory:

```bash
cd frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend development server:

```bash
npm start
```
# Testing
After successfully running both the backend and frontend,
you can access the registration page at [http://localhost:3000/register](http://localhost:3000/register).

If it goes well, it will look like the following image:

1. **Register:** Enter your name, email, password, and confirm password, then click the Register button.

  ![Registration Page](/images/register.png)

  This screenshot shows the registration page where users can sign up for your application.
  
2. **Login:** After registering successfully, you will be directed to the login form. Enter your username and password, then click the Login button.

   ![Login Page](/images/login.png)

3. **Dashboard:** Upon successful login, you will be directed to the dashboard page where you can access various features of the application.

   ![Dashboard Page](/images/dashboard.png)

4. **Logout:** To logout, simply click the “Logout” button, and you will be redirected to the login form.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
