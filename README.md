<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda de Celulares</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800">

  <!-- Header -->
  <header class="bg-blue-600 text-white p-4 shadow-lg">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">📱 Tu Nombre o Tienda</h1>
      <nav class="space-x-6">
        <a href="#catalogo" class="hover:underline">Catálogo</a>
        <a href="#contacto" class="hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-16 bg-white shadow-sm">
    <h2 class="text-4xl font-bold mb-4">Los mejores celulares al mejor precio</h2>
    <p class="text-lg text-gray-600 mb-8">Últimos modelos, garantía y atención personalizada.</p>
    <a href="#catalogo" class="bg-blue-600 text-white px-6 py-3 rounded-full hover:bg-blue-700">Ver Catálogo</a>
  </section>

  <!-- Catálogo -->
  <section id="catalogo" class="max-w-6xl mx-auto py-16 px-4">
    <h3 class="text-3xl font-bold mb-8 text-center">Catálogo de Celulares</h3>
    <div class="grid md:grid-cols-3 sm:grid-cols-2 grid-cols-1 gap-8">
      
      <!-- Producto 1 -->
      <div class="bg-white shadow-md rounded-lg overflow-hidden hover:shadow-xl transition">
        <img src="https://via.placeholder.com/400x300" alt="Celular 1" class="w-full h-48 object-cover">
        <div class="p-4">
          <h4 class="text-xl font-semibold mb-2">Nombre del Celular</h4>
          <p class="text-gray-600 mb-2">Descripción breve del producto.</p>
          <p class="font-bold text-blue-600 text-lg mb-4">$Precio</p>
          <a href="#" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver más</a>
        </div>
      </div>

      <!-- Copiá este bloque para más productos -->
      <div class="bg-white shadow-md rounded-lg overflow-hidden hover:shadow-xl transition">
        <img src="https://via.placeholder.com/400x300" alt="Celular 2" class="w-full h-48 object-cover">
        <div class="p-4">
          <h4 class="text-xl font-semibold mb-2">Nombre del Celular</h4>
          <p class="text-gray-600 mb-2">Descripción breve del producto.</p>
          <p class="font-bold text-blue-600 text-lg mb-4">$Precio</p>
          <a href="#" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver más</a>
        </div>
      </div>

      <div class="bg-white shadow-md rounded-lg overflow-hidden hover:shadow-xl transition">
        <img src="https://via.placeholder.com/400x300" alt="Celular 3" class="w-full h-48 object-cover">
        <div class="p-4">
          <h4 class="text-xl font-semibold mb-2">Nombre del Celular</h4>
          <p class="text-gray-600 mb-2">Descripción breve del producto.</p>
          <p class="font-bold text-blue-600 text-lg mb-4">$Precio</p>
          <a href="#" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver más</a>
        </div>
      </div>

    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="bg-blue-50 py-16">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Contacto</h3>
      <p class="text-gray-700 mb-4">¿Querés más información o hacer un pedido?</p>
      <a href="https://wa.me/xxxxxxxxxx" class="bg-green-500 text-white px-6 py-3 rounded-full hover:bg-green-600">📲 Escribinos por WhatsApp</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 text-center py-4">
    <p>© 2025 Tu Tienda de Celulares — Todos los derechos reservados.</p>
  </footer>

</body>
</html>
