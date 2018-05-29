

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
	<style>
		*{
			margin: 0;
			padding: 0;
		}
		.all{
			background-image: url(img/111/img/banner.jpg);
			background-attachment: fixed;
			background-repeat: no-repeat;
			background-size: cover;
			background-position: center center;
		}
		nav{
			background:scroll;
			height: 50px;
		}
		#banner{
			background: scroll;
			height: 700px;
		}
		header{
			background: rgba(0,0,0,0.2);
		}
		nav ul{
			list-style: none;
			margin: 0;
			float: right;
		}
		nav ul li, nav .logo{
			display: inline-block;
			line-height: 50px;
			margin-right: 20px;
		}
		nav ul li a{
			text-decoration: none;
			line-height: 50px;
			display: inline-block;
			height: 50px;
			color: #fff;
		}
	
			nav div a{
				color: #fff;
				text-decoration: none;
				margin-left: 20px;
				font: 20px;
				font-weight: 700;
			}
			#banner .inner{
				max-width: 300px;
				text-align: center;
				margin: 0 auto;
				position: relative;
				top: 200px;
				color: white;
				font-weight: 600;
			}
			#banner .inner h1{
				margin: 0;
			}
			button{
				border: none;
				background: #0f8592;
				color: #EEEEEE;
				cursor: pointer;
			}
			#banner button{
					padding: 14px 60px;
					font: 18px;
			}
			#banner .inner .more{
				margin-top: 220px;
				display: block;
				cursor:pointer;
			}
			#banner .inner .text{
				margin: 30px;
				line-height: 30px;
			}
			.green-section{
				background: #1a9c8b;
				color: #fff;
				text-align: center;
				padding: 100px 0;
			}
			.wrapper{
				max-width: 1080px;
				margin: 0 auto;
			}
			.hr{
				width: 100%;
				height: 2px;
				margin: 20px auto;
				
			}
			.green-section .hr{
				background: #0a7d6e;
				width: 60%;
			}
			.wrapper p{
				font-size: 18px;
				padding: 20px;
			}
			.green-section .icon-group .icon{
				display: inline-block;
				width: 80px;
				height: 80px;
				transform: rotate(45deg);
				margin: 20px;
				background: #1b8b8c;
			}
			.icon-group{
				margin-top: 60px;
			}
			.grey-section{
				background: #363e54;
				color: #fff;
			}
		
			.grey-section .imga{
				width: 45%;
			}
			.imga img{
				width: 100%;
			}
		.grey-section .teext{
			width: 55%;
		}
		.article > div{
			float: left;
			
		}
		.article:after{
			content: '';
			display: block;
			clear: both;
		}
		.teext{
			position: relative;
			top: 60px;
			left: 58px;
		}
		.teext h2{
			margin-bottom: 20px;
		}
		.teext p{
			font: 18px;
			letter-spacing: 1px;
		}
		.teext > *{
			width: 90%;
		}
		.article:nth-child(odd){
			background-color: rgba(255,255,255,0.1);
		}
		.purple-section{
			background: #2c264e;
			color: #fff;
		}
		.heading-wrapper{
			text-align: center;
			padding: 80px;
		}
		.heading-wrapper .hr{
			background:#3d3458;
			width: 60%;
			height: 2px;
		}
		.card{
			float: left;
			width: 50%;
			min-height: 300px;
			padding: 50px;
			box-sizing: border-box;
		}
		.clearfix:after{
			content: '';
			display: block;
			clear: both;
		}
		h3{
			font-size: 24px;
		}
		.card p{
			padding: 5px;
		}
		.card:first-child{
			background: rgba(0,0,0,0.04);
		}
		.card:nth-child(2){
			background: rgba(0,0,0,0.08);
		}
		.card:nth-child(3){
			background: rgba(0,0,0,0.12);
		}
		.card:nth-child(4){
			background: rgba(0,0,0,0.16);
		}
		.card:nth-child(5){
			background: rgba(0,0,0,0.20);
		}
		.card:nth-child(6){
			background: rgba(0,0,0,0.24);}
	</style>
	</head>
	<body>
		<div class="all">
		<header>
			<nav>
				<div class="logo"><a href="#" >张小窝</a></div>
				<ul>
					
					<li><a href="#">首页</a></li>
					<li><a href="#">MENU</a></li>
					<li><a href="#">关于</a></li>
					<li><a href="#">联系我</a></li>
				</ul>
			</nav>
			<div id="banner">
			<div class="inner">
				<h1>王小窝</h1>
				<p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. </p>
				<button>了解我</button>
				<div class="more">更多</div>
			</div>
			</div>
		</header>
		<div class="content">
			<section class="green-section">
				<div class="wrapper">
					<div>
						<h2>一个标题</h2>
						<div class="hr"></div>
						<p> Lorem ipsum dolor sit amet, consectetur adipisicing elit. </p>
					</div>
					<div class="icon-group">
						<span class="icon">item1</span>
						<span class="icon">item2</span>
						<span class="icon">item3</span>
					</div> 
				</div>
			</section>
			<section class="grey-section">
				<div class="article">
					<div class="imga">
						<img src="img/111/img/pic01.jpg" />
					</div>
					<div class="teext">
						<h2>其实一开始是拒绝的</h2>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. </p>
						<p> Voluptate ut iusto necessitatibus modi ipsam nemo ratione exceptur.</p>
					</div>
				</div>
				<div class="article">
					
					<div class="teext">
						<h2>其实一开始是拒绝的</h2>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. </p>
						<p> Voluptate ut iusto necessitatibus modi ipsam nemo ratione exceptur.</p>
					</div>
					<div class="imga">
						<img src="img/111/img/pic02.jpg" />
					</div>
				</div>
				<div class="article">
					<div class="imga">
						<img src="img/111/img/pic03.jpg" />
					</div>
					<div class="teext">
						<h2>其实一开始是拒绝的</h2>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. </p>
						<p> Voluptate ut iusto necessitatibus modi ipsam nemo ratione exceptur.</p>
					</div>
				</div>
			
			
			
			</section>
			<section class="purple-section">
				<div class="wrapper">
					<div class="heading-wrapper">
						<h2>不约</h2>
						<div class="hr"></div>
						<div class="teee">
						Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corrupti quasi aliquam dolor quia commodi fuga explicabo architecto repudiandae doloremque!
						</div>
					</div>
				
				<div class="card-group clearfix" >
					<div class="card">
						<h3>第一个标题</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit odit suscipit perferendis nemo laborum consequatur atque corrupti labore delectus tenetur at facilis quam. Sapiente deserunt fuga modi molestias distinctio numquam.</p>
					</div>
					<div class="card">
						<h3>第二个标题</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit odit suscipit perferendis nemo laborum consequatur atque corrupti labore delectus tenetur at facilis quam. Sapiente deserunt fuga modi molestias distinctio numquam.</p>
					</div>	
					<div class="card">
						<h3>第三个标题</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit odit suscipit perferendis nemo laborum consequatur atque corrupti labore delectus tenetur at facilis quam. Sapiente deserunt fuga modi molestias distinctio numquam.</p>
					</div>
					<div class="card">
						<h3>第四个标题</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit odit suscipit perferendis nemo laborum consequatur atque corrupti labore delectus tenetur at facilis quam. Sapiente deserunt fuga modi molestias distinctio numquam.</p>
					</div>		
					<div class="card">
						<h3>第五个标题</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit odit suscipit perferendis nemo laborum consequatur atque corrupti labore delectus tenetur at facilis quam. Sapiente deserunt fuga modi molestias distinctio numquam.</p>
					</div>
					<div class="card">
						<h3>第六个标题</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit odit suscipit perferendis nemo laborum consequatur atque corrupti labore delectus tenetur at facilis quam. Sapiente deserunt fuga modi molestias distinctio numquam.</p>
					</div>		
				</div>
				</div>
			</section>
		</div>
		<footer>
			
		</footer>
		</div>
	</body>
</html>
