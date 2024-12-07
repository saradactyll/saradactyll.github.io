<link rel="stylesheet" href="styles.css">
## 19 June 2024: Bull Pot

**People**: Sarah, Holly, Max, Nathan, Mobi

<div class="image-grid">
    <div>
        <img src="images/bull1.jpg" alt="Ogof Ffynnon Ddu">
        <p>Ogof Ffynnon Ddu</p>
    </div>
    <div>
        <img src="images/bull2.jpeg" alt="Swildon's Hole">
        <p>Swildon's Hole</p>
    </div>
    <div>
        <img src="images/bull3.jpeg" alt="Alum Pot">
        <p>Alum Pot</p>
    </div>
    <div>
        <img src="images/1733449617136.jpeg" alt="Dan yr Ogof">
        <p>Dan yr Ogof</p>
    </div>
    <div>
        <img src="images/1733449617158.jpeg" alt="Porth yr Ogof">
        <p>Porth yr Ogof</p>
    </div>
    <div>
        <img src="images/1733449617181.jpeg" alt="King Pot">
        <p>King Pot</p>
    </div>
</div>

<style>
body {
    font-family: Arial, sans-serif;
    color: #eee;
    background-color: #121212;
    margin: 0;
    padding: 0;
}

.image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
}

.image-grid img {
    width: 100%;
    height: 200px; /* Set a fixed height for uniformity */
    object-fit: cover; /* Ensures images fill the space without distortion */
    border-radius: 8px;
    border: 3px solid #444;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
    transition: transform 0.3s ease, border-color 0.3s ease;
}

.image-grid img:hover {
    transform: scale(1.05);
    border-color: #888;
}

.image-grid div {
    text-align: center;
}

.image-grid p {
    margin-top: 8px;
    font-size: 14px;
    color: #bbb;
}

/* Responsive Design */
@media (max-width: 768px) {
    .image-grid {
        grid-template-columns: 1fr 1fr;
    }
}

@media (max-width: 480px) {
    .image-grid {
        grid-template-columns: 1fr;
    }
}
</style>



