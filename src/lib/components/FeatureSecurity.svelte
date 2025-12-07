<script>
  // Feature Split Component 2: Security
</script>

<section class="py-24 bg-gray-50 overflow-hidden">
  <div class="mx-auto max-w-[1200px] px-6">
    <div class="flex flex-col lg:flex-row items-center gap-16">
      
      <!-- Phone Visual (Left side this time) -->
      <div class="w-full lg:w-1/2 relative flex justify-center lg:justify-start order-2 lg:order-1">
        <div class="relative h-[600px] w-[300px] rounded-[48px] border-[6px] border-gray-900 bg-white shadow-2xl overflow-hidden ring-1 ring-gray-900/5">
          <!-- Dynamic Island / Notch -->
          <div class="absolute top-2 left-1/2 -translate-x-1/2 h-7 w-28 bg-black rounded-full z-20"></div>
          
          <!-- Screen Content - Blurred Background -->
          <div class="h-full w-full bg-gray-100 flex flex-col items-center justify-center relative">
             <!-- Modal -->
             <div class="w-[90%] bg-white rounded-2xl shadow-2xl p-6 z-10 scale-100 transition-transform">
                <div class="flex justify-end mb-2">
                   <div class="h-6 w-6 rounded-full bg-gray-100 flex items-center justify-center text-gray-400 text-xs hover:bg-gray-200 cursor-pointer">✕</div>
                </div>
                <div class="text-center mb-6">
                   <h4 class="text-lg font-bold text-gray-900">Daily Spending Limit</h4>
                   <p class="text-[10px] text-gray-400 mt-1 px-4 leading-tight">Press complete to finalize the daily limit change</p>
                </div>

                <div class="flex items-center justify-center gap-4 mb-8">
                   <div class="text-xl font-medium text-gray-400 line-through decoration-gray-400 decoration-2">$400</div>
                   <svg class="w-4 h-4 text-gray-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
                   <div class="text-2xl font-bold text-gray-900">$1600</div>
                </div>

                <p class="text-[10px] text-center text-gray-400 mb-6">You can close this and return to it later.</p>

                <div class="flex gap-3">
                   <button class="flex-1 py-2.5 rounded-full bg-gray-100 text-xs font-semibold text-gray-900 hover:bg-gray-200 transition-colors">Cancel changes</button>
                   <button class="flex-1 py-2.5 rounded-full bg-[#22C55E] text-xs font-semibold text-white hover:bg-green-600 transition-colors shadow-lg shadow-green-200">Complete</button>
                </div>
             </div>
             
             <!-- Background elements to look like app behind modal -->
             <div class="absolute inset-0 z-0 bg-gray-200/50 backdrop-blur-md">
                 <!-- Fake app UI behind blur -->
                 <div class="h-full w-full p-6 opacity-20">
                     <div class="h-8 w-1/2 bg-gray-400 rounded mb-4"></div>
                     <div class="h-32 w-full bg-gray-300 rounded-xl mb-4"></div>
                     <div class="h-12 w-full bg-gray-300 rounded-xl mb-2"></div>
                     <div class="h-12 w-full bg-gray-300 rounded-xl mb-2"></div>
                 </div>
             </div>
          </div>
        </div>
      </div>

      <!-- Text Content -->
      <div class="w-full lg:w-1/2 order-1 lg:order-2">
        <h2 class="text-4xl font-bold tracking-tight text-gray-900 mb-12">
          Enterprise-grade<br>security that fits<br>in your pocket
        </h2>

        <div class="space-y-8">
          <!-- Progress Indicators -->
          <div class="flex gap-2 mb-8">
            <div class="h-1 w-12 rounded-full bg-gray-200"></div>
            <div class="h-1 w-12 rounded-full bg-blue-500"></div>
            <div class="h-1 w-12 rounded-full bg-gray-200"></div>
          </div>

          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Maximize Security, Minimize Friction</h3>
            <p class="text-gray-500 leading-relaxed">
              Upgrade your 2FA Key from iCloud to a hardware wallet while maintaining seamless transfers with custom spending limits.
            </p>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>
