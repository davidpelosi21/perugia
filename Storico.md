---
layout: page
permalink: /Storico/
long_title: Tutti gli eventi di AISF Perugia
img: ARCH
description: Archivio degli eventi AISF Perugia per l'anno 2019/20
---
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

{
  box-sizing: border-box;
}

body {
  font-family: Arial;
  font-size: 13px;
}

.container {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
}

.container img {vertical-align: middle;}

.container .content {
  position: absolute;
  bottom: 0;
  background: rgb(0, 0, 0);
  background: rgb(0, 0, 0, 0.8);
  color: #f1f1f1;
  width: 100%;
  padding: 15px;
}

</style>



<center>

<center>
    <img src="/perugia/ImgSlideShow/Arc.png" alt="centered image" style="max-width:25%"
    height="auto" width="auto" class="responsive" >
</center>
<h6><b>Tutti gli eventi di AISF Perugia 2019/2020</b></h6><br>

<div class="w3-content w3-section" style="max-width:500px">

<div class="container mySlides" >
  <img src="/perugia/Slideshow/caffe5.png" alt="Notebook" style="width:100%;">
  <div class="content">
    <h6>Biofisica</h6>
    <p>Caffè Scientifico: 27 Novembre 2019<br>
    Biofisica: Nano-Sequenze di DNA<br>
    Prof. Paciaroni  & Dott.ssa Comez </p>
  </div>
</div>

<div class="container mySlides" >
  <img src="/perugia/Slideshow/caffe6.png" alt="Notebook" style="width:100%;">
  <div class="content">
    <h6>Fisica Medica</h6>
    <p>Caffè Scientifico:  7 Novembre 2019<br>
    Fisica Medica: Radiazioni Ionizzanti<br>
    Prof. Servoli </p>
  </div>
</div>

<div class="container mySlides" >
  <img src="/perugia/Slideshow/qft4.png" alt="Notebook" style="width:100%;">
  <div class="content">
    <h6>Nessuno mi troverà: Il Caso Majorana</h6>
    <p>
    Cineforum: 5 Dicemebre 2019<br>

    Prof. Scopetta</p>
  </div>
</div>

<div class="container mySlides" >
  <img src="/perugia/Slideshow/qft5.png" alt="Notebook" style="width:100%;">
  <div class="content">
    <h6>Amaldi: la scelta</h6>
    <p>Cineforum: 18 Dicemebre 2019 <br>
    Dott.ssa Pancheri</p>
  </div>
</div>




</div>





<script>
var myIndex = 0;
carousel();
function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 4000);
}
</script>
