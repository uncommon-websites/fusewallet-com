<script>
  // Security Grid Component
</script>

<section class="py-24 bg-white">
  <div class="mx-auto max-w-[1200px] px-6">
    <div class="grid grid-cols-1 gap-6 md:grid-cols-2">
      
      <!-- Card 1: Dark -->
      <div class="relative overflow-hidden rounded-3xl bg-black p-12 text-white min-h-[400px] flex flex-col justify-end">
        <div class="absolute top-12 left-12">
            <!-- Shield Logo -->
            <div class="h-16 w-16">
                 <svg viewBox="0 0 24 24" fill="none" class="h-full w-full text-white">
                    <path d="M12 2L3 7v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V7l-9-5z" fill="url(#metal-gradient)" />
                    <defs>
                        <linearGradient id="metal-gradient" x1="0" y1="0" x2="1" y2="1">
                            <stop offset="0%" stop-color="#94a3b8" />
                            <stop offset="50%" stop-color="#e2e8f0" />
                            <stop offset="100%" stop-color="#475569" />
                        </linearGradient>
                    </defs>
                 </svg>
            </div>
        </div>
        
        <div class="relative z-10 max-w-md">
          <h3 class="text-2xl font-bold mb-4">Solana's security standard</h3>
          <p class="text-gray-400">
            Fuse is built on smart accounts to provide transparent, programmable self-custody.
          </p>
        </div>
      </div>

      <!-- Card 2: Light -->
      <div class="relative overflow-hidden rounded-3xl bg-gray-50 p-12 text-gray-900 min-h-[400px] flex flex-col justify-end">
        <div class="absolute top-12 left-12">
            <!-- Share/Network Icon -->
            <div class="h-16 w-16 rounded-full bg-blue-100 flex items-center justify-center">
                 <svg class="h-8 w-8 text-blue-500" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M18 16.08c-.76 0-1.44.3-1.96.77L8.91 12.7c.05-.23.09-.46.09-.7s-.04-.47-.09-.7l7.05-4.11c.54.5 1.25.81 2.04.81 1.66 0 3-1.34 3-3s-1.34-3-3-3-3 1.34-3 3c0 .24.04.47.09.7L8.04 9.81C7.5 9.31 6.79 9 6 9c-1.66 0-3 1.34-3 3s1.34 3 3 3c.79 0 1.5-.31 2.04-.81l7.12 4.16c-.05.21-.08.43-.08.65 0 1.61 1.31 2.92 2.92 2.92 1.61 0 2.92-1.31 2.92-2.92s-1.31-2.92-2.92-2.92z"/>
                 </svg>
            </div>
        </div>
        
        <div class="relative z-10 max-w-md">
          <h3 class="text-2xl font-bold mb-4">Your assets. Your control.</h3>
          <p class="text-gray-500">
            With Fuse, you have complete control over your assets. Your ownership is enforced by Solana's global network of 1,000+ validators—not by a centralized exchange or a trusted third party.
          </p>
        </div>
      </div>

    </div>

    <!-- Documentation Link -->
    <div class="mt-16 text-center">
        <p class="text-gray-500 mb-2">Explore our detailed documentation to learn</p>
        <p class="text-gray-500 mb-4">more about Fuse's features and benefits.</p>
        <a href="#" class="inline-flex items-center justify-center h-10 w-10 rounded-full border border-gray-300 text-gray-500 hover:bg-gray-50">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <path d="M5 12h14M12 5l7 7-7 7"/>
            </svg>
        </a>
    </div>

  </div>
</section>
