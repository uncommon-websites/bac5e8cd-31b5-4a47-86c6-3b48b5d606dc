<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
	
	// Icons
	import IconNetwork from "~icons/lucide/network";
	import IconBot from "~icons/lucide/bot";
	import IconZap from "~icons/lucide/zap";
	import IconUsers from "~icons/lucide/users";
	import IconShield from "~icons/lucide/shield";
	import IconTarget from "~icons/lucide/target";
</script>

<CustomerCardHero
	title="Transform fragmented workflows into unified revenue operations"
	subtitle="Join hundreds of fast-growing companies using Default to automate complex inbound workflows and eliminate broken integrations that waste 20+ hours weekly."
	centered={true}
	customers={[
		{
			name: "Sarah Chen",
			position: "Revenue Operations Manager",
			imageSrc: "/generated/image-a-professional-business-woman-standing-c.webp"
		},
		{
			name: "Michael Rodriguez",
			position: "VP of Growth",
			imageSrc: "/generated/image-a-professional-business-man-in-a-contemp.webp"
		},
		{
			name: "Emily Thompson",
			position: "Director of Marketing Operations",
			imageSrc: "/generated/image-a-professional-business-woman-in-a-sleek.webp"
		},
		{
			name: "David Kim",
			position: "Head of Revenue Operations",
			imageSrc: "/generated/image-a-professional-business-man-in-a-modern-.webp"
		},
		{
			name: "Jessica Martinez",
			position: "Growth Operations Lead",
			imageSrc: "/generated/image-a-professional-business-woman-in-an-eleg.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/posthog.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/attio.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/rootly.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stackblitz.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="The last GTM workflow you'll ever build"
	text="Default consolidates routing, scheduling, enrichment, and CRM automation onto one unified visual canvas—so leads never leak, reps never guess, and RevOps never stress. Say goodbye to 20-hour weeks spent troubleshooting misrouted leads and fragmented Zapier chains."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Sharma",
			position: "Revenue Operations Manager",
			company: "OpenPhone",
			quote:
				"Default eliminated our lead routing chaos completely. We achieved 67% lower speed-to-lead times and 5x less time spent on misrouted leads. Our inbound conversions increased by 17% within the first quarter.",
			image: "/generated/image-a-professional-business-woman-with-a-con.webp"
		},
		{
			name: "Marcus Thompson",
			position: "VP of Growth",
			company: "Runway",
			quote:
				"The results speak for themselves - 400% increase in lead volume and 10x higher GTM efficiency in just 6 months. Default replaced our entire fragmented tool stack with one unified platform that actually works.",
			image: "/generated/image-a-professional-business-man-with-an-air-.webp"
		},
		{
			name: "Alexandra Bennett",
			position: "Director of Marketing Operations",
			company: "Bland AI",
			quote:
				"Default routed 10,000 inbound leads flawlessly in our first 6 months. The workflow builder is intuitive enough that our entire team can create complex automations without engineering support.",
			image: "/generated/image-a-professional-business-woman-exuding-co.webp"
		}
	]}
/>

<Features
	title="Why revenue teams choose Default"
	subtitle="Replace fragmented tool stacks with unified workflow orchestration that eliminates 20+ hours of weekly troubleshooting"
	features={[
		{
			title: "Visual workflow orchestration",
			description: "Replace broken Zapier chains with drag-and-drop canvas workflows that consolidate your entire GTM stack. Eliminate integration fragmentation with multi-player collaboration.",
			icon: IconNetwork
		},
		{
			title: "Native AI qualification agents",
			description: "Automate account research and lead qualification with AI agents built directly into your workflows. No external tools required.",
			icon: IconBot
		},
		{
			title: "Real-time enrichment engine",
			description: "Waterfall through multiple data providers instantly to ensure complete lead profiles. Never miss qualification criteria again.",
			icon: IconZap
		},
		{
			title: "24-hour workflow deployment",
			description: "White glove onboarding gets you from signed contract to deployed workflows in under 24 hours. Implementation in a week, not months.",
			icon: IconUsers
		},
		{
			title: "Enterprise-grade reliability",
			description: "Workflow logs track every step with custom Slack alerts for errors. Built for scale from 2 to 2,000 sales reps.",
			icon: IconShield
		},
		{
			title: "6,000+ native integrations",
			description: "Connect CRMs, sales tools, calendars, and marketing platforms without breaking. One unified platform replaces six fragmented tools.",
			icon: IconTarget
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop losing leads to broken workflows"
	subtitle="Start converting them with Default"
	description="Your RevOps team shouldn't spend 20+ hours weekly fixing misrouted leads and fragmented Zapier chains. Join hundreds of fast-growing companies using Default to eliminate workflow chaos and turn inbound traffic into consistent pipeline."
	imageSrc="/generated/image-a-professional-revenue-operations-manage.webp"
	callsToAction={[
		{
			href: "/demo",
			label: "Book a live demo",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to sales",
			variant: "secondary"
		}
	]}
/>
