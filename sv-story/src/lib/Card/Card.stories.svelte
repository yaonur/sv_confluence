<script lang='ts'> 
import Card from './Card.svelte'
import { Story, Meta,Template } from '@storybook/addon-svelte-csf';
</script>

<Meta title='Card' component={Card} />

<Template let:args>
  <Card {...args}/>
</Template>

<Story name="Primary" args={{title:{name:"Title Wow",content:'Wow'}}}></Story>