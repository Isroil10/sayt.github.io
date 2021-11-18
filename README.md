# sayt.github.io
<!DOCTYPE html>
<html>
<head>
	<title>Sayt_03</title><link rel="icon" type="text/css" href="python.jpg">
	<link rel="stylesheet" type="text/css" href="Sayt.css">

	
	
	
	
	
	<style>
				@import url('https://fonts.googleapis.com/css2?family=DM+Sans&family=Open+Sans:wght@300;400&family=Roboto:wght@100;400;700&display=swap');
		/*
		font-family: 'DM Sans', sans-serif;
		font-family: 'Open Sans', sans-serif;
		font-family: 'Roboto', sans-serif;
		*/
		*{
			margin: 0;
			padding: 0;
			box-sizing: border-box;
			font-family: 'Roboto', sans-serif;
			outline: none;

		}
		html{

			scroll-behavior: smooth;
		}
		.container{
			width: 100%;
			min-height: 100vh;
			margin-top: 150px
		}
		.head{

			width: 80%;
			min-height: 110vh;
			margin: 0px auto;

		}
		 header{
			position: fixed;
			z-index: 10000;
			width:100%;
			left: 00px;
			top: 0px;
			min-height: 15vh;
			background: white;
			display: flex;
			/*justify-content: space-around;*/
			align-items: center;
			/*border: 1px solid red*/
		}
		header .logo{
			margin-left: 150px;
			width: 150px;
			display: flex;
			justify-content: space-around;
			align-items: center;

		}
		header .logo p{
			margin-left: 0px;
			color:black;
			font-size: 25px

		}
		nav{
		    display: block;
			width: 70%;
			margin-left: 15%;
			margin-right: 100px;
			min-height: 100%;
		}
		nav ul{
			display: flex;
			justify-content: space-between;
		}
		nav ul li {
			list-style-type: none;
			padding:20px 10px;

		}
		nav a{
			position: relative;
			text-decoration: none;
			color: #19191B;
			font-family: 'DM Sans', sans-serif;
			font-weight: bold;
			font-size: 17px;
			transition: 0.5s ease

		}
		nav a::before{
			content: "";
			position: absolute;
			bottom: -5px;
			/*left: 0;*/
			width: 100%;
			height: 2px;
			background: #5454D4;
			transition: 0.5s transform ease;
			transform-origin: right;
			transform: scale(0);
		}
		nav a:hover::before{
			transform: scale(1);
			transform-origin: left;
			transition: 0.5s transform ease;

		}
		nav ul  button{
			/*margin-left: 50px;*/
			width: 200px;
			padding: 10px 0px;
			background: #FF7143;
			outline: none;
			border: 1px solid #FF7143;
			border-radius: 5px;
			color:white;
			font-size: 20px;
			font-family: 'Open Sans', sans-serif;
			transform: scaleX();
			transition: .5s ease;
			cursor: pointer;

		}
		nav ul  button:hover{
			letter-spacing: 2px;
			transition: .5s ease;
			box-shadow: 0 0 15px 2px #FF7143;
		}
		.head main{
			display: flex;
			margin: 50px 0
		}
		.head main .main_left{
		    position: relative;
		     /*left: 100px;*/
			width: 50%;
			min-height: 100%;
			/*border: 1px solid red;*/
		}
		.main_left h1{
			margin-top: 50px;
			font-family: 'DM Sans', sans-serif;
			font-size: 60px;
		    font-weight:900;
		}
		.main_left p{
			margin: 30px 0; 
			width: 55%;
			font-weight: 400;
			color:#091921;

		}

		.main_left button{
			width:35%;
			padding: 10px 30px;
			background:#5454D4;
			border:1px solid #5454D4;
			border-radius: 5px;
			color:white;
			font-size: 20px;
			font-weight: 500;
		    transition: .7s ease
		}
		.main_left button:hover{
			letter-spacing: 2px;
			transition: .5s ease;
			box-shadow: 0 0 15px 2px #5454D4;
		}
		.main_right{
			position: relative;
			width: 50%;

		}
		.odam{
			position: relative;
			z-index: 1000
		}
		.stol{
			position: absolute;
			top: 100px;
			left: 50px
		}
		.sms{
			position: absolute;
			bottom:80px;
			right: -50px
		}
		.main{
			width:80%;
			max-height: 120vh;
			/*border: 1px solid red;*/
			margin: 0 auto;
			display: flex;
			flex-direction: column;

		}
		.top{
			width: 100%;
			min-height: 50vh;
			/*border: 1px solid red;*/
			display: flex;
		}
		.rasm_1{
			position: relative;
			width:40%;
		}
		.doira{
		position: absolute;
		top: 50px
		}
		.pose_11{
			position: relative;
			right: -180px
		}
		.sidebar{
			width: 50%;
			min-height: 50vh;
		    position: relative;
		    top: 100px;
		    left: 120px
		}
		.sidebar button{
			width: 30%;
			padding: 13px 0;
			background: #00C4F0;
			border: none;
			border-radius: 5px;
			color:#091921;
			font-size: 20px;
			transition: .5s ease;
			cursor: pointer;


		}
		.sidebar p{
			font-family: 'DM Sans', sans-serif;
			line-height: 27px;
			margin: 30px 0

		}
		.sidebar button:hover{
			letter-spacing: 2px;
			transition: .5s ease;
			box-shadow: 0 0 15px 1px #00C4F0;
		}
		.bottom{
			display: flex;
			position: relative;
			top: 100px
		}
		.toggle{
			width: 50%;
			/*border: 1px solid red;*/
		}
		.toggle  h1{
			margin-top: 150px
		}
		.toggle p{
			margin: 30px 0;
			line-height: 25px;
			font-family: 'Open Sans', sans-serif;
		}
		.toggle button{
			width:33%;
			padding: 15px 0;
			background: #00C4F0;
			border: none;
			border-radius: 5px;
			color:#091921;
			font-size: 20px;
			transition: .5s ease;
			cursor: pointer;

		}
		.toggle button:hover{
			letter-spacing: 2px;
			transition: .5s ease;
			box-shadow: 0 0 15px 1px #00C4F0;
		}
		.rasm_02{
			position: relative;

		}
		.pose_4{
			position: absolute;
			z-index: 100
		}
		.footer_img{
			position: absolute;
			z-index: 0;
			left: 200px
		}
		.item{
			width: 90%;
			margin: 0 auto;
			position: relative;
			top: 200px;
			display:flex;
		}
		.items{
			margin: 0 auto;
			width: 39%
		}
		.items img  {

		position: relative;
		left: 140px
		}
		.items h4  {
		width: 90%;
		text-align: center;
		 line-height: 23px
		}
		.items p  {
		width: 80%;
		text-align: center;
		 line-height: 23px
		}
		.footer{
			width: 80%;
			min-height: 120vh;
			/*border: 1px solid red;*/
			margin: 300px 0px 0px 150px
		}
		.header{
			width: 100%;
			min-height:20vh;
			display: flex;
			justify-content: space-between;
		}
		.header button{
			width: 100%;
			display: flex;
			justify-content: space-between;
		   padding: 0px 0px;
		   background: #ccc;
		   cursor: pointer;
		   border: 5px solid #ccc;
		   border-radius: 10px;
			transition: .5s ease


		}
		.header button .span_01{
		 background: #5454D4;
		 padding: 20px 60px;
		 letter-spacing:  2px;	
		 color: white;
		 border-radius: 5px;
		 transition: .3s ease

		}
		.header button .span_01:active{
			background: #ccc;
			color: #5454D4;
			transition: .3s ease


		}
		.header button:hover{
			box-shadow: 0 0 15px 1px #091921;
			transition: .5s ease


		}
		.header button .span_02{
		background:#ccc;
		letter-spacing:  2px;	
		padding: 20px 50px;
		border-radius: 5px;
		transition: .5s ease



		}
		.header button .span_02:active{
			background: #5454D4;
			color: white;
			transition: .3s ease


		}
		.main_02{
			width: 100%;
			min-height:80vh;
			/*border: 1px solid red;*/
			display: flex;
			justify-content: space-around;

		}
		.main_02 .itemes{
			cursor: pointer;
			width: 30%;
			min-height: 100%;
			/*border: 1px solid red;*/
			display: flex;
			flex-direction: column;
			justify-content: space-around;
			align-items: center;
			background: #eed;
			border-radius: 10px;
			transition: .5s ease

		}
		.main_02 .itemes:hover{
			box-shadow: 0 0 25px 2px rgba(0,0,0,0.5);
		  transition: .5s ease;
		  background:#FF7143;
		}
		.itemes h1{
			font-size: 50px
		}
		.itemes p{
			line-height: 40px;
			text-align:center;
		}
		.itemes button{
			font-weight: bold;
			background: white;
			width: 60%;
			min-height:50px;
			letter-spacing: 2px;
			border-radius: 10px;
			border:none;
		  transition: .5s ease;
		  cursor: pointer;

		}
		.main_02 .itemes:hover button{
			color: white;
			letter-spacing: 3px;
			background: #9F3919;
		  transition: .5s ease;

		}



		.adres a{
			position: relative;
			top: 15px;

			text-decoration: none;
			color:#333;

		}
		.adres a:hover{
			color: black
		}
		.adres li{
			list-style: none;
			padding: 5px
		}
		.mening{
			display: flex;
		}
		.mening a{
			text-decoration: none;
			color: #333;
			position: relative; 
			top: 20px;
			transition: 0.5s
		}
		.mening a:hover{
			color: black
		}
		.mening li{
			padding: 4px;
			list-style-type: none;
		}
		.mening p{
			color: white
		}
		.mening .home{
			position: relative;
			left: 100px;
			padding: 13px 20px;
			min-width: 100px;
			height: 50px; 	
		    top: 15px;
			border-radius: 50%;
			background: #5454D4;
			text-decoration:none;
			color: white;
		}
		.mening .home:hover{
			background:  #5454D4;
			color: white;
			opacity: 1
		}
		.email{
			position: relative;

			top: 0px;
			left: 20px;
			padding: 10px
		}
		.card_img p{
			background: rgba(0,0,0,0.5);
			color: white;
			opacity:color 0.5;
			min-width: 250px;
			padding: 5px;
			border-radius:10px;


		}
		.card_img p span{position: relative;
			text-transform:uppercase;
			padding-left: 10px;
			color: white;
			opacity:color 1;
			font-size: 29px;
			text-align: center;
		}
		.email p{
			padding: 3px 0px;
			color: black
		}
		.home{
			font-size: 20px;
			background: white
		}
		.navbar ul li a{
			text-decoration: none;
			color: rgba(255,255,255,0.5);

		}
		.email p a{
			padding: 100px;
			width: 100px
		}
		.footer_02{

			background: #ccc;
			width: 100%;
			height: 23vh;
			display: flex;
			/* justify-content: space-around; */
		}

		.adres {
			display: flex;
			position: relative;
			left: 300px;
		}
		.mening {
			position: relative;
			left: 400px;
		}












		@media only screen and (max-width:600px) {
			.footer_02{

				background: #ccc;
				width: 100%;
				height: 23vh;
				display: flex;
				justify-content: space-around;
			}
			.adres {
				display: flex;
				position: relative;
				left: 0px;
			}
			.mening {
				position: relative;
				left: 0px;
			}

			.head main{
			display: flex;
		    flex-direction: column;
		    margin: 50px 0;
			}
			.head main .main_left {
				position: relative;
			bottom: -600px;
				width: 100%;
				min-height: 100%;
			}
			.main_left p {
				margin: 30px 0;
				width: 100%;
				font-weight: 400;
				color: #091921;
			}
			.main_left button {
				width: 50%;
				padding: 15px 30px;
				background: #5454D4;
				border: 1px solid #5454D4;
				border-radius: 5px;
				color: white;
				font-size: 20px;
				font-weight: 500;
				transition: .7s ease;
				margin-bottom: 100px;
			}
			.odam {
				position: relative;
				z-index: 1000;
				top: -600px;
			}
			.stol {
				position: absolute;
				top: -500px;

				left: 50px
			;
			}
			.sms {
		    position: absolute;
		    top: -200px;
		    right: 10px;
		}
		nav{
		    display: none;
			width: 70%;
			margin-left: 15%;
			margin-right: 100px;
			min-height: 100%;
		}
		header .logo{
			margin-left: 50px;
			width: 150px;
			display: flex;
			justify-content: space-around;
			align-items: center;

		}
		.main .top{
			display:flex;
			flex-direction: column;
			top: 200px;
			/* border: 1px solid #333; */

		}
		.main .bottom{
			display: flex;
			flex-direction: column;
			position: relative;
			top: 00px;
			/* border: 1px solid red; */
		}

		.sidebar{
			width: 100%;
			min-height: 50vh;
		    position: relative;
		    top: 100px;
		    left: 0px;
			/* border: 1px solid red; */
		}
		.rasm_1{
			position: relative;
			width:100%;
		}
		.sidebar button{
			width: 50%;
			padding: 13px 0;
			background: #00C4F0;
			border: none;
			border-radius: 5px;
			color:#091921;
			font-size: 20px;
			transition: .5s ease;
			cursor: pointer;


		}
		.sidebar h1{
			width: 90%;

		}
		.toggle{
			width: 100%;
			margin-top: 1000px;
			height: 350px;
			position: relative;
			top: 100px;
			/* border: 1px solid yellow; */
		}
		.rasm_02{

			position: relative;
			top: -700px;
			/* border: 10px solid #333; */
		}
		.pose_4{
			position: absolute;
			z-index: 100
		}
		.footer_img{
			position: absolute;
			z-index: 0;
			top: 50px;
			left: 150px
		}
		.toggle button{
			width:50%;
			padding: 15px 0;
			background: #00C4F0;
			border: none;
			border-radius: 5px;
			color:#091921;
			font-size: 20px;
			transition: .5s ease;
			cursor: pointer;

		}
		.item{
			position: relative;
			top: 300px;
		    display: flex;
		    /* flex-direction: c; */
		    flex-wrap: wrap;
		}
		.items{
			position: relative;
			top: 1020px;

			/* margin: 0 auto; */
			width: 50%
		}
		.items img{
			margin-top: 50px;
		}

		.items{
			margin: 0 auto;
			width: 39%
		}
		.items img  {

		position: relative;
		left: 50px
		}
		.items h4  {
		width: 80%;
		text-align: center;
		 line-height: 23px;
		 letter-spacing: 2px;
		}
		.items p  {
		width: 80%;
		text-align: center;
		 line-height: 23px
		}

		.header{
			width: 100%;
			min-height:20vh;
			display: flex;
			flex-direction: column;
			justify-content: space-between;
		}
		.header h1{
			width: 100%;
		}
		.header button{
			width: 100%;
			display: flex;
			justify-content: space-between;
		   padding: 0px 0px;
		   background: #ccc;
		   cursor: pointer;
		   border: 5px solid #ccc;
		   margin: 50px 0;
		   border-radius: 10px;
			transition: .5s ease


		}
		.header button .span_01{
		 background: #5454D4;
		 padding: 20px 110px;
		 letter-spacing:  2px;	
		 color: white;
		 border-radius: 5px;
		 transition: .3s ease

		}
		.header button .span_02{
			background:#ccc;
			letter-spacing:  2px;	
			padding: 20px 110px;
			border-radius: 5px;
			transition: .5s ease



			}
			.header button .span_02:active{
				background: #5454D4;
				color: white;
				transition: .3s ease


			}





		.footer{
			margin:0;
			width: 100%;
			position: relative;
			top: 1400px;
			left: 0;
			display: flex;
			flex-direction: column;
			/* border: 1px solid red; */
		}
		.main_02{
			/* border: 1px solid red; */
			width: 100%;
			display: flex;
			flex-direction: column;
			min-height: 300vh;
		}
		.main_02{
			width: 100%;
			min-height:300vh;
			/*border: 1px solid red;*/
			display: flex;
			justify-content: space-around;

		}
		.main_02 .itemes{
			cursor: pointer;
			width: 90%;
		margin-top: 100px;
		margin-left: 20px;
			min-height: 500px;
			/*border: 1px solid red;*/
			display: flex;
			flex-direction: column;
			justify-content: space-around;
			align-items: center;
			background: #eed;
			border-radius: 10px;
			transition: .5s ease

		}

		.footer_02{
			position: relative;
			top: 1500px;
			background: #ccc;
			width: 100%;
			height: 30vh;
			display: flex;
			justify-content: space-around;
		}
		.mening{
			display: flex;
			flex-direction: column;
			justify-content: space-between;
		}
		.email p a{
			padding: 100px;
			width: 100px
		}
		.email{
			position: relative;

			left: -180px;
		}
		}
<style>
</head>
<body>
<header class="header_010">
	  		<div class="logo">
	  		  <img src="Shape.png">
	  		  <p>Thursday</p>
	  		</div>
	  		<nav> 
              <ul>
              	<li><a href="#head">Home</a></li>
              	<li><a href="#top">Feature</a></li>
              	<li><a href="#bottom">Pircing</a></li>
              	<li><a href="#footer">Blog</a></li>
              	<button>Get Started</button>
              </ul>
	  		</nav>
</header>
<div class="container">
	  <div class="head" id="head">
	  
	  	 <main>
	  	 	<div class="main_left" >
	  	 		<h1>
	  	 			Grow your <br> subscription <br> business
	  	 		</h1>
	  	 		<p>
	  	 		  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
	  	 		  tempor incididunt ut labore et dolore magna aliqua.
	  	 		  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
	  	 		  tempor incididunt ut labore et dolore magna aliqua. 
	  	 		</p>
	  	 		 <button>Get Started</button>
	  	 	</div>

	  	 	<div class="main_right">
	  	 		<img src="pose_7.png" class="odam">
	  	 		<img src="stol.png" class="stol">
	  	 		<img src="sms.png" class="sms">
	  	 	</div>
	  	 </main>
	  </div>
	  <div class="main">
	  	<div class="top" id="top">
	  		 <div class="rasm_1">
	  		     <img src="doira.png" class="doira">
	  		     <img src="pose_11.png" class="pose_11">
	  		 </div>
	  		 <div class="sidebar">
	  		 	<h1>Subscription indes</h1>
	  		 	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, <br>  sed do eiusmod
	  		 	tempor incididunt ut labore et dolore magna <br> aliqua. Ut enim ad minim veniam, 
	  		 	quis nostrud exercitation.</p>
	  		 	<button>Learn more</button>
	  		 </div>

	  	</div>
	  	<div class="bottom" id="bottom">
	  		<div class="toggle">
	  		 	<h1>Subscription index</h1>
	  		 	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, <br> sed do eiusmod
	  		 	tempor incididunt ut labore et dolore magna <br> aliqua. Ut enim ad minim veniam,
	  		 	quis nostrud exercitation.</p>
	  		 	<button>Learn more</button>
	  		 </div>
	  		  <div class="rasm_02">
	  		     <img src=pose_4.png class="pose_4">
	  		     <img src="footer.png" class="footer_img">
	  		 </div>
	  </div>
</div>
<div class="item">
	<div class="items">
	    <img src="Card.png">
	    <h4>Benchmark</h4>
	    <p>   
	    	Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod.
	     <p>
	</div>
		<div class="items">
	    <img src="sms.png" style="width: 100px">
	    <h4>Pricing audit</h4>
	    <p>   
	    	Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod.
	     <p>
	</div>
		<div class="items">
	    <img src="Camera.png">
	    <h4>Retention Audit</h4>
	    <p>   
	    	Lorem ipsum dolor sit amet, consectetur adipisicing  elit, sed do sed  do eiusmod.
	     <p>

</div>
</div>
<div class="footer" id="footer">
	<div class="header"> 
     <h1>
     	Get the right plan <br> for future product.
     </h1>
     <div class="">
     	<button><span class="span_01">Yearly</span><span class="span_02">Monthly</span></button>
     </div>
	</div>
	<div class="main_02">
		<div class="itemes">
			<p>Starter</p>
			<h1>Free</h1>
			<p>1 Website <br> 5 GB Hosting <br> Limited Support</p>

			<button> Get Started</button>
		</div>
		<div class="itemes">
			<p>Premiun</p>
			<h1><span>$29/</span>month</h1>
			<p>10 Website <br> 15 GB Hosting <br> Limited Support</p>

			<button>Get Started</button>
		</div>
        <div class="itemes">
			<p>Enterprise</p>
		<h1><span>$49/</span>month</h1>			<p>Unlimited Website <br> 5 GB Hosting <br> Limited Support</p>

			<button>Get Started</button>
		 </div>
  
	</div>

</div>
	<div class="footer_02">
	 <div class="adres">
             <ul>
               <li><a href="#head">Home</a></li>
               <li><a href="#top">Feature</a></li>
               <li><a href="#bottom">Pricing</a></li>
               <li><a href="#footer">Blog</a></li>
             </ul>
           </div>
             <div class="mening">
             <ul>
               <li><a href="#">Contact</a></li>
               <li><a href="gmail.com">Eamil: itoshpolatov955@gmail.com</a></li>
               <li><a href="#">Inst.notitanic33</a></li>
               <li><a href="#">Calls +998 99 527 24 45</a></li>
             </ul>
              <div class="email">
             <p class="footer_p">
               Isroil Toshpo'latov  <a href="#head" class="home" >↑</a>
             </p>
              <p> Copyright &copy 2021,Notitanic</p>
           </div>
           </div>
       </div>
 

</div>
<script>
	header = document.querySelector('.header_010')
    window.addEventListener('scroll', function go(){
    header.style.cssText="background:#ccc;"
  })

</script>
</body>
</html>
