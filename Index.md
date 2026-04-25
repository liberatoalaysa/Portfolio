<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Rose Jane Villejos Portfolio</title>

<!-- Bootstrap -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
body {
    background: #f5f7fa;
}

/* Card style */
.card {
    border-radius: 20px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

/* Avatar */
.avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
}

/* Navigation */
.navbar {
    background: #6c63ff;
}

.navbar a {
    color: white !important;
}

/* Section spacing */
section {
    padding: 60px 0;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg">
<div class="container">
    <a class="navbar-brand text-white" href="#">My Portfolio</a>
</div>
</nav>

<!-- HOME -->
<section class="text-center">
<div class="container">
    <div class="card p-4">
        <img src="profile.jpg" class="avatar mx-auto mb-3">
        <h2>Rose Jane Villejos</h2>
        <p>🎂 21 years old | 🎉 Oct 28, 2004</p>
        <p>📍 Aurora, Pudtol, Apayao</p>
    </div>
</div>
</section>

<!-- ABOUT -->
<section>
<div class="container">
    <div class="card p-4">
        <h3>About Me</h3>
        <p>
        Hello! My name is Rose Jane Villejos, I'm from Aurora Pudtol Apayao.
        You can call me RJ. I am a student trying to navigate the academic grind,
        juggling lessons, projects, and life while hoping to survive finals.
        </p>

        <p>
        I may be a slow learner, but I am doing my best to keep learning and
        adapt to modern technology.
        </p>
    </div>
</div>
</section>

<!-- PROFILE QUOTES -->
<section>
<div class="container">
    <div class="card p-4">
        <h3>Profile</h3>
        <p>"As an IT student, it is hard to start from nothing, but it feels good to achieve things you've worked hard for."</p>
        <p>"Being an IT student is not just about computers, it's also about how you respect technology."</p>
        <p>"Behind 'I can't do it' is always 'Ah, I can do it pala' — I'm glad I didn't give up."</p>
    </div>
</div>
</section>

<!-- SKILLS -->
<section>
<div class="container">
    <div class="card p-4">
        <h3>Skills</h3>
        <ul>
            <li>🍳 Cooking</li>
            <li>🎤 Singing</li>
            <li>🏀 Playing Ballgames</li>
        </ul>
    </div>
</div>
</section>

<!-- EDUCATION -->
<section>
<div class="container">
    <div class="card p-4">
        <h3>Educational Background</h3>

        <p><strong>Elementary:</strong> Aurora Elementary School</p>
        <p><strong>High School:</strong> Tawit National High School</p>

    </div>
</div>
</section>

<!-- VISION -->
<section>
<div class="container">
    <div class="card p-4">
        <h3>Vision</h3>
        <p>
        We dream of Filipinos who passionately love their country and whose values and competencies
        enable them to realize their full potential and contribute meaningfully to building the nation.
        </p>

        <p>
        As a learner-centered public institution, the Department of Education continuously improves
        itself to better serve its stakeholders.
        </p>
    </div>
</div>
</section>

<!-- MISSION -->
<section>
<div class="container">
    <div class="card p-4">
        <h3>Mission</h3>
        <p>
        To protect and promote the right of every Filipino to quality, equitable, culture-based,
        and complete basic education where:
        </p>

        <ul>
            <li>Students learn in a safe and motivating environment</li>
            <li>Teachers nurture every learner</li>
            <li>Staff ensure effective learning systems</li>
            <li>Community supports lifelong learning</li>
        </ul>
    </div>

    <!-- BOTTOM NAVIGATION (APP STYLE) -->
<div class="bottom-nav">
    <button onclick="showPage('home')">HOME</button>
    <button onclick="showPage('about')"> ABOUT ME</button>
    <button onclick="showPage('calendar')">BIRT. CALENDAR</button>
    <button onclick="showPage('education')">SCHOOL</button>
    <button onclick="showPage('mission')">MISSION AND VISION</button>
</div>
</div>

<script>
function showPage(pageId) {
    let pages = document.querySelectorAll(".page");
    pages.forEach(p => p.classList.remove("active"));

    document.getElementById(pageId).classList.add("active");
}
</script>

</body>
</html>

</div>
</section>

<!-- FOOTER -->
<footer class="text-center p-3">
    <p>© 2026 Rose Jane Villejos</p>
</footer>

</body>
</html>
