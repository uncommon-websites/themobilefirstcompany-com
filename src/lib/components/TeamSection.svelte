<script lang="ts">
  // Team Section
  const images = [
    "https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=500&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1600880292203-757bb62b4baf?q=80&w=500&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1519389950473-47ba0277781c?q=80&w=500&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1531482615713-2afd69097998?q=80&w=500&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1556761175-5973dc0f32e7?q=80&w=500&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1552664730-d307ca884978?q=80&w=500&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1542744173-8e7e53415bb0?q=80&w=500&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1600880292089-90a7e086ee0c?q=80&w=500&auto=format&fit=crop"
  ];
</script>

<section class="bg-[#F5F5F7] py-32">
  <div class="max-w-7xl mx-auto px-6">
    
    <div class="flex flex-col md:flex-row justify-between items-start mb-16">
      <h2 class="text-4xl font-bold text-gray-900">Our teams</h2>
      
      <div class="max-w-xl">
        <h3 class="text-3xl font-bold leading-tight mb-6">
          In <span class="text-pink-500 italic">Miami</span>, <span class="text-purple-500 italic">Paris</span> and <span class="text-yellow-600 italic">Buenos Aires</span>.<br/>
          A global team with one goal.
        </h3>
        
        <div class="grid grid-cols-3 gap-8 text-xs text-gray-500 mb-8">
          <div>
            <strong class="block text-purple-600 mb-1">Paris</strong>
            5 Rue de Tracy<br/>
            75002 Paris<br/>
            France
          </div>
          <div>
            <strong class="block text-pink-600 mb-1">Miami</strong>
            78 SW 7th Street<br/>
            Miami, FL 33130<br/>
            United States
          </div>
          <div>
            <strong class="block text-yellow-600 mb-1">Buenos Aires</strong>
            El Salvador 5218<br/>
            C1414BPV Buenos Aires<br/>
            Argentina
          </div>
        </div>
        
        <button class="px-6 py-2 border border-gray-300 rounded-full text-sm font-medium hover:bg-white transition-colors">
          Join the team
        </button>
      </div>
    </div>

    <!-- Photo Grid -->
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
      {#each images as img, i}
        <div class="aspect-[3/4] overflow-hidden rounded-xl bg-gray-200 relative group">
           <img src={img} alt="Team member" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
        </div>
      {/each}
    </div>

  </div>
</section>
