<script>
  import "../app.css";
</script>

<div class="font-body flex flex-col h-screen">
  <div class="bg-blue-900/70">
    <div class="mx-auto max-w-screen-2xl px-4 md:px-4">
      <header class="flex items-center py-4 md:py-4">
        <nav class="gap-12 lg:flex">
          <a
            href="/"
            class="text-xl font-semibold text-white transition duration-100"
          >
            Home
          </a>
          <a
            href="/gallery"
            class="text-xl font-semibold text-white transition duration-100"
          >
            Gallery
          </a>
        </nav>
      </header>
    </div>
  </div>

  <div class="bg-sky-100/50">
    <slot />
  </div>

  <div class="bg-blue-900/70 mb-auto">
    <footer class="flex justify-center py-5 md:py-5">
      <p class="text-white text-sm">Copyright © 2024 speak-mentaiko</p>
    </footer>
  </div>
</div>
