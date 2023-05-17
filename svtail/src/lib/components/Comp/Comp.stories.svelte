<script lang="ts">
	import { Meta, Story, Template } from '@storybook/addon-svelte-csf';
	import Comp from './Comp.svelte';
</script>

<Meta title="ui/Comp" component={Comp} />

<Template let:args>
	<Comp {...args} />
</Template>

<Story name="John" args={{ user: 'john doe' }} />

<Story name="Jane" source args={{ user: 'jane doe' }} />
