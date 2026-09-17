---
layout: page
title: people
permalink: /people/
nav: true
nav_order: 3
---

<div class="lab-people">

<h2>Principal Investigator</h2>

<div class="pi-profile">
  <div class="pi-photo">
    <img src="{{ '/assets/img/people/gonzalo.jpg' | relative_url }}" alt="Gonzalo E. Constante Flores">
  </div>

  <div class="pi-content">
    <h3>Gonzalo E. Constante Flores</h3>
    <p class="pi-title"><strong>Assistant Professor</strong><br>
    Department of Electrical, Computer &amp; Energy Engineering<br>
    University of Colorado Boulder</p>

    <div class="pi-links">
      <a href="mailto:gonzalo.constante@colorado.edu" aria-label="Email"><i class="fa-solid fa-envelope"></i> Email</a>
      <a href="https://scholar.google.com/citations?hl=en&amp;user=KFCcT3MAAAAJ" target="_blank" rel="noopener noreferrer"><i class="ai ai-google-scholar"></i> Scholar</a>
      <a href="https://orcid.org/0000-0002-9668-5889" target="_blank" rel="noopener noreferrer"><i class="ai ai-orcid"></i> ORCID</a>
      <a href="https://www.linkedin.com/in/gconstantef/" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
      <a href="{{ '/assets/pdf/gonzalo-constante-cv.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf"></i> CV</a>
      <a href="{{ '/assets/img/gonzalo-constante-headshot.jpg' | relative_url }}" target="_blank"><i class="fa-solid fa-camera"></i> Headshot</a>
    </div>

    <p>I am an Assistant Professor in the Department of Electrical, Computer, and Energy Engineering at the University of Colorado Boulder. Prior to joining CU Boulder, I was a Postdoctoral Scholar at Purdue University, working with <a href="https://canli1.github.io/" target="_blank" rel="noopener noreferrer">Can Li</a>, and a Visiting Researcher at the University of Waterloo, working with <a href="https://uwaterloo.ca/electrical-computer-engineering/profile/ccanizar" target="_blank" rel="noopener noreferrer">Claudio Cañizares</a>. I received my Ph.D. degree in Electrical and Computer Engineering from The Ohio State University, where I was advised by <a href="https://u.osu.edu/conejo.1/" target="_blank" rel="noopener noreferrer">Antonio J. Conejo</a>.</p>

    <p>My research focuses on the development of <strong>theory, algorithms, and models for large-scale decision-making under uncertainty</strong>, at the intersection of <strong>optimization and machine learning</strong>. While power and energy systems are a central application area of my work, I am broadly interested in developing theory and methods for infrastructure networks, and science and engineering problems.</p>

    <p>I am a recipient of the <strong>Fulbright Scholarship</strong> and <strong>The Ohio State University Presidential Fellowship</strong>, and was a finalist for the <strong>IEEE PES Outstanding Doctoral Dissertation Award</strong>. I am always happy to chat, so please feel free to reach out via email.</p>

    <p class="pi-address">
      <strong>Office:</strong> ECOT 347, Engineering Center<br>
      1111 Engineering Drive, Boulder, CO 80309
    </p>
  </div>
</div>

<h2>Postdoctoral Scholars</h2>

<div class="member member-with-photo">
    <img
      class="member-photo"
      src="{{ '/assets/img/people/julio-lopez.jpg' | relative_url }}"
      alt="Julio López"
    >
    <h3>Julio López</h3>
    <p>Postdoctoral Scholar · Electrical Engineering</p>
  </div>

<h2>Students</h2>

<div class="member-grid">

  <div class="member">
    <h3>André Quisaguano</h3>
    <p>Ph.D. Student</p>
  </div>

  <div class="member member-with-photo">
    <img
      class="member-photo"
      src="{{ '/assets/img/people/xinyi-su.jpg' | relative_url }}"
      alt="Xinyi Su"
    >
    <h3>Xinyi Su</h3>
    <p>B.S. Student · Computer Science</p>
  </div>

  <div class="member">
    <h3>Miles Reigel</h3>
    <p>B.S. Student · Electrical Engineering</p>
  </div>

  <div class="member">
    <h3>Pranav Vinoth</h3>
    <p>B.S. Student · Computer Engineering</p>
  </div>

  <div class="member">
    <h3>Alvin Nguyen</h3>
    <p>B.S. Student · Applied Mathematics</p>
  </div>

  <div class="member">
    <h3>Ellis Johnson</h3>
    <p>B.S. Student · Electrical Engineering</p>
  </div>

</div>

<h2>Join the Group</h2>

<p class="join-text">
We welcome students interested in optimization, machine learning, and their applications to energy systems and large-scale decision-making. Prospective students are encouraged to review our research and publications before reaching out.
</p>

</div>

<style>
/* Keep `title: people` for navigation, but hide the redundant page heading. */
.post-header {
  display: none;
}

.lab-people > h2 {
  margin-top: 2.4rem;
  margin-bottom: 1.2rem;
}

/* Principal Investigator */
.pi-profile {
  display: grid;
  grid-template-columns: 210px minmax(0, 1fr);
  gap: 2rem;
  align-items: start;
  margin-bottom: 2.5rem;
}

.pi-photo img {
  display: block;
  width: 210px;
  height: 210px;
  object-fit: cover;
  object-position: center;
  border-radius: 50%;
}

.pi-content h3 {
  margin-top: 0;
  margin-bottom: 0.3rem;
  font-size: 1.55rem;
}

.pi-title {
  margin-bottom: 0.75rem;
  line-height: 1.45;
}

.pi-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.9rem;
  margin: 0.7rem 0 1.15rem;
}

.pi-links a {
  text-decoration: none;
  white-space: nowrap;
}

.pi-links a:hover {
  text-decoration: underline;
}

.pi-links i {
  margin-right: 0.22rem;
}

.pi-content > p {
  max-width: 50rem;
}

.pi-address {
  margin-top: 1rem;
  font-size: 0.92rem;
  color: var(--global-text-color-light, #666);
  line-height: 1.5;
}

/* Group members */
.member-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  column-gap: 2rem;
  row-gap: 2rem;
  margin-bottom: 2rem;
}

.member-list {
  margin-bottom: 2rem;
}

.member {
  padding-bottom: 0.8rem;
  border-bottom: 1px solid rgba(128, 128, 128, 0.18);
}

.member h3 {
  margin: 0 0 0.2rem;
  font-size: 1.15rem;
}

.member p {
  margin: 0;
  color: var(--global-text-color-light, #666);
}

/* Members with profile photos */
.member-with-photo {
  text-align: center;
}

.member-photo {
  display: block;
  width: 180px;
  height: 180px;
  object-fit: cover;
  object-position: center;
  margin: 0 auto 0.8rem;
  border-radius: 50%;
}

.member-with-photo h3 {
  margin: 0 0 0.2rem;
}

.member-with-photo p {
  margin: 0;
}

.join-text {
  max-width: 50rem;
}

/* Tablet */
@media (max-width: 850px) {
  .member-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

/* Mobile */
@media (max-width: 700px) {
  .pi-profile {
    grid-template-columns: 1fr;
    gap: 1.2rem;
  }

  .pi-photo img {
    width: 180px;
    height: 180px;
  }

  .member-grid {
    grid-template-columns: 1fr;
  }
}
</style>