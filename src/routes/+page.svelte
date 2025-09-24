<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconRadar from "~icons/lucide/radar";
	import IconTarget from "~icons/lucide/target";
	import IconShield from "~icons/lucide/shield";
	import IconSettings from "~icons/lucide/settings";
	import IconFileText from "~icons/lucide/file-text";
	import IconZap from "~icons/lucide/zap";
</script>

<CenteredTextOnlyHero
	title="Neutralize drone threats within seconds"
	subtitle="Acoustic detection arrays combined with AI-powered kinetic interception systems protect critical infrastructure from drone intrusions that current solutions miss."
	imageSrc="/generated/image-straight-on-eye-level-view-of-a-small-in.webp"
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/boeing.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/lockheedmartin.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/rtx.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/gd.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Rodriguez",
			position: "Security Director",
			company: "Regional Airport Authority",
			quote:
				"Sentradel's acoustic detection caught three drone intrusions that our $400K radar system completely missed. We've prevented two potential runway shutdowns that would have cost us $2.3M in delays and diversions.",
			image: "/generated/image-professional-headshot-of-marcus-rodrigue.webp"
		},
		{
			name: "Sarah Chen",
			position: "Operations Manager",
			company: "Pacific Energy Solutions",
			quote:
				"Since installing Sentradel's system six months ago, we've eliminated 14 unauthorized drone flyovers of our power substation. Their 8-second response time gives us the protection we need without the $500K+ price tag of legacy systems.",
			image: "/generated/image-professional-headshot-of-sarah-chen-asia.webp"
		},
		{
			name: "David Thompson",
			position: "Chief Security Officer",
			company: "Metropolitan Correctional Facility",
			quote:
				"Contraband drops via drone were a weekly nightmare costing us thousands in investigations. Sentradel's kinetic interception system has stopped 23 attempts this year, with zero false positives. Our incident reports dropped 89%.",
			image: "/generated/image-photorealistic-professional-headshot-of-.webp"
		}
	]}
/>

<Features
	title="Advanced counter-drone technology"
	subtitle="Protecting critical infrastructure with acoustic detection and AI-powered kinetic interception systems that neutralize threats within seconds."
	features={[
		{
			title: "Acoustic detection arrays",
			description:
				"Bypass jamming vulnerabilities that plague existing radar solutions with our proprietary acoustic sensor networks that detect drone signatures at extended ranges.",
			icon: IconRadar
		},
		{
			title: "AI-powered kinetic interception",
			description:
				"Autonomous targeting systems combine machine learning with precision mechanics to neutralize drone threats before they reach critical infrastructure.",
			icon: IconTarget
		},
		{
			title: "Critical infrastructure protection",
			description:
				"Purpose-built for airports, prisons, and power plants with specialized threat profiles and regulatory compliance requirements for each facility type.",
			icon: IconShield
		},
		{
			title: "Switchable non-lethal payloads",
			description:
				"Address liability concerns with configurable interception methods including nets, electronic disruption, and containment systems for safe threat neutralization.",
			icon: IconSettings
		},
		{
			title: "Real-time incident reporting",
			description:
				"Comprehensive logging and automated reporting systems provide immediate documentation for security teams and regulatory compliance requirements.",
			icon: IconFileText
		},
		{
			title: "Sub-second response time",
			description:
				"Transform detected threats into neutralized targets within seconds using optimized processing pipelines that outperform traditional counter-drone systems.",
			icon: IconZap
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
