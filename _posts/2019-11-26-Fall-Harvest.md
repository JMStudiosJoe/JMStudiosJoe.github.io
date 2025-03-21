---
title: Fall Harvest
author: Joey
excerpt: A collection of the year's harvests

skills:
  - oil painting
categories:
  - works
  
background-image: FallHarvest/FallHarvestRedBubble.jpg

---
---
<script>
function myFunction(imgs) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = imgs.src;
  imgText.innerHTML = imgs.alt;
  expandImg.parentElement.style.display = "block";
}
</script>
<style>
  small{
    font-size: 10px;
  }
  /* The expanding image container */
.container {
  display: none;
  z-index: 10;
  margin-left: auto;
  margin-right: auto;
  position: fixed;
  top: 10%;
  left: 10%;
  width: 80vw;
  overflow-y: scroll;
  overflow-x: scroll;
  bottom: 3%;
}
/* Expanding image text */
#imgtext {
  position: absolute;
  bottom: 15px;
  left: 15px;
  color: white;
  font-size: 20px;
}
/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

## Fall Harvest
### 
Nov 26, 2019

<img class="imageDisplay" src="/images/FallHarvest/FallHarvestRedBubble.jpg" onclick="myFunction(this);">
 



