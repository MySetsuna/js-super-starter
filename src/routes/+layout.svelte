<script>
	import '../app.postcss';
	// Your selected Skeleton theme:
	import '@skeletonlabs/skeleton/themes/theme-skeleton.css';
	// import '@skeletonlabs/skeleton/themes/theme-gold-nouveau.css';
	// import '@skeletonlabs/skeleton/themes/theme-rocket.css';

	// This contains the bulk of Skeletons required styles:
	import '@skeletonlabs/skeleton/styles/all.css';

	// Finally, your application's global stylesheet (sometimes labeled 'app.css')
	import '../app.postcss';
	import Header from './header.svelte';
</script>

<slot />
