<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practics Work </title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body{
      background: color #d8d8d8;
      color: black;
      font-family: Arial, Helvetica, sans-serif;
      margin:none;
      padding: 50% 0;
      text-align: center;
}

h1{
font-weight: bold;
}

p {
font-weight: small;
word-spacing: 5px;
}
div{
font-size: small;
}
.container a{
font-size: small;
}

.text_1 {
animation: text1;
}

.text_2 {
animation: text2;
}

.text_1, .text_2 {
overflow: hidden;
white-space: nowrap;
display: inline-block;
position: relative;
animation-duration: 8s;
animation-timing-function: steps(10, end);
animation-iteration-count: infinite;
}

.text_1::after, .text_2::after {
content: "|";
position: absolute;
right: 0;
animation: caret infinite;
animation-duration: 1s;
animation-timing-function: steps(1, end);
}

@keyframes text2 {
0%, 50%, 100% {
width: 0;
}

60%, 90% {
width: 8em;
}
}

@keyframes text1 {
0%, 50%, 100% {
width: 0;
}
10%, 40% {
width: 15em;
}
}

@keyframes caret {
0%, 100% {
opacity: 0;
}
50% {
opacity: 1;
}
}
.social-menu ul{
right: 40%;;
position: absolute;
padding:0;
margin: 0px;
display: flex;
}
.social-menu ul li{
list-style: none;
margin: 0 15px;

}
.social-menu ul li .fa {
font-size: 25px;
line-height: 43px;
transition: .6s;
color: #000;
}
.social-menu ul li a{
position:relative ;
display:block;
width:40px ;
height: 40px;
border-radius:50% ;
background-color:#fff ;
text-align: center;
transition: .6s;
box-shadow: 0 5px 4px rgba(0,0,0,.5);
}
.social-menu ul li a:hover{
transform: translate(0 ,-10px);
}
.social-menu ul li:nth-child(1) a:hover{
background-color: #3b5999;
}
.social-menu ul li:nth-child(2) a:hover{
background-color: #55acee;
}
.social-menu ul li:nth-child(3) a:hover{
background-color: #e4405f;
}
.social-menu ul li:nth-child(4) a:hover{
background-color: #0077b5;
}

</style>
</head>
<body>
    <h1>SUMIT VEKARIYA</h1>
    <small><p><span class="text_1">Full Stock Software Engineer</span><span class="text_2">Based In India</span></p></small>
    <p><small> I'am enterprise level web/mobile application developer expertise in framework / programing language </small></p>
     <div class="container"> +
      <a href="https://angular.io/start/start-routing" target="_blank" rel="noopener-norffer"> Angular</a> + 
      <a href="https://nodejs.org/api/url.html" target="_blank" rel="noopener-norffer">NoseJS</a> +
      <a href="https://docs.nestjs.com/controllers" target="_blank" rel="noopener-norffer">NestJS</a> +
      <a href=" https://docs.flutter.dev/ui/navigation/url-strategies" target="_blank" rel="noopener-norffer">flutter</a> +
      <a href="https://serverless.com/blog/aws-lambda-function-urls-with-serverless-framework" target="_blank" rel="noopener-norffer">serverless</a> + 
      <a href="https://graphql.org/learn/serving-over-http/" target="_blank" rel="noopener-norffer">GraphQL</a> +
      <a href="https://webrtc.org/" target="_blank" rel="noopener-norffer">WebRTC</a> etc.
     </div>
     <br>
     <br>
    <div class="social-menu">
        <ul>
         <li><a href="#"><i class="fa fa-facebook"></i></a></li>
         <li><a href="#"><i class="fa fa-twitter"></i></a></li>
         <li><a href="#"><i class="fa fa-instagram"></i></a></li>
         <li><a href="#"><i class="fa fa-linkedin"></i></a></li>
        </ul>
      </div>
</body>
</html>