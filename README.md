<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="./style.css">
</head>
<body class="body">
<header class="heading">
<nav>
 <a class="link-1" href="#">Home</a>
 <a class="link-2" href="blog.html">Blog</a>
</nav>
</header>

<h1>The Box Model, Box Sizing and Box Shadow</h1>
<p class="para-1">Exersice One</p>
 <section>
<div>
<div class="multilayer-box"></div>
</div>
 </section>
<section class="section1">
<div class="smallcontainer"> 
<span class="smallcircle"></span>
<span>#99D8CA</span>
<div class="color1"></div>
<span>#0D1430</span>
<div class="smallcircle-2"></div>
<span>#90FFA9</span>
<div class="smallcircle-3"></div>
<span>#5873E2</span>
</div> </section>
<hr>
</section>

<h2>Exersice Two</h2>
<section class="section-2">
  <div class="bigcontainer">
    <div class="smallbox"></div>
    <div class="smallbox"></div>
    <div class="smallbox"></div>
  </div>
  <hr>
  <div class="large-container">
    <div class="minibox"></div>
    <div class="minibox"></div>
    <div class="minibox"></div>
  </div>



                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
</body>
</html>


/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
/* Custome Styles */

.heading { text-align: center;
background-color: rgb(4, 4, 58);
text-transform: uppercase;
padding: 15px;
}

.link-1 { margin: 0 30px;
color: #008000;
}

.link-2 { color: #ffff;
}

h1 { font-size: 20px;
text-align: center;
margin-top: 30px;
}
.para-1 {
text-align: center;
margin-top: 30px;
}
.multilayer-box {
width: 125px;
height: 120px;
background-color: #99D8CA;
margin-left: 46%;
margin-top: 50px;
border: 12px solid #5873E2;
position: relative;
}

.multilayer-box::before {
content: " ";
position: absolute;
z-index: -1;
top: -19px;
bottom: -19px;
right: -19px;
left: -19px;
border: 15px solid black;
border-radius: 5px;
outline:  10px solid #90FFA9;
}
.smallcontainer {
display: inline-block;
margin-top: 30px;
margin-left: 39%;
}
.smallcircle {
background-color: #99D8CA;
display: inline-block;
width: 20px;
height: 20px;
border-radius: 50%;
}


.color1 { background-color: #0D1430;
width: 20px;
height: 20px;
display: inline-block;
margin-top: px;
border-radius: 50%;
display: inline-bloc

}
.smallcircle-2 {
background-color: #90FFA9;
display: inline-block;
width: 20px;
height: 20px;
border-radius: 50%;
}
.smallcircle-3 {
background-color: #5873E2;
display: inline-block;
width: 20px;
height: 20px;
border-radius: 50%;

}
hr { width: 500px;
margin-top: 20px;
border: 1px dotted gray;
}

h2 {
text-align: center;
margin-top: 30px;
}
.bigcontainer {
width: 660px;
height: 200px;
border: 2px solid black;
margin: 24px auto;
font-size: 0px;
}
.smallbox {
background-color: grey;
width: 200px;
height: 180px;
margin: 10px;
display: inline-block;
}
.large-container {
width: 530px;
height: 140px;
border: 2px solid black;
margin: 24px auto;
}
.minibox { display: inline-block;
width: 150px;
height: 120px;
border: 2px solid black;
background-color: grey;
margin: 10px;

}
/* styles for blog.html */

.main-header { font-size: 15px;
text-align: center;
background-color: rgb(2, 2, 73);
padding: 15px;
}

.link-home { margin-right: 15px;
color: white;
}
.link-blog {
color: green;
}
img { display: inline-block;
width: 400px;
height: 300px;
margin-top: 20px;
}
.blogone { margin-bottom: 20px;
font-size: 26px;
float: right;
margin-right: 500px;
color: rgb (5,5,70);
}

.blog-para { 
padding-right: 510px;
margin-right: 100px;
line-height: 1.6;

}
.button {
background-color: green;
border: 5px solid green;
color: white;
font-size: 19px;
border-radius: 19px;
margin: 20px;

}



.blog-para2{
padding-right: 970px;
margin-top: 10px;
margin-bottom: 10px;
}

.learnmore { color: green;
font-size: 20px;
margin-top: 10px;
}

.two-images {
display: flex;
flex-flow: row nowrap;
justify-content: space-between;
margin-top: 40px;
margin-right: 500px;

}
.half-width { 
width: 48%; 
}
.para-heading2{
margin-top: 10px;
margin-bottom: 10px;
font-size: 26px;
}


.blog-heading3{ font-size: 26px;
margin-top: 10px;
margin-bottom: 10px;

}
.learnmore { color: green;
font-size: 20px;
border-bottom: 2px solid green;
}


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Blog</title>
 <link rel="stylesheet" href="./style.css">
</head>
<body class="body">
<header class="main-header">
<nav>
<a class="link-home" href="index.html">HOME</a>
<a class="link-blog" href="#">BLOG</a>
</nav>
</header>
<main>
<section class="blog-section">
<article>
<img src="bulb.jpg" alt="pic1"  style="float:left; margin-right:10px; margin-top:15px;"/>

<h2 class="blogone">The Standard Lorem Ispum, used since the 1500s</h2>

<p class="blog-para">But i must explain to you how all this mistaken of denouncing 
and pleasure and praising pain was born and i will give you a complete account of the system but i must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and i will give you the complete account of the system</p>
<button class="button">Read more </button>
</article>
</section>
</main>
<section class="lastsection">
<article>
<div class="two-images">
<figure class="half-width">
<img src="pic03.png" alt="pic03"/>
<figcaption class="para-heading2">1914 translation by H. Rackham</figcaption>
<figcaption>But i must tell you how all t his mistaken idea of denouncingpleasure and praising pain was born and i will give you a complete account of the system but i must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and i will give you a complete account of the system </figcaption>
<a class="learnmore">Learn More</a>
</figure>
<figure class="half-width">
<img src="pic02-1.png" alt="pic02"/>
<figcaption class="blog-heading3">Lorem Ispum is simply dummy text of the printing and typesetting</figcaption>
<figcaption class="blog-last">but i must tell you all this mistaken idea of denouncing and praising pain was born and i will give you a complete account of the system</figcaption>
<a class="learnmore">Learn More</a>
</figure>


</div>

</div>

</article>
</section>
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
</body>
</html>
![image](https://user-images.githubusercontent.com/91254956/150635274-9d686529-48ef-4313-b27a-0c4cd1cbfed0.png)
bulb.jpg
