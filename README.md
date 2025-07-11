<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
    <title>My First HTML Page</title>
</head>
<body>
<nav class="navbar">
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#table">Table</a></li>
    <li><a href="#form">Form</a></li>
    <li><a href="#end">End</a></li>
  </ul>
</nav>
<h1 id="home" class="title"><p align="center">REQUIRED TASK</p></h1>
<p style="color:red;font-size:15px;:">I tried to make a customized webpage which contains a <b>table</b> and a <b>form</b> with the given requirements.</p>
<p>*********************************************************************************************************************************************************************************************************</p>

<div class="flex-container">
<div class="box">
<h3 id="table"><p align="center"><mark>THE TABLE</mark></p></h3>
<div style="background-color:lightblue;padding:20px;text-align:center;">
<table border="2" align="center">
<tr>
<th>NAME</th>
<th>ENGLISH</th>
<th>BENGALI</th>
</tr>
<tr>
<td>RAM</td>
<td>90</td>
<td>86</td>
</tr>
<tr>
<td>SHYAM</td>
<td>88</td>
<td>87</td>
</tr>
</table>
</div>
</div>


<div class="box">
<h3 id="form"><p align="center"><mark>THE FORM</mark></p></h3>
<div style="background-color:lightgreen;padding:10px;text-align:center">
<form>
<label for="name">YOUR NAME:</label><br>
<input type="text" id="name" name="name"><br><br>
<label for="email">YOUR EMAIL ADDRESS:</label><br>
<input type="email" id="email" name="email"><br><br>
<label for="favourite programming language">YOUR FAVOURITE PROGRAMMING LANGUAGE:</label><br>
<input type="text" id="favourite programming language" name="favourite programming language"><br><br>
<input type="submit" value="submit">
</form>
</div>
</div>
</div>
<p>Hope you liked the table.</p>
<p>Now its time to show the form.</p>
<p>*********************************************************************************************************************************************************************************************************</p>
<div style="background-color:purple;padding:10px;text-align:center">
<h4><p align="center" style="color:white;font-size:60px;"><b>THE END</b></p></h4>
</div>

...
<div id="end" class="end-banner">

</body>
</html>
