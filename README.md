<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flawless Skincare | Simple, Radiant Results</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400&amp;family=Playfair+Display:ital,wght@0,400;0,600;1,400&amp;display=swap" rel="stylesheet">
  <style>
        /* --- Design Tokens --- */
        :root {
            --sage: #B2AC88;
            --linen: #F9F7F2;
            --charcoal: #333333;
            --white: #FFFFFF;
            --soft-gray: #E5E5E5;
            --transition: all 0.3s ease;
        }

        /* --- Global Styles --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
            color: var(--charcoal);
            background-color: var(--white);
            line-height: 1.6;
            -webkit-font-smoothing: antialiased;
        }

        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
            font-weight: 400;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        .btn {
            display: inline-block;
            background-color: var(--sage);
            color: var(--white);
            padding: 1.2rem 2.5rem;
            text-decoration: none;
            font-size: 0.9rem;
            letter-spacing: 1px;
            text-transform: uppercase;
            border-radius: 2px;
            transition: var(--transition);
            margin-top: 1.5rem;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            opacity: 0.9;
            transform: translateY(-2px);
        }

        /* --- Hero Section --- */
        .hero {
            background-color: var(--linen);
            padding: 10rem 0 8rem;
            text-align: center;
        }

        .hero h1 {
            font-size: clamp(2.5rem, 5vw, 3.5rem);
            margin-bottom: 1.5rem;
        }

        .hero p {
            max-width: 600px;
            margin: 0 auto;
            font-size: 1.1rem;
            color: #666;
        }

        /* --- Problem Section --- */
        .problem {
            padding: 8rem 0;
            text-align: center;
            background-color: var(--white);
        }

        .problem blockquote {
            font-family: 'Playfair Display', serif;
            font-size: 1.8rem;
            font-style: italic;
            max-width: 800px;
            margin: 0 auto 2rem;
            color: var(--sage);
        }

        .problem p {
            max-width: 700px;
            margin: 0 auto 1rem;
            color: #777;
        }

        /* --- Solution Section --- */
        .solution {
            padding: 6rem 0;
            background-color: var(--linen);
        }

        .split-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }

        .image-placeholder {
            background-color: var(--soft-gray);
            aspect-ratio: 4/5;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #999;
            font-style: italic;
        }

        .solution h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        /* --- Benefits Section --- */
        .benefits {
            padding: 8rem 0;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 3rem;
            margin-top: 4rem;
        }

        .benefit-card h3 {
            margin-bottom: 1rem;
            font-size: 1.3rem;
            border-bottom: 1px solid var(--linen);
            padding-bottom: 1rem;
        }

        .benefit-card p {
            color: #777;
            font-size: 0.95rem;
        }

        /* --- Testimonials Section --- */
        .testimonials {
            padding: 8rem 0;
            background-color: var(--linen);
        }

        .testimonials h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 4rem;
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 3rem;
        }

        .testimonial-card {
            background-color: var(--white);
            padding: 2.5rem;
            border-radius: 4px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
        }

        .testimonial-card p {
            color: #666;
            margin-bottom: 1.5rem;
            font-style: italic;
        }

        .testimonial-author {
            font-weight: 600;
            color: var(--charcoal);
            font-size: 0.9rem;
        }

        /* --- CTA Section --- */
        .cta {
            padding: 8rem 0;
            text-align: center;
            background-color: var(--white);
        }

        .cta h2 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
        }

        .cta p {
            max-width: 600px;
            margin: 0 auto 2rem;
            color: #777;
            font-size: 1.1rem;
        }

        /* --- Footer --- */
        footer {
            background-color: var(--charcoal);
            color: var(--white);
            padding: 3rem 0;
            text-align: center;
        }

        footer p {
            margin-bottom: 0.5rem;
            font-size: 0.9rem;
        }

        footer a {
            color: var(--sage);
            text-decoration: none;
            transition: var(--transition);
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* --- Responsive --- */
        @media (max-width: 768px) {
            .split-grid {
                grid-template-columns: 1fr;
                gap: 2rem;
            }

            .hero {
                padding: 6rem 0 4rem;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .solution h2 {
                font-size: 2rem;
            }

            .benefits-grid,
            .testimonials-grid {
                grid-template-columns: 1fr;
            }

            .container {
                padding: 0 1.5rem;
            }
        }
    </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="/_sdk/element_sdk.js" type="text/javascript"></script>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body><!-- Hero Section -->
  <section class="hero">
   <div class="container">
    <h1>Flawless Skincare</h1>
    <p>Simple, radiant results. Our curated collection of clean beauty essentials transforms your skin naturally.</p><button class="btn">Shop Now</button>
   </div>
  </section><!-- Problem Section -->
  <section class="problem">
   <div class="container">
    <blockquote>
     "Skincare shouldn't be complicated."
    </blockquote>
    <p>Most routines overwhelm with endless steps and conflicting ingredients. We stripped it back to what actually works—powerful botanicals, proven science, and nothing unnecessary.</p>
    <p>Your skin deserves simplicity without compromise.</p>
   </div>
  </section><!-- Solution Section -->
  <section class="solution">
   <div class="container">
    <div class="split-grid">
     <div class="image-placeholder">
      Product Image
     </div>
     <div>
      <h2>The Core Ritual</h2>
      <p>Three essential steps, carefully formulated to work together. Cleanse with intention, tone to balance, moisturize to protect. That's it.</p>
      <ul style="margin: 2rem 0; color: #666; line-height: 2;">
       <li>✓ Gentle plant-based actives</li>
       <li>✓ Hyaluronic acid &amp; botanical extracts</li>
       <li>✓ Dermatologist tested, cruelty-free</li>
       <li>✓ Works for all skin types</li>
      </ul><button class="btn">Discover More</button>
     </div>
    </div>
   </div>
  </section><!-- Benefits Section -->
  <section class="benefits">
   <div class="container">
    <h2 style="text-align: center; font-size: 2.5rem; margin-bottom: 1rem;">Why Flawless?</h2>
    <p style="text-align: center; color: #777; max-width: 700px; margin: 0 auto 4rem;">Crafted for those who believe beauty should be uncomplicated and effective.</p>
    <div class="benefits-grid">
     <div class="benefit-card">
      <h3>Pure Ingredients</h3>
      <p>No sulfates, parabens, or synthetic fragrances. Just clean actives that your skin recognizes and loves.</p>
     </div>
     <div class="benefit-card">
      <h3>Visible Results</h3>
      <p>See improvements in clarity, texture, and radiance within two weeks. Real results from real formulations.</p>
     </div>
     <div class="benefit-card">
      <h3>Sustainable Beauty</h3>
      <p>Recyclable packaging, ethically sourced botanicals, and zero waste in our production process.</p>
     </div>
     <div class="benefit-card">
      <h3>Expert Backed</h3>
      <p>Developed with dermatologists and tested across diverse skin types. Science you can trust.</p>
     </div>
    </div>
   </div>
  </section><!-- Testimonials Section -->
  <section class="testimonials">
   <div class="container">
    <h2>What Our Customers Say</h2>
    <div class="testimonials-grid">
     <div class="testimonial-card">
      <p>"My skin has never felt clearer. I ditched my 10-step routine and switched to Flawless—best decision ever."</p>
      <div class="testimonial-author">
       — Sarah M.
      </div>
     </div>
     <div class="testimonial-card">
      <p>"Finally, a skincare brand that understands simplicity. No irritation, just results. Absolutely obsessed."</p>
      <div class="testimonial-author">
       — James K.
      </div>
     </div>
     <div class="testimonial-card">
      <p>"The texture of my skin has transformed. Less is more—Flawless proved it to me."</p>
      <div class="testimonial-author">
       — Emma R.
      </div>
     </div>
    </div>
   </div>
  </section><!-- CTA Section -->
  <section class="cta">
   <div class="container">
    <h2>Start Your Glow-Up Today</h2>
    <p>Join thousands discovering what truly flawless skin feels like. Get 15% off your first order with code RADIANT.</p><button class="btn">Shop the Collection</button>
   </div>
  </section><!-- Footer -->
  <footer>
   <div class="container">
    <p>© 2024 Flawless Skincare. All rights reserved.</p>
    <p><a href="#privacy">Privacy Policy</a> • <a href="#terms">Terms of Service</a> • <a href="#contact">Contact Us</a></p>
   </div>
  </footer>
  <script>
        // Handle button clicks
        document.querySelectorAll('.btn').forEach(button => {
            button.addEventListener('click', function(e) {
                e.preventDefault();
                window.scrollTo({ top: 0, behavior: 'smooth' });
            });
        });
    </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9c8e24e297f03da8',t:'MTc3MDI0OTgwMC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
