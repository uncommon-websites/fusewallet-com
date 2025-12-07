<script>
  // Feature Split Component 1: Stablecoins
</script>

<section class="py-24 bg-white overflow-hidden">
  <div class="mx-auto max-w-[1200px] px-6">
    <div class="flex flex-col lg:flex-row items-center gap-16">
      
      <!-- Text Content -->
      <div class="w-full lg:w-1/2">
        <h2 class="text-4xl font-bold tracking-tight text-gray-900 mb-12">
          Use stablecoins<br>as everyday money
        </h2>

        <div class="space-y-8">
          <!-- Progress Indicators -->
          <div class="flex gap-2 mb-8">
            <div class="h-1 w-12 rounded-full bg-black"></div>
            <div class="h-1 w-12 rounded-full bg-gray-200"></div>
            <div class="h-1 w-12 rounded-full bg-gray-200"></div>
          </div>

          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Virtual Banking</h3>
            <p class="text-gray-500 leading-relaxed">
              Accept USD and EUR bank transfers that land in your account as USDC
            </p>
          </div>
        </div>
      </div>

      <!-- Phone Visual -->
      <div class="w-full lg:w-1/2 relative flex justify-center lg:justify-end">
        <div class="relative h-[600px] w-[300px] rounded-[48px] border-[6px] border-gray-900 bg-white shadow-2xl overflow-hidden ring-1 ring-gray-900/5">
          <!-- Dynamic Island / Notch -->
          <div class="absolute top-2 left-1/2 -translate-x-1/2 h-7 w-28 bg-black rounded-full z-20"></div>
          
          <!-- Screen Content -->
          <div class="h-full w-full bg-gray-50 flex flex-col pt-14 px-5">
             <!-- Status Bar (Hidden behind notch visually but space reserved) -->
             
             <!-- Toggle -->
             <div class="flex justify-center mb-8">
                <div class="flex bg-gray-200/80 p-1 rounded-full">
                   <div class="px-4 py-1.5 bg-white rounded-full shadow-sm text-xs font-semibold flex items-center gap-1.5 transition-all">
                      <span class="text-base">🇺🇸</span> USD
                   </div>
                   <div class="px-4 py-1.5 text-xs font-medium text-gray-500 flex items-center gap-1.5 cursor-pointer hover:text-gray-900 transition-colors">
                      <span class="text-base grayscale opacity-70">🇪🇺</span> EUR
                   </div>
                </div>
             </div>

             <!-- Title -->
             <div class="text-center mb-8">
                <h4 class="text-xl font-bold text-gray-900 tracking-tight">Virtual EU Bank Account</h4>
                <p class="text-xs text-gray-500 mt-1 font-medium">Accept SEPA Payments</p>
             </div>

             <!-- Pills -->
             <div class="flex flex-wrap justify-center gap-2 mb-8">
                <span class="px-2.5 py-1.5 bg-white rounded-lg text-[10px] font-medium text-gray-600 border border-gray-100 shadow-sm">Fees 0.1%</span>
                <span class="px-2.5 py-1.5 bg-white rounded-lg text-[10px] font-medium text-gray-600 border border-gray-100 shadow-sm flex items-center gap-1">Limits <svg class="w-2.5 h-2.5 text-gray-400" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M7 17L17 7M17 7H7M17 7V17"/></svg></span>
                <span class="px-2.5 py-1.5 bg-white rounded-lg text-[10px] font-medium text-gray-600 border border-gray-100 shadow-sm">Min. transfer is €2</span>
             </div>

             <!-- Details List -->
             <div class="space-y-0 bg-white rounded-2xl border border-gray-100 shadow-sm overflow-hidden">
                <div class="flex justify-between items-center p-4 border-b border-gray-50 hover:bg-gray-50 transition-colors cursor-pointer group">
                   <div>
                      <div class="text-[10px] font-medium text-gray-400 mb-0.5">IBAN</div>
                      <div class="text-xs font-semibold text-gray-900 font-mono tracking-tight">IE19MODR99035505871234</div>
                   </div>
                   <svg class="w-4 h-4 text-gray-300 group-hover:text-gray-500 transition-colors" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg>
                </div>
                <div class="flex justify-between items-center p-4 border-b border-gray-50 hover:bg-gray-50 transition-colors cursor-pointer group">
                   <div>
                      <div class="text-[10px] font-medium text-gray-400 mb-0.5">BIC</div>
                      <div class="text-xs font-semibold text-gray-900 font-mono tracking-tight">MODRIE24XEQ</div>
                   </div>
                   <svg class="w-4 h-4 text-gray-300 group-hover:text-gray-500 transition-colors" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg>
                </div>
                <div class="flex justify-between items-center p-4 hover:bg-gray-50 transition-colors cursor-pointer group">
                   <div>
                      <div class="text-[10px] font-medium text-gray-400 mb-0.5">Bank name</div>
                      <div class="text-xs font-semibold text-gray-900">Modulr Finance, Ireland Branch</div>
                   </div>
                   <svg class="w-4 h-4 text-gray-300 group-hover:text-gray-500 transition-colors" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"/></svg>
                </div>
             </div>

          </div>
        </div>
      </div>

    </div>
  </div>
</section>
