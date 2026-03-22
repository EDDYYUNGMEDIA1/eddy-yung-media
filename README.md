<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EDDY YUNG MEDIA</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0d0d0d;
    color: #ffffff;
}

header {
    text-align: center;
    padding: 50px 20px;
    background: #111;
}

header h1 {
    font-size: 32px;
    margin-bottom: 10px;
}

header p {
    color: #ccc;
}

section {
    padding: 40px 20px;
    text-align: center;
}

h2 {
    margin-bottom: 20px;
}

.services, .portfolio {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.card {
    background: #1a1a1a;
    padding: 20px;
    border-radius: 10px;
}

button {
    background: #00ff99;
    border: none;
    padding: 15px 25px;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
}

footer {
    text-align: center;
    padding: 20px;
    background: #111;
    color: #aaa;
}
</style>
</head>

<body>

<header>
    <h1>EDDY YUNG MEDIA</h1>
    <p>Creative Media | Motivation | Branding | Content Creation</p>
</header>

<section>
    <h2>About Us</h2>
    <p>
        EDDY YUNG MEDIA is a results-driven creative brand focused on mindset,
        discipline, and powerful content creation. We help individuals and
        brands stand out with high-impact visuals and storytelling.
    </p>
</section>

<section>
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">Flyer Design</div>
        <div class="card">Video Reel Creation</div>
        <div class="card">Voice-over Scripts</div>
        <div class="card">Content Strategy</div>
    </div>
</section>

<section>
    <h2>Portfolio</h2>
    <div class="portfolio">
        <div class="card">Discipline Flyer</div>
        <div class="card">Motivation Reel</div>
        <div class="card">Success Script</div>
    </div>
</section>

<section>
    <h2>Work With Us</h2>
    <p>If you are serious about growing your brand, we are ready to work with you.</p>
    <button onclick="contact()">Contact Us</button>
</section>

<footer>
    <p>Powered by EDDY YUNG MEDIA</p>
</footer>

<script>
function contact() {
    alert("Contact us on WhatsApp: +2349056453769");
}
</script>

</body>
</html>
