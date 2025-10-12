<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>R.e.m Products</title>
  <style>
  article {
    background-color: #009bff;
    width: 100%;
    height: 100px;
    color: white;
    border-radius: 5px;
    border: 1px gray;
    margin: 0px;
    text-align: center;
    display: flex;
    justify-content: center;   /* horizontal */
    align-items: center;       /* vertical */
   }
  .po {
  float: down;
  }
  * {
  box-sizing: border-box;
}
.img-container {
  float: left;
  width: 33.33%;
  padding: 5px;
}
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
  .h1 {
  text-align: center;
  }
    .topnav {
      background-color: #333;
      overflow: hidden;
    }
    .topnav a {
      float: left;
      color: #f2f2f2;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
      font-size: 17px;
    }
    .topnav a:hover {
      background-color: #ddd;
      color: black;
    }
    .topnav a.active {
      background-color: #04AA6D;
      color: white;
    }
  </style>
</head>
<body>
<nav><img src="https://static.vecteezy.com/system/resources/previews/043/765/969/original/tree-logo-design-illustration-vector.jpg" width="44" height="44"></nav>
  <div class="topnav">
    <a href="index.html">Mission</a>
    <a class="active" href="about.html">Products</a>
  </div>

  <div style="padding:20px">
    <h1 class="h1">Products</h1>
    <p class="h1">Note that our products are not sold here, and instead they are sold in Wranglers Park, P.C.R.</p>
  </div>
  <div class="clearfix">
  <div class="img-container">
  <img src="https://th.bing.com/th/id/OIP.h3JA7TunS1qA_Ky0yblFSAHaHa?w=162&h=180&c=7&r=0&o=7&dpr=1.4&pid=1.7&rm=3" alt="Italy" style="width:100%">
  <p class="po">Basalt. 1.50$</p>
  <img class="po" src="https://th.bing.com/th/id/OIP.YzAyLnstdX2O39eJWuCD-QHaEK?w=322&h=181&c=7&r=0&o=7&dpr=1.4&pid=1.7&rm=3" alt="Forest" style="width:100%">
  <p class="po">Adventurine. $18–$22/lb</p>
  </div>
  <div class="img-container">
  <img src="https://www.publicdomainpictures.net/pictures/100000/velka/tree-1408913303yNa.jpg" alt="Forest" style="width:100%">
  <p class="po">Herb medicicine for wounds.</p>
  <img src="https://www.publicdomainpictures.net/pictures/100000/velka/tree-1408913303yNa.jpg" alt="Forest" style="width:100%">
  <p class="po">Rare rocks pack. 10 rocks per each.</p>
  </div>
  <div class="img-container">
  <img src="https://www.publicdomainpictures.net/pictures/100000/velka/tree-1408913303yNa.jpg" alt="Mountains" style="width:100%">
  <p class="po">Homemade fertilizer.</p>
  <img src="https://www.publicdomainpictures.net/pictures/100000/velka/tree-1408913303yNa.jpg" alt="Mountains" style="width:100%">
  <p class="po">Volcanic rock pack. 10 rocks per each.</p>
  </div>
</div>
<div style="text-align: center;"><article>Earth first, you next.</article></div>
</body>
</html>
