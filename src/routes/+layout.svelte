

<div class="min-h-screen flex flex-col w-screen">
  <!-- Navbar -->
  <nav class="bg-blue-900 text-white p-4">
    <div class="container mx-auto flex justify-between items-center">
      <div class="flex items-center space-x-4">
  
        <a href="/" class="hover:underline">Home</a>
        <a href="/database" class="hover:underline">Database</a>
        <a href="/waterfalls" class="hover:underline">Waterfalls</a>
        <a href="/blog" class="hover:underline">Blog</a>
        <a href="/contacts" class="hover:underline">Contacts</a>
      </div>
      <div class="flex items-center space-x-2">
        <span>EN</span>
        <span>▼</span>
      </div>
    </div>
  </nav>

  <!-- Main content slot -->
  <main class="flex-grow">
    <slot />
  </main>

  <!-- Footer -->
  <footer class="bg-blue-900 text-white p-4">
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-4 gap-4">
      <div>
        <h3 class="font-bold mb-2">Links</h3>
        <ul class="space-y-1">
          <li><a href="/" class="hover:underline">Home</a></li>
          <li><a href="/about" class="hover:underline">About</a></li>
          <li><a href="/blog" class="hover:underline">Blog</a></li>
          <li><a href="/help" class="hover:underline">Help</a></li>
        </ul>
      </div>
      <div>
        <h3 class="font-bold mb-2">Lists</h3>
        <ul class="space-y-1">
          <li><a href="/highest-waterfalls" class="hover:underline">Highest Waterfalls</a></li>
          <li><a href="/single-drop" class="hover:underline">Single Drop Waterfalls</a></li>
          <li><a href="/free-falls" class="hover:underline">Free Falls</a></li>
          <li><a href="/widest-waterfalls" class="hover:underline">Widest Waterfalls</a></li>
        </ul>
      </div>
      <div>
        <h3 class="font-bold mb-2">Browse</h3>
        <ul class="space-y-1">
          <li><a href="/state-list" class="hover:underline">State List</a></li>
          <li><a href="/map-tool" class="hover:underline">Map Tool</a></li>
          <li><a href="/updates" class="hover:underline">Updates</a></li>
          <li><a href="/top-100" class="hover:underline">Top 100 List</a></li>
        </ul>
      </div>
      <div>
        <h3 class="font-bold mb-2">Contact Us</h3>
        <div class="flex space-x-2">
          <a href="#" class="hover:text-gray-300"><i class="fab fa-twitter"></i></a>
          <a href="#" class="hover:text-gray-300"><i class="fab fa-facebook"></i></a>
        </div>
      </div>
    </div>
  </footer>
</div>