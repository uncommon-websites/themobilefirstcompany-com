<script lang="ts">
  // Hero Section
</script>

<section class="relative min-h-[90vh] bg-[#FDFCF8] overflow-hidden pt-20 pb-32 flex flex-col items-center justify-center text-center">
  <!-- Background Elements (The "Messy Desk") -->
  
  <!-- Keyboard (Top Right) -->
  <div class="absolute -top-10 -right-20 w-[600px] h-[300px] bg-gray-100 rounded-xl shadow-lg transform -rotate-12 border border-gray-200 p-4 opacity-80">
    <div class="grid grid-cols-[repeat(20,1fr)] gap-2 h-full">
      {#each Array(60) as _, i}
        <div class="bg-white rounded shadow-sm border border-gray-200"></div>
      {/each}
    </div>
  </div>

  <!-- CD Case (Top Left) -->
  <div class="absolute top-10 -left-10 w-64 h-64 bg-transparent border-2 border-gray-300 rounded-lg transform rotate-12 flex items-center justify-center backdrop-blur-sm">
     <div class="w-56 h-56 rounded-full bg-gradient-to-tr from-gray-200 to-gray-100 border border-gray-300 flex items-center justify-center relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-tr from-transparent via-white/40 to-transparent rotate-45"></div>
        <div class="text-[10px] font-mono text-gray-400 rotate-90">Compact Disc</div>
     </div>
     <div class="absolute top-2 left-4 bg-black text-white text-xs px-2 py-0.5 rotate-12">The Mobile-First Issue</div>
  </div>

  <!-- Sticky Note (Left) -->
  <div class="absolute top-1/3 left-[5%] xl:left-[10%] w-48 h-48 bg-[#FFF8A8] shadow-md transform -rotate-6 p-4 font-handwriting text-gray-800 flex flex-col justify-center items-center z-0">
    <p class="text-2xl leading-relaxed text-center font-bold rotate-[-5deg]">Don't forget<br>to check the<br>new update!</p>
  </div>

  <!-- Mouse (Right) -->
  <div class="absolute bottom-32 right-[10%] w-28 h-44 bg-gradient-to-b from-gray-100 to-gray-300 rounded-[40px] shadow-xl transform rotate-12 border border-gray-300 flex justify-center pt-4 z-0">
    <div class="w-1 h-12 bg-gray-300 rounded-full"></div>
  </div>

  <!-- Cable -->
  <svg class="absolute bottom-0 right-0 w-full h-full pointer-events-none z-0 opacity-20" viewBox="0 0 1000 800">
    <path d="M 800 600 Q 600 700 400 600 T 100 800" fill="none" stroke="#333" stroke-width="4" />
  </svg>

  <!-- Receipts/Papers (Bottom Center/Left) -->
  <div class="absolute bottom-10 left-[25%] w-40 h-56 bg-white shadow-md transform rotate-6 border border-gray-200 p-4 text-[8px] font-mono text-gray-400 flex flex-col gap-2">
    <div class="w-full h-4 bg-gray-100"></div>
    <div class="w-3/4 h-2 bg-gray-100"></div>
    <div class="w-1/2 h-2 bg-gray-100"></div>
    <div class="mt-auto border-t border-dashed border-gray-300 pt-2 flex justify-between">
      <span>Total</span>
      <span>$0.00</span>
    </div>
  </div>


  <!-- Content -->
  <div class="relative z-10 max-w-3xl mx-auto px-4 mt-20">
    <div class="inline-block mb-4 text-xs font-medium tracking-widest text-gray-500 uppercase">The Mobile-First company</div>
    
    <h1 class="text-5xl md:text-7xl font-bold text-gray-900 tracking-tight leading-[1.1] mb-6">
      AI Suite for Small Teams<br/>
      replacing legacy software.
    </h1>
    
    <p class="text-lg md:text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
      We're building the first software legacy platforms never built.<br/>
      Modern, reliable, affordable tools for businesses like yours.
    </p>
    
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
      <button class="px-8 py-3 bg-[#EAE088] text-gray-900 font-semibold rounded-full hover:bg-[#e6da75] transition-colors shadow-sm text-sm">
        Start using Now
      </button>
      <button class="px-8 py-3 bg-white text-gray-900 font-semibold rounded-full border border-gray-200 hover:bg-gray-50 transition-colors shadow-sm flex items-center gap-2 text-sm">
        Try Me
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
      </button>
    </div>
  </div>
</section>
