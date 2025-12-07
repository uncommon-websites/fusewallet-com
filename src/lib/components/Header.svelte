<script>
  import Button from "./Button.svelte";
</script>

<header class="sticky top-0 z-50 w-full bg-white/80 backdrop-blur-md">
  <div class="mx-auto flex h-20 max-w-[1200px] items-center justify-between px-6">
    <a href="/" class="flex items-center gap-2">
      <!-- Logo Icon -->
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2ZM10 16C10 16.5523 10.4477 17 11 17H13C13.5523 17 14 16.5523 14 16V14H16C16.5523 14 17 13.5523 17 13V11C17 10.4477 16.5523 10 16 10H14V8C14 7.44772 13.5523 7 13 7H11C10.4477 7 10 7.44772 10 8V10H8C7.44772 10 7 10.4477 7 11V13C7 13.5523 7.44772 14 8 14H10V16Z" fill="black"/>
        <!-- This is a placeholder logo, I'll try to match the screenshot closer if I can see it better. 
             The screenshot logo looks like a stylized 4-dot or knot. 
             Let's try to make a closer approximation: 4 dots forming a square with connections? 
             Actually, looking at the footer, it's a black rounded square with a white shape inside.
             The header logo is just text "Fuse" with a small icon maybe? 
             Let's just use text "Fuse" with a bold font for now and a small icon. -->
      </svg>
      <span class="text-xl font-bold tracking-tight">Fuse</span>
    </a>

    <nav class="flex items-center gap-8">
      <a href="/support" class="text-sm font-medium text-gray-600 hover:text-black">Support</a>
      <a href="/blog" class="text-sm font-medium text-gray-600 hover:text-black">Blog</a>
      <Button href="#">Download on iOS</Button>
    </nav>
  </div>
</header>
