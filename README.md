# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Top Navigation Bar -->
    <div class="top-bar">
        <input type="text" class="search-bar" placeholder="Search...">
        <a href="#" class="nav-item">Explore</a>
        <a href="#" class="nav-item">Hire a Designer</a>
        <a href="#" class="nav-item">Find Jobs</a>
        <a href="#" class="nav-item">Blog</a>
        <a href="#" class="nav-item blue-text">Sign up</a>
        <a href="#" class="nav-item blue-text">Log in</a>
    </div>

    <!-- Header Section -->
    <header>
        <div class="header-content">
            <h1>Discover the world’s top designers</h1>
            <p>Explore work from the most talented and accomplished designers ready to take on your next project</p>
            <input type="text" class="search-input" placeholder="What are you looking for?">
        </div>
    </header>

    <!-- Trending Searches Section -->
    <section class="trending">
        <h2>Trending Searches</h2>
        <div class="trending-tags">
            <span>landing page</span>
            <span>e-commerce</span>
            <span>mobile app</span>
            <span>logo design</span>
            <span>dashboard</span>
            <span>icons</span>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery">

        <div class="card">
            <img src="https://images.pexels.com/photos/2480395/pexels-photo-2480395.jpeg" alt="Design Sample">
            <h3>Dog</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/27680249/pexels-photo-27680249/free-photo-of-a-human-is-playing-tug-of-war-with-an-eager-white-golden-retriever-both-fully-engaged-in-the-fun-game.jpeg" alt="Design Sample">
            <h3>Angry Dog</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/20782645/pexels-photo-20782645/free-photo-of-white-cat-with-a-collar-on-a-street.jpeg" alt="Design Sample">
            <h3>Cat</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/28959769/pexels-photo-28959769/free-photo-of-adorable-white-maltese-dog-running-on-grass.jpeg" alt="Design Sample">
            <h3>White Dog</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/8907831/pexels-photo-8907831.jpeg" alt="Design Sample">
            <h3>Whale</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/17826913/pexels-photo-17826913/free-photo-of-close-up-of-a-speckled-wood-butterfly.jpeg" alt="Design Sample">
            <h3>Butterfly</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/4412930/pexels-photo-4412930.jpeg" alt="Design Sample">
            <h3>Swan</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/7265596/pexels-photo-7265596.jpeg" alt="Design Sample">
            <h3>squirrel</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/160722/cat-tiger-getiegert-feel-at-home-160722.jpeg" alt="Design Sample">
            <h3>Cat</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/357316/pexels-photo-357316.jpeg" alt="Design Sample">
            <h3>Bird</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/12764322/pexels-photo-12764322.png" alt="Design Sample">
            <h3>Grass Hopper</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://images.pexels.com/photos/12755675/pexels-photo-12755675.jpeg" alt="Design Sample">
            <h3>Deer</h3>
            <p>Emote Team | 7.2k Views</p>
        </div>
        <!-- Add more cards as needed -->
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Design Portfolio. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```
### styles.css
```
/* Reset and basic styles */
body, h1, h2, p, a, input, button {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f5f5f5;
    color: #333;
}

/* Top Bar Styling */
.top-bar {
    display: flex;
    align-items: center;
    background-color: #ffffff;
    padding: 10px 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.search-bar {
    margin-right: 15px;
    padding: 8px;
    border: 1px solid #ddd;
    border-radius: 4px;
    outline: none;
}

.nav-item {
    margin: 0 10px;
    color: #333;
    text-decoration: none;
}

.blue-text {
    color: #007bff;
    font-weight: bold;
}

.blue-text:hover {
    text-decoration: underline;
}

/* Header Section */
header {
    background-image: url('https://images.pexels.com/photos/1072179/pexels-photo-1072179.jpeg'); /* Add your header image */
    background-size: cover;
    padding: 80px 20px;
    text-align: center;
    color: #fff;
}

.header-content h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.header-content p {
    font-size: 18px;
    margin-bottom: 20px;
}

.search-input {
    padding: 10px;
    width: 60%;
    max-width: 500px;
    border: none;
    border-radius: 4px;
    outline: none;
}

/* Trending Searches Section */
.trending {
    padding: 20px;
    text-align: center;
}

.trending h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

.trending-tags {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.trending-tags span {
    background-color: #007bff;
    color: #fff;
    padding: 5px 10px;
    margin: 5px;
    border-radius: 4px;
    font-size: 14px;
}

/* Gallery Section */
.gallery {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
}

.card img {
    width: 100%;
    height: auto;
}

.card h3 {
    font-size: 16px;
    margin: 10px 0;
}

.card p {
    font-size: 12px;
    color: #555;
    margin-bottom: 10px;
}

/* Gallery Section */
.gallery {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
    position: relative;
}

.card img {
    width: 100%;
    height: auto;
    transition: transform 0.3s ease;
}

.card:hover img {
    transform: scale(1.2); /* Scale image to 120% on hover */
}

.card h3 {
    font-size: 16px;
    margin: 10px 0;
}

.card p {
    font-size: 12px;
    color: #555;
    margin-bottom: 10px;
}

/* Footer Section */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 20px;
    margin-top: 20px;
}
```
### script.js
```
// Search functionality
const searchBar = document.querySelector('.search-bar');

searchBar.addEventListener('keydown', function(event) {
    if (event.key === 'Enter') {
        event.preventDefault(); // Prevent default form submission
        alert(`Searching for: ${searchBar.value}`);
    }
});
```
## OUTPUT:

![Screenshot 2024-11-14 192031](https://github.com/user-attachments/assets/840ffaab-bae3-457f-9316-96e9d87ef902)

![Screenshot 2024-11-14 191957](https://github.com/user-attachments/assets/83e1b989-b225-4df9-b56f-d2863ef9577b)

![Screenshot 2024-11-14 192015](https://github.com/user-attachments/assets/4d544212-7c7e-4a77-b85a-8d94424c2a6b)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
