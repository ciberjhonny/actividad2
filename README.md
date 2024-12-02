<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>¡Bienvenido a macOS Sonoma!</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900 font-sans">
  <header class="bg-blue-600 text-white p-6 text-center">
    <h1 class="text-4xl font-bold">Bienvenido a macOS Sonoma</h1>
    <p class="mt-2 text-lg">Descubre las nuevas funcionalidades y mejoras para aprovechar al máximo tu Mac.</p>
  </header>

  <main class="container mx-auto p-6">
    <section id="introduccion" class="mb-12">
      <h2 class="text-3xl font-semibold mb-4">Instalación y Compatibilidad</h2>
      <p class="leading-relaxed">Antes de comenzar, asegúrate de que tu Mac sea compatible con macOS Sonoma. Los modelos compatibles incluyen:</p>
      <ul class="list-disc list-inside mt-4 mb-4">
        <li>MacBook Pro (2018 y posteriores)</li>
        <li>MacBook Air (2018 y posteriores)</li>
        <li>Mac mini (2018 y posteriores)</li>
        <li>iMac (2019 y posteriores)</li>
        <li>iMac Pro (2017)</li>
        <li>Mac Studio (2022 y posteriores)</li>
        <li>Mac Pro (2019 y posteriores)</li>
      </ul>
      <p class="leading-relaxed">Para instalar macOS Sonoma, sigue los pasos:</p>
      <ol class="list-decimal list-inside mt-4 mb-4">
        <li>Respalda tus datos con Time Machine o iCloud.</li>
        <li>Accede a "Configuración del Sistema" &gt; "General" &gt; "Actualización de Software".</li>
        <li>Selecciona "Actualizar ahora" y sigue las instrucciones.</li>
      </ol>
    </section>
    <section id="widgets" class="mb-12">
      <h2 class="text-3xl font-semibold mb-4">Personalización del Escritorio con Widgets</h2>
      <p class="leading-relaxed">macOS Sonoma permite colocar widgets interactivos directamente en el escritorio, facilitando el acceso a información y funciones clave.</p>
      <p class="leading-relaxed mt-4">Para agregar widgets al escritorio:</p>
      <ol class="list-decimal list-inside mt-4 mb-4">
        <li>Haz clic derecho en el escritorio y selecciona "Editar Widgets".</li>
        <li>Explora las opciones y arrastra el widget deseado al escritorio.</li>
      </ol>
      <p class="leading-relaxed">Los widgets se integran con el fondo de pantalla y permiten controlar funciones clave sin necesidad de abrir las aplicaciones correspondientes.</p>
    </section>

    <section id="modo_juego" class="mb-12">
      <h2 class="text-3xl font-semibold mb-4">Modo Juego</h2>
      <p class="leading-relaxed">Para los entusiastas de los videojuegos, macOS Sonoma introduce un Modo Juego que optimiza el rendimiento al priorizar recursos de la CPU y GPU durante las sesiones de juego. Esto mejora la experiencia, especialmente en términos de fluidez y latencia en dispositivos de audio y controladores inalámbricos.</p>
      <p class="leading-relaxed mt-4">El Modo Juego se activa automáticamente al iniciar un juego compatible, mejorando la frecuencia de cuadros y reduciendo la latencia de audio y controles.</p>
    </section>

    <section id="contacto" class="mb-12">
      <h2 class="text-3xl font-semibold mb-4">Contacto</h2>
      <p class="leading-relaxed">Para cualquier duda o consulta sobre macOS Sonoma, no dudes en contactarnos:</p>
      <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mt-6">
        <div class="mb-4">
          <label class="block text-gray-700 text-sm font-bold mb-2" for="nombre">
            Nombre
          </label>
          <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="nombre" type="text" placeholder="Tu nombre">
        </div>
        <div class="mb-4">
          <label class="block text-gray-700 text-sm font-bold mb-2" for="email">
            Correo electrónico
          </label>
          <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email" type="email" placeholder="tu@email.com">
        </div>
        <div class="mb-6">
          <label class="block text-gray-700 text-sm font-bold mb-2" for="mensaje">
            Mensaje
          </label>
          <textarea class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="mensaje" rows="4" placeholder="Escribe tu mensaje aquí..."></textarea>
        </div>
        <div class="flex items-center justify-between">
          <button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
            Enviar
          </button>
        </div>
      </form>
    </section>
  </main>

  <footer class="bg-gray-800 text-white text-center p-6 mt-12">
    <p>&copy; 2024 macOS Sonoma. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
