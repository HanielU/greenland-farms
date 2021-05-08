<script>
	import { metatags } from "@roxi/routify";
	import PageIntro from "./_components/homepage/PageIntro.svelte";
	import AboutPreview from "./_components/homepage/AboutUs.svelte";
	import ServicesPreview from "./_components/homepage/Services.svelte";
	metatags.title = "Greenland Farms";
	metatags.description = "Greenland farms, thegreenlandfarms";
</script>

<PageIntro />
<AboutPreview />
<ServicesPreview />
