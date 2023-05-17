<script lang="ts">
	import Meow from './Meow.svelte';
	import type { Hst } from '@histoire/plugin-svelte';
	export let Hst: Hst;
</script>
<style>
	 @import 'tailwindcss/base';
  @import 'tailwindcss/components';
  @import 'tailwindcss/utilities';
</style>

<Hst.Story>
	<Meow />
</Hst.Story>


