<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CITIVISER – Book Anything, Anywhere</title>
  <link rel="stylesheet" href="styles.css" />
  <script defer src="script.js"></script>
</head>
<body>

  <!-- HEADER -->
  <header class="navbar">
    <div class="logo">CITIVISER</div>
    <nav class="nav-links" id="nav-links">
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#explore">Explore</a>
      <a href="#vendors">Vendors</a>
      <a href="#booking">Book Now</a>
      <a href="#about">About</a>
      <a href="#team">Team</a>
      <a href="#testimonials">Reviews</a>
      <a href="#faq">FAQ</a>
      <a href="#blog">Blog</a>
      <a href="#footer">More</a>
    </nav>
    <div class="menu-icon" id="menu-icon">&#9776;</div>
  </header>

  <!-- HERO SECTION -->
  <section id="home" class="hero">
    <div class="hero-text">
      <h1>Welcome to CITIVISER</h1>
      <p>India’s Most Powerful Booking Platform</p>
      <a href="#services" class="btn-primary">Get Started</a>
    </div>
  </section>

  <!-- SERVICES -->
  <section id="services" class="section services">
    <h2>What Can You Book?</h2>
    <div class="grid services-grid">
      <div class="service-card">Hotels</div>
      <div class="service-card">Restaurants</div>
      <div class="service-card">Banquet Halls</div>
      <div class="service-card">Cars & Taxis</div>
      <div class="service-card">Event Tickets</div>
      <div class="service-card">Doctors & Clinics</div>
      <div class="service-card">Pet Services</div>
      <div class="service-card">Cinemas</div>
      <div class="service-card">Freelancers</div>
      <div class="service-card">Gyms & Studios</div>
      <div class="service-card">Repair Technicians</div>
      <div class="service-card">Tutors & Classes</div>
    </div>
  </section>

  <!-- EXPLORE FILTER -->
  <section id="explore" class="section explore">
    <h2>Explore Services</h2>
    <input type="text" id="searchBox" placeholder="Search anything...">
    <div class="filter-tags">
      <button>Popular</button>
      <button>Nearby</button>
      <button>Latest</button>
      <button>Top Rated</button>
      <button>Budget Friendly</button>
    </div>
    <div id="exploreResults" class="grid results-grid">
      <!-- Results populated by JS -->
    </div>
  </section>

  <!-- VENDOR CTA -->
  <section id="vendors" class="section vendor-cta">
    <h2>List Your Business on CITIVISER</h2>
    <p>Join thousands of vendors growing daily bookings with us.</p>
    <a href="#" class="btn-secondary">Become a Vendor</a>
  </section>

  <!-- BOOKING SECTION -->
  <section id="booking" class="section booking">
    <h2>Book in 3 Simple Steps</h2>
    <div class="steps">
      <div class="step">Choose a Service</div>
      <div class="step">Select Time/Date</div>
      <div class="step">Confirm & Pay</div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="section about">
    <h2>About CITIVISER</h2>
    <p>CITIVISER is built for the future of seamless booking. Whether it's a hall or haircut, we make discovery and reservations simple and smooth.</p>
    <p><strong>Founded by:</strong> Abhijeet Jain – Founder & Owner of CITIVISER</p>
  </section>

  <!-- TEAM -->
  <section id="team" class="section team">
    <h2>Meet Our Team</h2>
    <div class="grid team-grid">
      <div class="team-member">Abhijeet Jain<br><span>Founder & CEO</span></div>
      <div class="team-member">R&D Team<br><span>Future Builders</span></div>
      <div class="team-member">Design Squad<br><span>UI/UX Creators</span></div>
      <div class="team-member">Marketing<br><span>Growth Drivers</span></div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section id="testimonials" class="section testimonials">
    <h2>What Users Say</h2>
    <div class="carousel">
      <blockquote>“CITIVISER made my wedding booking effortless!”</blockquote>
      <blockquote>“Highly professional vendors and zero hidden fees.”</blockquote>
      <blockquote>“I use it to book everything from cabs to doctors!”</blockquote>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" class="section faq">
    <h2>Frequently Asked Questions</h2>
    <div class="faq-grid">
      <div><strong>How do I book?</strong><p>Just search, select, and confirm. It’s that easy.</p></div>
      <div><strong>Is it free to use?</strong><p>Absolutely! We only charge vendors.</p></div>
      <div><strong>How do I cancel?</strong><p>You can cancel anytime before confirmation.</p></div>
    </div>
  </section>

  <!-- BLOG -->
  <section id="blog" class="section blog">
    <h2>From Our Blog</h2>
    <div class="blog-preview">
      <div class="blog-post">10 Wedding Venues to Consider in 2025</div>
      <div class="blog-post">How to Save Money on Last Minute Bookings</div>
      <div class="blog-post">Vendor Spotlight: Top Taxi Services in Delhi</div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer id="footer" class="footer">
    <p>&copy; 2025 CITIVISER. All rights reserved.</p>
    <p>Built by Abhijeet Jain – Founder & Owner</p>
    <nav class="footer-nav">
      <a href="#">Privacy Policy</a>
      <a href="#">Terms & Conditions</a>
      <a href="#">Refund Policy</a>
    </nav>
  </footer>

</body>
</html>
/* Reset & Base */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background: #f9f9f9;
  color: #222;
  scroll-behavior: smooth;
}

a {
  text-decoration: none;
  color: inherit;
}

h1, h2, h3 {
  margin-bottom: 1rem;
  font-weight: 600;
}

/* Utility Classes */
.section {
  padding: 5rem 2rem;
  max-width: 1200px;
  margin: auto;
}

.grid {
  display: grid;
  gap: 2rem;
}

.btn-primary,
.btn-secondary {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  margin-top: 1rem;
  border-radius: 50px;
  font-weight: bold;
  transition: background 0.3s ease;
}

.btn-primary {
  background: #3b82f6;
  color: white;
}

.btn-primary:hover {
  background: #2563eb;
}

.btn-secondary {
  background: #10b981;
  color: white;
}

.btn-secondary:hover {
  background: #059669;
}

/* Navbar */
.navbar {
  background: white;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  position: sticky;
  top: 0;
  z-index: 1000;
  padding: 1rem 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.navbar .logo {
  font-size: 1.8rem;
  font-weight: 800;
  color: #111827;
}

.nav-links {
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  color: #374151;
  font-weight: 500;
  position: relative;
}

.nav-links a::after {
  content: '';
  display: block;
  height: 2px;
  background: #3b82f6;
  width: 0;
  transition: width 0.3s ease;
}

.nav-links a:hover::after {
  width: 100%;
}

/* Hero */
.hero {
  background: linear-gradient(to right, #4f46e5, #3b82f6);
  color: white;
  text-align: center;
  padding: 6rem 2rem;
}

.hero h1 {
  font-size: 3rem;
}

.hero p {
  font-size: 1.3rem;
  margin: 1rem 0;
}

/* Services Grid */
.services-grid {
  grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
}

.service-card {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.07);
  text-align: center;
  font-weight: 600;
  color: #111827;
  transition: transform 0.3s ease;
}

.service-card:hover {
  transform: translateY(-5px);
}

/* Explore */
.explore input[type="text"] {
  width: 100%;
  max-width: 600px;
  margin: 1rem auto;
  display: block;
  padding: 0.8rem;
  border: 2px solid #d1d5db;
  border-radius: 8px;
  font-size: 1rem;
}

.filter-tags {
  margin: 2rem 0;
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
}

.filter-tags button {
  padding: 0.5rem 1rem;
  background: #e0f2fe;
  border: none;
  border-radius: 20px;
  color: #0369a1;
  font-weight: 600;
  cursor: pointer;
}

.filter-tags button:hover {
  background: #bae6fd;
}

.results-grid {
  grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
}

/* Vendor CTA */
.vendor-cta {
  text-align: center;
  background: #ecfccb;
  border-radius: 12px;
}

/* Booking */
.steps {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
  margin-top: 2rem;
}

.step {
  background: #fef9c3;
  padding: 1.5rem;
  border-radius: 12px;
  font-weight: bold;
  color: #92400e;
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

/* About */
.about p {
  max-width: 800px;
  margin: auto;
  font-size: 1.1rem;
}

/* Team */
.team-grid {
  grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  text-align: center;
}

.team-member {
  background: white;
  padding: 1rem;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
}

/* Testimonials */
.testimonials blockquote {
  font-size: 1.2rem;
  font-style: italic;
  background: #f3f4f6;
  padding: 1.5rem;
  border-left: 5px solid #3b82f6;
  margin-bottom: 1rem;
}

/* FAQ */
.faq-grid {
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.5rem;
}

.faq-grid div {
  background: white;
  padding: 1.2rem;
  border-radius: 8px;
  box-shadow: 0 3px 6px rgba(0,0,0,0.05);
}

/* Blog */
.blog-preview {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-top: 2rem;
}

.blog-post {
  background: #e0e7ff;
  padding: 1.2rem;
  border-radius: 10px;
  font-weight: 600;
  color: #1e3a8a;
  transition: background 0.3s;
}

.blog-post:hover {
  background: #c7d2fe;
}

/* Footer */
.footer {
  text-align: center;
  padding: 3rem 2rem;
  background: #111827;
  color: #e5e7eb;
}

.footer-nav {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
  margin-top: 1rem;
  flex-wrap: wrap;
}

.footer-nav a {
  color: #93c5fd;
  font-size: 0.9rem;
}
// MENU TOGGLE FOR MOBILE
const menuIcon = document.getElementById('menu-icon');
const navLinks = document.getElementById('nav-links');

menuIcon.addEventListener('click', () => {
  navLinks.classList.toggle('active');
  menuIcon.classList.toggle('open');
});

// SMOOTH SCROLL FOR NAV LINKS
document.querySelectorAll('.nav-links a').forEach(link => {
  link.addEventListener('click', e => {
    e.preventDefault();
    const targetId = link.getAttribute('href').substring(1);
    const targetSection = document.getElementById(targetId);
    if(targetSection){
      window.scrollTo({
        top: targetSection.offsetTop - 70,
        behavior: 'smooth'
      });
      // Close menu on mobile after click
      if(navLinks.classList.contains('active')){
        navLinks.classList.remove('active');
        menuIcon.classList.remove('open');
      }
    }
  });
});

// EXPLORE SEARCH FUNCTIONALITY
const searchBox = document.getElementById('searchBox');
const exploreResults = document.getElementById('exploreResults');

const sampleServices = [
  {name: 'Hotel Royal Inn', category: 'Hotels', rating: 4.5},
  {name: 'Green Leaf Restaurant', category: 'Restaurants', rating: 4.7},
  {name: 'City Banquet Hall', category: 'Banquet Halls', rating: 4.3},
  {name: 'Quick Taxi Service', category: 'Cars & Taxis', rating: 4.0},
  {name: 'Medic Clinic', category: 'Doctors & Clinics', rating: 4.8},
  {name: 'Paws Pet Care', category: 'Pet Services', rating: 4.1},
  {name: 'Silver Screen Cinema', category: 'Cinemas', rating: 4.4},
  {name: 'FitLife Gym', category: 'Gyms & Studios', rating: 4.6},
  {name: 'TechFix Repair', category: 'Repair Technicians', rating: 4.2},
  {name: 'Bright Tutors', category: 'Tutors & Classes', rating: 4.9},
];

function renderExploreResults(filtered) {
  exploreResults.innerHTML = '';
  if(filtered.length === 0){
    exploreResults.innerHTML = '<p>No results found.</p>';
    return;
  }
  filtered.forEach(service => {
    const div = document.createElement('div');
    div.className = 'service-card';
    div.innerHTML = `<strong>${service.name}</strong><br><small>${service.category}</small><br>Rating: ${service.rating}`;
    exploreResults.appendChild(div);
  });
}

// Initial load all
renderExploreResults(sampleServices);

// Search filter
searchBox.addEventListener('input', e => {
  const query = e.target.value.toLowerCase();
  const filtered = sampleServices.filter(service => 
    service.name.toLowerCase().includes(query) || 
    service.category.toLowerCase().includes(query)
  );
  renderExploreResults(filtered);
});

// FILTER TAG BUTTONS
document.querySelectorAll('.filter-tags button').forEach(btn => {
  btn.addEventListener('click', () => {
    let filtered;
    switch(btn.textContent){
      case 'Popular':
        filtered = sampleServices.filter(s => s.rating >= 4.5);
        break;
      case 'Nearby':
        filtered = sampleServices.slice(0,5); // Just demo top 5
        break;
      case 'Latest':
        filtered = sampleServices.reverse();
        break;
      case 'Top Rated':
        filtered = sampleServices.sort((a,b) => b.rating - a.rating);
        break;
      case 'Budget Friendly':
        filtered = sampleServices; // No price data, so show all
        break;
      default:
        filtered = sampleServices;
    }
    renderExploreResults(filtered);
  });
});

// SIMPLE CAROUSEL FOR TESTIMONIALS
const testimonials = document.querySelectorAll('.testimonials blockquote');
let currentTestimonial = 0;

function showTestimonial(index){
  testimonials.forEach((t,i) => {
    t.style.display = i === index ? 'block' : 'none';
  });
}

showTestimonial(currentTestimonial);

setInterval(() => {
  currentTestimonial = (currentTestimonial + 1) % testimonials.length;
  showTestimonial(currentTestimonial);
}, 4000);

// LAZY ANIMATIONS ON SCROLL (fade-in)
const sections = document.querySelectorAll('section');

const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if(entry.isIntersecting){
      entry.target.classList.add('visible');
    }
  });
}, {threshold: 0.1});

sections.forEach(section => {
  section.classList.add('hidden');
  observer.observe(section);
});
