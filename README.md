<html>
<head>
	<title>Teacher's Day</title>
	<link rel="icon" type="image/x-icon" href="party.png" />
<!--<link rel="stylesheet" media="screen and (max-width: 750px)" href="max-width 750.css">--> 


	<style>

   body
   {
      background: red;
   }
}
		html{
			height: 100%;
		}
         *{
         	box-sizing: border-box;

         }
         body{
         	
         	background-color: lightblue;
         
		 background-repeat:no-repeat;
display: flex;
justify-content: center;
         	align-items: center;

         }
         
         #main{
         
         	perspective: 800px;
         	margin:200px;
         	
         }
         #img{
         	transform-style: preserve-3d;
         	width:300px;
         	height:300PX;
         	margin: auto;
         	animation: cube 15s infinite linear ;
         	position: relative;
         }
         @keyframes cube{
         	0%{
         		transform:rotateX(0deg) rotateY(0deg);
         	}
         	100%{
         		transform: rotateX(360deg) rotateY(360deg);
         	}
         	

         }
         #img  img{
         	position: absolute;
         	
         	opacity: 0.95;
         	width: 200px;
         	height: 200px;
         	border:4px solid black;
         }
		img:nth-child(1){
			transform:rotateY(0deg) translateZ(100px);
		}
		img:nth-child(2){
			transform:rotateY(90deg) translateZ(100px);
		}
		img:nth-child(3){
			transform:rotateY(180deg) translateZ(100px);
		}
		img:nth-child(4){
			transform:rotateY(-90deg) translateZ(100px);
		}
		img:nth-child(5){
			transform:rotateX(90deg) translateZ(100px);
		}
		img:nth-child(6){
			transform:rotateX(-90deg) translateZ(100px);
		}
		

#main2{
	display: flex;
         	justify-content: center;
         	align-items: center;
         	
         	width: 200px;
         	height: 200px;
         	transform-style: preserve-3d;
         	animation:slideShow  30s infinite linear ;
         	margin-top: 200px;
         	margin-bottom: 200px;	
	margin-right: 100px;
position: absolute;
         }
         @keyframes slideShow{
         	0%{
         		transform: perspective(800px) rotateY(0deg);
         	}
         	100%{
         		transform: perspective(800px) rotateY(360deg);
         	}
         	

         }
         #main2 span{
         	position: absolute;
         	transform-style: preserve-3d;
         	transform-origin: center;
         	width: 100%;
         	height: 100%;

         }
		span:nth-child(1){
			transform:rotateY(16.36363636363636deg) translateZ(370px);
		}
		span:nth-child(2){
			transform:rotateY(32.72727272727272deg) translateZ(370px);
		}
		span:nth-child(3){
			transform:rotateY(49.09090909090908deg) translateZ(370px);
		}
		span:nth-child(4){
			transform:rotateY(65.45454545454544deg) translateZ(370px);
		}
		span:nth-child(5){
			transform:rotateY(81.8181818181818deg) translateZ(370px);
		}
		span:nth-child(6){
			transform:rotateY(98.18181818181816deg) translateZ(370px);
		}
		span:nth-child(7){
			transform:rotateY(114.5454545454545deg) translateZ(370px);
		}
		span:nth-child(8){
			transform:rotateY(130.9090909090909deg) translateZ(370px);
}
		span:nth-child(9){
			transform:rotateY(147.2727272727272deg) translateZ(370px);
		}
		span:nth-child(10){
			transform:rotateY(163.6363636363636deg) translateZ(370px);
		}
		span:nth-child(11){
			transform:rotateY(180deg) translateZ(370px);
		}
		span:nth-child(12){
			transform:rotateY(196.3636363636363deg) translateZ(370px);
		}
		span:nth-child(13){
			transform:rotateY(212.7272727272727deg) translateZ(370px);
		}
		span:nth-child(14){
			transform:rotateY(229.090909090909deg) translateZ(370px);
		}
		span:nth-child(15){
			transform:rotateY(245.4545454545454deg) translateZ(370px);
		}
		span:nth-child(16){
			transform:rotateY(261.8181818181818deg) translateZ(370px);
		}
		span:nth-child(17){
			transform:rotateY(278.1818181818181deg) translateZ(370px);
		}
		span:nth-child(18){
			transform:rotateY(294.5454545454545deg) translateZ(370px);
		}
		span:nth-child(19){
			transform:rotateY(310.9090909090908deg) translateZ(370px);
		}
		span:nth-child(20){
			transform:rotateY(327.2727272727272deg) translateZ(370px);
		}
		span:nth-child(21){
			transform:rotateY(343.6363636363636deg) translateZ(370px);
		}
		span:nth-child(22){
			transform:rotateY(360deg) translateZ(370px);
		}
span img{
	position: absolute;
	height: 65%;
	width: 65%;
}
marquee{
	margin-top: 400px;
		color: red;
		background-color: lightgreen;
		font-size: 50px;
		font-family: 'Algerian',serif;

}
button{
	background-color: lightgreen;
	color: red;
	transition-duration: 0.4s;
	font-size: 20px;
	border-radius: 10px;
}
button:hover{
	background-color: pink;
	color: lightgreen;
}



	</style>



</head>
<body>
<button style="align-self: left;margin-bottom: 500px;" onclick="myFunction()">Click</button>

<div id="main2">
<span>
		<img src="1.png">
	</span>
	<span>
		<img src="2.png">
	</span>

	<span>
		<img src="3.png">
	</span>
<span>
	<img src="4.jpg">
</span>
<span>
	<img src="5.jpg">
</span>
<span>
	
	<img src="6.png">
</span>
<span>
	<img src="7.png">
</span>
<span>
	<img src="8.png">
</span>
<span>
		<img src="22.PNG">
	</span>
	<span>
		<img src="11 .png">
	</span>

	<span>
		<img src="12.png">
	</span>
<span>
	<img src="13 .png">
</span>
<span>
	<img src="14.png">
</span>
<span>
	
	<img src="15.png">
</span>
<span>
	<img src="16.png">
</span>
<span>
	<img src="18.png">
</span>
<span>
	<img src="19 .png">
</span>
<span>
	<img src="20.png">
</span>
<span>
	<img src="21.png">
</span>
<span>
	<img src="25.jpg">
</span>
<span>
	<img src="23.jpg">
</span>
<span>
	<img src="24.jpg">
</span>
<audio autoplay loop> 
	<source src="bgm.mp3" type="audio/mp3" id="audio1">
</audio>


</div>
<br><br>

</body>

<marquee scrollamount=15px>Happy Teacher's Day To All My Dear Teachers</marquee>


<SCRIPT language=JavaScript>

<!-- http://www.spacegun.co.uk -->

var message = "function disabled";

function rtclickcheck(keyp){ if (navigator.appName == "Netscape" && keyp.which == 3){ alert(message); return false; }

if (navigator.appVersion.indexOf("MSIE") != -1 && event.button == 2) { alert(message); return false; } }

document.onmousedown = rtclickcheck;

function myFunction(){
	var x=document.getElementById('audio1');
	x.play;
}
</SCRIPT>
</html>
