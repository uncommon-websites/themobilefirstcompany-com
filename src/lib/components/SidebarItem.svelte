<script lang="ts">
  export let icon: string;
  export let label: string;
  export let active: boolean = false;
</script>

<button class="flex items-center gap-3 p-2 rounded-lg transition-colors hover:bg-gray-100 w-full text-left group {active ? 'bg-white shadow-sm' : ''}">
  <div class="w-8 h-8 flex items-center justify-center rounded-md bg-white border border-gray-200 shadow-sm group-hover:scale-105 transition-transform">
    {@html icon}
  </div>
  <span class="text-sm font-medium text-gray-700">{label}</span>
</button>
