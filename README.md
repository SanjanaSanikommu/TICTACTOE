# TICTACTOE
<html>
<head>

<style>

#grid{
	width:300px;
	height:300px;
	position:absolute;
	left:50%;
	top:50%;
	margin:-100px 0 0 -100px;

}

.rows{
	width:90%;
	height:30%;
	
	padding:2px;
	margin: 2px;
}

.cell{
	width: 30%;
	height: 100%;
	float:left;
	background-color:orange;
	margin:2px;
	padding: 2px;
	display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 7px;
}

</style>

<script src="WEB_02_06.js"> </script>


</head>
<body onload = "loadGame(3)">

<div id="grid">

</div>

</body>
</html>







