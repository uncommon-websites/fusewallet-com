<script>
  // Bento Grid Component
</script>

<section class="py-24 bg-white">
  <div class="mx-auto max-w-[1200px] px-6">
    <div class="mb-16 text-center">
      <h2 class="mb-4 text-4xl font-bold tracking-tight text-gray-900">
        Fuse isn't another crypto wallet.
      </h2>
      <p class="mx-auto max-w-2xl text-lg text-gray-500">
        It's a personal finance app powered by the same smart accounts that secure billions for the leading teams building on Solana - now available to everyone
      </p>
    </div>

    <!-- Main Grid Layout -->
    <div class="grid grid-cols-1 gap-6 lg:grid-cols-3">
      
      <!-- Left Column: Large Dark Card -->
      <div class="group relative overflow-hidden rounded-[32px] bg-[#0F172A] p-8 text-white lg:col-span-1 min-h-[500px] flex flex-col justify-end">
        <!-- Background Gradient -->
        <div class="absolute inset-0 bg-gradient-to-br from-blue-900/30 via-[#0F172A] to-[#0F172A]"></div>
        
        <!-- Graph Visual -->
        <div class="absolute inset-x-0 top-[20%] h-48 w-full opacity-90">
           <svg viewBox="0 0 400 200" preserveAspectRatio="none" class="h-full w-full">
             <defs>
               <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
                 <stop offset="0%" style="stop-color:#64748b;stop-opacity:0.2" />
                 <stop offset="50%" style="stop-color:#cbd5e1;stop-opacity:0.8" />
                 <stop offset="100%" style="stop-color:#ffffff;stop-opacity:1" />
               </linearGradient>
             </defs>
             <!-- Smooth curve -->
             <path d="M0,180 C100,180 150,120 250,80 C320,50 360,40 400,30" fill="none" stroke="url(#grad1)" stroke-width="40" stroke-linecap="round" />
           </svg>
           <div class="absolute left-8 top-40 text-xs text-gray-500 font-medium">Today</div>
           <div class="absolute right-8 top-6 text-xs text-white font-medium text-right">In one<br>year</div>
        </div>

        <div class="relative z-10 mt-auto">
          <h3 class="text-3xl font-medium leading-tight tracking-tight">
            Grow your balance with integrated <span class="text-gray-500">stablecoin yield</span> and <span class="text-gray-500">staking rewards</span>
          </h3>
        </div>
      </div>

      <!-- Right Column: 2x2 Grid with unequal widths -->
      <div class="flex flex-col gap-6 lg:col-span-2">
        
        <!-- Top Row -->
        <div class="grid grid-cols-1 gap-6 md:grid-cols-12">
            <!-- Trade Solana (Smaller) -->
            <div class="rounded-[32px] bg-gray-50 p-8 md:col-span-5 flex flex-col justify-between min-h-[240px]">
                <div class="mb-4 flex items-center gap-2">
                    <div class="flex h-10 w-10 items-center justify-center rounded-full bg-black text-white shrink-0">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 16V4M7 4L3 8M7 4L11 8M17 8V20M17 20L21 16M17 20L13 16" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <span class="rounded-full bg-[#E0F2FE] px-3 py-1 text-xs font-bold text-[#0284C7]">0% Fee</span>
                </div>
                <h3 class="text-xl font-medium text-gray-900 leading-snug">Trade Solana tokens with zero-fee swaps</h3>
            </div>

            <!-- Pay with stablecoins (Larger) -->
            <div class="relative rounded-[32px] bg-gray-50 p-8 md:col-span-7 flex flex-col overflow-hidden min-h-[240px]">
                <h3 class="text-xl font-medium text-gray-900 leading-snug mb-8 relative z-10">Pay with stablecoins using Fuse Card</h3>
                <!-- Card Visual -->
                <div class="absolute bottom-[-60px] right-0 left-0 flex justify-center">
                    <div class="h-40 w-64 rounded-[24px] bg-black p-5 shadow-2xl transform rotate-[-5deg] hover:rotate-0 transition-transform duration-500">
                        <div class="flex justify-between items-start">
                             <div class="h-8 w-10 rounded bg-gray-700/50"></div> <!-- Chip -->
                             <div class="h-6 w-6 rounded-full border border-gray-600"></div> <!-- Logo placeholder -->
                        </div>
                        <div class="mt-16 flex gap-2">
                            <div class="h-2 w-12 rounded-full bg-gray-800"></div>
                            <div class="h-2 w-8 rounded-full bg-gray-800"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Bottom Row -->
        <div class="grid grid-cols-1 gap-6 md:grid-cols-12">
            <!-- Move between (Larger) -->
            <div class="rounded-[32px] bg-gray-50 p-8 md:col-span-7 flex flex-col justify-between min-h-[240px]">
                 <div class="mb-8 flex items-center gap-3">
                    <div class="flex h-12 w-12 items-center justify-center rounded-full bg-[#2563EB] text-white shadow-lg shadow-blue-200 shrink-0 z-10">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6" />
                        </svg>
                    </div>
                    <div class="-ml-6 flex items-center gap-3 pl-6">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-gray-400">
                            <path d="M5 12h14M12 5l7 7-7 7" />
                        </svg>
                        <div class="flex h-10 w-10 items-center justify-center rounded-full bg-white border border-gray-100 text-gray-500 shadow-sm text-sm font-medium">€</div>
                        <div class="flex h-10 w-10 items-center justify-center rounded-full bg-white border border-gray-100 text-gray-500 shadow-sm text-sm font-medium">$</div>
                        <div class="flex h-10 w-10 items-center justify-center rounded-full bg-white border border-gray-100 text-gray-500 shadow-sm text-sm font-medium">£</div>
                    </div>
                </div>
                <h3 class="text-xl font-medium text-gray-900 leading-snug">Move between crypto and cash seamlessly</h3>
            </div>

            <!-- Secure your assets (Smaller) -->
            <div class="rounded-[32px] bg-gray-50 p-8 md:col-span-5 flex flex-col justify-between min-h-[240px]">
                <div class="mb-8">
                    <div class="h-12 w-10">
                        <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-[#22C55E] h-full w-full drop-shadow-sm">
                            <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" fill="currentColor"/>
                        </svg>
                    </div>
                </div>
                <h3 class="text-xl font-medium text-gray-900 leading-snug">Secure your assets with self-custodial smart accounts</h3>
            </div>
        </div>

      </div>
    </div>
  </div>
</section>
