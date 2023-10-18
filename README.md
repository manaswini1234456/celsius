# celsius
body {
    font-family: Arial, sans-serif;
    background-color: #111;
    color: #fff;
    margin: 0;
    padding: 0;
}

header {
    background-color: #111;
    padding: 20px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1000px;
    margin: 0 auto;
    padding: 0 20px;
}

nav img {
    max-height: 60px;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

.search {
    max-width: 300px;
    margin: 20px auto;
    padding: 0 20px;
}

.search input {
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 5px;
}

main {
    max-width: 1000px;
    margin: 20px auto;
    padding: 0 20px;
}

.hero {
    background-image: url('hero-background.jpg');
    background-size: cover;
    background-position: center;
    padding: 100px 0;
    text-align: center;
}

.hero-content {
    max-width: 600px;
    margin: 0 auto;
}

.hero h1 {
    font-size: 3rem;
}

.hero p {
    margin: 20px 0;
}

.hero button {
    padding: 15px 40px;
    background-color: #e50914;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.featured h2, .browse h2 {
    font-size: 2rem;
    margin: 20px 0;
}

footer {
    text-align: center;
    background-color: #111;
    padding: 10px 0;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <img src="netflix-logo.png" alt="Netflix Logo">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">TV Shows</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">New & Popular</a></li>
                <li><a href="#">My List</a></li>
            </ul>
        </nav>
        <div class="search">
            <input type="text" placeholder="Search">
        </div>
    </header>
    
    <main>
        <section class="hero">
            <div class="hero-content">
                <h1>Unlimited movies, TV shows, and more.</h1>
                <p>Watch anywhere. Cancel anytime.</p>
                <button>Get Started</button>
            </div>
        </section>
        
        <section class="featured">
            <h2>Popular on Netflix</h2>
            <!-- Add featured movie and TV show images here -->
        </section>
        
        <section class="browse">
            <h2>Browse by Genre</h2>
            <!-- Add genre categories and movie posters here -->
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 Netflix Clone</p>
    </footer>
</body>
</html>
