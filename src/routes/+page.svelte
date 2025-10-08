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
	title="Building the future of California"
	subtitle="A new city in Solano County creating 53,000 jobs and $16 billion in annual economic impact, restoring the California Dream for the next generation."
	imageSrc="/generated/image-a-modern-office-space-with-a-variety-of-.webp"
	callsToAction={[
		{ href: "/contact", label: "Learn more" },
		{ href: "/about", label: "Our vision" }
	]}
/>
<LogoScroller
	label="Partnering with industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/northropgrumman.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/boeing.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/lockheedmartin.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/rtx.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Building California's future"
	subtitle="A comprehensive vision that addresses affordability, economic opportunity, and sustainable growth for Solano County"
	features={[
		{
			title: "53,000 permanent jobs",
			description:
				"Create a 26% increase in Solano County employment through defense, aerospace, advanced manufacturing, and agricultural technologies. By 2040, generate $16.1 billion in annual economic impact while providing career opportunities that keep families local."
		},
		{
			title: "Affordable homeownership",
			description:
				"Restore the California Dream with binding commitments to build starter homes and integrate all housing types in walkable neighborhoods. End the affordability crisis forcing 81% of Solano parents to watch their children leave the county."
		},
		{
			title: "Travis AFB partnership",
			description:
				"Located 4+ miles from Travis Air Force Base, entirely outside noise and crash zones, with official base support. Strengthen national security through advanced manufacturing jobs, affordable airmen housing, and military spouse employment opportunities."
		},
		{
			title: "Agricultural innovation",
			description:
				"Transform 17,500 acres of non-prime grazing land generating $6 million annually into greenhouses and vertical farms producing $10-40 million per facility. Increase total agricultural output while protecting Solano's prime farmland that generates 98% of county revenue."
		},
		{
			title: "Sustainable infrastructure",
			description:
				"Full water recycling with aquifer recharge, clean energy systems, and fire-resistant building standards create climate-resilient living. Reduce vehicle miles through walkable neighborhoods where children walk to school and seniors maintain independence."
		},
		{
			title: "Community-first development",
			description:
				"Forty-year gradual development plan with $2.39 billion annual construction impact injecting $5,328 per Solano resident. Binding agreements protect existing communities while creating shared prosperity through local job creation and mixed-use neighborhoods."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
