# Baidu_Web
!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title></title>
		<style type="text/css">
		body,html{
			padding: 0px;
		}
			#container{
				position: absolute;
				width: 400px;
				height: 200px;
				top:50%;
				left: 50%;
				margin-left: -200px;
				margin-top: -100px;
				background-color: #ccc;
				overflow: hidden;
			}
			#topCircle{
				margin-left: -50px;
				margin-top: -50px;
			}
			#bottomCircle{
				margin-left: 350px;
				margin-top: 100px;
			}
			.circle{
				background-color:#fc0;
				width: 100px;
				height: 100px;
				border-radius: 50%;			
			}
			*{
				-moz-box-sizing: border-box;
				 -webkit-box-sizing: border-box;
				 			box-sizing: border-box;
			}
		</style>
	</head>
	<body>
		<div id="container">
			<div class="circle" id="topCircle"></div>
			<div class="circle" id="bottomCircle"></div>
		</div>
	</body>
</html>
