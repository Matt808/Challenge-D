# Challenge-D 


<html>

	<head>
		<!-- important information the computer needs -->
		<meta charset="utf-8">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon" />
		<title>Flex v. Block</title>
		<link rel="stylesheet" href="style.css" />
	</head>
    
	<body>
		<!-- all content that shows up on the web page --> 
		<div class="container-1">
			<div class="row green"></div>  
			<div class="row light_blue"></div>   
		</div>
		<div class="container-2">
		    <div class="box purple"></div>
	        <div class="box red"></div>
            <div class="box orange"></div> 
        </div>
	
	</body>
	
</html>

.body {   
 margin: 0;
}

.green {
	background-color: #008D24; 
}

.light_blue {
	background-color: #0B69C0;
}

.purple {
	background-color: #3A246D;
}

.red {
	background-color: #CA1B22;
}

.orange {
	background-color: #EA6626;
}

.box {
	height: 100%;
	width: 50%; 
	display: flex; 
}

.container-1 { 
  display: flex;
  width: 100%;
  height: 50%;  
} 

.container-2 {
  display: flex; 
  height: 50%;
  width: 100%; 
  
}
.row {
	height: 100%;
	width: 100%; 
    display: flex;	
	
}
