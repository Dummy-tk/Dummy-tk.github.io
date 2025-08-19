<html lang="en">
 <head>
<title>Backroom Information</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Bootstrap CSS -->
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
<style>
	 {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

/* Header/logo Title */
.header {
  padding: 40px;
  text-align: center;
  background: <img> background1.jpg;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: #323306;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: left;
  padding: 5px 10px;
  list-style: breadcrumb;
  text-decoration: true;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #323306;
}

/* Change color on active */
.navbar a.active {
   background-color: #323306;
   color: red;
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
 </head>
 <body>
   <!-- Header -->
  <div class=header>
   <style>
    body {
	background-image: url("Background1.jpg");
    }
   </style>
     <a href="https://dummy-tk.github.io/"><span style="color: #c4a404;font-family: Verdana;font-size: 55px"><b> BACKROOM </b></span></a>
  </div>

  <!-- navigationbar -->
   <nav class="navbar">
    <div class="container-fluid">
      <a href="#home">Trang chủ</a>
      <a href="#about">Thông tin</a>
     <form class="navbar-form navbar-right" action="/action_page.php">
      <div class="form-group">
        <input type="text" class="form-control" placeholder="Tìm kiếm...">
      </div>
      <button type="submit" class="btn btn-default"><span style="color: red">Tìm</span></button>
     </form>
  </div>
</nav>



  <!-- Middle -->
   <div class="container">
    <div class="row">
        <!-- Middle Text -->
        <div class="col-md-9">
            <h1>Middle Text</h1>
            <p> Testing   </p>
        </div>
	</div>
   </div>
<!-- Footer -->
   <footer class="bg-dark text-white text-center py-3">
    <span style="color: #d4d64b"> 
    <p>Project Backroom - Copyright &copy; 2023</p></span>
   </footer>
</body>
</html>