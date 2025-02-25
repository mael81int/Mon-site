# Mon-site
Termites et nuisibles 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="description" content="ITN - Entreprise spécialisée dans le traitement des termites, des charpentes bois, la lutte contre les nuisibles et le démoussage de toiture." />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ITN - Traitement termites et nuisibles</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- En-tête / Header -->
  <header>
    <div class="header-container">
      <div class="logo">
        <!-- Vous pouvez insérer votre logo en image -->
        <img src="votre-logo.png" alt="Logo ITN" />
        <!-- Ou simplement un texte stylisé -->
        <!-- <h1>ITN</h1> -->
      </div>
      <div class="header-info">
        <p class="slogan">Entreprise spécialisée dans le traitement des termites et des charpentes bois</p>
        <p class="phone">07 69 36 81 19</p>
      </div>
      <nav>
        <ul>
          <li><a href="index.html">Accueil</a></li>
          <li><a href="nuisibles.html">Nuisibles</a></li>
          <li><a href="demoussage.html">Démoussage toiture</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Section Hero / Bannière principale -->
  <section class="hero">
    <div class="hero-text">
      <h2>Traitement des Termites</h2>
      <p>Diagnostic gratuit – Intervention rapide</p>
      <a href="#contact" class="btn-hero">Demander un devis</a>
    </div>
  </section>

  <!-- Section Services -->
  <section class="services">
    <h2>Nos Services</h2>
    <div class="services-container">
      <!-- Service 1 : Traitement termites & charpentes -->
      <div class="service-box">
        <img src="images/termites.jpg" alt="Termites" />
        <h3>Traitement Termites & Charpentes</h3>
        <p>Spécialistes dans l’éradication des termites, vrillettes et capricornes, nous protégeons vos charpentes en bois et préservons la solidité de votre maison.</p>
        <a href="#contact" class="btn">En savoir plus</a>
      </div>

      <!-- Service 2 : Lutte contre les nuisibles -->
      <div class="service-box">
        <img src="images/nuisibles.jpg" alt="Nuisibles" />
        <h3>Nuisibles (rongeurs, blattes, pigeons...)</h3>
        <p>Nous intervenons pour éliminer rats, souris, blattes, puces de lit, pigeons et tout autre nuisible. Solutions efficaces et préventives.</p>
        <a href="nuisibles.html" class="btn">Découvrir</a>
      </div>

      <!-- Service 3 : Démoussage toiture + Hydrofuge -->
      <div class="service-box">
        <img src="images/demoussage.jpg" alt="Démoussage de toiture" />
        <h3>Démoussage toiture & Hydrofuge</h3>
        <p>Protégez et prolongez la durée de vie de votre toiture grâce à un nettoyage en profondeur et un traitement hydrofuge adapté.</p>
        <a href="demoussage.html" class="btn">Découvrir</a>
      </div>
    </div>
  </section>

  <!-- Section Zone d'intervention -->
  <section class="zone">
    <h2>Zone d’intervention</h2>
    <p>Nous intervenons principalement dans le Tarn (81) et les départements voisins. Contactez-nous pour toute question.</p>
    <!-- Exemple de carte ou visuel -->
    <img src="images/carte.png" alt="Zone d'intervention" class="carte" />
  </section>

  <!-- Section Contact -->
  <section class="contact" id="contact">
    <h2>Contact & Devis</h2>
    <p>Pour toute demande de renseignements ou de devis, n’hésitez pas à nous contacter.</p>
    <form action="#" method="post">
      <label for="name">Nom / Prénom</label>
      <input type="text" id="name" name="name" required />

      <label for="email">E-mail</label>
      <input type="email" id="email" name="email" required />

      <label for="phone">Téléphone</label>
      <input type="tel" id="phone" name="phone" />

      <label for="message">Votre demande</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit" class="btn-submit">Envoyer</button>
    </form>
  </section>

  <!-- Pied de page / Footer -->
  <footer>
    <div class="footer-container">
      <p>© 2025 ITN - Tous droits réservés</p>
      <p>07 69 36 81 19 - [Votre adresse] - [Votre email]</p>
    </div>
  </footer>

</body>
</html>
