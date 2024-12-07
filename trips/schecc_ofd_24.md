<link rel="stylesheet" href="styles.css">
## SCHECC Saturday 2024: OFD 2

**People**: Sarah, Vedant, Hette, Amber

<div class="image-grid">
    <div>
        <img src="images/hette and amber.jpg">
    </div>
    <div>
        <img src="images/judge.jpg">
    </div>
    <div>
        <img src="images/hette.jpg">
    </div>
    <div>
        <img src="images/moi.jpg">
    </div>
    <div>
        <img src="images/on hill.jpg">
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
