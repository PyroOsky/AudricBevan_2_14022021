<!DOCTYPE html>
<html>

  <!--HEAD-->

  <head>

    <meta charset="utf-8" />
    <link rel="stylesheet" href="css/style.css" />
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap" rel="stylesheet">
    <title>Reservia</title>
    <script
      src="https://kit.fontawesome.com/027b01606f.js"
      crossorigin="anonymous"
    ></script>

  </head>

  <!--BODY-->

  <body>

    <div class="main-wrap">

      <!--HEADER-->

      <header class="menu">

        <a href="index.html">
          <img
            class="logo"
            src="images/logo/Reservia@3x.png"
            alt="Reservia"
          />
        </a>

        <div></div>

        <nav class="header-nav">
          <a class="nav-button" href="#accomodations" active-link="true">Hébergements</a>
          <a class="nav-button" href="#activities" active-link="false">Activités</a>
        </nav>

        <a class="signup" href="#">S'inscrire</a>

      </header>

      <!--MAIN-->

      <main>

        <!--SEARCH-->

        <section class="search-accomodation">

          <h1 class="search-title">Trouvez votre hébergement pour des vacances de rêve</h1>
          <p class="search-subtitle">En plein centre ville ou en pleine nature</p>
  
          <form class="search-wrap">
              <i class="fas fa-map-marker-alt search-icon"></i>
            <input class="search-bar" type="search" placeholder="Marseille, France" size="1">
            <button class="search-button">
              <span class="search-button-text">Rechercher</span>
              <i class="fas fa-search search-button-icon"></i>
            </button>
          </form>

        </section>
  
        <!--FILTERS-->

        <section class="filters">
    
          <h2 class="filters-title">Filtres</h2>

          <div class="filter-button">
            <div class="filter-wrap-icon">
              <i class="fas fa-money-bill-wave filter-icon"></i>
            </div>
            <span class="filter-title">Économique</span>
          </div>

          <div class="filter-button">
            <div class="filter-wrap-icon">
              <i class="fas fa-child filter-icon"></i>
            </div>
            <span class="filter-title">Familial</span>
          </div>

          <div class="filter-button">
            <div class="filter-wrap-icon">
              <i class="fas fa-heart filter-icon"></i>
            </div>
            <span class="filter-title">Romantique</span>
          </div>

          <div class="filter-button">
            <div class="filter-wrap-icon">
              <i class="fas fa-dog filter-icon"></i>
            </div>
            <span class="filter-title">Animaux autorisés</span>
          </div>
    
          <div class="info">
            <div class="info-wrap-icon"><i class="fas fa-info info-icon"></i></div>
            <p class="info-text">Plus de 500 logements sont disponibles dans cette ville</p>
          </div>
        </section>

        <!--ACCOMODATIONS-->

        <section class="accomodations" id="accomodations">

          <div class="marseille-accomodations">

            
            <h2 class="marseille-accomodation-title">Hébergement à Marseille</h2>

            <article class="marseille-accomodation-article">
              <a href="#" class="marseille-accomodation-link">
                <img 
                  class="marseille-accomodation-image"
                  src="images/hebergements/3_medium/marcus-loke-WQJvWU_HZFo-unsplash.jpg"
                  alt="Cannebière Inn"
                >
                <div class="marseille-accomodation-content">
                  <h3 class="marseille-accomodation-article-title article-subtitle">Auberge la Cannebière</h3>
                  <p class="article-text">Nuit à partir de <strong class="marseille-accomodation-price">25€</strong></p>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starempty"></i>
                </div>
              </a>
            </article>

            <article class="marseille-accomodation-article">
              <a href="#" class="marseille-accomodation-link">
                <img 
                  class="marseille-accomodation-image"
                  src="images/hebergements/3_medium/fred-kleber-gTbaxaVLvsg-unsplash.jpg"
                  alt="Harbour Hostel."
                >
                <div class="marseille-accomodation-content">
                  <h3 class="marseille-accomodation-article-title article-subtitle">Hôtel du port</h3>
                  <p class="article-text">Nuit à partir de <strong class="marseille-accomodation-price">52€</strong></p>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                </div>
              </a>
            </article>

            <article class="marseille-accomodation-article">
              <a href="#" class="marseille-accomodation-link">
                <img 
                  class="marseille-accomodation-image"
                  src="images/hebergements/3_medium/reisetopia-B8WIgxA_PFU-unsplash.jpg"
                  alt="Seagull Hostel."
                >
                <div class="marseille-accomodation-content">
                  <h3 class="marseille-accomodation-article-title article-subtitle">Hôtel Les mouettes</h3>
                  <p class="article-text">Nuit à partir de <strong class="marseille-accomodation-price">76€</strong></p>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starempty"></i>
                </div>
              </a>
            </article>

            <article class="marseille-accomodation-article">
              <a href="#" class="marseille-accomodation-link">
                <img 
                  class="marseille-accomodation-image"
                  src="images/hebergements/3_medium/annie-spratt-Eg1qcIitAuA-unsplash.jpg"
                  alt="Sea Inn."
                >
                <div class="marseille-accomodation-content">
                  <h3 class="marseille-accomodation-article-title article-subtitle">Auberge de la mer</h3>
                  <p class="article-text">Nuit à partir de <strong class="marseille-accomodation-price">46€</strong></p>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starempty"></i>
                    <i class="fas fa-star starempty"></i>
                </div>
              </a>
            </article>

            <article class="marseille-accomodation-article">
              <a href="#" class="marseille-accomodation-link">
                <img 
                  class="marseille-accomodation-image"
                  src="images/hebergements/3_medium/nicate-lee-kT-ZyaiwBe0-unsplash.jpg"
                  alt="Basket Inn."
                >
                <div class="marseille-accomodation-content">
                  <h3 class="marseille-accomodation-article-title article-subtitle">Auberge Le Panier</h3>
                  <p class="article-text">Nuit à partir de <strong class="marseille-accomodation-price">23€</strong></p>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starempty"></i>
                </div>
              </a>
            </article>

            <article class="marseille-accomodation-article">
              <a href="#" class="marseille-accomodation-link">
                <img 
                  class="marseille-accomodation-image"
                  src="images/hebergements/3_medium/febrian-zakaria-M6S1WvfW68A-unsplash.jpg"
                  alt="Amina Hostel."
                >
                <div class="marseille-accomodation-content">
                  <h3 class="marseille-accomodation-article-title article-subtitle">Hôtel chez Amina</h3>
                  <p class="article-text">Nuit à partir de <strong class="marseille-accomodation-price">96€</strong></p>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                </div>
              </a>
            </article>

            <a href="#" class="viewmore">Afficher plus</a>
          </div>
    
          <aside class="popular-accomodations">

            <h2 class="popular-accomodation-title">Les plus populaires<i class="fas fa-chart-line"></i></h2>
            
            <article class="marseille-accomodation-article">
              <a href="#" class="popular-accomodation-wrap">
                <div class="popular-accomodation-image-wrap">
                  <img 
                    class="popular-accomodation-image"
                    src="images/hebergements/3_medium/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg"
                    alt="Morning Sun Hostel"
                  >
                </div>
                <div class="popular-accomodation-content">
                  <h3 class="popular-accomodation-content-margin article-subtitle">Hôtel Le soleil du matin</h3>
                  <p class="popular-accomodation-content-margin article-text">Nuit à partir de <strong class="marseille-accomodation-price">128€</strong></p>
                  <div class="blank-space"></div>
                  <div>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                  </div>
                </div>
              </a>
            </article>

            <article class="marseille-accomodation-article">
              <a href="#" class="popular-accomodation-wrap">
                <div class="popular-accomodation-image-wrap">
                  <img 
                    class="popular-accomodation-image"
                    src="images/hebergements/3_medium/aw-creative-VGs8z60yT2c-unsplash.jpg"
                    alt="Water Heart Inn"
                  >
                </div>
                <div class="popular-accomodation-content">
                  <h3 class="popular-accomodation-content-margin article-subtitle">Au coeur de l'eau Chambres d'hôtes</h3>
                  <p class="popular-accomodation-content-margin article-text">Nuit à partir de <strong class="marseille-accomodation-price">71€</strong></p>
                  <div class="blank-space"></div>
                  <div>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                  </div>
                </div>
              </a>
            </article>

            <article class="marseille-accomodation-article">
              <a href="#" class="popular-accomodation-wrap">
                <div class="popular-accomodation-image-wrap">
                  <img 
                    class="popular-accomodation-image"
                    src="images/hebergements/3_medium/febrian-zakaria-sjvU0THccQA-unsplash.jpg"
                    alt="All Blue And White Hostel"
                  >
                </div>
                <div class="popular-accomodation-content">
                  <h3 class="popular-accomodation-content-margin article-subtitle">Hôtel Tout bleu et Blanc</h3>
                  <p class="popular-accomodation-content-margin article-text">Nuit à partir de <strong class="marseille-accomodation-price">68€</strong></p>
                  <div class="blank-space"></div>
                  <div>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                    <i class="fas fa-star starfull"></i>
                  </div>
                </div>
              </a>
            </article>

          </aside>

        </section>

        <!--ACTIVITIES-->

        <section id="activities">

          <h2 class="activity-title">Activités à Marseille</h2>

          <a href="#" class="activity-card activity-card1">

            <div class="activity-card-wrap">
              <img 
                class="activity-card-wrap-image"
                src="images/activites/3_medium/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg"
                alt="Old Harbour" 
              >
            </div>

            <h3 class="activity-card-title">Vieux Port</h3>

          </a>

          <a href="#" class="activity-card activity-card2">

            <div class="activity-card-wrap">
              <img 
                class="activity-card-wrap-image"
                src="images/activites/3_medium/paul-hermann-QFTrLdQIRhI-unsplash.jpg"
                alt="Pomègue Fort" 
              >
            </div>

            <h3 class="activity-card-title">Fort de Pomègues</h3>

          </a>

          <a href="#" class="activity-card activity-card3">

            <div class="activity-card-wrap">
              <img 
                class="activity-card-wrap-image"
                src="images/activites/3_medium/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" 
                alt="Calanques National Park" 
              >
            </div>

            <h3 class="activity-card-title">Parc National des Calanques</h3>

          </a>

          <a href="#" class="activity-card activity-card4">

            <div class="activity-card-wrap">

              <img 
                class="activity-card-wrap-image"
                src="images/activites/3_medium/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg"
                alt="Notre-Dame-de-la-Garde" 
              >
            </div>

            <h3 class="activity-card-title">Notre-Dame-de-la-Garde</h3>

          </a>

          <a href="#" class="activity-card activity-card5">

            <div class="activity-card-wrap">
              <img 
                class="activity-card-wrap-image"
                src="images/activites/3_medium/florian-wehde-xW9e8gdotxI-unsplash.jpg"
                alt="Frioul Island" 
              >
            </div>

            <h3 class="activity-card-title">Île du Frioul</h3>

          </a>
          
          <a href="#" class="activity-card activity-card6">

            <div class="activity-card-wrap">
              <img 
                class="activity-card-wrap-image"
                src="images/activites/3_medium/lena-paulin-wH2-EJoDcV0-unsplash.jpg"
                alt="Longchamp Park" 
              >
            </div>

            <h3 class="activity-card-title">Parc Longchamp</h3>

          </a>

        </section>

      </main>

    </div>


    <!--FOOTER-->

    <footer class="footer-background">

      <div class="footer">

        <div class="about">

          <h2 class="footer-title">A propos</h2>

          <ul class="list-footer">
            <li><a class="link-footer" href="#">Fonctionnement du site</a></li>
            <li><a class="link-footer" href="#">Conditions générales de vente</a></li>
            <li><a class="link-footer" href="#">Données et confidentialité</a></li>
          </ul>

        </div>

        <div class="our-accommodations">

          <h2 class="footer-title">Nos hébergements</h2>

          <ul class="list-footer">
            <li><a class="link-footer" href="#">Charte qualité</a></li>
            <li><a class="link-footer" href="#">Soumettre votre hôtel</a></li>
          </ul>

        </div>

        <div class="assistance">

          <h2 class="footer-title">Assistance</h2>

          <ul class="list-footer">
            <li><a class="link-footer" href="#">Centre d'aide</a></li>
            <li><a class="link-footer" href="#">Nous contacter</a></li>
          </ul>

        </div>

      </div>

    </footer>
    
  </body>

</html>
