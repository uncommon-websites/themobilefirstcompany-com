<script lang="ts">
  // Black Section
</script>

<section class="bg-[#0A0A0A] text-white py-32 overflow-hidden relative">
  <div class="max-w-6xl mx-auto px-6 flex flex-col gap-40 relative z-10">
    
    <!-- Feature 1 -->
    <div class="flex flex-col md:flex-row items-center justify-between gap-12">
      <div class="md:w-1/2">
        <h2 class="text-4xl md:text-5xl font-bold leading-tight mb-6">
          AI software that works everywhere you work.
        </h2>
        <p class="text-gray-400 text-lg leading-relaxed max-w-md">
          Desktop? Of course we have it. What makes us different is native mobile apps that are just as powerful.
        </p>
      </div>
      <div class="md:w-1/2 flex justify-end">
        <!-- Grid of icons visual -->
        <div class="grid grid-cols-3 gap-4 opacity-50">
            {#each Array(9) as _}
            <div class="w-16 h-16 bg-gray-800 rounded-xl border border-gray-700"></div>
            {/each}
        </div>
      </div>
    </div>

    <!-- Feature 2 -->
    <div class="flex flex-col md:flex-row items-center justify-between gap-12">
      <div class="md:w-1/2">
        <h2 class="text-4xl md:text-5xl font-bold leading-tight mb-6">
          Trusted by 5,000+ businesses worldwide.
        </h2>
        <p class="text-gray-400 text-lg leading-relaxed max-w-md">
          From Michelin-starred restaurants to auto repair shops, from coworking spaces to tech schools. Real businesses are replacing legacy software with our AI suite.
        </p>
      </div>
      <div class="md:w-1/2 flex justify-start">
         <!-- Globe wireframe placeholder -->
         <div class="w-64 h-64 rounded-full border border-gray-700 relative flex items-center justify-center">
            <div class="absolute w-full h-full rounded-full border border-gray-800 transform rotate-45"></div>
            <div class="absolute w-full h-full rounded-full border border-gray-800 transform -rotate-45"></div>
            <div class="absolute w-[120%] h-[1px] bg-gray-800"></div>
            <div class="absolute h-[120%] w-[1px] bg-gray-800"></div>
         </div>
      </div>
    </div>
  </div>

  <!-- Center Phone Visual -->
  <div class="flex justify-center my-20">
      <div class="w-[300px] h-[600px] bg-black border-[8px] border-gray-800 rounded-[3rem] relative overflow-hidden shadow-2xl">
          <!-- Dynamic Island -->
          <div class="absolute top-2 left-1/2 transform -translate-x-1/2 w-24 h-6 bg-black rounded-full z-20"></div>
          
          <!-- Screen Content -->
          <div class="w-full h-full bg-gradient-to-b from-gray-900 to-black relative">
              <img src="https://images.unsplash.com/photo-1531123897727-8f129e1688ce?q=80&w=1000&auto=format&fit=crop" alt="Profile" class="w-full h-full object-cover opacity-80" />
              <div class="absolute bottom-10 left-6 text-white text-4xl font-bold leading-tight">
                  let's<br/>
                  breathe<br/>
                  <span class="text-gray-500">you are on</span>
              </div>
          </div>
      </div>
  </div>
</section>
