<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6" id="about">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-sans font-bold mb-12 leading-tight">
					Built by PE and consulting<br />
					<span class="text-primary-500">veterans</span>
				</h2>

				<div class="space-y-8">
					<div>
						<div class="flex items-center gap-3 text-primary-400 font-semibold mb-3">
							<div class="w-2 h-2 bg-primary-400 rounded-sm"></div>
							Frederik Kofoed Hansen, CEO
						</div>
						<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1">
							6+ years at Blackstone leading commercial due diligence across major deals. Experienced firsthand the slow, expensive traditional process and knows exactly where investors lose time and money.
						</p>
					</div>

					<div>
						<div class="flex items-center gap-3 text-primary-400 font-semibold mb-3">
							<div class="w-2 h-2 bg-primary-400 rounded-sm"></div>
							Soren Biltoft-Knudsen, President
						</div>
						<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1">
							Executed 40+ commercial due diligences at BCG. Deep pattern recognition across industries shows him exactly how to compress weeks into days without sacrificing quality.
						</p>
					</div>

					<div>
						<div class="flex items-center gap-3 text-primary-400 font-semibold mb-3">
							<div class="w-2 h-2 bg-primary-400 rounded-sm"></div>
							Harshil Rastogi, CTO
						</div>
						<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1">
							Built AI systems at Google Ads detecting fraud at massive scale. 10 years building production systems means he knows how to ship AI that investors can actually trust.
						</p>
					</div>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative bg-gradient-to-br from-primary-950 to-black border border-white/10 flex items-center justify-center">
                     <!-- Professional business setting placeholder -->
                     <div class="text-center p-12">
                         <div class="text-6xl mb-4 opacity-20">🤝</div>
                         <div class="text-gray-500 text-sm">Combined 20+ years experience</div>
                         <div class="text-gray-600 text-xs mt-2">Blackstone • BCG • Google</div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>
