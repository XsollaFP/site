<!DOCTYPE html>

<html>

<head>

<meta http-equiv="content-type" content="text/html; charset=utf-8" />

<meta name="" content="">
<link rel="stylesheet" href="main.css">

<title>Heart</title>

<style type="text/css" media="all">

body {

margin: 0;

padding: 0;

display: flex;

align-items: center;

justify-content: center;

min-height: 92vh;

background: black;

}

.heart {

height: 100px;

width: 100px;

background: rgb(255, 255, 255);

position: relative;

transform: rotate(-45deg);

box-shadow: -10px 10px 90px rgb(255, 255, 255);

animation: heart 0.6s linear infinite;

}

@keyframes heart {

0% {

transform: rotate(-45deg) scale(1.00);

}

80% {

transform: rotate(-45deg) scale(0.90);

}

100% {

transform: rotate(-45deg) scale(0.80);

}

}

.heart::before {

content: "";

position: absolute;

height: 100px;

width: 100px;

background:#fff;

top: -55%;

border-radius: 50px;

box-shadow: -10px 10px 90px rgb(255, 255, 255);

}

.heart::after {

content: "";

position: absolute;

height: 100px;

width: 100px;

background: rgb(255, 255, 255);

right: -55%;

border-radius: 50px;

box-shadow: -10px 10px 90px rgb(255, 255, 255);

}
.text{
color:white;
position:absolute;
right: 40%;
bottom: 80%;
font-size: 45px;
text-shadow: 2px 10px 10px #ffffff;
}
</style>

</head>

<body>

<div class="heart">
</div>
<div class="text">C 14 февраля!</div>

</body>

</html>
