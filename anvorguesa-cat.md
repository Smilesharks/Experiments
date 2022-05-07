---
layout: cat
title: Anvorguesa cat
status: OK
---
<div style="background-color: #982121;" id="svgx" class="relative flex flex-col justify-center min-h-screen py-6 overflow-hidden sm:py-12">
	<div class="max-w-2xl mx-auto">
	<div class="box">
		<div class="logo">
			<div class="fluff">
			<i class="ion-android-star-outline"></i>
			<i class="ion-android-star-outline"></i>
			<div class="michi">
				<div class="ear ear--left"></div>
				<div class="ear ear--right"></div>
				<div class="face">
					<div class="ojito ojito--left">
					<div class="ojito-pupil"></div>
					</div>
					<div class="ojito ojito--right">
					<div class="ojito-pupil"></div>
					</div>
					<div class="muzzle"></div>
				</div>
				</div>
			<i class="ion-android-star-outline"></i>
			<i class="ion-android-star-outline"></i>
			</div>
			<div class="h1">Anvorguesa</div>
			<div class="h5">I can haz cheezburger?</div>
		</div>
	</div>
	</div>

</div>


<style>

	@import url(https://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css);

body {
    background-color: #982121;
}
.logo {
    font-family: "Raleway", Arial, sans-serif;
    position: relative;
    color: #ffb80e;
    margin: 0px 20px 60px;
    max-width: 295px;
    width: 100%;
    text-align: center;
    font-size: 16px;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}
.logo .h1,
.logo .h5 {
    margin: 0;
    text-transform: uppercase;
}
.logo .h1 {
    font-family: "Arvo", Arial, sans-serif;
    font-size: 2.4em;
    line-height: 1.3em;
    position: relative;
    font-weight: 900;
    margin-top: 38px;
}
.logo .h1:before {
    content: "";
    position: absolute;
    background-color: #ed6b36;
    left: 50%;
    -webkit-transform: translateX(-50%);
    transform: translateX(-50%);
    width: 200px;
    height: 34px;
    border-radius: 50% 50% 0 0;
    border: solid #ed6b36;
    border-width: 3px;
    box-shadow: 0 0 0 3px #982121 inset;
    bottom: 100%;
}
.logo .h5 {
    font-size: 0.7em;
    font-weight: 800;
    color: #8c2c27;
    background-color: #ed6b36;
    width: 200px;
    margin: 0 auto;
    line-height: 3em;
    border-radius: 0 0px 20px 20px;
    border: solid #ed6b36;
    border-width: 3px;
    box-shadow: 0 0 0 3px #982121 inset;
}
.logo i {
    font-size: 2em;
    color: #ffb80e;
}
.logo i:first-child,
i:last-child {
    font-size: 1em;
    bottom: -100px;
    transform: translateY(10px);
}
.fluff {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px 10px;
}
.michi {
    position: relative;
    height: 50px;
    width: 56.5px;
}
.ear {
    position: absolute;
    top: -30%;
    height: 60%;
    width: 25%;
    background: #fff;
}
.ear::before,
.ear::after {
    content: "";
    position: absolute;
    bottom: 24%;
    height: 10%;
    width: 5%;
    border-radius: 50%;
    background: #982121;
}
.ear::after {
    transform-origin: 50% 100%;
}
.ear--left {
    left: -7%;
    border-radius: 70% 30% 0% 0% / 100% 100% 0% 0%;
    transform: rotate(-15deg);
}
.ear--left::before,
.ear--left::after {
    right: 10%;
}
.ear--left::after {
    transform: rotate(-45deg);
}
.ear--right {
    right: -7%;
    border-radius: 30% 70% 0% 0% / 100% 100% 0% 0%;
    transform: rotate(15deg);
}
.ear--right::before,
.ear--right::after {
    left: 10%;
}
.ear--right::after {
    transform: rotate(45deg);
}
.face {
    position: absolute;
    height: 100%;
    width: 100%;
    background: #982121;
    border-radius: 50%;
}
.ojito {
    position: absolute;
    top: 35%;
    height: 30%;
    width: 31%;
    background: #fff;
    border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}
.ojito::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    height: 0;
    width: 100%;
    border-radius: 0 0 50% 50array/0array 0 40% 40%;
    background: #982121;
    animation: blink 4s infinite ease-in;
}
@keyframes blink {
    0% {
        height: 0;
    }
    90% {
        height: 0;
    }
    92.5% {
        height: 100%;
    }
    95% {
        height: 0;
    }
    97.5% {
        height: 100%;
    }
    100% {
        height: 0;
    }
}
.ojito::before {
    content: "";
    position: absolute;
    top: 60%;
    height: 10%;
    width: 15%;
    background: #fff;
    border-radius: 50%;
}
.ojito--left {
    left: 0;
}
.ojito--left::before {
    right: -5%;
}
.ojito--right {
    right: 0;
}
.ojito--right::before {
    left: -5%;
}
.ojito-pupil {
    position: absolute;
    top: 25%;
    height: 50%;
    width: 20%;
    background: #982121;
    border-radius: 50%;
    animation: look-around 4s infinite;
}
@keyframes look-around {
    0% {
        transform: translate(0);
    }
    5% {
        transform: translate(50%, -25%);
    }
    10% {
        transform: translate(50%, -25%);
    }
    15% {
        transform: translate(-100%, -25%);
    }
    20% {
        transform: translate(-100%, -25%);
    }
    25% {
        transform: translate(0, 0);
    }
    100% {
        transform: translate(0, 0);
    }
}
.ojito--left .ojito-pupil {
    right: 30%;
}
.ojito--right .ojito-pupil {
    left: 30%;
}
.ojito-pupil::after {
    content: "";
    position: absolute;
    top: 30%;
    right: -5%;
    height: 20%;
    width: 35%;
    border-radius: 50%;
    background: #fff;
}
.muzzle {
    position: absolute;
    top: 60%;
    left: 50%;
    height: 6%;
    width: 10%;
    background: #fff;
    transform: translateX(-50%);
    border-radius: 50% 50% 50% 50% / 30% 30% 70% 70%;
}

</style>