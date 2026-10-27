# Portfolio
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Personale | Graphic Design & Art Direction</title>
    <style>
        /* Reset e Stili Generali */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        }

        body {
            background-color: #0b0b0b;
            color: #ffffff;
            line-height: 1.6;
            padding: 0 2rem;
        }

        /* Header e Navbar */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 2.5rem 0;
            border-bottom: 1px solid #222;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        nav a {
            color: #888;
            text-decoration: none;
            margin-left: 2rem;
            transition: color 0.3s;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        nav a:hover {
            color: #fff;
        }

        /* Sezione Hero (Presentazione) */
        .hero {
            max-width: 1200px;
            margin: 5rem auto;
            padding: 0;
        }

        .hero h1 {
            font-size: 3.5rem;
            line-height: 1.2;
            font-weight: 700;
            margin-bottom: 1.5rem;
            max-width: 800px;
        }

        .hero p {
            font-size: 1.2rem;
            color: #888;
            max-width: 600px;
        }

        /* Griglia del Portfolio */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 2.5rem;
            max-width: 1200px;
            margin: 0 auto 5rem auto;
        }

        .portfolio-item {
            background: #121212;
            border: 1px solid #1c1c1c;
            border-radius: 4px;
            overflow: hidden;
            transition: transform 0.3s, border-color 0.3s;
        }

        .portfolio-item:hover {
            transform: translateY(-5px);
            border-color: #444;
        }

        .portfolio-item img {
            width: 100%;
            height: 450px;
            object-fit: cover;
            display: block;
            filter: grayscale(20%);
            transition: filter 0.3s;
        }

        .portfolio-item:hover img {
            filter: grayscale(0%);
        }

        .item-info {
            padding: 1.5rem;
        }

        .item-info h3 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            font-weight: 600;
        }

        .item-info p {
            color: #666;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Footer e Contatti */
        footer {
            max-width: 1200px;
            margin: 0 auto;
            padding: 4rem 0;
            border-top: 1px solid #222;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: #444;
            font-size: 0.9rem;
        }

        footer a {
            color: #888;
            text-decoration: none;
            font-weight: 600;
        }

        footer a:hover {
            color: #fff;
        }

        /* Responsive Mobile */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.2rem; }
            header { flex-direction: column; gap: 1.5rem; text-align: center; }
            nav a { margin: 0 1rem; }
            .portfolio-grid { grid-template-columns: 1fr; }
            .portfolio-item img { height: 350px; }
            footer { flex-direction: column; gap: 1.5rem; text-align: center; }
        }
    </style>
</head>
<body>

    <!-- Navigazione -->
    <header>
        <div class="logo">DEVID . STUDIO</div>
        <nav>
            <a href="#progetti">Progetti</a>
            <a href="#contatti">Contatti</a>
        </nav>
    </header>

    <!-- Presentazione -->
    <section class="hero">
        <h1>Graphic Design, Art Direction & Visual Exploration.</h1>
        <p>Progettazione visiva per eventi, identità di brand ed editoria con un'estetica tagliente e contemporanea.</p>
    </section>

    <!-- Griglia Lavori -->
    <main class="portfolio-grid" id="progetti">
        
        <!-- Progetto 1 -->
        <div class="portfolio-item">
            <!-- Sostituisci il nome del file con la tua immagine reale -->
            <img src="vibes-magazine.jpg" alt="Vibes Motoring Magazine">
            <div class="item-info">
                <h3>VIBES Magazine</h3>
                <p>Editorial Design & Cover Art</p>
            </div>
        </div>

        <!-- Progetto 2 -->
        <div class="portfolio-item">
            <img src="glamour-cover.jpg" alt="Glamour Magazine Concept">
            <div class="item-info">
                <h3>GLAMOUR Style</h3>
                <p>Fashion Poster & Typography</p>
            </div>
        </div>

        <!-- Progetto 3 -->
        <div class="portfolio-item">
            <img src="strawhay-techno.jpg" alt="Strawhay Techno Field">
            <div class="item-info">
                <h3>Strawhay Techno Field</h3>
                <p>Event Poster & Dark Artwork</p>
            </div>
        </div>

        <!-- Progetto 4 -->
        <div class="portfolio-item">
            <img src="devid-logo.jpg" alt="Devid Vinyl Logo">
            <div class="item-info">
                <h3>DEVid Vinyl</h3>
                <p>Logo Design & Identity</p>
            </div>
        </div>

        <!-- Progetto 5 -->
        <div class="portfolio-item">
            <img src="bivio-bar.jpg" alt="Bivio Bar Opening">
            <div class="item-info">
                <h3>Bivio Bar Event</h3>
                <p>Flyer Design & Fluid Art</p>
            </div>
        </div>

        <!-- Progetto 6 -->
        <div class="portfolio-item">
            <img src="techno-road.jpg" alt="Techno Road Flyer">
            <div class="item-info">
                <h3>Techno Road</h3>
                <p>Visual Flyer & Clubbing Culture</p>
            </div>
        </div>

    </main>

    <!-- Piè di pagina / Contatti -->
    <footer id="contatti">
        <div>© 2026 DEVID . STUDIO. Tutti i diritti riservati.</div>
        <div>Iniziamo un progetto: <a href="mailto:tuanome@email.com">Scrivimi via Email</a></div>
    </footer>

</body>
</html>
