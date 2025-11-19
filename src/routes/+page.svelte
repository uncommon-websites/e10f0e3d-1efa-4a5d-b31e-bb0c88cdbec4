<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Adviser-grade intelligence for the art market"
	subtitle="Transform fragmented art market data into predictive insights. Artsignal empowers collectors and advisers with comprehensive intelligence that was once accessible only to industry insiders."
	imageSrc="/generated/image-a-sophisticated-private-art-advisory-roo.webp"
/>
<LogoScroller
	label="Trusted by leading art market players"
	logoUrls={[
		'https://cdn.brandfetch.io/christies.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/gagosian.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hauserwirth.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/whitecube.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Intelligence that scales expertise"
	text="Artsignal synthesizes auction results, exhibition histories, and cultural sentiment into comprehensive artist reports and market forecasts. We serve collectors building meaningful collections and advisers managing client portfolios, delivering the systematic intelligence once available only through decades of specialist experience.\n\nOur agentic AI platform processes fragmented data from across the $68B art market, revealing emerging artists before mainstream breakthrough and identifying shifting collector preferences in real-time."
/>

<Testimonials
	testimonials={[
		{
			name: "Elena Karavas",
			position: "Independent Art Adviser",
			company: "Karavas Art Advisory",
			quote:
				"Artsignal cut my research time from three days to three hours per artist report. The comprehensive market data and exhibition histories I once pieced together from dozens of sources are now synthesized instantly, letting me focus on strategic advice for my collectors.",
			image: "/generated/image-a-professional-greek-woman-art-adviser-i.webp"
		},
		{
			name: "Marcus Chen",
			position: "Gallery Director",
			company: "Chen Contemporary",
			quote:
				"We avoided a costly acquisition misstep when Artsignal's sentiment analysis revealed shifting collector interest before it hit auction results. The platform's predictive intelligence has become essential for inventory decisions and artist representation strategy.",
			image: "/generated/image-a-professional-chinese-man-gallery-direc.webp"
		},
		{
			name: "Sophie Beaumont",
			position: "Private Collector",
			company: "Beaumont Collection",
			quote:
				"I no longer need to maintain relationships with multiple specialists to understand emerging markets. Artsignal provides the adviser-grade intelligence I need to build my collection with confidence, identifying artists eighteen months before mainstream recognition.",
			image: "/generated/image-a-professional-french-woman-art-collecto.webp"
		}
	]}
/>

<Features
	title="Intelligence that transforms how you collect"
	subtitle="Artsignal delivers predictive insights that were once accessible only to the world's most sophisticated collectors and advisers"
	features={[
		{
			title: "Predictive market intelligence",
			description:
				"Move beyond historical data with AI-driven forecasts that reveal emerging trends before they reach the mainstream. Our agentic AI platform analyzes decades of collecting expertise to predict artist trajectories and market movements with unprecedented accuracy."
		},
		{
			title: "Comprehensive data integration",
			description:
				"Access the complete picture with intelligence synthesized from auction results, exhibition histories, media coverage, and sentiment data. We transform fragmented information across the art market into unified, actionable insights."
		},
		{
			title: "Adviser-grade reports",
			description:
				"Receive institutional-quality artist reports including biographies, market outlooks, and valuation analysis. Democratizing access to sophisticated intelligence that was previously available only through expensive private advisers."
		},
		{
			title: "Real-time market signals",
			description:
				"Identify shifting collector preferences and emerging opportunities as they unfold. Our platform monitors all market stakeholders simultaneously to surface insights that keep you ahead of the curve."
		},
		{
			title: "Artist discovery engine",
			description:
				"Discover rising talent before their mainstream breakthrough with AI-powered recommendations. Our system identifies similar artists and reveals connections that expand your collecting horizons."
		},
		{
			title: "Transparent data sourcing",
			description:
				"Build confidence with clear visibility into where our intelligence comes from and how it's analyzed. In an historically opaque market, we earn trust through transparency in every insight we deliver."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start collecting with confidence"
	subtitle="Join forward-thinking collectors"
	description="Access the same predictive intelligence that once required decades of specialist expertise and insider connections. Artsignal provides transparent, adviser-grade insights that empower you to build your collection with conviction—whether you're discovering your first acquisition or expanding an established portfolio."
	imageSrc="/generated/image-a-confident-professional-art-collector-w.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Request early access",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Schedule a demo",
			variant: "secondary"
		}
	]}
/>
