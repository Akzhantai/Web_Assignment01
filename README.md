# Web_Assignment01
``html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Anime & Manhwa News</title>
  <link rel="stylesheet" href="style.css">
  <link rel="icon" type="" href="https://cdn-icons-png.flaticon.com/512/651/651590.png">
</head>
<body>
<header>
  <h1>Anime & Manhwa News Portal</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Anime</a></li>
      <li><a href="#">Manhwa</a></li>
      <li><a href="#">Reviews</a></li>
      <li><a href="#">About Us</a></li>
    </ul>
  </nav>
</header>

<main>
  <section class="news">
    <h2>Latest News</h2>
    <article>
      <img src="https://m.media-amazon.com/images/M/MV5BMzA0YmI0ZmQtMTk3Mi00N2I1LTlkMmItOWJiODFhZjQzOGI4XkEyXkFqcGdeQXVyMTA4NjE0NjEy._V1_.jpg" alt="Anime Image">
      <h3><a href="https://youtu.be/ufYEythBd3w?si=m7ZRiTC2QsFCnRVp">New Anime Series Announced</a></h3>
      <p>Exciting news! A new anime series has been announced for this season. Stay tuned for more details.</p>
    </article>
    <article>
      <img src="https://ecsmedia.pl/c/solo-leveling-volume-2-b-iext116604935.jpg" alt="Manhwa Image">
      <h3><a href="https://youtu.be/9vIxi5XkQ8Y?si=DpSfg7Vhv_qu7Uow">Manhwa Adaptation Coming Soon</a></h3>
      <p>Get ready for the upcoming manhwa adaptation that's set to premiere in a few months.</p>
    </article>
  </section>

  <section class="featured">
    <h2>Featured Articles</h2>
    <article>
      <img src="https://preview.redd.it/friends-tell-me-that-my-anime-taste-is-too-basic-how-bad-is-v0-789tk150vtbb1.jpg?width=640&crop=smart&auto=webp&s=b68c0cbef86a8dea589b0f00f968a718db646cba" alt="Anime Image">
      <h3><a href="https://youtu.be/-b65vvzap30?si=TRrhWltRFePu5NN5">Top 10 Must-Watch Anime of the Year</a></h3>
      <p>Check out our list of the top 10 anime series you shouldn't miss this year.</p>
    </article>
    <article>
      <img src="https://i.ebayimg.com/images/g/kqkAAOSwqvJiuxJw/s-l1200.jpg" alt="Manhwa Image">
      <h3><a href="https://sssclasshunter.com/">Manhwa Review: SSS-Class Suicide Hunter</a></h3>
      <p>We review the latest manhwa release and share our thoughts on the story and art.</p>
    </article>
  </section>
</main>

<footer>
  <p>&copy; 2023 Anime & Manhwa News Portal</p>
</footer>
</body>
</html>
``

``css

body {
  margin: 0;
  padding: 0;
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav li {
  display: inline;
  margin-right: 20px;
}

nav a {
  text-decoration: none;
  color: #fff;
}

main {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section {
  margin-bottom: 20px;
}

h2 {
  color: #333;
}

article h3 {
  color: #007acc;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #333;
  color: #fff;
}

``
