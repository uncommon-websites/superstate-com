<script lang="ts">
    const newsItems = [
        {
            source: "BARRON'S",
            type: "PRESS",
            date: "09.03.25",
            title: "Galaxy Digital Tokenizes Its Stock. It Won't Be the Last.",
            link: "#"
        },
        {
            source: "GALAXY BRAINS PODCAST",
            type: "PRESS",
            date: "09.03.25",
            title: "Tokenizing GLXY with Robert Leshner.",
            link: "#"
        },
        {
            source: "THE BLOCK",
            type: "PRESS",
            date: "08.27.25",
            title: "Aave Labs launches Horizon, offering institutional stablecoin borrowing against tokenized RWAs",
            link: "#"
        },
        {
            source: "", // Internal Blog
            type: "BLOG",
            date: "09.03.25",
            title: "Galaxy Stock Becomes First SEC-Registered Equity Tokenized on a Major Blockchain",
            link: "#"
        },
        {
            source: "", // Internal Blog
            type: "BLOG",
            date: "07.22.25",
            title: "Solana and Plume: The First Step in Superstate's Multichain Expansion",
            link: "#"
        },
        {
            source: "", // Internal Blog
            type: "BLOG",
            date: "07.16.25",
            title: "Smart Contract Upgrade: Enhanced Access Control with AllowlistV3",
            link: "#"
        }
    ];
</script>

<section class="bg-off-white py-24 border-b border-gray-200">
    <div class="max-w-[1400px] mx-auto px-6">
        <div class="flex items-center justify-between mb-16">
            <h2 class="text-3xl md:text-4xl font-medium text-gray-900">Superstate latest news and updates</h2>
            <button class="px-6 py-2 rounded-full border border-gray-300 text-sm font-medium hover:bg-gray-900 hover:text-white hover:border-gray-900 transition-all hidden md:block">
                View all
            </button>
        </div>

        <!-- Grid with 1px gap for borders -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-[1px] bg-gray-200 border border-gray-200">
            {#each newsItems as item}
                <a href={item.link} class="group block p-8 bg-off-white hover:bg-white transition-colors relative h-full flex flex-col justify-between">
                    
                    <div class="mb-8">
                        <div class="flex items-center justify-between mb-12 text-[10px] font-bold tracking-widest text-gray-500 uppercase h-4">
                            {#if item.source}
                                <span>{item.source}</span>
                            {:else}
                                <span></span> <!-- Spacer -->
                            {/if}
                            <span>{item.type}</span>
                        </div>
                        
                        <div class="text-xs text-gray-500 mb-4 font-mono">{item.date}</div>
                        
                        <h3 class="text-2xl font-medium text-gray-900 leading-tight group-hover:text-gray-600 transition-colors">
                            {item.title}
                        </h3>
                    </div>

                    <div class="flex items-center text-sm font-medium text-gray-900 group-hover:translate-x-1 transition-transform">
                        Read
                        <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                    </div>
                </a>
            {/each}
        </div>
        
        <div class="mt-8 md:hidden">
             <button class="w-full px-6 py-3 rounded-full border border-gray-300 text-sm font-medium hover:bg-gray-900 hover:text-white hover:border-gray-900 transition-all">
                View all
            </button>
        </div>
    </div>
</section>
