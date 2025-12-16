<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20" id="platform">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-sans font-bold mb-6">
				How DiligenceSquared<br />
				transforms due diligence
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				AI-moderated interviews, automated synthesis, and interactive reports deliver investor-grade insights in days.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: AI Interviews -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">AI-Moderated Interviews</h3>
					<p class="text-gray-400 text-sm">Conduct hundreds of expert interviews simultaneously in multiple languages</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex items-center justify-center">
                         <!-- Interview representation -->
                         <div class="w-full h-full border border-white/5 rounded-lg bg-[#0a0a0a] p-6 relative">
                             <div class="space-y-4">
                                 <div class="flex items-start gap-3">
                                     <div class="w-8 h-8 rounded-full bg-primary-500/20 flex items-center justify-center text-primary-400 text-xs font-bold shrink-0">AI</div>
                                     <div class="bg-white/5 rounded-lg p-3 flex-1">
                                         <p class="text-xs text-gray-400">Can you describe your experience with the product's key features?</p>
                                     </div>
                                 </div>
                                 <div class="flex items-start gap-3 flex-row-reverse">
                                     <div class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center text-white text-xs font-bold shrink-0">EX</div>
                                     <div class="bg-primary-500/10 rounded-lg p-3 flex-1 border border-primary-500/20">
                                         <p class="text-xs text-gray-300">The integration capabilities were particularly valuable for our workflow...</p>
                                     </div>
                                 </div>
                                 <div class="flex items-start gap-3">
                                     <div class="w-8 h-8 rounded-full bg-primary-500/20 flex items-center justify-center text-primary-400 text-xs font-bold shrink-0">AI</div>
                                     <div class="bg-white/5 rounded-lg p-3 flex-1">
                                         <p class="text-xs text-gray-400">What specific integration features did you find most useful?</p>
                                     </div>
                                 </div>
                             </div>
                             <div class="absolute bottom-6 left-6 right-6 text-center">
                                 <div class="text-[10px] text-gray-600 bg-black/50 rounded px-3 py-1.5 inline-block">
                                     Interview 47 of 120 • English • 12:34 elapsed
                                 </div>
                             </div>
                         </div>
                    </div>
                </div>
			</div>

			<!-- Card 2: Synthesis -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Automated Synthesis</h3>
					<p class="text-gray-400 text-sm">AI extracts and organizes insights with full source traceability</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <!-- Key Findings -->
                    <div class="space-y-3 mb-6">
                        <div class="bg-primary-500/10 p-4 rounded border border-primary-500/20">
                            <div class="text-xs text-primary-300 mb-2 font-semibold">KEY FINDING</div>
                            <div class="text-sm text-white mb-2">Strong product-market fit in enterprise segment</div>
                            <div class="flex gap-2 flex-wrap">
                                <span class="text-[9px] bg-white/10 px-2 py-0.5 rounded text-gray-400">Source: 23 interviews</span>
                                <span class="text-[9px] bg-white/10 px-2 py-0.5 rounded text-gray-400">Confidence: High</span>
                            </div>
                        </div>
                        <div class="bg-white/5 p-4 rounded border border-white/10">
                            <div class="text-xs text-gray-400 mb-2 font-semibold">INSIGHT</div>
                            <div class="text-sm text-white mb-2">Integration capabilities drive purchasing decisions</div>
                            <div class="flex gap-2 flex-wrap">
                                <span class="text-[9px] bg-white/10 px-2 py-0.5 rounded text-gray-400">Source: 18 interviews</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Chart -->
                    <div class="flex-1 w-full relative mt-4 bg-[#111] rounded border border-white/5 p-4">
                         <div class="text-[10px] text-gray-500 mb-2">Sentiment Analysis</div>
                         <svg class="w-full h-full overflow-visible" viewBox="0 0 100 50" preserveAspectRatio="none">
                             <!-- Grid lines -->
                             <line x1="0" y1="10" x2="100" y2="10" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="25" x2="100" y2="25" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="40" x2="100" y2="40" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             
                             <!-- Bar chart representation -->
                             <rect x="10" y="20" width="8" height="30" fill="oklch(0.696 0.17 162.48)" opacity="0.8" />
                             <rect x="25" y="15" width="8" height="35" fill="oklch(0.696 0.17 162.48)" opacity="0.8" />
                             <rect x="40" y="25" width="8" height="25" fill="oklch(0.696 0.17 162.48)" opacity="0.8" />
                             <rect x="55" y="10" width="8" height="40" fill="oklch(0.696 0.17 162.48)" opacity="0.8" />
                             <rect x="70" y="18" width="8" height="32" fill="oklch(0.696 0.17 162.48)" opacity="0.8" />
                         </svg>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6" id="how-it-works">
			<!-- Card 3: Interactive Reports -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Interactive Reports</h3>
					<p class="text-gray-400 text-sm">Every finding links back to source conversations</p>
				</div>
                
                 <!-- Mockup Content - Report Preview -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4 text-[10px] leading-relaxed text-gray-400">
                    <div class="space-y-3">
                        <div class="border-b border-white/5 pb-2">
                            <div class="text-white font-semibold text-xs mb-1">Executive Summary</div>
                            <div class="text-gray-500 text-[9px]">Market Intelligence Report</div>
                        </div>
                        <div class="space-y-2">
                            <div class="bg-white/5 p-2 rounded">
                                <div class="text-white text-[10px] mb-1">Market size estimated at $2.3B</div>
                                <div class="text-primary-400 text-[8px] cursor-pointer hover:underline">→ View 15 supporting quotes</div>
                            </div>
                            <div class="bg-white/5 p-2 rounded">
                                <div class="text-white text-[10px] mb-1">Strong competitive moat identified</div>
                                <div class="text-primary-400 text-[8px] cursor-pointer hover:underline">→ View 8 supporting quotes</div>
                            </div>
                            <div class="bg-white/5 p-2 rounded">
                                <div class="text-white text-[10px] mb-1">Customer retention rate 85%+</div>
                                <div class="text-primary-400 text-[8px] cursor-pointer hover:underline">→ View 12 supporting quotes</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Quality Assurance -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Expert Review</h3>
					<p class="text-gray-400 text-sm">Top-tier consultants validate all findings</p>
				</div>
                
                 <!-- Mockup Content - Quality Check -->
                <div class="flex-1 relative flex flex-col gap-3">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-xl p-4 flex-1">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="w-6 h-6 rounded-full bg-green-500/20 flex items-center justify-center">
                                <svg class="w-3 h-3 text-green-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            <span class="text-xs text-green-400 font-semibold">Validated by Expert</span>
                        </div>
                        <div class="space-y-2 text-[10px] text-gray-400">
                            <div class="flex items-center gap-2">
                                <div class="w-1 h-1 bg-gray-600 rounded-full"></div>
                                <span>Data completeness verified</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <div class="w-1 h-1 bg-gray-600 rounded-full"></div>
                                <span>Source traceability confirmed</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <div class="w-1 h-1 bg-gray-600 rounded-full"></div>
                                <span>Insights cross-referenced</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-[#1a1a1a] border border-primary-500/30 rounded-xl p-4">
                        <div class="text-[10px] text-gray-400 mb-2">Reviewed by</div>
                        <div class="text-xs text-white font-medium">Former BCG Principal</div>
                        <div class="text-[9px] text-gray-500 mt-1">15+ years CDD experience</div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Speed -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Rapid Delivery</h3>
					<p class="text-gray-400 text-sm">From kickoff to final report in days</p>
				</div>
                
                 <!-- Mockup Content - Timeline -->
                <div class="flex-1 relative flex flex-col justify-center">
                    <div class="space-y-4">
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-primary-500 flex items-center justify-center text-white text-xs font-bold shrink-0">1</div>
                            <div class="flex-1">
                                <div class="text-sm text-white font-medium">Scope & Setup</div>
                                <div class="text-[10px] text-gray-500">Day 1</div>
                            </div>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-primary-500 flex items-center justify-center text-white text-xs font-bold shrink-0">2</div>
                            <div class="flex-1">
                                <div class="text-sm text-white font-medium">AI Interviews</div>
                                <div class="text-[10px] text-gray-500">Days 2-4</div>
                            </div>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-primary-500 flex items-center justify-center text-white text-xs font-bold shrink-0">3</div>
                            <div class="flex-1">
                                <div class="text-sm text-white font-medium">Synthesis & Review</div>
                                <div class="text-[10px] text-gray-500">Day 5</div>
                            </div>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-green-500 flex items-center justify-center text-white text-xs font-bold shrink-0">✓</div>
                            <div class="flex-1">
                                <div class="text-sm text-white font-medium">Delivery</div>
                                <div class="text-[10px] text-gray-500">Day 5-7</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>
