<script lang="ts">
    // CTA Section
</script>

<section class="bg-dark-black text-white py-24 border-t border-white/10 relative overflow-hidden">
    <!-- Background Abstract Shape -->
    <div class="absolute top-0 right-0 w-1/2 h-full opacity-10 pointer-events-none">
        <!-- Using a large SVG or div to simulate the dark gear/coin shape in the background -->
        <div class="absolute top-1/2 right-0 -translate-y-1/2 translate-x-1/4 w-[800px] h-[800px] bg-gray-800 rounded-full blur-3xl opacity-20"></div>
        <svg class="absolute top-1/2 right-0 -translate-y-1/2 translate-x-1/4 w-[600px] h-[600px] text-gray-800" viewBox="0 0 100 100" fill="currentColor">
            <path d="M50 0 C22.4 0 0 22.4 0 50 C0 77.6 22.4 100 50 100 C77.6 100 100 77.6 100 50 C100 22.4 77.6 0 50 0 Z M50 80 C33.4 80 20 66.6 20 50 C20 33.4 33.4 20 50 20 C66.6 20 80 33.4 80 50 C80 66.6 66.6 80 50 80 Z" />
        </svg>
    </div>

    <div class="max-w-[1400px] mx-auto px-6 relative z-10">
        <h2 class="text-4xl md:text-5xl font-medium mb-16">Get started with Superstate</h2>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 border-t border-white/10 pt-12">
            <!-- Issuers Column -->
            <div class="pr-8 md:border-r md:border-white/10">
                <div class="flex items-center gap-2 mb-6 text-xs font-semibold tracking-widest text-gray-400 uppercase">
                    <span class="w-3 h-3 border border-gray-600 rounded-sm"></span>
                    Issuers
                </div>
                <h3 class="text-2xl font-medium mb-8">Tokenize your company's stock onchain</h3>
                <button class="px-6 py-3 rounded-full bg-white text-black text-sm font-medium hover:bg-gray-200 transition-colors">
                    Contact us
                </button>
            </div>

            <!-- Investors Column -->
            <div class="pl-0 md:pl-8">
                 <div class="flex items-center gap-2 mb-6 text-xs font-semibold tracking-widest text-gray-400 uppercase">
                    <span class="w-3 h-3 border border-gray-600 rounded-sm"></span>
                    Investors
                </div>
                <h3 class="text-2xl font-medium mb-8">Start investing in tokenized stocks and funds</h3>
                <button class="px-6 py-3 rounded-full bg-white text-black text-sm font-medium hover:bg-gray-200 transition-colors">
                    Register
                </button>
            </div>
        </div>
    </div>
</section>
