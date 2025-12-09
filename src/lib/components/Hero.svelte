<script lang="ts">
    // Hero section with dark background and abstract wave
</script>

<section class="relative min-h-[90vh] bg-dark-black text-white flex flex-col justify-center overflow-hidden pt-20">
    <!-- Grid Background -->
    <div class="absolute inset-0 opacity-20 pointer-events-none" 
         style="background-image: linear-gradient(#333 1px, transparent 1px), linear-gradient(90deg, #333 1px, transparent 1px); background-size: 50px 50px;">
    </div>

    <!-- Abstract Wave Graphic Placeholder -->
    <!-- In a real scenario, this would be a WebGL canvas or a high-res image/video. 
         We will simulate it with CSS gradients and shapes for now. -->
    <div class="absolute inset-0 pointer-events-none overflow-hidden">
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[150%] h-[150%] opacity-40 blur-3xl rounded-full bg-gradient-to-br from-gray-800 via-gray-900 to-black"></div>
        
        <!-- Simulated Wave - Using multiple radial gradients to create depth -->
        <div class="absolute bottom-0 left-0 right-0 h-[60vh] opacity-30 bg-gradient-to-t from-gray-800 to-transparent"></div>
        
        <!-- A more specific shape to mimic the ribbon -->
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[80vw] h-[40vh] border-[1px] border-white/10 rounded-[100%] transform -rotate-12 scale-150 opacity-20 blur-sm"></div>
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[70vw] h-[35vh] border-[1px] border-white/10 rounded-[100%] transform -rotate-6 scale-150 opacity-20 blur-sm"></div>
        
        <!-- Dark overlay at bottom to blend into next section if needed, though next section is light -->
    </div>

    <div class="relative z-10 max-w-4xl mx-auto px-6 text-center">
        <h1 class="text-5xl md:text-7xl font-medium tracking-tight leading-[1.1] mb-8">
            Superstate is reshaping<br />capital markets
        </h1>
        <p class="text-lg md:text-xl text-gray-400 max-w-2xl mx-auto leading-relaxed">
            We connect financial assets with crypto capital markets through onchain public listings and tokenized investment products.
        </p>
    </div>
</section>
