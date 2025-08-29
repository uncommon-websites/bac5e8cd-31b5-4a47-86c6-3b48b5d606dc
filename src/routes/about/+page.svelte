<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Unified workflows",
			description: "Transforming fragmented go-to-market operations into seamless revenue orchestration that actually works."
		},
		{
			title: "RevOps first",
			description: "Built by and for revenue operations teams who know the pain of misrouted leads and broken integrations."
		},
		{
			title: "Visual simplicity",
			description: "Making complex workflow automation accessible through drag-and-drop interfaces your entire team can manage."
		}
	];
</script>

<SecondaryHero
	title="Workflows, not workarounds"
	subtitle="Finally, one place for your go-to-market ops"
	imageSrc="/generated/image-a-modern-team-of-diverse-professionals-c.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Every RevOps manager knows the pain: 20+ hours weekly troubleshooting misrouted leads, stitching together Zapier chains that break at the worst moments, and explaining to sales why hot prospects disappeared into workflow black holes. We started Default because we lived this reality and knew there had to be a better way.",
		"Instead of building another point solution, we reimagined revenue operations from the ground up. Default transforms fragmented go-to-market chaos into unified visual workflows that actually work—combining scheduling, routing, enrichment, and CRM automation in one platform that your entire team can manage without engineering help.",
		"Today, hundreds of fast-growing companies trust Default to power their inbound operations. From Bland AI routing 10,000 leads in six months to OpenPhone cutting speed-to-lead by 67%, we're proving that revenue operations doesn't have to be held together with digital duct tape. The future of RevOps is unified, visual, and built for the teams who live it every day."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and Investors sections removed - no founder/team information available -->

<!-- CTA Section -->
<CallToAction
	title="Stop troubleshooting workflows"
	subtitle="Start orchestrating revenue"
	description="Join hundreds of fast-growing companies who've eliminated 20+ hours of weekly troubleshooting and transformed their go-to-market operations with Default's unified workflow platform."
	imageSrc="/generated/image-a-professional-revops-manager-sits-at-a-.webp"
/>
