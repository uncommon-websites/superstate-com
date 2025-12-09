<script lang="ts">
    const currentYear = new Date().getFullYear();
</script>

<footer class="bg-dark-black text-white pt-24 pb-12 border-t border-white/10 overflow-hidden relative">
    <div class="max-w-[1400px] mx-auto px-6 relative z-10">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-12 mb-24">
            <!-- Links Columns -->
            <div class="md:col-span-2">
                <h4 class="text-xs font-bold tracking-widest text-gray-500 uppercase mb-6">Issuers</h4>
                <ul class="space-y-4">
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Opening Bell</a></li>
                </ul>
            </div>

            <div class="md:col-span-2">
                <h4 class="text-xs font-bold tracking-widest text-gray-500 uppercase mb-6">Investors</h4>
                <ul class="space-y-4">
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Overview</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">USTB</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">USCC</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">All equities</a></li>
                </ul>
            </div>

            <div class="md:col-span-2">
                <h4 class="text-xs font-bold tracking-widest text-gray-500 uppercase mb-6">About</h4>
                <ul class="space-y-4">
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Company</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Newsroom</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Documentation</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Careers</a></li>
                    <li><a href="#" class="text-sm text-gray-400 hover:text-white transition-colors">Terms of Service</a></li>
                </ul>
            </div>

            <!-- Newsletter & Social -->
            <div class="md:col-span-6 md:pl-12">
                <h4 class="text-lg font-medium mb-6">Get Superstate news and updates</h4>
                <div class="flex gap-4 mb-12">
                    <button class="px-8 py-3 rounded-full border border-gray-600 text-sm font-medium hover:border-white transition-colors">
                        Subscribe
                    </button>
                </div>

                <div class="flex gap-4">
                    <a href="#" class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center hover:bg-white/10 transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                    </a>
                    <a href="#" class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center hover:bg-white/10 transition-colors">
                        <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
                    </a>
                </div>
            </div>
        </div>

        <!-- Disclaimer -->
        <div class="border-t border-white/10 pt-12 text-[10px] text-gray-500 leading-relaxed space-y-4 max-w-5xl">
            <p>
                All content available on this Website is general in nature, not directed or tailored to any particular person, and is for informational purposes only. Neither the Website nor any of its content is offered as, nor should be relied on as providing, investment, tax or legal advice or a recommendation to purchase or sell any specific security. The information provided on this Website is not intended for distribution to, or use by, any person or entity in any jurisdiction or country where such distribution or use would be contrary to applicable law or regulation. For more important disclaimers, please visit superstate.com/terms#disclaimers.
            </p>
            <p>
                Superstate Advisers LLC is a registered investment adviser under the Investment Advisers Act of 1940. Information about Superstate can be found by visiting the SEC website adviserinfo.sec.gov and searching for our firm name. Superstate Services LLC is a registered transfer agent with the SEC. Superstate is a registered service mark of Superstate Inc.
            </p>
        </div>
    </div>

    <!-- Big Watermark Text -->
    <div class="absolute bottom-0 left-0 w-full overflow-hidden pointer-events-none opacity-[0.03]">
        <div class="text-[20vw] font-bold leading-none tracking-tighter text-white whitespace-nowrap select-none transform translate-y-[20%]">
            Superstate
        </div>
    </div>
</footer>
