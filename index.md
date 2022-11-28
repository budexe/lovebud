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
}

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
  <h1>welcome to my awful website</h1>
  here are some things you might be looking for<br>
  <br>
  <a href="journal.html">stupid journal</a>
  <br>
  <br>
anything else? sorry, you're out of luck -- try another website
  <h2>good songs i'm listening to currently</h2>
  <li> What Once Was - Her's 
<li> Big Bang Baby - Stone Temple Pilots </li> 
</body>
</html>
