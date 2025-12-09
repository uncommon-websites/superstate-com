<script lang="ts">
    const equities = [
        {
            name: 'Galaxy Digital Inc.',
            ticker: 'GLXY',
            icon: 'galaxy' // Placeholder for logic
        },
        {
            name: 'SharpLink Gaming, Inc.',
            ticker: 'SBET',
            icon: 'sharplink'
        },
        {
            name: 'Forward Industries, Inc.',
            ticker: 'FWDI',
            icon: 'forward'
        },
        {
            name: 'Exodus Movement, Inc.',
            ticker: 'EXOD',
            icon: 'exodus'
        }
    ];
</script>

<section class="bg-dark-black text-white pb-24 border-b border-white/10">
    <div class="max-w-[1400px] mx-auto px-6">
        <div class="mb-12">
            <h2 class="text-3xl font-medium mb-4">Tokenized equities</h2>
            <p class="text-gray-400 font-mono text-sm tracking-tight max-w-3xl">
                Invest in the official tokenized shares of public companies that you can hold, trade, and use as collateral onchain.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4">
            {#each equities as equity}
                <div class="bg-[#111] border border-white/10 rounded-sm p-6 flex items-center gap-4 hover:border-white/30 transition-colors cursor-pointer group">
                    <!-- Icon Placeholder -->
                    <div class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center text-gray-400 group-hover:text-white transition-colors">
                        {#if equity.icon === 'galaxy'}
                            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="8"></circle></svg>
                        {:else if equity.icon === 'sharplink'}
                             <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path></svg>
                        {:else if equity.icon === 'forward'}
                             <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M13 5l7 7-7 7M5 5l7 7-7 7"></path></svg>
                        {:else}
                             <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path></svg>
                        {/if}
                    </div>
                    
                    <div class="flex flex-col">
                        <span class="text-sm font-medium text-gray-200 group-hover:text-white transition-colors">{equity.name}</span>
                        <span class="text-xs text-gray-500">{equity.ticker}</span>
                    </div>
                </div>
            {/each}
        </div>
    </div>
</section>
