<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   My Personal Website
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
  </style>
 </head>
 <body class="bg-gray-100 text-gray-800">
  <header class="bg-white shadow-md py-4">
   <div class="container mx-auto flex justify-between items-center">
    <h1 class="text-3xl font-bold text-blue-500">
     My Life
    </h1>
    <nav>
     <ul class="flex space-x-4">
      <li>
       <a class="text-gray-700 hover:text-blue-500" href="#about">
        About
       </a>
      </li>
      <li>
       <a class="text-gray-700 hover:text-blue-500" href="#stories">
        Stories
       </a>
      </li>
      <li>
       <a class="text-gray-700 hover:text-blue-500" href="#gallery">
        Gallery
       </a>
      </li>
      <li>
       <a class="text-gray-700 hover:text-blue-500" href="#contact">
        Contact
       </a>
      </li>
     </ul>
    </nav>
   </div>
  </header>
  <section class="container mx-auto py-12" id="about">
   <h2 class="text-4xl font-bold text-center text-blue-500 mb-8">
    About Me
   </h2>
   <p class="text-center text-lg text-gray-700 max-w-2xl mx-auto">
    Hello! I'm [Your Name], a passionate individual who loves to share my life experiences and stories. Welcome to my personal website where you can learn more about me and see some of my favorite moments captured in photos.
   </p>
  </section>
  <section class="bg-white py-12" id="stories">
   <div class="container mx-auto">
    <h2 class="text-4xl font-bold text-center text-blue-500 mb-8">
     My Stories
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
     <div class="bg-gray-100 p-6 rounded-lg shadow-md">
      <h3 class="text-2xl font-bold mb-4">
       Story Title 1
      </h3>
      <p class="text-gray-700">
       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.
      </p>
     </div>
     <div class="bg-gray-100 p-6 rounded-lg shadow-md">
      <h3 class="text-2xl font-bold mb-4">
       Story Title 2
      </h3>
      <p class="text-gray-700">
       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.
      </p>
     </div>
     <div class="bg-gray-100 p-6 rounded-lg shadow-md">
      <h3 class="text-2xl font-bold mb-4">
       Story Title 3
      </h3>
      <p class="text-gray-700">
       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.
      </p>
     </div>
     <div class="bg-gray-100 p-6 rounded-lg shadow-md">
      <h3 class="text-2xl font-bold mb-4">
       Story Title 4
      </h3>
      <p class="text-gray-700">
       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.
      </p>
     </div>
    </div>
   </div>
  </section>
  <section class="container mx-auto py-12" id="gallery">
   <h2 class="text-4xl font-bold text-center text-blue-500 mb-8">
    Photo Gallery
   </h2>
   <div class="grid grid-cols-3 gap-4">
    <img alt="Photo 1" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 2" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 3" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 4" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 5" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 6" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 7" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 8" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 9" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 10" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 11" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
    <img alt="Photo 12" class="w-full h-full object-cover rounded-lg shadow-md" src="https://placehold.co/100x100"/>
   </div>
  </section>
  <section class="bg-white py-12" id="contact">
   <div class="container mx-auto">
    <h2 class="text-4xl font-bold text-center text-blue-500 mb-8">
     Contact Me
    </h2>
    <form class="max-w-lg mx-auto bg-gray-100 p-6 rounded-lg shadow-md">
     <div class="mb-4">
      <label class="block text-gray-700 font-bold mb-2" for="name">
       Name
      </label>
      <input class="w-full p-2 border border-gray-300 rounded-lg" id="name" placeholder="Your Name" type="text"/>
     </div>
     <div class="mb-4">
      <label class="block text-gray-700 font-bold mb-2" for="email">
       Email
      </label>
      <input class="w-full p-2 border border-gray-300 rounded-lg" id="email" placeholder="Your Email" type="email"/>
     </div>
     <div class="mb-4">
      <label class="block text-gray-700 font-bold mb-2" for="message">
       Message
      </label>
      <textarea class="w-full p-2 border border-gray-300 rounded-lg" id="message" placeholder="Your Message" rows="4"></textarea>
     </div>
     <button class="w-full bg-blue-500 text-white p-2 rounded-lg hover:bg-blue-600" type="submit">
      Send Message
     </button>
    </form>
   </div>
  </section>
  <footer class="bg-gray-800 text-white py-4">
   <div class="container mx-auto text-center">
    <p>
     © 2023 My Personal Website. All rights reserved.
    </p>
   </div>
  </footer>
 </body>
</html>
