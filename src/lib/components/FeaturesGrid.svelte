<script lang="ts">
    const features = [
        {
            id: '01',
            title: 'Official shares, tokenized',
            description: 'Tokenized shares are the same shares that trade on traditional exchanges like the Nasdaq or NYSE. They are not derivatives, wrappers, or new share classes.'
        },
        {
            id: '02',
            title: 'Global market access',
            description: 'Reach investors worldwide in supported jurisdictions through 24/7 onchain decentralized trading. Enable peer-to-peer transfer and instant settlement within a compliant framework.'
        },
        {
            id: '03',
            title: 'Built-in compliance',
            description: 'Token-level permissioning, allowlisted wallets, and programmatically-enforced restrictions on every transaction.'
        }
    ];
</script>

<section class="bg-off-white py-20 border-t border-gray-200">
    <div class="max-w-[1400px] mx-auto px-6">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12 md:gap-8">
            {#each features as feature}
                <div class="flex flex-col gap-4 pr-8 border-r border-gray-200 last:border-0">
                    <span class="text-gray-500 text-sm mb-2">{feature.id}</span>
                    <h3 class="text-xl font-medium text-gray-900">{feature.title}</h3>
                    <p class="text-gray-600 text-sm leading-relaxed max-w-sm">
                        {feature.description}
                    </p>
                </div>
            {/each}
        </div>
    </div>
</section>
