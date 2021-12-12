<template>
	<div class="main-container">

		<!-- Navbar section -->
		<Header />

		<!-- hero section -->
		<Hero />

		<!-- contact us section -->
		<Contact />

		<!-- footer section -->
        <Footer />

        <!-- offcanvas search component -->
        <OffcanvasSearchBox />

	</div>
</template>

<script>
	import Header from "@/components/dcism/Header";
	import Hero from "@/components/dcism/sections/Hero";
	import Contact from "@/components/dcism/sections/Contact";
	import Footer from "@/components/dcism/Footer";
	import OffcanvasSearchBox from "@/components/dcism/OffcanvasSearchBox";

	export default {
		name: "app",
		components: {
			Header,
			Hero,
			Contact,
            Footer,
            OffcanvasSearchBox	
		},

		metaInfo: {
            title: 'Aeroland - Home Agency',
            htmlAttrs: {
                lang: 'en',
                amp: true
            }
        }
	};
</script>

<style lang="scss">
	@import '../assets/scss/_variabls.scss';
    @import '../assets/scss/page-section/_dcism.scss';
</style>

