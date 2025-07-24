<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8" />
  <title>Don't be mad... - Something for You</title>
  <meta name="description" content="Instagram @aoudumber.dev - Script HTML by aoudumber.dev">
  <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1" />
  <meta name="description" content="Special For Cutieee">
  <meta property="og:title" content="Special HTML For You ✨">
  <meta property="og:description" content="Open it, my Cutieee ❤️">
  <meta property="og:image" content="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhMDugl2siKVTnQUhkzqZXmNhnUl_IXm-tsnodgHf4C3dPn6v4gz06nVm1ASqpRXO65Dg3PkYB9bKsThBPUxygLD9Euem9SSTr0LRIGK9x5uaLvK4WIPn6VlSx0qSrPGhTknGVHeVMpioiBcXiqrk-dF3d4SYS8QIkWkDlMgRrdF4vw_iw-EOgTYcwo6xhs/s300/1000314955.jpg">
  <meta property="og:image:alt" content="Cutieee">
  <meta property="og:type" content="website">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
  <link rel="stylesheet" href="style.css"><script src="https://unpkg.com/scrollreveal"></script><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>

  <!-- Demo styles -->
  <style>
        * {
            padding: 0;
            margin: 0;
        }
        body {
            background: linear-gradient(0.25turn, rgb(0, 38, 77), rgb(0, 38, 70));
            background: #000;
            background-size: cover;
            background-position: center;
            height: 100vh;
            overflow: hidden;
            color: black;
        }
        #container {
            width: 80%;
            margin: 20px auto;
            min-height: 650px;
            margin-top: 150px;
            color: black;
        }
        @media screen and (max-width: 400px) {
            #container {
                width: 100%;
                margin: 50% auto;
                min-height: 800px;
            }
        }
        .wrapper {
            position: fixed;
        }
        .box div {
            position: fixed;
            width: 60px;
            height: 60px;
            background-color: transparent;
            border: 6px solid rgba(255, 255, 255, 0.3);
            border-radius:50%;
        }
        .box div:nth-child(1) {
            top: 12%;
            left: 42%;
            animation: animate 10s linear infinite;
        }
        .box div:nth-child(2) {
            top: 70%;
            left: 50%;
            animation: animate 7s linear infinite;
        }
        .box div:nth-child(3) {
            top: 17%;
            left: 6%;
            animation: animate 9s linear infinite;
        }
        .box div:nth-child(4) {
            top: 20%;
            left: 60%;
            animation: animate 10s linear infinite;
        }
        .box div:nth-child(5) {
            top: 67%;
            left: 10%;
            animation: animate 6s linear infinite;
        }
        .box div:nth-child(6) {
            top: 80%;
            left: 70%;
            animation: animate 12s linear infinite;
        }
        .box div:nth-child(7) {
            top: 60%;
            left: 80%;
            animation: animate 15s linear infinite;
        }
        .box div:nth-child(8) {
            top: 32%;
            left: 25%;
            animation: animate 16s linear infinite;
        }
        .box div:nth-child(9) {
            top: 90%;
            left: 25%;
            animation: animate 9s linear infinite;
        }
        .box div:nth-child(10) {
            top: 20%;
            left: 80%;
            animation: animate 5s linear infinite;
        }
        @keyframes animate {
            0% {
                transform: scale(0) translateY(0) rotate(0);
                opacity: .8;
            }
            100% {
                transform: scale(1.3) translateY(-90px) rotate(360deg);
                opacity: 0;
            }
        }
    </style>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Caveat&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@400;700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Inter&family=Itim&display=swap');
	
	:root {
	--poppins: 'Poppins', sans-serif;
	--nunito: 'Nunito Sans', sans-serif;
	--caveat: 'Caveat', cursive;
	--quicksand: 'Quicksand', sans-serif;
	--itim: 'Itim', cursive;
	--inter: 'Inter', sans-serif;
	}

    html, body {position: relative;height: 100%;}
    body {font-family: 'Itim', cursive;font-size: 14px;color: #fff;text-shadow: 0px 2px 2px rgba(0, 0, 0, .5);margin: 0;padding: 0;}
    
    #bodyblur{opacity:.25;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.5);transition:all 1s ease;} 
    #sthisblur{backdrop-filter:blur(3px);-webkit-backdrop-filter:blur(3px);position:absolute;top:0;left:0;right:0;bottom:0;}
    #wallpaper{/*animation: jj 7s infinite;*/width:100%;height:100%;transform: scale(1.3);transition:all 1.3s ease;}
    #wallpaper2, #wallpaper3, #wallpaper4{display:none}
    @keyframes jj{0%  {transform: scale(1);} 50% {transform: scale(1.3);} 100% {transform: scale(1);} }

    p{margin-left:50px;margin-right:70px;text-align:left}
    #ket{margin:20px}

    .swiper {width: 100%;height: 100%;padding:0;margin:0;}
    .swiper-slide {text-align: center;font-size: 18px;/*background: #fff;*/display: flex;flex-direction: column;justify-content: center;align-items: center;margin-top:-100px;}
    .swiper-slide img {display: block;width: 100%;height: 100%;object-fit: cover;}
    .swiper-pagination{margin-bottom:25vh}
    .swiper-pagination-bullet-active{background-color: #fff !important;opacity:1 !important}
    .swiper-pagination-bullet{background-color:rgba(255,255,255, 1) !important;}
    .swiper-button-next, .swiper-button-prev{display:flex;top:unset;bottom:-100px}
    
    .sembunyi{display: none !important;}
    .stiker{display:flex;justify-content:center;align-items:center;margin-left:auto;margin-right:auto;margin-bottom:20px;transition:all .75s ease}
    .stiker img{width:90px;height:90px;box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);background: rgba(255, 255, 255, 0.7);border: 2px solid rgba(255, 255, 255, 1);border-radius: 50%;padding:10px;}
    .stiker img.sty2{background:none;filter: drop-shadow(0 4px 8px rgba(255, 255, 255, 0.2));box-shadow: none;backdrop-filter: none;-webkit-backdrop-filter: none;border: none;border-radius: 0;padding:0;width: auto;height:90px;}
	b.merah{color:red}
	b.kuning{color:yellow}
	b.putih{text-shadow:none;padding-left:8px;padding-right:8px;padding-top:2px;padding-bottom:2px;background-color:white;border-radius:12px}
	span.garismerah{border-bottom:2px solid red}
	span.gariskuning{border-bottom:2px solid yellow}
    p{color:white;font-size:15px;line-height:1.5em;}
    .scale0{opacity:0;transform: scale(0);transition: all .9s ease;}
    .scale1{opacity:1;transform: scale(1);transition: all .9s ease;}
    svg{vertical-align: middle;width: 22px;height: 22px;fill: #fff}
    .heart-icon {z-index:100;width: 30px;height: 30px;position: fixed;animation:  heartMove linear 1;top: -10vh;}

	@keyframes heartMove {
	  0% {transform: translateY(-10vh);}
	  100% {transform: translateY(100vh);}
	}
	    svg.line{fill: none;stroke: #fff;stroke-width: 2;animation: moving .7s linear infinite alternate;}
	    .spin{animation: spin 3s linear infinite alternate;}
	@keyframes spin {
	  from {
	    transform: rotate(20deg);
	  }
	  to {
	    transform: rotate(-20deg);
	  }
	}
	@keyframes moving {
	  from {
	    transform: translateY(0);
	  }
	  to {
	    transform: translateY(3px);
	  }
	}
    .overlay {position: fixed;top: 0;left: 0;width: 100%;height: 100%;display: flex;justify-content: center;align-items: center;background:#000;z-index:100;}
    .loading-message {font-size: 13px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);color:white;text-align: center;}
    .blocklove{display: none;flex-direction: column;justify-content: center;align-items: center;}
    .lovein{background:#fff;color:#FF0900;border-radius:50%;width:40px;height:40px;padding:10px;font-size:30px;display:flex;align-items:center;text-align:center;justify-content:center;transition:all .3s ease;}
    .lovein:hover{transform: scale(.9);color:#FF0900;}
    .lovein svg{stroke:#FF0600;width:30px;height:30px}
    
    .blocktext{margin-top:10px;position:relative;width:100%;height: 160px; overflow: auto;background-color:none;}

    .tombol{background-color: rgba(255,255,255,0);border-radius: 50px;overflow: hidden;display: flex;align-items: center;justify-content: center;-webkit-transition: all .2s ease-out;transition: all .2s ease-out}
    .tombol svg{margin: auto;fill:#ffd4d4;stroke: #ff0000;width: 60px;height: 60px;animation: spin2 1s linear infinite alternate;}
    #Tombol{margin-top:20px;position:relative;margin-left:auto;margin-right:auto;display:flex;align-items:center;justify-content:center;list-style:none;transition:all 1s ease;}
    #Tombol a{display:inline-flex;align-items:center; margin:0;margin:10px;transition:all .2s ease;padding:10px;outline:0;border:2px solid white;border-radius:30px;line-height:15px;background:rgba(0,0,0,.3);color:white;font-size:13px;font-weight:700;white-space:nowrap;overflow:hidden;box-shadow: rgba(255,255,255, 0.15) 0px 7px 29px 0px;z-index:1}
    #Tombol, #Tombol2, #TombolWA{position:relative;opacity:0;margin-left:auto;margin-right:auto;display:flex;justify-content:center;align-items:center;list-style:none;transition:all 1s ease;}
    #Tombol a, #Tombol2 a, #TombolWA a{display:inline-flex;align-items:center; margin:0;margin:10px;transition:all .2s ease;padding:10px;outline:0;border:2px solid white;border-radius:30px;line-height:15px;background:rgba(255, 182, 193, .3);color:white;font-size:13px;font-weight:700;white-space:nowrap;overflow:hidden;box-shadow: rgba(255,255,255, 0.15) 0px 7px 29px 0px;z-index:1}
    
    .swal2-modal > *{font-size:16px;color:white}
	.swal2-title{line-height:1.3em;font-size:17px;text-align:center;padding:15px 30px 0 30px;}
	.swal2-timer-progress-bar-container > *{opacity:.5;background:#00B6FF;margin:0 20px}
	.swal2-modal{background: rgba(0,0,0, 1);backdrop-filter: blur(0);-webkit-backdrop-filter: blur(0);box-shadow: 0 4px 30px rgba(255,255,255, 0.3);border: 2px solid rgba(255, 255, 255, 1);border-radius: 30px;max-width:325px;top:-60px;}
	.swal2-image{background: rgba(255, 255, 255, 0.5);box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);border: 2px solid rgba(255, 255, 255, 1);border-radius: 50%;padding:10px;}
	.swal2-styled.swal2-confirm, .swal2-styled.swal2-cancel{position: relative;background-color: #4839eb;color: #fff;border-radius:18px;z-index: 1;transition: all 0.2s;}
	
	/* Calculator */
    .calculator{display:none;position:relative;margin-top:50px;box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);background: rgba(255, 255, 255, 0.1);border: 1px solid rgba(255, 255, 255, 0.3);border-radius:20px;padding:18px;width:180px;flex-direction:column;justify-content:center;align-items:center;}
    .calculator-screen{font-family: 'Itim', cursive;font-weight:700;width:100%;height:50px;border:none;background-color:rgba(255,255,255,0.1);margin:auto;padding:0;font-size:23px;color:#fff;text-shadow: 0px 2px 2px rgba(0, 0, 0, .5);border-radius:15px;text-align:center;}
    .calculator-keys{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;}
    .calculator-keys button{width:38px;height:38px;border:none;border-radius:50%;background-color:rgba(255,182,193,0.6);font-size:16px;color:#fff;transition:background-color 0.3s,transform 0.2s;}
    .calculator-keys button:hover{background-color:rgba(255,182,193,0.8);}
    .calculator-keys button:active{background-color:rgba(255,182,193,1);transform:scale(0.9);}
    .calculator-keys .operator{background-color:rgba(255,105,135,0.8);color:#fff;}
    .calculator-keys .operator:hover{background-color:rgba(255,105,135,1);}
    .calculator-keys .equals{background-color:rgba(255,92,128,0.8);color:#fff;}
    .calculator-keys .equals:hover{background-color:rgba(255,92,128,1);}
    .calculator-keys {margin-top:20px;transition: opacity 0.5s ease;}
    .calculator-keys.hide {opacity: 0;pointer-events: none;}
</style>
</head>

<body>
  <audio src="" id="linkmp3" class="sembunyi"></audio>
	<div class="overlay">
    <div class="loading-message">Hey you!<br>Wait a moment...</div>
     <div id="loveIn" class="blocklove">
        <a href="#" target="_blank" class="lovein"></a>
        <p id="ket">Touch the LOVE!</p>
     </div>
   </div>
   
   <div id="bodyblur">
     <img src="./assets/nightin.jpeg" id="wallpaper"/>
     <div id="thisblur"></div>
   </div>
   
    <!-- Swiper -->
    <div class="swiper mySwiper">
        <div class="swiper-wrapper">

            <div class="swiper-slide">
                <div id="stiker1" class="scale0 stiker">
                    <img src="./assets/cilukba.gif" />
                </div>
                <h1 id="teks1" class="scale0 quicksand" style="font-size: 20px;">Hello Cutieee 🫢<br><br> >>>>
                </h1>
            </div>

            <div class="swiper-slide">
                <div id="stiker2" class="scale0 stiker">
                    <img src="./assets/gemoy.gif" />
                </div>
                <h1 id="teks2" class="scale0 quicksand" style="font-size: 19px;">My Cutieee, Still Mad? 🫣</h1>
                <div id="Tombol" style="opacity:0;transform: scale(0)">
                    <a id="By" onClick="swiper.slideNext();">Not anymore 💗</a>
                    <a id="Bn" onClick="btn='Bn';fungsibaru(btn)">Still 🤬</a>
                </div>
                <img id="stikerTolak" class="sembunyi" src="./assets/cubit.gif"/>
                <p id="teksTolak" class="sembunyi">Aww, just sulking like that 😋😝</p>
                
                <img id="stikerTolak2" class="sembunyi" src="./assets/weee.gif"/>
                <p id="teksTolak2" class="sembunyi">You'll age quickly 🫣🤣</p>
            </div>

            <div class="swiper-slide">
                <div id="stiker3" class="scale0 stiker" style="margin-top:50px">
                    <img id="stikerAkhir1" src="./assets/ciumpipi.gif" />
                    <img id="stikerAkhir2" class="sembunyi" src="./assets/panah.gif" />
                </div>
                <div id="scroll-container" class="blocktext">
                    <h1 id="teks3" class="scale0 quicksand" style="font-size: 17px;font-weight:400"><b style="font-size: 22px;">Yay! 🥳</b><br><br>Thank you for not being mad 😋<br><br><b>Now I Want to Ask You Something 😝🩷</b></h1>
                    <h1 id="teksTambahan" class="sembunyi"><span id="teksLove">I Love You</span></h1>
                    <script>const loveEmojis = ['💖']</script>
                </div>
            </div>
            
            <div class="swiper-slide">
		       <div id="stiker4" class="scale0 stiker">
		        <img id="stikerAkhir3" src="./assets/inicinta.gif"/>
		        <img id="stikerAkhir4" class="sembunyi" src="./assets/terlope.gif"/>
		       </div>
		      	<h1 id="teks4" class="scale0 quicksand" style="font-size: 20px;">Answer here! 😆<br><br> >>>></h1>
		      
		      <div id="calculator" class="scale0 calculator">
		        <input type="text" class="calculator-screen" id="screen" disabled>
		        <div class="calculator-keys">
		            <button type="button">7</button>
		            <button type="button">8</button>
		            <button type="button">9</button>
		            <button type="button" class="operator">C</button>
		
		            <button type="button">4</button>
		            <button type="button">5</button>
		            <button type="button">6</button>
		            <button type="button" class="operator">-</button>
		
		            <button type="button">1</button>
		            <button type="button">2</button>
		            <button type="button">3</button>
		            <button type="button" class="operator">+</button>
		
		            <button type="button">0</button>
		            <button type="button" class="operator">%</button>
		            <button type="button" class="operator">×</button>
		            <button type="button" class="equals operator">=</button>
		          </div>
		        </div>
		        <p id="teksLoveU" class="sembunyi">I Love U 1% 💗</p>
		        <p id="teksRandomEmoji" class="sembunyi"></p>
		        
		        <style>.containerAkhir{display:flex;width:100%;height:80px;justify-content:center;line-height:1.35em;text-align:center;margin-top:0px}</style>
		        <div id="contentAkhir" class="containerAkhir sembunyi">
		           <h1 id="teksAkhir" class="sembunyi quicksand" style="font-size: 18px;font-weight:400">Don't be mad again, okay? 😍😋🩷</h1>
		        </div>
		      </div>

        </div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
        <div class="swiper-pagination"></div>
    </div>
    
    <div id="container">
        <div class="wrapper">
            <div class="box">
                <!-- Box elements -->
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
            </div>
        </div>
    </div>

  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<script>
var teksSekarang = 1;const body = document.querySelector("body"); audio = new Audio('' + linkmp3.src); 
var swiper = new Swiper(".mySwiper", {
    pagination: {el: ".swiper-pagination", dynamicBullets: false,},
    on: {
    slideChange: function () {
        teksSekarang++;
        teksScale = document.querySelector('#teks' + teksSekarang);
        stikerScale = document.querySelector('#stiker' + teksSekarang);
        Tombol = document.querySelector('#Tombol');

        setTimeout(function(){
          teksScale.classList.add("scale1");
          stikerScale.classList.add("scale1");
          
          if(teksSekarang == 2){
              Tombol.style="opacity:1;transform: scale(1);"
          } else if(teksSekarang == 3){
              setTimeout(katanimasi, 300);              
          } else if(teksSekarang == 4){setTimeout(function(){teksScale.classList.remove("scale1");stikerScale.classList.remove("scale1");teksScale.classList.add("scale0");stikerScale.classList.add("scale0");setTimeout(function(){calculator.style="display:flex";setTimeout(function(){calculator.classList.add("scale1");teksScale.style="display:none";stikerScale.style="display:none"},50);},550);}, 1400);}
          
        }, 50);
    },
    },
    navigation: {nextEl: ".swiper-button-next", prevEl: ".swiper-button-prev",},
});
    
initeks = teks3.innerHTML;
teks3.innerHTML = "";
function katanimasi(){
    teks3.innerHTML = "";
	new TypeIt("#teks3", {
    strings: ["" + initeks], startDelay: 10, speed: 25, cursor: true,
    afterComplete: function(){
      	//clearInterval(scrollInterval);
      	teks3.innerHTML = initeks;
          
        setTimeout(function(){
            teksScale.classList.remove("scale1");
            stikerScale.classList.remove("scale1");
            teksScale.classList.add("scale0");
            stikerScale.classList.add("scale0");
               
            setTimeout(function(){stikerAkhir1.src = stikerAkhir2.src;teks3.innerHTML="";}, 450);
               
            setTimeout(function(){
                //setTimeout(katanimasi3, 200);
       <!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8" />
  <title>Don't be mad... - Something for You</title>
  <meta name="description" content="Instagram @aoudumber.dev - Script HTML by aoudumber.dev">
  <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1" />
  <meta name="description" content="Special For Cutieee">
  <meta property="og:title" content="Special HTML For You ✨">
  <meta property="og:description" content="Open it, my Cutieee ❤️">
  <meta property="og:image" content="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhMDugl2siKVTnQUhkzqZXmNhnUl_IXm-tsnodgHf4C3dPn6v4gz06nVm1ASqpRXO65Dg3PkYB9bKsThBPUxygLD9Euem9SSTr0LRIGK9x5uaLvK4WIPn6VlSx0qSrPGhTknGVHeVMpioiBcXiqrk-dF3d4SYS8QIkWkDlMgRrdF4vw_iw-EOgTYcwo6xhs/s300/1000314955.jpg">
  <meta property="og:image:alt" content="Cutieee">
  <meta property="og:type" content="website">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
  <link rel="stylesheet" href="style.css"><script src="https://unpkg.com/scrollreveal"></script><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>

  <!-- Demo styles -->
  <style>
        * {
            padding: 0;
            margin: 0;
        }
        body {
            background: linear-gradient(0.25turn, rgb(0, 38, 77), rgb(0, 38, 70));
            background: #000;
            background-size: cover;
            background-position: center;
            height: 100vh;
            overflow: hidden;
            color: black;
        }
        #container {
            width: 80%;
            margin: 20px auto;
            min-height: 650px;
            margin-top: 150px;
            color: black;
        }
        @media screen and (max-width: 400px) {
            #container {
                width: 100%;
                margin: 50% auto;
                min-height: 800px;
            }
        }
        .wrapper {
            position: fixed;
        }
        .box div {
            position: fixed;
            width: 60px;
            height: 60px;
            background-color: transparent;
            border: 6px solid rgba(255, 255, 255, 0.3);
            border-radius:50%;
        }
        .box div:nth-child(1) {
            top: 12%;
            left: 42%;
            animation: animate 10s linear infinite;
        }
        .box div:nth-child(2) {
            top: 70%;
            left: 50%;
            animation: animate 7s linear infinite;
        }
        .box div:nth-child(3) {
            top: 17%;
            left: 6%;
            animation: animate 9s linear infinite;
        }
        .box div:nth-child(4) {
            top: 20%;
            left: 60%;
            animation: animate 10s linear infinite;
        }
        .box div:nth-child(5) {
            top: 67%;
            left: 10%;
            animation: animate 6s linear infinite;
        }
        .box div:nth-child(6) {
            top: 80%;
            left: 70%;
            animation: animate 12s linear infinite;
        }
        .box div:nth-child(7) {
            top: 60%;
            left: 80%;
            animation: animate 15s linear infinite;
        }
        .box div:nth-child(8) {
            top: 32%;
            left: 25%;
            animation: animate 16s linear infinite;
        }
        .box div:nth-child(9) {
            top: 90%;
            left: 25%;
            animation: animate 9s linear infinite;
        }
        .box div:nth-child(10) {
            top: 20%;
            left: 80%;
            animation: animate 5s linear infinite;
        }
        @keyframes animate {
            0% {
                transform: scale(0) translateY(0) rotate(0);
                opacity: .8;
            }
            100% {
                transform: scale(1.3) translateY(-90px) rotate(360deg);
                opacity: 0;
            }
        }
    </style>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Caveat&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@400;700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap');
	@import url('https://fonts.googleapis.com/css2?family=Inter&family=Itim&display=swap');
	
	:root {
	--poppins: 'Poppins', sans-serif;
	--nunito: 'Nunito Sans', sans-serif;
	--caveat: 'Caveat', cursive;
	--quicksand: 'Quicksand', sans-serif;
	--itim: 'Itim', cursive;
	--inter: 'Inter', sans-serif;
	}

    html, body {position: relative;height: 100%;}
    body {font-family: 'Itim', cursive;font-size: 14px;color: #fff;text-shadow: 0px 2px 2px rgba(0, 0, 0, .5);margin: 0;padding: 0;}
    
    #bodyblur{opacity:.25;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.5);transition:all 1s ease;} 
    #sthisblur{backdrop-filter:blur(3px);-webkit-backdrop-filter:blur(3px);position:absolute;top:0;left:0;right:0;bottom:0;}
    #wallpaper{/*animation: jj 7s infinite;*/width:100%;height:100%;transform: scale(1.3);transition:all 1.3s ease;}
    #wallpaper2, #wallpaper3, #wallpaper4{display:none}
    @keyframes jj{0%  {transform: scale(1);} 50% {transform: scale(1.3);} 100% {transform: scale(1);} }

    p{margin-left:50px;margin-right:70px;text-align:left}
    #ket{margin:20px}

    .swiper {width: 100%;height: 100%;padding:0;margin:0;}
    .swiper-slide {text-align: center;font-size: 18px;/*background: #fff;*/display: flex;flex-direction: column;justify-content: center;align-items: center;margin-top:-100px;}
    .swiper-slide img {display: block;width: 100%;height: 100%;object-fit: cover;}
    .swiper-pagination{margin-bottom:25vh}
    .swiper-pagination-bullet-active{background-color: #fff !important;opacity:1 !important}
    .swiper-pagination-bullet{background-color:rgba(255,255,255, 1) !important;}
    .swiper-button-next, .swiper-button-prev{display:flex;top:unset;bottom:-100px}
    
    .sembunyi{display: none !important;}
    .stiker{display:flex;justify-content:center;align-items:center;margin-left:auto;margin-right:auto;margin-bottom:20px;transition:all .75s ease}
    .stiker img{width:90px;height:90px;box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);background: rgba(255, 255, 255, 0.7);border: 2px solid rgba(255, 255, 255, 1);border-radius: 50%;padding:10px;}
    .stiker img.sty2{background:none;filter: drop-shadow(0 4px 8px rgba(255, 255, 255, 0.2));box-shadow: none;backdrop-filter: none;-webkit-backdrop-filter: none;border: none;border-radius: 0;padding:0;width: auto;height:90px;}
	b.merah{color:red}
	b.kuning{color:yellow}
	b.putih{text-shadow:none;padding-left:8px;padding-right:8px;padding-top:2px;padding-bottom:2px;background-color:white;border-radius:12px}
	span.garismerah{border-bottom:2px solid red}
	span.gariskuning{border-bottom:2px solid yellow}
    p{color:white;font-size:15px;line-height:1.5em;}
    .scale0{opacity:0;transform: scale(0);transition: all .9s ease;}
    .scale1{opacity:1;transform: scale(1);transition: all .9s ease;}
    svg{vertical-align: middle;width: 22px;height: 22px;fill: #fff}
    .heart-icon {z-index:100;width: 30px;height: 30px;position: fixed;animation:  heartMove linear 1;top: -10vh;}

	@keyframes heartMove {
	  0% {transform: translateY(-10vh);}
	  100% {transform: translateY(100vh);}
	}
	    svg.line{fill: none;stroke: #fff;stroke-width: 2;animation: moving .7s linear infinite alternate;}
	    .spin{animation: spin 3s linear infinite alternate;}
	@keyframes spin {
	  from {
	    transform: rotate(20deg);
	  }
	  to {
	    transform: rotate(-20deg);
	  }
	}
	@keyframes moving {
	  from {
	    transform: translateY(0);
	  }
	  to {
	    transform: translateY(3px);
	  }
	}
    .overlay {position: fixed;top: 0;left: 0;width: 100%;height: 100%;display: flex;justify-content: center;align-items: center;background:#000;z-index:100;}
    .loading-message {font-size: 13px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);color:white;text-align: center;}
    .blocklove{display: none;flex-direction: column;justify-content: center;align-items: center;}
    .lovein{background:#fff;color:#FF0900;border-radius:50%;width:40px;height:40px;padding:10px;font-size:30px;display:flex;align-items:center;text-align:center;justify-content:center;transition:all .3s ease;}
    .lovein:hover{transform: scale(.9);color:#FF0900;}
    .lovein svg{stroke:#FF0600;width:30px;height:30px}
    
    .blocktext{margin-top:10px;position:relative;width:100%;height: 160px; overflow: auto;background-color:none;}

    .tombol{background-color: rgba(255,255,255,0);border-radius: 50px;overflow: hidden;display: flex;align-items: center;justify-content: center;-webkit-transition: all .2s ease-out;transition: all .2s ease-out}
    .tombol svg{margin: auto;fill:#ffd4d4;stroke: #ff0000;width: 60px;height: 60px;animation: spin2 1s linear infinite alternate;}
    #Tombol{margin-top:20px;position:relative;margin-left:auto;margin-right:auto;display:flex;align-items:center;justify-content:center;list-style:none;transition:all 1s ease;}
    #Tombol a{display:inline-flex;align-items:center; margin:0;margin:10px;transition:all .2s ease;padding:10px;outline:0;border:2px solid white;border-radius:30px;line-height:15px;background:rgba(0,0,0,.3);color:white;font-size:13px;font-weight:700;white-space:nowrap;overflow:hidden;box-shadow: rgba(255,255,255, 0.15) 0px 7px 29px 0px;z-index:1}
    #Tombol, #Tombol2, #TombolWA{position:relative;opacity:0;margin-left:auto;margin-right:auto;display:flex;justify-content:center;align-items:center;list-style:none;transition:all 1s ease;}
    #Tombol a, #Tombol2 a, #TombolWA a{display:inline-flex;align-items:center; margin:0;margin:10px;transition:all .2s ease;padding:10px;outline:0;border:2px solid white;border-radius:30px;line-height:15px;background:rgba(255, 182, 193, .3);color:white;font-size:13px;font-weight:700;white-space:nowrap;overflow:hidden;box-shadow: rgba(255,255,255, 0.15) 0px 7px 29px 0px;z-index:1}
    
    .swal2-modal > *{font-size:16px;color:white}
	.swal2-title{line-height:1.3em;font-size:17px;text-align:center;padding:15px 30px 0 30px;}
	.swal2-timer-progress-bar-container > *{opacity:.5;background:#00B6FF;margin:0 20px}
	.swal2-modal{background: rgba(0,0,0, 1);backdrop-filter: blur(0);-webkit-backdrop-filter: blur(0);box-shadow: 0 4px 30px rgba(255,255,255, 0.3);border: 2px solid rgba(255, 255, 255, 1);border-radius: 30px;max-width:325px;top:-60px;}
	.swal2-image{background: rgba(255, 255, 255, 0.5);box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);border: 2px solid rgba(255, 255, 255, 1);border-radius: 50%;padding:10px;}
	.swal2-styled.swal2-confirm, .swal2-styled.swal2-cancel{position: relative;background-color: #4839eb;color: #fff;border-radius:18px;z-index: 1;transition: all 0.2s;}
	
	/* Calculator */
    .calculator{display:none;position:relative;margin-top:50px;box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);background: rgba(255, 255, 255, 0.1);border: 1px solid rgba(255, 255, 255, 0.3);border-radius:20px;padding:18px;width:180px;flex-direction:column;justify-content:center;align-items:center;}
    .calculator-screen{font-family: 'Itim', cursive;font-weight:700;width:100%;height:50px;border:none;background-color:rgba(255,255,255,0.1);margin:auto;padding:0;font-size:23px;color:#fff;text-shadow: 0px 2px 2px rgba(0, 0, 0, .5);border-radius:15px;text-align:center;}
    .calculator-keys{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;}
    .calculator-keys button{width:38px;height:38px;border:none;border-radius:50%;background-color:rgba(255,182,193,0.6);font-size:16px;color:#fff;transition:background-color 0.3s,transform 0.2s;}
    .calculator-keys button:hover{background-color:rgba(255,182,193,0.8);}
    .calculator-keys button:active{background-color:rgba(255,182,193,1);transform:scale(0.9);}
    .calculator-keys .operator{background-color:rgba(255,105,135,0.8);color:#fff;}
    .calculator-keys .operator:hover{background-color:rgba(255,105,135,1);}
    .calculator-keys .equals{background-color:rgba(255,92,128,0.8);color:#fff;}
    .calculator-keys .equals:hover{background-color:rgba(255,92,128,1);}
    .calculator-keys {margin-top:20px;transition: opacity 0.5s ease;}
    .calculator-keys.hide {opacity: 0;pointer-events: none;}
</style>
</head>

<body>
  <audio src="" id="linkmp3" class="sembunyi"></audio>
	<div class="overlay">
    <div class="loading-message">Hey you!<br>Wait a moment...</div>
     <div id="loveIn" class="blocklove">
        <a href="#" target="_blank" class="lovein"></a>
        <p id="ket">Touch the LOVE!</p>
     </div>
   </div>
   
   <div id="bodyblur">
     <img src="./assets/nightin.jpeg" id="wallpaper"/>
     <div id="thisblur"></div>
   </div>
   
    <!-- Swiper -->
    <div class="swiper mySwiper">
        <div class="swiper-wrapper">

            <div class="swiper-slide">
                <div id="stiker1" class="scale0 stiker">
                    <img src="./assets/cilukba.gif" />
                </div>
                <h1 id="teks1" class="scale0 quicksand" style="font-size: 20px;">Hello Cutieee 🫢<br><br> >>>>
                </h1>
            </div>

            <div class="swiper-slide">
                <div id="stiker2" class="scale0 stiker">
                    <img src="./assets/gemoy.gif" />
                </div>
                <h1 id="teks2" class="scale0 quicksand" style="font-size: 19px;">My Cutieee, Still Mad? 🫣</h1>
                <div id="Tombol" style="opacity:0;transform: scale(0)">
                    <a id="By" onClick="swiper.slideNext();">Not anymore 💗</a>
                    <a id="Bn" onClick="btn='Bn';fungsibaru(btn)">Still 🤬</a>
                </div>
                <img id="stikerTolak" class="sembunyi" src="./assets/cubit.gif"/>
                <p id="teksTolak" class="sembunyi">Aww, just sulking like that 😋😝</p>
                
                <img id="stikerTolak2" class="sembunyi" src="./assets/weee.gif"/>
                <p id="teksTolak2" class="sembunyi">You'll age quickly 🫣🤣</p>
            </div>

            <div class="swiper-slide">
                <div id="stiker3" class="scale0 stiker" style="margin-top:50px">
                    <img id="stikerAkhir1" src="./assets/ciumpipi.gif" />
                    <img id="stikerAkhir2" class="sembunyi" src="./assets/panah.gif" />
                </div>
                <div id="scroll-container" class="blocktext">
                    <h1 id="teks3" class="scale0 quicksand" style="font-size: 17px;font-weight:400"><b style="font-size: 22px;">Yay! 🥳</b><br><br>Thank you for not being mad 😋<br><br><b>Now I Want to Ask You Something 😝🩷</b></h1>
                    <h1 id="teksTambahan" class="sembunyi"><span id="teksLove">I Love You</span></h1>
                    <script>const loveEmojis = ['💖']</script>
                </div>
            </div>
            
            <div class="swiper-slide">
		       <div id="stiker4" class="scale0 stiker">
		        <img id="stikerAkhir3" src="./assets/inicinta.gif"/>
		        <img id="stikerAkhir4" class="sembunyi" src="./assets/terlope.gif"/>
		       </div>
		      	<h1 id="teks4" class="scale0 quicksand" style="font-size: 20px;">Answer here! 😆<br><br> >>>></h1>
		      
		      <div id="calculator" class="scale0 calculator">
		        <input type="text" class="calculator-screen" id="screen" disabled>
		        <div class="calculator-keys">
		            <button type="button">7</button>
		            <button type="button">8</button>
		            <button type="button">9</button>
		            <button type="button" class="operator">C</button>
		
		            <button type="button">4</button>
		            <button type="button">5</button>
		            <button type="button">6</button>
		            <button type="button" class="operator">-</button>
		
		            <button type="button">1</button>
		            <button type="button">2</button>
		            <button type="button">3</button>
		            <button type="button" class="operator">+</button>
		
		            <button type="button">0</button>
		            <button type="button" class="operator">%</button>
		            <button type="button" class="operator">×</button>
		            <button type="button" class="equals operator">=</button>
		          </div>
		        </div>
		        <p id="teksLoveU" class="sembunyi">I Love U 1% 💗</p>
		        <p id="teksRandomEmoji" class="sembunyi"></p>
		        
		        <style>.containerAkhir{display:flex;width:100%;height:80px;justify-content:center;line-height:1.35em;text-align:center;margin-top:0px}</style>
		        <div id="contentAkhir" class="containerAkhir sembunyi">
		           <h1 id="teksAkhir" class="sembunyi quicksand" style="font-size: 18px;font-weight:400">Don't be mad again, okay? 😍😋🩷</h1>
		        </div>
		      </div>

        </div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
        <div class="swiper-pagination"></div>
    </div>
    
    <div id="container">
        <div class="wrapper">
            <div class="box">
                <!-- Box elements -->
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
                <div></div>
            </div>
        </div>
    </div>

  <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<script>
var teksSekarang = 1;const body = document.querySelector("body"); audio = new Audio('' + linkmp3.src); 
var swiper = new Swiper(".mySwiper", {
    pagination: {el: ".swiper-pagination", dynamicBullets: false,},
    on: {
    slideChange: function () {
        teksSekarang++;
        teksScale = document.querySelector('#teks' + teksSekarang);
        stikerScale = document.querySelector('#stiker' + teksSekarang);
        Tombol = document.querySelector('#Tombol');

        setTimeout(function(){
          teksScale.classList.add("scale1");
          stikerScale.classList.add("scale1");
          
          if(teksSekarang == 2){
              Tombol.style="opacity:1;transform: scale(1);"
          } else if(teksSekarang == 3){
              setTimeout(katanimasi, 300);              
          } else if(teksSekarang == 4){setTimeout(function(){teksScale.classList.remove("scale1");stikerScale.classList.remove("scale1");teksScale.classList.add("scale0");stikerScale.classList.add("scale0");setTimeout(function(){calculator.style="display:flex";setTimeout(function(){calculator.classList.add("scale1");teksScale.style="display:none";stikerScale.style="display:none"},50);},550);}, 1400);}
          
        }, 50);
    },
    },
    navigation: {nextEl: ".swiper-button-next", prevEl: ".swiper-button-prev",},
});
    
initeks = teks3.innerHTML;
teks3.innerHTML = "";
function katanimasi(){
    teks3.innerHTML = "";
	new TypeIt("#teks3", {
    strings: ["" + initeks], startDelay: 10, speed: 25, cursor: true,
    afterComplete: function(){
      	//clearInterval(scrollInterval);
      	teks3.innerHTML = initeks;
          
        setTimeout(function(){
            teksScale.classList.remove("scale1");
            stikerScale.classList.remove("scale1");
            teksScale.classList.add("scale0");
            stikerScale.classList.add("scale0");
               
            setTimeout(function(){stikerAkhir1.src = stikerAkhir2.src;teks3.innerHTML="";}, 450);
               
            setTimeout(function(){
                //setTimeout(katanimasi3, 200);
       
