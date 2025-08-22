# My_blog
The blogs is about current things happening in the world and the things necessary for the youths to know and gain valuable knowledge 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> HR Blog</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header -->
  <header>
    
    <nav class="navbar">
     <h1> HR Blog</h1> 
     <div class="nav-links">
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
      
      <button id="dark-toggle">🌙</button>
      </div>
    </nav>
  </header>

  <!-- Articles -->
  <main class="articles">
    <article>
      <img src="https://source.unsplash.com/600x400/?nature" alt="Article">
      <h2>10 Morning Habits That Will Change Your Entire Day </h2>
      <p>Discover 10 powerful morning habits that boost energy, productivity, and focus. Start your day right and transform your life with simple routines.</p>
      <a href="article1.html">Read More</a>
    </article>

    <article>
      <img src="https://source.unsplash.com/600x400/?technology" alt="Article">
      <h2>5 Simple Mindset Shifts to Become More Confident </h2>
      <p>Discover 5 powerful mindset shifts to build self-confidence. Learn how to overcome self-doubt, improve self-esteem, and become more confident in daily life.</p>
      <a href="article2.html">Read More</a>
    </article>

    <article>
      <img src="https://source.unsplash.com/600x400/?motivation" alt="Article">
      <h2>How to Use ChatGPT & AI Tools to Save Time Every Day</h2>
      <p>Discover how to use ChatGPT and AI tools to save time, boost productivity, and simplify daily tasks. Practical examples for students, professionals, and everyday life.</p>
      <a href="article3.html">Read More</a>
    </article>
  </main>

  <!-- Footer -->
  <footer>
    <p>© 2025 HR Blog. All rights reserved.</p>
    <div class="socials">
      <a href="#">🌐</a>
      <a href="#">📘</a>
      <a href="#">🐦</a>
      <a href="#">📸</a>
    </div>
  </footer>

  <script>
    // Dark Mode Toggle
    const toggleBtn = document.getElementById('dark-toggle');
    toggleBtn.addEventListener('click', () => {
      document.body.classList.toggle('dark');
      localStorage.setItem('dark-mode', document.body.classList.contains('dark'));
    });
    if(localStorage.getItem('dark-mode') === 'true') {
      document.body.classList.add('dark');
    }
  </script>
</body>
</html>
