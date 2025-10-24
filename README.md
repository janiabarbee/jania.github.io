# jania.github.io
<!DOCTYPE html>
<html>
<head>
<title>NeXTflix Gallery</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif; margin:0; background-color:#141414; color:#fff;}
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}
.movie-card {
    background-color: #1f1f1f;
    margin: 15px;
    border-radius: 10px;
    overflow: hidden;
    width: 200px;
    text-align: center;
    transition: transform 0.2s, box-shadow 0.2s;
    cursor: pointer;
}
.movie-card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 15px #e50914;
}
.movie-card img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}
.movie-info {
    padding: 10px;
}
.movie-info h2 {
    font-size: 1.2em;
    margin: 10px 0 5px;
}
.movie-info p {
    margin: 5px 0;
    color: #ccc;
}
.rating {
    color: #ffcc00;
    font-weight: bold;
}
@media (max-width: 600px) {
    .movie-card { width: 45%; margin: 10px; }
}
</style>
</head>
<body>

<header class="w3-container w3-center w3-padding-32 w3-black">
    <h1>NeXTflix Movie Gallery</h1>
</header>

<div class="container">
    <div class="movie-card">
        <img src="https://academymuseumstore.org/cdn/shop/files/40fcb32e-dcd3-4132-bdd8-f8e65a86a592.jpg?v=1754499174" alt="Ponyo Movie Cover">
        <div class="movie-info">
            <h2>Ponyo</h2>
            <p class="rating">Rating: ⭐⭐⭐⭐⭐ (5/5 stars)</p>
        </div>
    </div>

    <div class="movie-card">
        <img src="https://i.ebayimg.com/images/g/bRYAAOSw9WFhuibA/s-l1200.jpg" alt="Meet the Robinsons Movie Cover">
        <div class="movie-info">
            <h2>Meet the Robinsons</h2>
            <p class="rating">Rating: ⭐⭐⭐.5 (3.5/5 stars)</p>
        </div>
    </div>
    
    <div class="movie-card">
        <img src="https://halleonard-coverimages.s3.amazonaws.com/wl/00313290-wl.jpg" alt="The Incredibles Movie Cover">
        <div class="movie-info">
            <h2>The Incredibles</h2>
            <p class="rating">Rating: ⭐⭐⭐⭐ (4/5 stars)</p>
        </div>
    </div>

    <div class="movie-card">
        <img src="https://cdn.shopify.com/s/files/1/0310/7487/7577/products/00719ToyStory_Blackstone__Rounded_68fca521-8ef3-42ec-8250-fbaef4f85431.webp?v=1673447814" alt="Toy Story Movie Cover">
        <div class="movie-info">
            <h2>Toy Story</h2>
            <p class="rating">Rating: ⭐⭐⭐⭐ (4/5 stars)</p>
        </div>
    </div>

    <div class="movie-card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ9SJhm3ttGkylwZtBEqfKEAXbilLdI7Po0MfwuS2J_RWQZ3lfNKU-3h48kip02iGvvSXxq" alt="Coraline Movie Cover">
        <div class="movie-info">
            <h2>Coraline</h2>
            <p class="rating">Rating: ⭐⭐⭐⭐⭐ (5/5 stars)</p>
        </div>
    </div>

    <div class="movie-card">
        <img src="https://resizing.flixster.com/oUhtUz7GmvoykUVt69-1wKm6irc=/fit-in/705x460/v2/https://resizing.flixster.com/-XZAfHZM39UwaGJIFWKAE8fS0ak=/v3/t/assets/p159533_v_h8_se.jpg" alt="Monster House">
        <div class="movie-info">
            <h2>Monster House</h2>
            <p class="rating">Rating: ⭐⭐⭐⭐ (4/5 stars)</p>
        </div>
    </div>

    <div class="movie-card">
        <img src="https://upload.wikimedia.org/wikipedia/en/6/63/Monsters_Inc.JPG" alt="Monsters, Inc.">
        <div class="movie-info">
            <h2>Monsters, Inc.</h2>
            <p class="rating">Rating: ⭐⭐⭐⭐⭐ (5/5 stars)</p>
        </div>
    </div>
</div>

</body>
</html>
