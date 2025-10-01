<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Roblox Airlines</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900 font-sans">

  <!-- Header -->
  <header class="bg-blue-600 text-white p-6 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Roblox Airlines</h1>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="#about" class="hover:underline">Om oss</a></li>
          <li><a href="#routes" class="hover:underline">Destinasjoner</a></li>
          <li><a href="#contact" class="hover:underline">Kontakt</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-blue-500 text-white text-center py-20">
    <h2 class="text-4xl font-bold mb-4">Velkommen til Roblox Airlines</h2>
    <p class="text-lg mb-6">Opplev virtuelle flyreiser på Roblox med stil ✈️</p>
    <a href="https://www.roblox.com/groups/YOURGROUPID"
       class="bg-white text-blue-600 font-bold px-6 py-3 rounded-lg shadow hover:bg-gray-200">
       Bli med nå
    </a>
  </section>

  <!-- Om oss -->
  <section id="about" class="container mx-auto py-16 px-6">
    <h3 class="text-3xl font-bold mb-4">Om oss</h3>
    <p class="text-lg">Roblox Airlines er et fellesskap som bringer spillere sammen for realistiske og morsomme flyopplevelser. 
       Vi arrangerer flyvninger, events og bygger et unikt samfunn rundt luftfart i Roblox.</p>
  </section>

  <!-- Destinasjoner -->
  <section id="routes" class="bg-gray-200 py-16 px-6">
    <div class="container mx-auto">
      <h3 class="text-3xl font-bold mb-6">Våre destinasjoner</h3>
      <ul class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <li class="bg-white p-6 rounded-lg shadow text-center">🛫 Oslo</li>
        <li class="bg-white p-6 rounded-lg shadow text-center">🛫 London</li>
        <li class="bg-white p-6 rounded-lg shadow text-center">🛫 New York</li>
      </ul>
    </div>
  </section>

  <!-- Kontakt -->
  <section id="contact" class="container mx-auto py-16 px-6 text-center">
    <h3 class="text-3xl font-bold mb-4">Kontakt oss</h3>
    <p class="mb-4">Har du spørsmål? Ta kontakt via vår Discord eller Roblox-gruppe!</p>
    <a href="https://discord.gg/YOURDISCORDLINK" 
       class="bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700">
       Bli med på Discord
    </a>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-600 text-white text-center p-4 mt-10">
    <p>&copy; 2025 Roblox Airlines - Laget for fellesskapet</p>
  </footer>

</body>
</html>
