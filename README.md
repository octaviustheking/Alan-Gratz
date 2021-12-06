<!DOCTYPE html>
<html lang="en">
<head>
<title>Alan Gratz - Birth</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other - menu*/
nav {
  float: left;
  width: 30%;
  height: 400px;
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0px;
}

/* Right text, like the article */
article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 400px;
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>
<header>
  <h2>Alan Gratz</h2>
</header>

<section>
  <nav>
  	<h3>Menu</h3>
    <nl>
      <li><a href="#">Birth</a></li>
      <li><a href="#">Family</a></li>
      <li><a href="#">Early Life</a></li>
      <li><a href="#">Struggles</a></li>
      <li><a href="#">Books</a></li>
      <li><a href="#">How He Became Famous</a></li>
      <li><a href="#">Impact</a></li>
      <li><a href="#">Jobs Before Being an Author</a></li>
      <li><a href="#">Hobbies</a></li>
      <li><a href="#">Quotes</a></li>
      <li><a href="#">Traits</a></li>
      <li><a href="#">Awards</a></li>
      <li><a href="#">Interesting Facts</a></li>
    </nl>
  </nav>
  
  <article>
    <h1>Birth</h1>
    <p>Alan Gratz was born on the 27th of January, 1972, in Knoxville, Tennessee. </p>
    <p>That's really all there is about his birth. </p>
  </article>
</section>

<footer>
  <p>This was created using HTML and CSS!</p>
</footer>

</body>
</html>
