<script>
  import Button from "./Button.svelte";
</script>

<section class="py-24 bg-white text-center">
  <div class="mx-auto max-w-[1200px] px-6">
    
    <div class="mb-8 flex justify-center">
       <!-- Logo Icon -->
       <div class="h-16 w-16 bg-black rounded-2xl flex items-center justify-center text-white">
          <svg width="32" height="32" viewBox="0 0 24 24" fill="currentColor">
              <!-- Simple knot/fuse shape -->
              <circle cx="8" cy="8" r="3" />
              <circle cx="16" cy="8" r="3" />
              <circle cx="8" cy="16" r="3" />
              <circle cx="16" cy="16" r="3" />
          </svg>
       </div>
    </div>

    <h2 class="mb-4 text-5xl font-bold tracking-tight text-gray-900">
      Get started with Fuse today.
    </h2>
    <p class="mb-10 text-xl text-gray-500">
      The personal finance app to save, trade and pay with crypto
    </p>
    
    <div class="flex justify-center">
      <Button href="#">
        <svg class="h-5 w-5" viewBox="0 0 24 24" fill="currentColor">
          <path d="M17.5 12.625c0-2.604 2.135-3.854 2.229-3.906-.01-.042-0.427-1.469-1.469-2.99-1.031-1.49-2.646-1.573-3.219-1.573-1.354 0-2.646.792-3.333.792-.698 0-1.802-.771-2.969-.771-1.531 0-2.948.896-3.74 2.271-1.594 2.771-.417 6.875 1.135 9.125.76 1.104 1.667 2.344 2.854 2.344 1.146 0 1.583-.729 2.979-.729 1.385 0 1.781.729 2.958.729 1.229 0 2.01-1.115 2.771-2.229.875-1.271 1.24-2.51 1.26-2.573-.031-.01-2.458-.948-2.458-3.51ZM14.667 4.635c.677-.823 1.135-1.969 1.01-3.115-1.073.042-2.375.719-3.146 1.615-.688.792-1.292 2.063-1.135 3.167 1.198.094 2.417-.604 3.271-1.667Z"/>
        </svg>
        Download on iOS
      </Button>
    </div>

  </div>
</section>
