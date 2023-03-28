<!DOCTYPE html>
<html>
<head>
	<title>Searchable Button Options</title>
	<style>
		/* Add some basic styles to the search bar and buttons */
		input[type="text"] {
			padding: 8px;
			border: none;
			border-radius: 5px;
			margin-bottom: 20px;
			width: 100%;
		}
		
		button {
			background-color: #4CAF50;
			color: white;
			padding: 14px 20px;
			margin: 8px 0;
			border: none;
			border-radius: 5px;
			cursor: pointer;
			width: 100%;
		}
		
		button:hover {
			background-color: #45a049;
		}
		
		/* Add some styles to the container div that holds the buttons */
		.container {
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			max-width: 800px;
			margin: 0 auto;
		}
		
		/* Add some styles to the individual button elements */
		.box {
			background-color: #f2f2f2;
			padding: 20px;
			margin: 10px;
			text-align: center;
			width: 200px;
			height: 200px;
			border-radius: 5px;
			box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
			transition: 0.3s;
		}
		
		.box:hover {
			box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
		}
		
		.box h2 {
			margin-top: 0;
		}
	</style>
</head>
<body>
	<!-- Add the search bar at the top -->
	<div>
		<input type="text" placeholder="Search...">
	</div>
	
	<!-- Add the container div that holds the buttons -->
	<div class="container">
		<!-- Add some example buttons -->
		<div class="box">
			<h2>Button 1</h2>
			<p>This is an example button.</p>
		</div>
		
		<div class="box">
			<h2>Button 2</h2>
			<p>This is another example button.</p>
		</div>
		
		<div class="box">
			<h2>Button 3</h2>
			<p>This is a third example button.</p>
		</div>
		
		<div class="box">
			<h2>Button 4</h2>
			<p>This is a fourth example button.</p>
		</div>
	</div>
</body>
</html>
