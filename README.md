<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Finding Frames — Film Production House</title>
  <meta name="description" content="Finding Frames — Production company creating bold, cinematic stories." />
  <link rel="stylesheet" href="assets/css/styles.css" />
  <link rel="icon" href="assets/images/favicon.png" />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="logo" href="/">Finding Frames</a>
      <nav class="site-nav" aria-label="Primary">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#team">Team</a>
        <a href="#contact">Contact</a>
      </nav>
      <a class="cta" href="#projects">Our Films</a>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-inner">
        <div class="hero-text">
          <h1>We craft cinematic stories that move audiences.</h1>
          <p>Production · Direction · Post-Production · Distribution</p>
          <p class="hero-actions">
            <a class="btn" href="#projects">View Films</a>
            <a class="btn btn-outline" href="#contact">Work With Us</a>
          </p>
        </div>
        <div class="hero-media">
          <img src="assets/images/hero-placeholder.jpg" alt="Cinematic still" />
        </div>
      </div>
    </section>

    <section class="about" id="about">
      <div class="container">
        <h2>About Us</h2>
        <p>Finding Frames is an independent film production house focused on original storytelling across short films, features, and branded content. With a core team of award-winning directors and producers, we handle everything from development through post-production and festival strategy.</p>
        <ul class="highlights">
          <li><strong>Founded:</strong> 2025</li>
          <li><strong>Services:</strong> Production, Development, Post, Distribution</li>
          <li><strong>Location:</strong> (City, Country)</li>
        </ul>
      </div>
    </section>

    <section class="projects" id="projects">
      <div class="container">
        <h2>Selected Projects</h2>
        <div class="grid projects-grid">
          <article class="project-card">
            <img src="assets/images/project1.jpg" alt="Project 1 still" />
            <div class="project-info">
              <h3>Project Title One</h3>
              <p>Short logline for the film — festival award winner and international screenings.</p>
              <p class="meta">Year · Short Film · Director Name</p>
            </div>
          </article>

          <article class="project-card">
            <img src="assets/images/project2.jpg" alt="Project 2 still" />
            <div class="project-info">
              <h3>Project Title Two</h3>
              <p>Feature in development exploring identity and memory.</p>
              <p class="meta">Year · Feature · Producer Name</p>
            </div>
          </article>

          <article class="project-card">
            <img src="assets/images/project3.jpg" alt="Project 3 still" />
            <div class="project-info">
              <h3>Commercial / Branded</h3>
              <p>High-production commercials and branded content for tech and lifestyle clients.</p>
              <p class="meta">Year · Agency / Client</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="team" id="team">
      <div class="container">
        <h2>Our Team</h2>
        <div class="grid team-grid">
          <div class="team-member">
            <img src="assets/images/person1.jpg" alt="Director Name" />
            <h4>Director Name</h4>
            <p>Director & Founder</p>
          </div>
          <div class="team-member">
            <img src="assets/images/person2.jpg" alt="Producer Name" />
            <h4>Producer Name</h4>
            <p>Producer</p>
          </div>
          <div class="team-member">
            <img src="assets/images/person3.jpg" alt="Editor Name" />
            <h4>Editor Name</h4>
            <p>Post-Production Lead</p>
          </div>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <div class="container">
        <h2>Contact</h2>
        <p>For inquiries, collaborations, or festival submissions please reach out:</p>
        <div class="contact-grid">
          <div>
            <h3>Email</h3>
            <p><a href="mailto:info@findingframes.example">info@findingframes.example</a></p>
            <h3>Address</h3>
            <p>Studio address (City, Country)</p>
          </div>
          <div>
            <h3>Work with us</h3>
            <form action="https://formspree.io/f/moqpnkdr" method="POST">
              <label>
                Name
                <input type="text" name="name" required />
              </label>
              <label>
                Email
                <input type="email" name="_replyto" required />
              </label>
              <label>
                Message
                <textarea name="message" rows="4" required></textarea>
              </label>
              <button class="btn" type="submit">Send Message</button>
            </form>
          </div>
        </div>

        <div class="social">
          <a href="#" aria-label="YouTube">YouTube</a>
          <a href="#" aria-label="Instagram">Instagram</a>
          <a href="#" aria-label="Vimeo">Vimeo</a>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; <span id="year"></span> Finding Frames — All rights reserved.</p>
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
