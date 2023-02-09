<script>
	import { base } from '$app/paths';
</script>

<div>
	<i class="ph icon train thin" />
	<i class="ph icon train light" />
	<i class="ph icon train" />
	<i class="ph icon train bold" />
	<i class="ph icon train fill" />
	<i class="ph icon train duotone" />
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

<style lang="scss">
	.ph.icon {
		animation: rainbow 5s linear infinite;

		@keyframes rainbow {
			0% {
				background-color: red;
			}
			20% {
				background-color: orange;
			}
			40% {
				background-color: yellow;
			}
			60% {
				background-color: green;
			}
			80% {
				background-color: blue;
			}
			100% {
				background-color: purple;
			}
		}
	}
</style>
