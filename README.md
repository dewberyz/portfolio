<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>my e-portfolio!</title>
<link rel="stylesheet" href="dewberyz.css">
</head>
<body>
<section class="home" id="home">
<div class="circle"></div>
<header>
<a href="#"><img src="C:\Users\acer\Downloads\logo (1).jpg" class="logo"></a>
<ul>
<li><a href="dewberyz.html">Home</a></li>
<li><a href="q1.html">First Quarter</a></li>
<li><a href="q2.html">Second Quarter</a></li>
<li><a href="q3.html">Third Quarter</a></li>
<li><a href="q4.html">Fourth Quarter</a></li>
</ul>
</header>
<div class="content">
<div class="textBox">
<h2>Dewi Nuqui's<br>ICT <span>e-portfolio!</span></h2>
<p>Welcome to my e-portfolio, a curated collection showcasing my activities, outputs, and reflection. Here, you'll delve into my journey of growth and learning, highlighting key projects and experiences that illustrate my skills and insights during the first quarter of 9th grade. I hope this reflects my ultimate commitment to continuous improvement and personal development.</p>
<a href="#">Learn More</a>
</div>
<div class="imgBox">
<img src="C:\Users\acer\Downloads\sonnyangel.png" class="dewi">
</div>
</div>
<ul class="sonnyangel">
<li><img src="C:\Users\acer\Downloads\sonnyangel.jpg" onclick="imgSlider('C:\Users\acer\Downloads\sonnyangel.png')"></li>
<li><img src="C:\Users\acer\Downloads\sonnyangel1.jpg" onclick="imgSlider('C:\Users\acer\Downloads\sonnyangel1.png')"></li>
<li><img src="C:\Users\acer\Downloads\sonnyangel2.jpg" onclick="imgSlider('C:\Users\acer\Downloads\sonnyangel2.png')"></li>
</ul>
<ul class="sci">
<li><a href="#"><img src="C:\Users\acer\Downloads\facebook.png"></a></li>
<li><a href="#"><img src="C:\Users\acer\Downloads\twitter.png"></a></li>
<li><a href="#"><img src="C:\Users\acer\Downloads\instagram.png"></a></li>
</ul>
</section>
<script type="text/javascript">
function imgSlider(anything){
document.querySelector('.dewi').src=anything;
}
</script>

<section class="about" id="about">
<div class="content1">
<div class="textBox1">
<h2>Get to Know<br><span>Dewi Nuqui!</span></h2>
<p>Hello! My name is Princess Dewi L. Nuqui, please call me Dewi. I’m 14 years old and my birthday is on July 26, 2010. I study at Las Pinas City National Science High School. I love dancing, listening to music, graphic designing, doing math, and eating.<br><br>
I am currently in 9 - Family, but I was once in 8 - Consideration and 7 - Blessedness. I was the class muse of 8 - Consideration ('23-'24). </p><br><br>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<div class="table">
<table style="width:50%" align="center">
  <tr>
    <td><img src="C:\Users\acer\Downloads\baby1.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby2.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby3.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby4.png" alt="baby" style="width:250px;height:250px;"></img></td>
    <td><img src="C:\Users\acer\Downloads\baby5.png" alt="baby" style="width:250px;height:250px;"></img></td>
  </tr>
</table>
</div>
</div>
</div>

</section>

<script>
let next = document.querySelector('.next')
let prev = document.querySelector('.prev')

next.addEventListener('click', function(){
let items = document.querySelectorAll('.item')
document.querySelector('.slide').appendChild(items[0])
})

prev.addEventListener('click', function(){
    let items = document.querySelectorAll('.item')
    document.querySelector('.slide').prepend(items[items.length - 1]) // here the length of items = 6
})
</script>
</section>
</body>
</html>
