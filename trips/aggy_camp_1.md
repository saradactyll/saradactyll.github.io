<link rel="stylesheet" href="styles.css">
## 16/02-17/02: Agen Allwedd Camp

**People**: Alex, Benedict, Sarah
**Duration**: 23 hours

<div class="image-grid">
    <div>
        <img src="images/camp.jpeg">
    </div>
    <div>
        <img src="images/courtesan.jpeg">
    </div>
    <div>
        <img src="images/pretties.jpg">
    </div>
    <div>
        <img src="images/waterfall.jpeg">
    </div>
    <div>
        <img src="images/pretty2.jpeg">
    </div>
    <div>
        <img src="images/sleeping.jpg">
    </div>
    <div>
        <img src="images/water.jpg">
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

.image-grid img:hover {transform: scale(1.05);border-color: #888;}

.image-grid div {text-align: center;}

.image-grid p {margin-top: 8px;font-size: 14px;color: #bbb;}

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
