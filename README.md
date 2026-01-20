# My-live-site
Be casual
<!DOCTYPE html>
 <html lang="en">
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>ComicDev | My Comic Projects</title>
     <script src="https://cdn.tailwindcss.com"></script>
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
     <style>
         body { background-color: #0a0a0c; color: #e2e8f0; }
         .comic-card { transition: transform 0.3s ease, box-shadow 0.3s ease; }
         .comic-card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(99, 102, 241, 0.2); }
     </style>
 </head>
 <body class="min-h-screen">
     <!-- Header -->
     <header class="py-10 text-center border-b border-gray-800 bg-gray-900">
         <h1 class="text-4xl font-black text-indigo-500 uppercase tracking-widest">Comic<span class="text-white">Vault</span></h1>
         <p class="text-gray-400 mt-2">A collection of my digital comic platforms & repositories</p>
     </header>
     <!-- Project Grid -->
     <main class="max-w-6xl mx-auto p-8">
         <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
             
             <!-- Comic Project 1 -->
             <div class="comic-card bg-gray-800 rounded-xl overflow-hidden border border-gray-700">
                 <div class="h-48 bg-gradient-to-br from-indigo-600 to-purple-700 flex items-center justify-center">
                     <i class="fas fa-book-open text-6xl text-white opacity-50"></i>
                 </div>
                 <div class="p-6">
                     <h3 class="text-xl font-bold mb-2">Cyber-Punk Chronicles</h3>
                     <p class="text-gray-400 text-sm mb-6">An interactive web-comic built with React and Framer Motion for smooth transitions.</p>
                     <div class="flex flex-col gap-3">
                         <a href="https://your-live-link-1.com" target="_blank" class="flex items-center justify-center gap-2 bg-indigo-600 hover:bg-indigo-500 text-white py-2 rounded-lg font-semibold transition">
                             <i class="fas fa-external-link-alt"></i> Live Website
                         </a>
                         <a href="https://github.com/your-username/repo-1" target="_blank" class="flex items-center justify-center gap-2 bg-gray-700 hover:bg-gray-600 text-white py-2 rounded-lg font-semibold transition">
                             <i class="fab fa-github"></i> GitHub Repo
                         </a>
                     </div>
                 </div>
             </div>
             <!-- Comic Project 2 -->
             <div class="comic-card bg-gray-800 rounded-xl overflow-hidden border border-gray-700">
                 <div class="h-48 bg-gradient-to-br from-red-600 to-orange-700 flex items-center justify-center">
                     <i class="fas fa-mask text-6xl text-white opacity-50"></i>
                 </div>
                 <div class="p-6">
                     <h3 class="text-xl font-bold mb-2">Manga Reader Pro</h3>
                     <p class="text-gray-400 text-sm mb-6">A custom manga reading API integration with dark mode and offline support features.</p>
                     <div class="flex flex-col gap-3">
                         <a href="#" target="_blank" class="flex items-center justify-center gap-2 bg-indigo-600 hover:bg-indigo-500 text-white py-2 rounded-lg font-semibold transition">
                             <i class="fas fa-external-link-alt"></i> Live Website
                         </a>
                         <a href="#" target="_blank" class="flex items-center justify-center gap-2 bg-gray-700 hover:bg-gray-600 text-white py-2 rounded-lg font-semibold transition">
                             <i class="fab fa-github"></i> GitHub Repo
                         </a>
                     </div>
                 </div>
             </div>
             <!-- Comic Project 3 -->
             <div class="comic-card bg-gray-800 rounded-xl overflow-hidden border border-gray-700">
                 <div class="h-48 bg-gradient-to-br from-emerald-600 to-teal-700 flex items-center justify-center">
                     <i class="fas fa-paint-brush text-6xl text-white opacity-50"></i>
                 </div>
                 <div class="p-6">
                     <h3 class="text-xl font-bold mb-2">Illustrators Hub</h3>
                     <p class="text-gray-400 text-sm mb-6">A landing page for comic artists to showcase their portfolios and commission rates.</p>
                     <div class="flex flex-col gap-3">
                         <a href="#" target="_blank" class="flex items-center justify-center gap-2 bg-indigo-600 hover:bg-indigo-500 text-white py-2 rounded-lg font-semibold transition">
                             <i class="fas fa-external-link-alt"></i> Live Website
                         </a>
                         <a href="#" target="_blank" class="flex items-center justify-center gap-2 bg-gray-700 hover:bg-gray-600 text-white py-2 rounded-lg font-semibold transition">
                             <i class="fab fa-github"></i> GitHub Repo
                         </a>
                     </div>
                 </div>
             </div>
         </div>
     </main>
     <!-- Footer -->
     <footer class="text-center py-10 text-gray-500 text-sm">
         <p>© 2024 ComicDev Portfolio. Powered by Tailwind CSS.</p>
     </footer>
 </body>
 </html>
