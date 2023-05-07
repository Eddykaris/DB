<!DOCTYPE html>
<html>
<head>
	<title>Eddy Marster</title>
	<style type="text/css">
		body {
			font-family: Arial, Verdana, sans-serif;
			font-size: 90%;
			color: #666
			background-color: #f8f8f8;}
		li {
			list-style-type: ;
			line-height: 1.6 em;}
		table {
			border-spacing: 0px;}
		th, td {
			padding: 5px 30px 5px 10px;
			margin: 0px;
			text-align: left;
			background-color: #e0e9f0;
			border: 1px solid #cbd2d8;
			border top: 1px solid #f1f8fe;}
		tr.head th {
			color: #fff;
			background-color: #90b4d6;
			border: 1px solid #90b4d6
			border-bottom: 2px solid #749abe;
			text-align: center;
			text-shadow: -1px -1px 1px #666
			letter-spacing:0.15em;}
		td {text-shadow: 1px 1px 1px #fff;}
		tr.even td, tr.even th {background-clip: #e8eff5}
		tr.head th: first-child{
			-webkit-border-top-left-radius:5px;
			-moz-border-radius-top-left:5px;
			border-top-left-radius:5px;}
		tr.head th: last-child{
			-webkit-border-top-right-radius:5px;
			-moz-border-radius-top-right:5px;
			border-top-right-radius:5px;}
		fieldset {
			width: 310px;
			margin-top: 20px;
			border: 1px solid #d6d6d6;
			background-color: #ffffff;
			line-height: 3.6em;}
		legend {font-style: italic; color: #666666}
		input[type="text"] {
			width: 120px;
			border: 1px solid #d6d6d6
			padding:2px;
			outline: none;}
		input[type="text"]:focus,
		input[type="text"]:hover{
			background-color: #d0e2f0;
			border: 1px solid #999;}
		input[type="submit"]{
			border: 1px solid #006633;
			background-color: #009966;
			color: #ffffff;
			border-radius: 5px;
			padding: 5px;
			margin-top: 10px;}
		input[type="submit"]:hover{
			border: 1px solid #006633;
			background-color: #00CC33;
			color: #ffffff;
			cursor: pointer;}
		.title{
			float: left;
			width: 160px;
			clear: left;}
		.submit {
			width: 310px;
			text-align: right;}
	</style>
</head>
<body>
	<h1>Meal Plan</h1>
	<P>
		The planing of food is critical.
		We should be both physicaly and phycological be prepared on what we desire to eat.
		The timing of what as well as when we to have a meal is a <a href="http://google.com" target="_blank">healthy life practice</a>.
	</P>
	<h2> GODS GRACE </h2>
	<p>
		It is essencal to pray for God's grace so that he may guide you through your path.
	</p>

	<h2>
		Shopping list
	</h2>
	<p>
		<ol>
			<li>Maize flour</li>
			<li>Wheat flour</li>
			<li>Rice</li>
			<li>Maize&beans</li>
			<li>Cooking oil</li>
		</ol>

		<h3>Regular stock</h3>
		<ul>
			<li>Tomatoes</li>
			<li>Onions</li>
			<li>Cabbage</li>
			<li>Potatos</li>
			<li>Rice</li>
			<li>Maize Flour</li>
			<li>Kunde</li>
			<li>Ndengu</li>
			<li>Wheat flour</li>
			<li>Omena</li>
		</ul>
	</p>

	<h2>
		Meal time table
	</h2>
	<p>
		<table>
			<thead>
				<tr class="head">
					<th>WEEK</th>
					<th>Monday</th>
					<th>Tuesday</th>
					<th>Wednesday</th>
					<th>Thusday</th>
					<th>Friday</th>
					<th>Sarturday</th>
					<th>Sunday</th>
				</tr>
			</thead>
			<tbody>
				<tr class="even">
					<th>W1 3rd to 9th</th>
					<td>Ugali Omena</td>
					<td>Rice ndengu</td>
					<td>Ugali Cabbage</td>
					<td>Rice kunde</td>
					<td>Ugali mayai</td>
					<td>Rice Viazi</td>
					<td>Githeti or Special</td>	 
				</tr>
				<tr>
					<th>W2 10th to 16th</th>
					<td>Ugali Omena</td>
					<td>Rice ndengu</td>
					<td>Ugali Cabbage</td>
					<td>Rice kunde</td>
					<td>Ugali mayai</td>
					<td>Rice Viazi</td>
					<td>Githeti or Special</td> 
				</tr>
				<tr class="even">
					<th>W3 17th to 23rd</th>
					<td>Ugali Omena</td>
					<td>Rice ndengu</td>
					<td>Ugali Cabbage</td>
					<td>Rice kunde</td>
					<td>Ugali mayai</td>
					<td>Rice Viazi</td>
					<td>Githeti or Special</td>
				</tr>
			</tbody>
		</table>
		
	</p>
	<h2> Members Choices</h2>
	<p>
		<form action="eddys.php" method="get">
			<fieldset>
				<legend>Family member details</legend>
				<p>
					<label class="title" for="name">Member's Name</label>
					<input type="text" name="Members name" id="name"> <br />
					<label class="title" for="email">Email</label>
					<input type="email" name="email" id="email"> <br>
					<label for="Gender" class="title">Gender</label>
					<select name="Gender" id="Gender">
						<option value="Male">Male</option>
						<option value="Female">Female</option>
						<option value="others">Other</option>
					</select><br>
					<span class="title"> Are you a family Member</span>
					<label><input type="radio" name="Member"/> Yes</label>
					<label><input type="radio" name="Member"/> No</label> <br>
					<label>Age</label>
					<input type="number" name="age" value="27"><br>
					<label>Date of birth</label>
					<input type="date" name="DOB"><br>
					<label>Speak your mind out</label>
					<textarea name="Speak your mind out"></textarea><br>	
					<div class="submit"><input type="Submit" name="Submit" value="Confirm"></div>
				</p>
			</fieldset>	
		</form>
	</p>
	<p>
		<button>next meal</button>
	</p>
	<h2>
		Food Sample Of the week
	</h2>
	<p>
		<a href="Images/Project1.jpg" target="_blank">
			<img src="Images/Project1.jpg" alt="Project1" width="200" height="100"></a>
		<img src="Images/Project2.jpg" alt="Project2" width="200" height="100">
		<img src="Images/Project3.jpg" alt="Project3" width="200" height="100">
		<img src="Images/Project4.jpg" alt="Project4" width="200" height="100">
	</p>


</body>
</html>

