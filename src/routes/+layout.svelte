<script>
	import { base } from '$app/paths';
</script>

<div>
	<i class="ph train thin" />
	<i class="ph train light" />
	<i class="ph train" />
	<i class="ph train bold" />
	<i class="ph train fill" />
	<i class="ph train duotone" />
</div>

<svelte:head><meta name="robots" content="noindex" /></svelte:head>

<slot />

<ul>
	<li>Multi-weight</li>
	<li><a data-sveltekit-reload href="{base}/">css</a></li>
	<li><a data-sveltekit-reload href="{base}/sass">sass</a></li>
	<li><a data-sveltekit-reload href="{base}/less">less</a></li>
</ul>

<ul>
	<li>Thin</li>
	<li><a data-sveltekit-reload href="{base}/thin">css</a></li>
	<li><a data-sveltekit-reload href="{base}/thin/sass">sass</a></li>
	<li><a data-sveltekit-reload href="{base}/thin/less">less</a></li>
</ul>

<ul>
	<li>Light</li>
	<li><a data-sveltekit-reload href="{base}/light">css</a></li>
	<li><a data-sveltekit-reload href="{base}/light/sass">sass</a></li>
	<li><a data-sveltekit-reload href="{base}/light/less">less</a></li>
</ul>

<ul>
	<li>Regular</li>
	<li><a data-sveltekit-reload href="{base}/regular">css</a></li>
	<li><a data-sveltekit-reload href="{base}/regular/sass">sass</a></li>
	<li><a data-sveltekit-reload href="{base}/regular/less">less</a></li>
</ul>

<ul>
	<li>Bold</li>
	<li><a data-sveltekit-reload href="{base}/bold">css</a></li>
	<li><a data-sveltekit-reload href="{base}/bold/sass">sass</a></li>
	<li><a data-sveltekit-reload href="{base}/bold/less">less</a></li>
</ul>

<ul>
	<li>Fill</li>
	<li><a data-sveltekit-reload href="{base}/fill">css</a></li>
	<li><a data-sveltekit-reload href="{base}/fill/sass">sass</a></li>
	<li><a data-sveltekit-reload href="{base}/fill/less">less</a></li>
</ul>

<ul>
	<li>Duotone</li>
	<li><a data-sveltekit-reload href="{base}/duotone">css</a></li>
	<li><a data-sveltekit-reload href="{base}/duotone/sass">sass</a></li>
	<li><a data-sveltekit-reload href="{base}/duotone/less">less</a></li>
</ul>
