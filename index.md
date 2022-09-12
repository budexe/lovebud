<html lang="en">
<head>
<meta charset="utf-8">
<title>index page</title>
<style>

ul {
list-style-type: none;
  margin: 0;
padding: 0;
}

body {
background-image: url(https://www.toptal.com/designers/subtlepatterns/uploads/blue-snow.png);
}
table, th, td {
  border: 1px solid;
}

table {
  width: 100%;
}
li {
  margin-bottom: 20px;
}
a {
  text-decoration: none;
  padding: 5px;
  border: 2px solid black;
  border-radius: 15px;
  background-color: white;
}
a:hover{
background: blue;
color: white;
}
a:active {
  background:red;
}


#shaq {
  text-decoration: none;
  padding: none;
  border: none;
  border-radius: none;
  background: transparent;
}

#shaq:hover{
background: transparent;
color: none;
}

#shaq:active {
  background:none;
}

#jerma {
  height: 150px;

}

* {box-sizing: border-box;}

body {
  margin: 0;
  font-family: serif;
}

.header {
  overflow: hidden;
  background-image: url("jermaheader.jpg");
  background-size: contain;
  padding: 1px 1px;
  display:flex;
  justify-content: space-between;
  width: 100vw;
}

.header a {
  float: left;
  color: black;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px;
  line-height: 25px;
  border-radius: 4px;
}

.header a.logo {
  font-size: 25px;
  font-weight: bold;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: dodgerblue;
  color: white;
}

/*
.header-right {
  float: right;
}*/

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
}

#wrap {
  height:200px;
  position: relative;
  margin-bottom: 100px;
  margin-top: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
}

#box1 {
  background: linear-gradient(to top, #005aa7, #fffde4);
  border: 3px solid black;
  border-radius: 10px;
  padding: 10px;
}

#box2 {
  background: linear-gradient(to bottom, #ed213a, #93291e);
  border: 3px solid black;
  border-radius: 10px;
  padding: 10px;
  flex-grow: 4;
}

#box3 {
background: linear-gradient(to right, #636363, #a2ab58);
  border: 3px solid black;
  border-radius: 10px;
}

.container {  display: grid;
  grid-template-columns: 2fr 4.8fr 2fr;
  grid-template-rows: 0.4fr 2.1fr;
  grid-auto-columns: 1fr;
  gap: 10px 10px;
  grid-auto-flow: row;
  grid-template-areas:
    "header header header"
    "side-left center side-right";
}

.side-left { grid-area: side-left; }

.center { grid-area: center; }

.side-right { grid-area: side-right; }

.header { grid-area: header; }


</style>
</head>

<body>

  <div class="container">
  <div class="side-left">
  <div id="box1">
  <h1>random stuff</h1>
    <li><a href="journal.html">stupid thoughts</a></li>

</div>

</div>
  </div><div id="box2">
  <h2>good songs i'm listening to currently</h2>

  </div>
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/4P5KoWXOxwuobLmHXLMobV?utm_source=generator&theme=0" width="100%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/1D3wLZMFsFnoPXlS93DBHp?utm_source=generator&theme=0" width="100%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/2ffMaevgvKOc9WmNlUwddk?utm_source=generator&theme=0" width="100%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
</div>


</body>
</html>
