
[index.html](https://github.com/user-attachments/files/34621237/index.html)

      

<!DOCTYPE html>
<html lang="en" data-theme="light">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aurelia Vance — Contemporary Visual Artist & Gallery</title>
  <meta name="description"
    content="Official portfolio and digital archive of contemporary artist Aurelia Vance. Exploring memory, form, texture, and human emotion through painting, sculpture, and mixed media.">
  <meta property="og:title" content="Aurelia Vance — Contemporary Visual Artist">
  <meta property="og:description"
    content="Contemporary art gallery, exhibition archive, and studio portal of Aurelia Vance.">
  <meta property="og:image"
    content="https://images.unsplash.com/photo-1579783902614-a3fb3927b675?auto=format&fit=crop&w=1200&q=80">

  <!-- Bootstrap 5 CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Favicon -->
  <link rel="icon" type="image/svg+xml" href="assets/images/favicon.svg">
  <link rel="alternate icon" href="assets/images/favicon.svg">
  <!-- Stylesheet -->
  <link rel="stylesheet" href="assets/css/style.css">
</head>

<body>

  <!-- MANDATORY NAVBAR -->
  <nav class="navbar navbar-editorial" id="mainNavbar">
    <div class="container-fluid px-lg-5">
      <!-- Brand Logo -->
      <a class="brand-logo" href="index.html" id="navBrandLogo">
        Aurelia Vance
      </a>

      <!-- Desktop Nav Menu -->
      <div class="d-none d-xl-flex align-items-center gap-4">
        <a class="nav-link-custom active" href="index.html" id="navHome">Home</a>
        <a class="nav-link-custom" href="about.html" id="navAbout">About</a>
        <a class="nav-link-custom" href="works.html">Works</a>
        <a class="nav-link-custom" href="collections.html" id="navCollections">Collections</a>
        <a class="nav-link-custom" href="exhibitions.html" id="navExhibitions">Exhibitions</a>
        <a class="nav-link-custom" href="journal.html" id="navJournal">Journal</a>
        <a class="nav-link-custom" href="contact.html" id="navContact">Contact</a>
      </div>

      <!-- Action Buttons -->
      <div class="d-flex align-items-center gap-3">
        <div class="d-none d-xl-flex align-items-center gap-3">
          <button class="btn-theme-toggle" aria-label="Toggle Light/Dark Theme">
            <i class="bi bi-moon-stars"></i>
          </button>
          <a class="btn-commission-nav" href="commission.html">Commission Me</a>
        </div>
        <button class="btn-mobile-toggle d-xl-none" type="button" data-bs-toggle="offcanvas" data-bs-target="#mobileNavDrawer" aria-controls="mobileNavDrawer" aria-label="Open Navigation Menu">
          <i class="bi bi-list"></i>
        </button>
      </div>
    </div>
  </nav>

  <!-- MOBILE NAVIGATION DRAWER -->
  <div class="offcanvas offcanvas-end offcanvas-editorial" tabindex="-1" id="mobileNavDrawer"
    aria-labelledby="mobileNavLabel">
    <div class="offcanvas-header">
      <h5 class="offcanvas-title brand-logo" id="mobileNavLabel">Aurelia Vance</h5>
      <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
    </div>
    <div class="offcanvas-body">
      <div class="mobile-nav-links">
        <a class="mobile-nav-link active" href="index.html">Home</a>
        <a class="mobile-nav-link" href="about.html">About</a>
        <a class="mobile-nav-link" href="works.html">Works</a>
        <a class="mobile-nav-link" href="collections.html">Collections</a>
        <a class="mobile-nav-link" href="exhibitions.html">Exhibitions</a>
        <a class="mobile-nav-link" href="journal.html">Journal</a>
        <a class="mobile-nav-link" href="contact.html">Contact</a>
      </div>

      <div class="mobile-nav-footer mt-auto pt-4 border-top">
        <div class="d-flex align-items-center justify-content-between mb-3">
          <span class="font-meta text-muted">Theme Mode</span>
          <button class="btn-theme-toggle" aria-label="Toggle Light/Dark Theme">
            <i class="bi bi-moon-stars"></i>
          </button>
        </div>
        <a class="btn-editorial btn-editorial-accent py-3 w-100 justify-content-center text-center mt-2" href="commission.html">
          Commission Me <i class="bi bi-arrow-right ms-2"></i>
        </a>
        <p class="small text-muted mt-3 mb-0 text-center">&copy; 2026 Aurelia Vance Studio</p>
      </div>
    </div>
  </div>

  <!-- HERO SECTION -->
  <section class="hero-section" id="heroSection">
    <div class="container-fluid px-lg-5">
      <div class="row align-items-center g-5">
        <div class="col-lg-7">
          <span class="section-tag font-meta">Contemporary Fine Art & Sculpture</span>
          <p class="hero-subtitle">"Exploring Memory, Form and Human Emotion."</p>
          <h1 class="hero-title">Art Beyond the Obvious.</h1>
          <p class="lead text-muted mb-4 pe-lg-5">
            Aurelia Vance creates evocative visual dialogues between raw materiality, organic geometry, and quiet
            solitude. Her practice bridges contemporary painting, dimensional sculpture, and tactile mixed media.
          </p>
          <div class="d-flex flex-wrap gap-3">
            <a href="works.html" class="btn-editorial" id="heroViewWorksBtn">
              Explore Works <i class="bi bi-arrow-right"></i>
            </a>
            <a href="commission.html" class="btn-editorial btn-editorial-accent" id="heroCommissionBtn">
              Commission Me
            </a>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="hero-image-wrapper">
            <img src="assets/images/hero/hero-artwork.jpg"
              onerror="this.src='https://images.unsplash.com/photo-1579783900882-c0d3dad7b119?auto=format&fit=crop&w=1000&q=85'"
              alt="Featured Masterpiece — Lapis & Gold Mineral Canvas" class="img-fluid" width="800" height="960"
              loading="eager">
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FEATURED WORKS SECTION -->
  <section class="py-5" id="featuredWorksSection">
    <div class="container-fluid px-lg-5">
      <div
        class="section-header d-flex flex-column flex-md-row justify-content-between align-items-md-end border-bottom pb-4">
        <div>
          <span class="section-tag font-meta">Curated Selection</span>
          <h2 class="section-title mb-0">Featured Artworks</h2>
        </div>
        <a href="works.html" class="btn-editorial btn-editorial-accent mt-3 mt-md-0">View All 24 Works</a>
      </div>

      <div class="row g-4">
        <!-- Artwork 1 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="artwork-card">
            <div class="artwork-img-container">
              <img src="https://images.unsplash.com/photo-1541701494587-cb58502866ab?auto=format&fit=crop&w=1200&q=80"
                onerror="this.src='assets/images/artworks/artwork-01.svg'" alt="Quiet Geometry" loading="lazy">
              <div class="artwork-overlay">
                <h3 class="artwork-overlay-title">Quiet Geometry</h3>
                <span class="artwork-overlay-meta">2025 • Oil & Pigment on Canvas • 160 × 200 cm</span>
                <a href="artwork-details.html?id=1"
                  class="btn-editorial btn-editorial-accent mt-3 py-2 px-3 align-self-start">View Details</a>
              </div>
            </div>
            <div class="artwork-info">
              <div>
                <h3 class="artwork-title-main">Quiet Geometry</h3>
                <span class="artwork-subtitle">Category: Paintings</span>
              </div>
              <span class="font-meta text-muted">2025</span>
            </div>
          </div>
        </div>

        <!-- Artwork 2 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="artwork-card">
            <div class="artwork-img-container">
              <img src="https://images.unsplash.com/photo-1549887534-1541e9326642?auto=format&fit=crop&w=800&q=80"
                onerror="this.src='assets/images/artworks/artwork-02.svg'" alt="Red Horizon" loading="lazy">
              <div class="artwork-overlay">
                <h3 class="artwork-overlay-title">Red Horizon</h3>
                <span class="artwork-overlay-meta">2024 • Acrylic & Mineral Sand • 120 × 150 cm</span>
                <a href="artwork-details.html?id=2"
                  class="btn-editorial btn-editorial-accent mt-3 py-2 px-3 align-self-start">View Details</a>
              </div>
            </div>
            <div class="artwork-info">
              <div>
                <h3 class="artwork-title-main">Red Horizon</h3>
                <span class="artwork-subtitle">Category: Paintings</span>
              </div>
              <span class="font-meta text-muted">2024</span>
            </div>
          </div>
        </div>

        <!-- Artwork 3 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="artwork-card">
            <div class="artwork-img-container">
              <img src="https://images.unsplash.com/photo-1561839561-b13bcfe95249?auto=format&fit=crop&w=800&q=80"
                onerror="this.src='assets/images/artworks/artwork-09.svg'" alt="Organic Structure" loading="lazy">
              <div class="artwork-overlay">
                <h3 class="artwork-overlay-title">Organic Structure</h3>
                <span class="artwork-overlay-meta">2025 • Carved Alabaster & Bronze • 45 × 30 × 30 cm</span>
                <a href="artwork-details.html?id=9"
                  class="btn-editorial btn-editorial-accent mt-3 py-2 px-3 align-self-start">View Details</a>
              </div>
            </div>
            <div class="artwork-info">
              <div>
                <h3 class="artwork-title-main">Organic Structure</h3>
                <span class="artwork-subtitle">Category: Sculptures</span>
              </div>
              <span class="font-meta text-muted">2025</span>
            </div>
          </div>
        </div>

        <!-- Artwork 4 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="artwork-card">
            <div class="artwork-img-container">
              <img src="https://images.unsplash.com/photo-1579783902614-a3fb3927b675?auto=format&fit=crop&w=800&q=80"
                onerror="this.src='assets/images/artworks/artwork-17.svg'" alt="Echoes" loading="lazy">
              <div class="artwork-overlay">
                <h3 class="artwork-overlay-title">Echoes</h3>
                <span class="artwork-overlay-meta">2024 • Mixed Media on Linen • 140 × 140 cm</span>
                <a href="artwork-details.html?id=17"
                  class="btn-editorial btn-editorial-accent mt-3 py-2 px-3 align-self-start">View Details</a>
              </div>
            </div>
            <div class="artwork-info">
              <div>
                <h3 class="artwork-title-main">Echoes</h3>
                <span class="artwork-subtitle">Category: Mixed Media</span>
              </div>
              <span class="font-meta text-muted">2024</span>
            </div>
          </div>
        </div>

        <!-- Artwork 5 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="artwork-card">
            <div class="artwork-img-container">
              <img src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?auto=format&fit=crop&w=800&q=80"
                onerror="this.src='assets/images/artworks/artwork-13.svg'" alt="Light / Shadow" loading="lazy">
              <div class="artwork-overlay">
                <h3 class="artwork-overlay-title">Light / Shadow</h3>
                <span class="artwork-overlay-meta">2025 • Archival Silver Gelatin Print • 100 × 125 cm</span>
                <a href="artwork-details.html?id=13"
                  class="btn-editorial btn-editorial-accent mt-3 py-2 px-3 align-self-start">View Details</a>
              </div>
            </div>
            <div class="artwork-info">
              <div>
                <h3 class="artwork-title-main">Light / Shadow</h3>
                <span class="artwork-subtitle">Category: Photography</span>
              </div>
              <span class="font-meta text-muted">2025</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ARTIST STATEMENT EDITORIAL SECTION -->
  <section class="py-5 bg-secondary position-relative" id="artistStatementSection">
    <div class="container-fluid px-lg-5 py-lg-5">
      <div class="row align-items-center g-5">
        <div class="col-lg-4 col-md-5">
          <div class="position-relative mx-auto" style="max-width: 350px;">
            <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=600&q=80"
              onerror="this.src='assets/images/artist/portrait.svg'" alt="Artist Aurelia Vance in Her Studio"
              class="img-fluid border shadow-sm rounded-1" style="max-height: 440px; object-fit: cover; width: 100%;" loading="lazy">
          </div>
        </div>
        <div class="col-lg-8 col-md-7">
          <span class="section-tag font-meta">Artist Philosophy & Practice</span>
          <h2 class="section-title mb-4">"My practice explores the relationship between memory, place and perception."
          </h2>
          <p class="lead text-muted mb-4">
            Through deliberate layering of raw earth pigments, graphite powder, carved alabaster, and salvaged
            architectural elements, my works search for silence amid contemporary acceleration. Each piece serves as a
            tactile vessel capturing transient light and structural tension.
          </p>
          <div class="row g-4 my-4 border-top border-bottom py-4">
            <div class="col-sm-4">
              <span class="font-meta text-muted d-block mb-1">Primary Mediums</span>
              <strong class="font-display h5 mb-0">Oil, Alabaster, Charcoal</strong>
            </div>
            <div class="col-sm-4">
              <span class="font-meta text-muted d-block mb-1">Studio Location</span>
              <strong class="font-display h5 mb-0">Venice & Zürich</strong>
            </div>
            <div class="col-sm-4">
              <span class="font-meta text-muted d-block mb-1">Active Series</span>
              <strong class="font-display h5 mb-0">6 Major Collections</strong>
            </div>
          </div>
          <a href="about.html" class="btn-editorial">Read Full Biography & Career Timeline</a>
        </div>
      </div>
    </div>
  </section>

  <!-- FEATURED COLLECTION -->
  <section class="py-5" id="featuredCollectionSection">
    <div class="container-fluid px-lg-5 py-lg-4">
      <div class="section-header">
        <span class="section-tag font-meta">Highlight Series</span>
        <h2 class="section-title">Collection: Material & Silence</h2>
      </div>

      <div class="collection-card">
        <div class="row g-0 align-items-center">
          <div class="col-lg-7">
            <div class="collection-cover">
              <img src="https://images.unsplash.com/photo-1579783902614-a3fb3927b675?auto=format&fit=crop&w=1200&q=80"
                onerror="this.src='assets/images/collections/collection-2.svg'"
                alt="Material & Silence Collection Cover" loading="lazy">
            </div>
          </div>
          <div class="col-lg-5">
            <div class="collection-body">
              <span class="collection-count font-meta">Series of 14 Artworks • 2024–2025</span>
              <h3 class="h1 font-display mb-3">Material & Silence</h3>
              <p class="text-muted mb-4">
                An investigation into acoustic density and structural minimalism. Utilizing organic linen, ground
                volcanic ash, and cold wax, this body of work examines how physical surfaces absorb and resonate light
                within quiet architectural spaces.
              </p>
              <a href="collection-details.html?id=2" class="btn-editorial btn-editorial-accent">Explore Full
                Collection</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- EXHIBITIONS PREVIEW -->
  <section class="py-5 bg-secondary" id="exhibitionsPreviewSection">
    <div class="container-fluid px-lg-5">
      <div class="section-header d-flex flex-column flex-md-row justify-content-between align-items-md-end">
        <div>
          <span class="section-tag font-meta">Public Shows & Archives</span>
          <h2 class="section-title mb-0">Exhibitions</h2>
        </div>
        <a href="exhibitions.html" class="btn-editorial mt-3 mt-md-0">View All Exhibitions</a>
      </div>

      <div class="exhibitions-list">
        <!-- Item 1 -->
        <div class="exhibition-item d-flex flex-column flex-md-row justify-content-between align-items-md-center">
          <div>
            <span class="exhibition-status upcoming">Upcoming Solo Exhibition</span>
            <h3 class="h3 font-display mb-1"><a href="exhibition-details.html?id=1">Echoes of Silence: Venice
                Pavilion</a></h3>
            <p class="text-muted mb-0">Galleria d'Arte Moderna • Venice, Italy</p>
          </div>
          <div class="text-md-end mt-3 mt-md-0">
            <span class="font-meta d-block text-primary">Nov 14 — Dec 28, 2026</span>
            <a href="exhibition-details.html?id=1" class="btn-editorial btn-editorial-accent py-2 px-3 mt-2">Exhibition
              Overview</a>
          </div>
        </div>

        <!-- Item 2 -->
        <div class="exhibition-item d-flex flex-column flex-md-row justify-content-between align-items-md-center">
          <div>
            <span class="exhibition-status current">Current Group Showcase</span>
            <h3 class="h3 font-display mb-1"><a href="exhibition-details.html?id=2">Form & Materiality in Contemporary
                Abstraction</a></h3>
            <p class="text-muted mb-0">Kunsthalle Zürich • Zürich, Switzerland</p>
          </div>
          <div class="text-md-end mt-3 mt-md-0">
            <span class="font-meta d-block text-primary">Aug 01 — Oct 15, 2026</span>
            <a href="exhibition-details.html?id=2" class="btn-editorial py-2 px-3 mt-2">Exhibition Overview</a>
          </div>
        </div>

        <!-- Item 3 -->
        <div class="exhibition-item d-flex flex-column flex-md-row justify-content-between align-items-md-center">
          <div>
            <span class="exhibition-status past">Past Retrospective</span>
            <h3 class="h3 font-display mb-1"><a href="exhibition-details.html?id=3">Monoliths & Memory: 2021–2025</a>
            </h3>
            <p class="text-muted mb-0">Palais de Galerie • Paris, France</p>
          </div>
          <div class="text-md-end mt-3 mt-md-0">
            <span class="font-meta d-block text-muted">Jan 10 — Mar 22, 2025</span>
            <a href="exhibition-details.html?id=3" class="btn-editorial py-2 px-3 mt-2">Exhibition Overview</a>
          </div>
        </div>
      </div>
    </div>
  </section>



  <!-- JOURNAL PREVIEW -->
  <section class="py-5 bg-secondary" id="journalPreviewSection">
    <div class="container-fluid px-lg-5">
      <div class="section-header d-flex flex-column flex-md-row justify-content-between align-items-md-end">
        <div>
          <span class="section-tag font-meta">Art Publication & Essays</span>
          <h2 class="section-title mb-0">Studio Journal</h2>
        </div>
        <a href="journal.html" class="btn-editorial mt-3 mt-md-0">Explore All Articles</a>
      </div>

      <div class="row g-4 justify-content-center">
        <!-- Article 1 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="journal-card">
            <div class="journal-img">
              <img src="https://images.unsplash.com/photo-1579783900882-c0d3dad7b119?auto=format&fit=crop&w=800&q=80"
                onerror="this.src='assets/images/journal/journal-1.svg'"
                alt="Inside the Studio: The Geometry of Pigment" loading="lazy">
            </div>
            <span class="font-meta text-warning mb-2 d-block">Studio Notes • 5 Min Read</span>
            <h3 class="h3 font-display mb-2"><a href="journal-details.html?id=1">Inside the Studio: The Geometry of
                Pigment</a></h3>
            <p class="text-muted small">Reflections on how natural earth minerals dictate canvas texture and light
              refraction.</p>
          </div>
        </div>

        <!-- Article 2 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="journal-card">
            <div class="journal-img">
              <img src="https://images.unsplash.com/photo-1541701494587-cb58502866ab?auto=format&fit=crop&w=800&q=80"
                onerror="this.src='assets/images/journal/journal-2.svg'"
                alt="Notes on Color: Working with Earth Minerals" loading="lazy">
            </div>
            <span class="font-meta text-warning mb-2 d-block">Process • 7 Min Read</span>
            <h3 class="h3 font-display mb-2"><a href="journal-details.html?id=2">Notes on Color: Working with Earth
                Minerals</a></h3>
            <p class="text-muted small">Understanding the historical longevity and tactile qualities of lapis, ochre,
              and soot pigments.</p>
          </div>
        </div>

        <!-- Article 3 -->
        <div class="col-lg-4 col-md-6 ">
          <div class="journal-card">
            <div class="journal-img">
              <img src="https://images.unsplash.com/photo-1579783928621-6a13d66a62d1?auto=format&fit=crop&w=800&q=80"
                onerror="this.src='assets/images/journal/journal-3.svg'" alt="From Sketch to Final Work" loading="lazy">
            </div>
            <span class="font-meta text-warning mb-2 d-block">Inspiration • 4 Min Read</span>
            <h3 class="h3 font-display mb-2"><a href="journal-details.html?id=3">From Sketch to Final Work: The
                Anatomy</a></h3>
            <p class="text-muted small">Tracing the progression from quick charcoal studies to 2-meter monumental
              canvases.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FINAL CTA SECTION -->
  <section class="py-5 text-center" id="finalCtaSection">
    <div class="container px-lg-5 py-lg-5">
      <span class="section-tag font-meta justify-content-center">Custom Artwork & Commissions</span>
      <h2 class="section-title display-3 mb-4">Interested in a collaboration or commission?</h2>
      <p class="lead text-muted max-w-600 mx-auto mb-5">
        Aurelia Vance accepts select private commissions, architectural installations, and museum collaborations each
        season.
      </p>
      <div class="d-flex flex-wrap justify-content-center gap-3">
        <a href="commission.html" class="btn-editorial btn-editorial-accent">Submit Commission Brief</a>
        <a href="contact.html" class="btn-editorial">General Studio Contact</a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer-editorial" id="mainFooter">
    <div class="container-fluid px-lg-5">
      <div class="row g-5">
        <!-- Col 1: Artist -->
        <div class="col-12 col-md-6 col-lg-4">
          <a class="brand-logo mb-3 d-inline-block" href="index.html">Aurelia Vance</a>
          <p class="text-muted small pe-lg-4">
            Contemporary painter, sculptor, and visual artist exploring form, texture, memory, and silence. Based in
            Venice and Z&uuml;rich.
          </p>
          <div class="d-flex gap-3 mt-4">
            <a href="https://instagram.com" target="_blank" rel="noopener" aria-label="Instagram"
              class="text-muted fs-5"><i class="bi bi-instagram"></i></a>
            <a href="https://pinterest.com" target="_blank" rel="noopener" aria-label="Pinterest"
              class="text-muted fs-5"><i class="bi bi-pinterest"></i></a>
            <a href="https://behance.net" target="_blank" rel="noopener" aria-label="Behance" class="text-muted fs-5"><i
                class="bi bi-behance"></i></a>
            <a href="https://linkedin.com" target="_blank" rel="noopener" aria-label="LinkedIn"
              class="text-muted fs-5"><i class="bi bi-linkedin"></i></a>
          </div>
        </div>

        <!-- Col 2: Explore -->
        <div class="col-12 col-md-6 col-lg-2">
          <h4 class="footer-title font-meta">Explore</h4>
          <ul class="footer-links">
            <li><a href="works.html">Works Gallery</a></li>
            <li><a href="collections.html">Collections</a></li>
            <li><a href="exhibitions.html">Exhibitions Archive</a></li>
            <li><a href="about.html">About the Artist</a></li>
          </ul>
        </div>

        <!-- Col 3: Information -->
        <div class="col-12 col-md-6 col-lg-3">
          <h4 class="footer-title font-meta">Information</h4>
          <ul class="footer-links">
            <li><a href="journal.html">Studio Journal</a></li>
            <li><a href="contact.html">General Contact</a></li>
            <li><a href="commission.html">Commission Request</a></li>
            <li><a href="coming-soon.html">Upcoming Launch</a></li>
          </ul>
        </div>

        <!-- Col 4: Connect / Newsletter -->
        <div class="col-12 col-md-6 col-lg-3">
          <h4 class="footer-title font-meta">Studio Newsletter</h4>
          <p class="small text-muted mb-3">Subscribe for private exhibition previews and new series releases.</p>
          <form class="footer-newsletter-form d-flex flex-column gap-2" id="footerNewsletterForm">
            <input type="email" class="form-control-editorial" placeholder="Your Email Address" required>
            <button type="submit" class="btn-editorial btn-editorial-accent py-2 mt-2">Subscribe</button>
          </form>
        </div>
      </div>

      <div class="footer-bottom d-flex flex-column flex-md-row justify-content-between align-items-center">
        <p class="mb-2 mb-md-0">&copy; 2026 Aurelia Vance Studio. All rights reserved.</p>
        <div class="d-flex gap-4">
          <a href="#" class="text-muted">Privacy Policy</a>
          <a href="#" class="text-muted">Terms of Exhibition</a>
          <a href="#" class="text-muted">Accessibility</a>
        </div>
      </div>
    </div>
  </footer>

  <!-- Back to top button -->
  <button class="btn-back-to-top" id="btnBackToTop" aria-label="Back to Top">
    <i class="bi bi-arrow-up"></i>
  </button>

  <!-- LIGHTBOX MODAL -->
  <div class="lightbox-modal" id="lightboxModal">
    <div class="lightbox-content">
      <button class="lightbox-close" aria-label="Close Lightbox">&times;</button>
      <img src="" alt="" class="lightbox-img" id="lightboxImg">
      <div class="lightbox-caption" id="lightboxCaption"></div>
    </div>
  </div>

  <!-- JS Scripts -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
  <script src="assets/js/main.js"></script>
</body>

</html>
