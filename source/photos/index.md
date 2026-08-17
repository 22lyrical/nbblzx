--- 
title: "photo wall" 
date: 2026-08-17 22:00:00 
type: photos 
--- 
 
<div class="gallery"> 
  <img src="/img/photo1.jpg" alt="photo1"> 
  <img src="/img/photo2.jpg" alt="photo2"> 
  <img src="/img/photo3.jpg" alt="photo3"> 
</div> 
 
<style> 
.gallery { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; } 
.gallery img { width: 100%; border-radius: 8px; transition: transform 0.3s; } 
.gallery img:hover { transform: scale(1.05); } 
</style> 
