<script lang="ts">
  // Green/Teal Section
</script>

<section class="bg-[#1A4D45] text-white py-32 overflow-hidden">
  <div class="max-w-6xl mx-auto px-6 flex flex-col gap-32">
    
    <!-- Row 1 -->
    <div class="flex flex-col md:flex-row items-center justify-between gap-12">
      <div class="md:w-1/2">
        <h2 class="text-4xl md:text-5xl font-bold leading-tight mb-6">
          Our parents' generation never got access to modern software.
        </h2>
        <p class="text-gray-300 text-lg leading-relaxed max-w-md">
          An entire generation of business owners has been stuck with outdated, expensive tools while the world moved on.
        </p>
      </div>
      <div class="md:w-1/2 flex justify-center relative">
        <!-- CD Visual -->
        <div class="w-64 h-64 rounded-full bg-gradient-to-br from-gray-200 to-gray-400 relative flex items-center justify-center shadow-2xl animate-spin-slow" style="animation-duration: 10s;">
           <div class="absolute inset-0 rounded-full bg-[conic-gradient(transparent_0deg,white_45deg,transparent_60deg)] opacity-50"></div>
           <div class="w-20 h-20 bg-[#1A4D45] rounded-full border-4 border-gray-300"></div>
           <div class="absolute bottom-8 text-black font-bold text-xl tracking-widest opacity-60">Excel</div>
        </div>
      </div>
    </div>

    <!-- Row 2 -->
    <div class="flex flex-col md:flex-row items-center justify-between gap-12">
      <div class="md:w-1/2">
        <h2 class="text-4xl md:text-5xl font-bold leading-tight mb-6">
          We build software younger than the businesses using it.
        </h2>
        <p class="text-gray-300 text-lg leading-relaxed max-w-md">
          Our mission is simple: create tools entrepreneurs love. Software that's modern, intuitive, and fair-priced.
        </p>
      </div>
      <div class="md:w-1/2 flex justify-center relative">
        <!-- Document Visual -->
        <div class="w-72 h-96 bg-white rounded-lg shadow-2xl transform -rotate-6 p-6 text-gray-800 text-[10px] overflow-hidden relative">
            <div class="flex justify-between items-center mb-4 border-b pb-2">
                <span class="font-bold text-lg">Invoice</span>
                <span class="text-gray-500">#00123</span>
            </div>
            <div class="space-y-2">
                <div class="h-2 bg-gray-100 w-1/3"></div>
                <div class="h-2 bg-gray-100 w-1/2"></div>
            </div>
            <div class="mt-8">
                <div class="grid grid-cols-4 gap-2 mb-2 font-bold text-gray-600">
                    <div>Item</div>
                    <div>Qty</div>
                    <div>Price</div>
                    <div>Total</div>
                </div>
                {#each Array(5) as _}
                <div class="grid grid-cols-4 gap-2 mb-2 border-b border-gray-100 pb-1">
                    <div class="h-2 bg-gray-100 w-full"></div>
                    <div class="h-2 bg-gray-100 w-1/2"></div>
                    <div class="h-2 bg-gray-100 w-3/4"></div>
                    <div class="h-2 bg-gray-100 w-full"></div>
                </div>
                {/each}
            </div>
            <div class="absolute bottom-0 left-0 w-full h-24 bg-gradient-to-t from-white to-transparent"></div>
        </div>
      </div>
    </div>

  </div>
</section>
