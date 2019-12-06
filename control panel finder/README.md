# Control-Panel-Finder
this is a simple script for PT
run it & enjoy...

BY body{
	background-color: #232122;
	padding: 0;
	margin: 0;
}
.wrapper{
	height: 500px;
	width: 350px;
	position: absolute;
	margin: auto;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
}
.container{
	height: 500px;
	width: 350px;
	position: absolute;
	margin: auto;
	left: 0;
	top: 0;
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-align: center;
	    -ms-flex-align: center;
	        align-items: center;
	-webkit-box-pack: center;
	    -ms-flex-pack: center;
	        justify-content: center;
	perspective: 500px;
	-webkit-perspective: 500px;
	perspective-origin: 50%;
	-webkit-perspective-origin:50% ;
}
.button{
	height: 80px;
	width: 200px;
	position: relative;
	-webkit-transform-style: preserve-3d;
	        transform-style: preserve-3d;
	-webkit-transition: 0.5s;
	-o-transition: 0.5s;
	transition: 0.5s;
	
	}
.front,.right{
	background-color: #262626;
	-webkit-box-shadow: 0 10px 20px rgba(0,0,0,0.3);
	        box-shadow: 0 10px 20px rgba(0,0,0,0.3);
	height:100%;
	width: 100%;
	-webkit-box-sizing: border-box;
	        box-sizing: border-box;
	position: absolute;
}
.front{
	-webkit-transform: translateZ(100px);
	        transform: translateZ(100px);
	display:-webkit-box;
	display:-ms-flexbox;
	display:flex;
	-webkit-box-align: center;
	    -ms-flex-align: center;
	        align-items: center;
	-webkit-box-pack: center;
	    -ms-flex-pack: center;
	        justify-content: center;
	font-family: 'Poppins',sans-serif;
	font-weight: 500;
	font-size: 25px;
	letter-spacing: 1.7px;
	color: white;
}
.right{
	-webkit-transform: rotateY(-270deg) translateX(100px);
	        transform: rotateY(-270deg) translateX(100px);
	-webkit-transform-origin: top right;
	    -ms-transform-origin: top right;
	        transform-origin: top right;
	display:-webkit-box;
	display:-ms-flexbox;
	display:flex;
	-webkit-box-align: center;
	    -ms-flex-align: center;
	        align-items: center;
	-ms-flex-pack: distribute;
	    justify-content: space-around;
}	
.button:hover{
	-webkit-transform: rotateY(-90deg);
	        transform: rotateY(-90deg);
}
.right>a{
	text-decoration: none;
	display:-webkit-box;
	display:-ms-flexbox;
	display:flex;
	height: 40px;
	width: 40px;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    border-radius: 3px;
    -webkit-box-shadow: 0 5px 10px rgba(0,0,0,0.3);
            box-shadow: 0 5px 10px rgba(0,0,0,0.3);
    -webkit-transition: 0.2s;
    -o-transition: 0.2s;
    transition: 0.2s;
}
.right>a:hover{
	-webkit-transform:scale(1.15);
	    -ms-transform:scale(1.15);
	        transform:scale(1.15);
	 -webkit-box-shadow: 0 5px 15px rgba(0,0,0,0.3);
	         box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}
.right>a:nth-child(1){
	background-color: #11B1FC;
}
.right>a:nth-child(2){
	background-color: #1562BC;
}
.right>a:nth-child(3){
	background-color: #F70000;
}
i.fa{
	color: white;
	font-size: 25px;
}
.wrapper>a{
	background-color: #11B1FC;
	color: white;
	font-size: 23px;
	padding: 5px 15px;
	font-family: 'Poppins',sans-serif;
	font-weight: 500;
	position: absolute;
	bottom: 70px;
	text-decoration: none;
	border-radius: 3px;
}
.ytlink{
	left: 20px;
}
.wblink{
	right: 20px;
} & CL0UDY & 1N1T5
