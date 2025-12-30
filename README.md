# Story-Forge
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="StoryForge AI: Transform your raw emotions and stories into polished masterpieces with AI. Share, publish, and monetize your unique narrative.">
    <meta name="keywords" content="AI storytelling, express emotions, monetize stories, voice to text AI">
    <title>StoryForge AI - Unlock Your Story</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Roboto', sans-serif; line-height: 1.6; color: #333; background: #f9f9f9; }
        header { position: fixed; top: 0; width: 100%; background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); z-index: 100; }
        nav { display: flex; justify-content: space-between; align-items: center; padding: 1rem 2rem; }
        nav .logo { font-family: 'Playfair Display', serif; font-size: 1.5rem; color: #4a90e2; }
        nav ul { list-style: none; display: flex; }
        nav ul li { margin-left: 2rem; }
        nav ul li a { text-decoration: none; color: #333; transition: color 0.3s; }
        nav ul li a:hover { color: #4a90e2; }
        .hero { background: linear-gradient(135deg, #4a90e2, #50e3c2); color: #fff; padding: 5rem 2rem; text-align: center; min-height: 100vh; display: flex; flex-direction: column; justify-content: center; }
        .hero h1 { font-family: 'Playfair Display', serif; font-size: 3rem; margin-bottom: 1rem; }
        .hero p { font-size: 1.2rem; margin-bottom: 2rem; }
        .hero .cta { display: inline-block; padding: 1rem 2rem; background: #fff; color: #4a90e2; text-decoration: none; border-radius: 5px; margin: 0 0.5rem; transition: background 0.3s; }
        .hero .cta:hover { background: #e0e0e0; }
        section { padding: 4rem 2rem; max-width: 1200px; margin: 0 auto; }
        section h2 { font-family: 'Playfair Display', serif; font-size: 2.5rem; margin-bottom: 2rem; text-align: center; color: #4a90e2; }
        .about, .how-it-works, .features, .pricing, .blog, .contact { background: #fff; margin-bottom: 2rem; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .steps { display: flex; justify-content: space-around; flex-wrap: wrap; }
        .step { text-align: center; width: 30%; margin-bottom: 2rem; }
        .step img { width: 100px; height: 100px; margin-bottom: 1rem; }
        .features-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; }
        .feature { text-align: center; padding: 2rem; border: 1px solid #ddd; border-radius: 10px; }
        .pricing-grid { display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; }
        .plan { background: #f9f9f9; padding: 2rem; border-radius: 10px; text-align: center; width: 250px; }
        .plan h3 { color: #4a90e2; }
        .demo { margin: 2rem 0; }
        .demo textarea { width: 100%; height: 100px; padding: 1rem; border: 1px solid #ddd; border-radius: 5px; }
        .demo button { margin-top: 1rem; padding: 1rem 2rem; background: #4a90e2; color: #fff; border: none; border-radius: 5px; cursor: pointer; }
        .demo button:hover { background: #357abd; }
        .blog-posts { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .post { background: #f9f9f9; padding: 2rem; border-radius: 10px; }
        .contact form { display: flex; flex-direction: column; gap: 1rem; }
        .contact input, .contact textarea { padding: 1rem; border: 1px solid #ddd; border-radius: 5px; }
        .contact button { padding: 1rem; background: #4a90e2; color: #fff; border: none; border-radius: 5px; cursor: pointer; }
        footer { background: #333; color: #fff; text-align: center; padding: 2rem; }
        @media (max-width: 768px) { nav ul { display: none; } .hero h1 { font-size: 2rem; } .steps { flex-direction: column; } }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">StoryForge AI</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#how-it-works">How It Works</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Unlock Your Story with AI</h1>
        <p>Turn raw emotions into masterpieces. Overcome barriers and share your unique narrative.</p>
        <a href="#demo" class="cta">Try It Free</a>
        <a href="#pricing" class="cta">Sign Up</a>
        <p>Helped 10,000+ stories reach the world.</p>
    </section>

    <section id="about" class="about">
        <h2>About StoryForge AI</h2>
        <p>StoryForge AI is a human-centric platform solving the overlooked challenge of expressing emotions and stories. Linguistic barriers, fear of judgment, and lack of skills hold back unique narratives. We transform raw text or voice into refined, elegant content—poems, stories, posts, and chapters—empowering you to share, publish, and monetize.</p>
    </section>

    <section id="how-it-works" class="how-it-works">
        <h2>How It Works</h2>
        <div class="steps">
            <div class="step">
                <img src="https://via.placeholder.com/100?text=Submit" alt="Submit Story">
                <h3>1. Submit Your Story</h3>
                <p>Input raw text or voice.</p>
            </div>
            <div class="step">
                <img src="https://via.placeholder.com/100?text=AI+Refines" alt="AI Refines">
                <h3>2. AI Transforms It</h3>
                <p>Emotionally preserved, grammatically refined.</p>
            </div>
            <div class="step">
                <img src="https://via.placeholder.com/100?text=Share" alt="Share">
                <h3>3. Share & Monetize</h3>
                <p>Choose formats and publish.</p>
            </div>
        </div>
    </section>

    <section id="features" class="features">
        <h2>Features</h2>
        <div class="features-grid">
            <div class="feature">
                <h3>Poems</h3>
                <p>Turn emotions into lyrical verses.</p>
            </div>
            <div class="feature">
                <h3>Short Stories</h3>
                <p>Craft compelling narratives.</p>
            </div>
            <div class="feature">
                <h3>Social Media Posts</h3>
                <p>Share bite-sized stories.</p>
            </div>
            <div class="feature">
                <h3>Book Chapters</h3>
                <p>Build full manuscripts.</p>
            </div>
        </div>
    </section>

    <section id="pricing" class="pricing">
        <h2>Pricing</h2>
        <div class="pricing-grid">
            <div class="plan">
                <h3>Free</h3>
                <p>$0/month</p>
                <p>Basic generations, limited exports.</p>
            </div>
            <div class="plan">
                <h3>Basic</h3>
                <p>$9/month</p>
                <p>Unlimited generations, social sharing.</p>
            </div>
            <div class="plan">
                <h3>Pro</h3>
                <p>$19/month</p>
                <p>All features, monetization tools.</p>
            </div>
        </div>
    </section>

    <section id="demo" class="demo">
        <h2>Try the Demo</h2>
        <textarea placeholder="Enter your raw story here..."></textarea>
        <button onclick="generateStory()">Generate Story</button>
        <div id="output"></div>
    </section>

    <section id="blog" class="blog">
        <h2>Blog & Resources</h2>
        <div class="blog-posts">
            <div class="post">
                <h3>Storytelling Tips</h3>
                <p>How to express emotions effectively.</p>
            </div>
            <div class="post">
                <h3>AI in Creativity</h3>
                <p>The future of personal narratives.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Name" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 StoryForge AI. Privacy | Terms | Social Media</p>
    </footer>

    <script>
        function generateStory() {
            const input = document.querySelector('.demo textarea').value;
            const output = document.getElementById('output');
            if (input) {
                output.innerHTML = <p><strong>Generated Poem:</strong><br>Roses are red,<br>Violets are blue,<br>Your story is unique,<br>And now it's polished too!</p>;
            } else {
                output.innerHTML = '<p>Please enter a story first.</p>';
            }
        }
        // Smooth scrolling for nav links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>
