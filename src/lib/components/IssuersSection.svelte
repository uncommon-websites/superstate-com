<script lang="ts">
    // Issuers section - Light background
</script>

<section id="issuers" class="bg-off-white w-full">
    <div class="flex flex-col md:flex-row min-h-[600px]">
        <!-- Left Content -->
        <div class="w-full md:w-1/2 p-12 md:p-20 flex flex-col justify-center border-r border-gray-200">
            <div class="flex items-center gap-2 mb-8 text-xs font-semibold tracking-widest text-gray-500 uppercase">
                <span class="w-3 h-3 border border-gray-400 rounded-sm"></span>
                Issuers
            </div>
            
            <h2 class="text-4xl md:text-5xl font-medium text-gray-900 mb-10 leading-tight">
                Tokenize your stock on Ethereum, Solana, and other major blockchains
            </h2>
            
            <div>
                <button class="px-6 py-3 rounded-full border border-gray-300 text-sm font-medium hover:bg-gray-900 hover:text-white hover:border-gray-900 transition-all">
                    Learn more
                </button>
            </div>
        </div>

        <!-- Right Visual -->
        <div class="w-full md:w-1/2 bg-gray-100 relative overflow-hidden">
             <!-- Abstract Paper Graphic Simulation -->
             <div class="absolute inset-0 flex items-center justify-center">
                <!-- We'll use CSS shadows and gradients to create the "folded paper" look -->
                <div class="relative w-full h-full">
                    <!-- Paper Sheet 1 -->
                    <div class="absolute top-0 right-0 w-2/3 h-full bg-gradient-to-l from-white to-gray-200 shadow-[-20px_0_40px_rgba(0,0,0,0.05)] transform skew-x-[-5deg] origin-bottom-right"></div>
                    <!-- Paper Sheet 2 -->
                    <div class="absolute top-0 right-[30%] w-1/2 h-full bg-gradient-to-l from-gray-50 to-gray-300 shadow-[-20px_0_40px_rgba(0,0,0,0.08)] transform skew-x-[-10deg] origin-bottom-right"></div>
                    <!-- Paper Sheet 3 (Curved) -->
                    <div class="absolute bottom-0 left-0 w-full h-1/2 bg-gradient-to-t from-gray-200 to-transparent opacity-20"></div>
                </div>
             </div>
        </div>
    </div>
</section>
