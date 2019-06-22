<!DOCTYPE html>
<html lang="en">
<head>
<title> Job </title>
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
  h1{color: white;}
* {
  box-sizing: border-box;
}
body {
  margin: 0;
}
.navbar {
  overflow: hidden;
  background-color: darkslateblue ;
  font-family: Arial, Helvetica, sans-serif;
}
.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.dropdown {
  float: left;
  overflow: hidden;
}
.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font: inherit;
  margin: 0;
}
.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: purple;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  width: 100%;
  left: 0;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.dropdown-content .header {
  background: red;
  padding: 16px;
  color: white;
}
.dropdown:hover .dropdown-content {
  display: block;
}
/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  background-color: #ccc;
  height: 250px;
}
.column a {
  float: none;
  color: black;
  padding: 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}
.column a:hover {
  background-color: #ddd;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
<style>
body, html {
  height: 100%;
  font-family: Arial, Helvetica, sans-serif;
}
* {
  box-sizing: border-box;
}
.bg-img {
  /* The image used */
  background-image: url("job.jpg");
  min-height: 650px; 
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
/* Add styles to the form container */
.container {
  position: absolute;
  right: 0;
  margin: 20px;
  max-width: 300px;
  padding: 16px;
  background-color: white;
}
/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  border: none;
  background: #f1f1f1;
}
input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}
/* Set a style for the submit button */
.btn {
  background-color: red;
  color: white;
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}
.btn:hover {
  opacity: 1;
}
</style>
</head>
<body>
<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <ul class="nav navbar-nav navbar-right">
      <li><a href="#"> I'm looking for a job</a></li>
      <li><a href="#"> I'm looking to hire</a></li>
    </ul>
  </div>
  
<div class="navbar">
    
  <a href="#find a job">find a job</a>
  <a href="#employers">employers</a>
  <div class="dropdown">
    <button class="dropbtn">candidates 
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content"> 
      <div class="row">
        <div class="column">
          <h3>candidates</h3>
          <a href="#">start applying instantly</a>
        </div>
        <div class="column">
          <h3>get started</h3>
          <a href="#">job search</a>
          <a href="#">company search</a>
          <a href="#">create your cv</a>
          <a href="#">how it works</a>
        </div>
        <div class="column">
          <h3>find a job today</h3>
          <button type="button" class="btn btn-default">log in</button>
          <br> <br>
          <button type="button" class="btn btn-danger">register</button>
        </div>
      </div>
    </div>
  </div> 
</div>
<h1>employ.im</h1>
</nav>
<div class="bg-img">
  <form action="/action_page.php" class="container">
    <h2>Login</h2>
     
    <label for="name"><b>Name</b></label>
    <input type="text" placeholder="Enter Name" name="name" required>

    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Enter Email" name="email" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <label for="company"><b>Company</b></label>
    <input type="text" placeholder="Enter Company" name="company" required>

    <label for="job type"><b>Job Type</b></label>
    <input type="text" placeholder="Enter Job Type" name="job type" required>

    <button type="submit" class="btn">find a job now</button>
  </form>
</div>


<body>
</html>
