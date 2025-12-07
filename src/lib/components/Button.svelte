<script>
  export let href = "#";
  export let variant = "primary"; // primary, secondary
</script>

<a
  {href}
  class="inline-flex items-center justify-center gap-2 rounded-full px-6 py-3 text-sm font-medium transition-transform hover:scale-105 active:scale-95 {variant ===
  'primary'
    ? 'bg-black text-white hover:bg-gray-800'
    : 'bg-white text-black border border-gray-200 hover:bg-gray-50'}"
>
  <slot />
</a>
