<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>AFRIKAYA | Restaurant Africain</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
  </style>
</head>
<body class="bg-yellow-50 text-gray-900">

  <!-- Header -->
  <header class="bg-yellow-600 text-white p-4 shadow-md">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <div class="flex items-center gap-4">
        <img src="https://s11.aconvert.com/convert/p3r68-cdx67/v3ehh-j3cfo.jpg" alt="Logo AFRIKAYA" class="h-12 w-auto">
        <h1 class="text-2xl font-bold">AFRIKAYA</h1>
      </div>
      <nav>
        <ul class="flex gap-6 text-lg">
          <li><a href="#accueil" class="hover:underline">Accueil</a></li>
          <li><a href="#menu" class="hover:underline">Menu</a></li>
          <li><a href="#apropos" class="hover:underline">À propos</a></li>
          <li><a href="#galerie" class="hover:underline">Galerie</a></li>
          <li><a href="#contact" class="hover:underline">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="accueil" class="bg-cover bg-center h-screen flex items-center justify-center" style="background-image: url('https://s11.aconvert.com/convert/p3r68-cdx67/87b4j-tjj8p.jpg');">
    <div class="bg-black bg-opacity-50 p-10 rounded-xl text-center">
      <h2 class="text-4xl text-white font-bold mb-4">Bienvenue chez AFRIKAYA</h2>
      <p class="text-white text-lg mb-6">Découvrez la richesse de la cuisine africaine avec un goût inoubliable</p>
      <a href="#menu" class="bg-yellow-400 hover:bg-yellow-500 text-black px-6 py-2 rounded-full font-semibold">Voir le Menu</a>
    </div>
  </section>

  <!-- Menu Section -->
  <section id="menu" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-10">Notre Menu</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <div>
          <h3 class="text-xl font-semibold mb-2">Efo Riro (Viande)</h3>
          <p>Viande, huile de palme, épinards, poisson fumé ou crevettes séchées.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Efo Riro (Poulet)</h3>
          <p>Poulet, huile de palme, épinards, poisson fumé ou crevettes séchées.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Suya Bœuf</h3>
          <p>Bœuf, poudre d’arachide, épices (yaji), oignons.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Jollof Rice</h3>
          <p>Riz, tomates, poivrons, oignons, épices.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Pastilla au poisson</h3>
          <p>Poisson, vermicelles, olives, citron confit, feuilles de brick.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Couscous Tfaya</h3>
          <p>Semoule, viande, oignons caramélisés, raisins secs, pois chiches, cannelle.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- À propos Section -->
  <section id="apropos" class="py-16 bg-yellow-100">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-6">À propos de nous</h2>
      <p class="text-lg">
        AFRIKAYA est un restaurant dédié à la célébration de la cuisine africaine authentique. Nous mélangeons traditions, saveurs et hospitalité pour vous offrir une expérience culinaire chaleureuse et inoubliable. Chaque plat raconte une histoire venue d’Afrique.
      </p>
    </div>
  </section>

  <!-- Galerie Section -->
  <section id="galerie" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-10">Galerie</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <img src="https://source.unsplash.com/400x300/?african,food" alt="plat africain" class="rounded-lg shadow hover:scale-105 transition-transform duration-300" />
        <img src="https://source.unsplash.com/400x300/?cuisine,africaine" alt="cuisine africaine" class="rounded-lg shadow hover:scale-105 transition-transform duration-300" />
        <img src="https://source.unsplash.com/400x300/?restaurant,african" alt="restaurant africain" class="rounded-lg shadow hover:scale-105 transition-transform duration-300" />
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-16 bg-yellow-100">
    <div class="max-w-xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-6">Contact & Réservation</h2>
      <form class="bg-white p-8 rounded-lg shadow space-y-6">
        <div>
          <label for="nom" class="block font-semibold mb-2">Nom</label>
          <input id="nom" name="nom" type="text" required
            class="w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-yellow-400" placeholder="Votre nom" />
        </div>
        <div>
          <label for="email" class="block font-semibold mb-2">Email</label>
          <input id="email" name="email" type="email" required
            class="w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-yellow-400" placeholder="Votre email" />
        </div>
        <div>
          <label for="message" class="block font-semibold mb-2">Message</label>
          <textarea id="message" name="message" rows="5" required
            class="w-full p-3 border border-gray-300 rounded-md resize-none focus:ring-2 focus:ring-yellow-400"
            placeholder="Votre message ou réservation..."></textarea>
        </div>
        <button type="submit"
          class="w-full bg-yellow-500 hover:bg-yellow-600 text-white font-bold py-3 rounded-md transition">Envoyer</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-yellow-600 text-white text-center p-4 mt-10">
    <p>&copy; 2025 AFRIKAYA. Tous droits réservés.</p>
  </footer>

</body>
</html>
