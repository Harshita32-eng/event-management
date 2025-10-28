<html>
<head>
<title>event</title>
<link rel="stylesheet" href="object1.css">
</head>
<body>
<header>
<h1>Our college events</h1>
<nav>
<a href="#">Home</a>
<a href="#">Event</a>
<a href="#">Contact</a>
<a href="#">Register</a>
</nav>
</header>

<section class="zero">
<h2>Welcome to  our college fest!</h2>
<p>plz join us ,to different different activities and enjoy this events</p>
<button onlick="scrollTosection('event')">view event</button>
</section>

<section id="events">
<h2>Upcoming event</h2>
<div class="event-card">
<h3>Hachkthon 2025</h3>
<p>24-hours coding to showcase your skills</p>
<p><strong>date:</strong> 27 aug 2025</p>
</div>
<div class="event-card">
    <h3>DJ night</h3>
    <p>Show your talent in music,dance.</p>
    <p><strong>date:</strong> 28 aug 2025</p>
</div>
<div class="event-card">
    <h3>Fun game</h3>
    <p>like musical chair,paper dance,script,drama,comedy</p>
    <p><strong>date: </strong> 2 sep 2025</p>
</div>
</section>
<section id-="register">
  <marquee><h2>Register for event</h2></marquee>
    <form id="Registration form">
        <input type="text" placeholder="Enetr full name" required>
        <input type="text" placeholder="Enter email id" required>
           <select required>
            <option value="">select event</option>
            <option>Hachkthon</option>
            <option>DJ night</option>
            <option>Fun game</option>
        </select>
        <button type="submit">Register</button>
    </form>
</section>
    <section id="Contact">
        <h2>Contact us</h2>
        <p>Email: jvwu@gmail.com</p>
        <p>phone no. 8787654322</p>
    </section>
    <footer>
        <p>@ college event management / design by harshita kanwar</p>
    </footer>
    </body>
    </html>
