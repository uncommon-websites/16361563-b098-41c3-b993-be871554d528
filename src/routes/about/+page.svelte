<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Mission-critical reliability",
			description: "Every threat matters. Our systems are built to never fail when lives and critical infrastructure depend on them."
		},
		{
			title: "Real-world engineering",
			description: "We solve problems that matter, building solutions tested under actual threat conditions by people who've lived the problem."
		},
		{
			title: "Acoustic advantage",
			description: "While others chase fragile signals, we listen to what can't be jammed, delivering detection that works when everything else fails."
		},
		{
			title: "Rapid response",
			description: "Seconds matter in threat neutralization. Our AI-powered systems react faster than human operators while maintaining precision."
		}
	];
</script>

<SecondaryHero
	title="Protecting critical infrastructure"
	subtitle="through autonomous drone defense technology"
	imageSrc="/generated/image-professional-executive-headshot-of-a-con.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Sentradel was founded by engineers who experienced drone threats firsthand and understood the critical gaps in existing defense systems. Traditional counter-drone solutions cost over $500K and still miss 40% of threats.",
		"Our breakthrough combines acoustic detection arrays with AI-powered kinetic interception systems, bypassing the jamming vulnerabilities that plague existing solutions. We transform drone threats into neutralized targets within seconds.",
		"Starting with critical infrastructure protection at airports, prisons, and power plants, we're capturing the $3.5B counter-drone market. Our acoustic detection technology provides reliable threat identification that radio-based systems simply cannot match.",
		"We understand that security directors need solutions that work reliably in real-world scenarios. Our switchable non-lethal payloads and comprehensive incident reporting address liability concerns while maintaining operational effectiveness."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Leaders in autonomous drone defense."
	stakeholders={[
		{
			name: "Cameron Rowe",
			position: "Founder & CEO",
			bio: "Lead engineer with hands-on experience dealing with drone threats, bringing deep technical insight into the vulnerabilities that need protection.",
			image: "/generated/image-professional-executive-headshot-of-a-con.webp"
		},
		{
			name: "Anshul Singh",
			position: "Founder & COO",
			bio: "Former DeDrone Special Projects Operator who understands the limitations of existing counter-drone solutions and what actually works in real-world scenarios.",
			image: "/generated/image-professional-executive-headshot-of-a-dec.webp"
		},
		{
			name: "Stefan Spain",
			position: "Founder & CTO",
			bio: "Expert in embedded systems robotics and mechatronics, providing the technical foundation for autonomous turret systems and sensor integration.",
			image: "/generated/image-professional-executive-headshot-of-a-tho.webp"
		}
	]}
/>

<!-- Investors section removed - no specific investors mentioned in company context -->

<!-- CTA Section -->
<CallToAction
	title="Secure your facility"
	subtitle="before the next threat"
	description="While legacy systems miss 40% of drone threats and cost $500K+, Sentradel installs in days with acoustic detection that bypasses jamming. Join 500+ critical infrastructure facilities already protected."
	imageSrc="/generated/image-a-diverse-security-team-of-five-adults-c.webp"
/>
