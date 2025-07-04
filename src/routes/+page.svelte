<script lang="ts">
	// Components
	import UseCases from "$lib/components/layout/UseCases.svelte";
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Build ideas fast"
	subtitle="We design, build, and ship products in days"
	imageSrc="/generated/image-a-group-of-early-stage-startup-entrepren.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by innovative companies"
	logoUrls={[
		'https://logo.clearbit.com/notion.so',
		'https://logo.clearbit.com/figma.com',
		'https://logo.clearbit.com/airtable.com',
		'https://logo.clearbit.com/canva.com'
	]}
/>

<Summary
	title="What we do"
	text="We design, implement, and ship early-stage products rapidly for startups and entrepreneurs. Our streamlined process accelerates product development from months to days. We handle everything from design to launch, helping you validate ideas and get to market faster."
/>

<Testimonials
	testimonials={[
		{
			name: "Zara Hendricks",
			position: "Founder & CEO",
			company: "VelocityTech",
			quote:
				"Envel compressed our 6-month product timeline into 8 days. We launched two weeks ahead of our biggest competitor and secured early market advantage that translated into $2M in pre-orders.",
			image: "/generated/image-a-professional-woman-entrepreneur-standi.webp"
		},
		{
			name: "Kai Nakamura",
			position: "CTO",
			company: "FlowState Labs",
			quote:
				"Building in-house would have been a $200K gamble with uncertain outcomes. Envel eliminated the technical risk entirely and delivered a validated MVP for under $15K that immediately attracted investor interest.",
			image: "/generated/image-a-young-male-entrepreneur-in-a-creative-.webp"
		},
		{
			name: "Reese Pemberton",
			position: "VP of Product",
			company: "Nexus Dynamics",
			quote:
				"Instead of hiring a $180K developer for 6 months, we spent $12K with Envel and had our product live in one week. The ROI was immediate and the speed-to-market advantage was game-changing.",
			image: "/generated/image-a-female-executive-in-a-sophisticated-bu.webp"
		}
	]}
/>

<Features
	title="Why choose Envel"
	subtitle="Accelerating product development with proven solutions"
	features={[
		{
			title: "Lightning fast delivery",
			description:
				"Ship quality products in days, not months, with our accelerated development process designed specifically for early-stage ventures."
		},
		{
			title: "End-to-end product development",
			description:
				"From initial design concepts to full implementation and launch, we handle every aspect of bringing your product to market."
		},
		{
			title: "Early-stage expertise",
			description:
				"Built for startups and entrepreneurs who need rapid validation and quick market entry to test ideas and secure early users."
		}
	]}
/>

<UseCases
	title="Use Cases"
	subtitle="Real-world applications for your business needs"
	useCases={[
		{
			title: "Transform ideas into products",
			description: "Stop spending months planning and start building. We take your concept from idea to deployed product in days, letting you test market demand while your competitors are still planning.",
			image: "/generated/image-a-startup-founder-is-enthusiastically-pr.webp",
			link: {
				href: "/use-cases/idea-to-product",
				label: "Learn more"
			}
		},
		{
			title: "Accelerate feature development",
			description: "Need a new feature but don't want to slow down your core product? We rapidly develop and integrate new functionality so your team can stay focused on what matters most.",
			image: "/generated/image-a-group-of-software-developers-is-gather.webp",
			link: {
				href: "/use-cases/feature-acceleration",
				label: "See how it works"
			}
		},
		{
			title: "Validate before you invest",
			description: "Reduce risk by testing your assumptions with real users before committing significant resources. Get user feedback on working prototypes in days, not quarters.",
			image: "/generated/image-an-entrepreneur-is-interacting-with-a-gr.webp",
			link: {
				href: "/use-cases/validation-testing",
				label: "Start validating"
			}
		}
	]}
/>

<AboutTeaser />
<CallToAction />
