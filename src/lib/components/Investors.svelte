<script lang="ts">
  // Investors Section
</script>

<section class="bg-[#F5F5F7] pb-32 pt-10 px-4">
  <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center justify-center gap-10">
    
    <!-- Yellow Note -->
    <div class="w-80 h-80 bg-[#FFF8A8] shadow-lg transform -rotate-3 p-8 flex flex-col justify-center items-center text-center">
       <div class="text-4xl font-bold leading-tight mb-4">
         We've raised<br/>
         <span class="inline-block border-2 border-black rounded-full px-3 py-1 bg-white text-2xl my-2">$12M</span><br/>
         to rebuild<br/>
         business software
       </div>
    </div>

    <!-- Dark Tablet/Interface -->
    <div class="w-full max-w-md bg-[#111] rounded-3xl p-6 shadow-2xl text-white">
      <div class="flex justify-between items-center mb-6">
        <h3 class="font-bold text-lg">Our investors</h3>
        <div class="flex gap-1">
           <div class="w-2 h-2 rounded-full bg-red-500"></div>
           <div class="w-2 h-2 rounded-full bg-yellow-500"></div>
           <div class="w-2 h-2 rounded-full bg-green-500"></div>
        </div>
      </div>
      
      <div class="space-y-3">
        {#each ['Y Combinator', 'Founders Fund', 'Slow Ventures', 'Kima Ventures', 'Motier Ventures'] as investor}
        <div class="flex items-center gap-3 p-3 bg-white/5 rounded-xl hover:bg-white/10 transition-colors cursor-default">
          <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-gray-700 to-gray-600 flex items-center justify-center text-xs font-bold">
            {investor[0]}
          </div>
          <span class="font-medium text-sm">{investor}</span>
          <span class="ml-auto text-gray-500 text-xs">→</span>
        </div>
        {/each}
      </div>
    </div>

  </div>
</section>
