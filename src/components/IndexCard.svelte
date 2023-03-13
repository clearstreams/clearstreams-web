<script>
	import IndexDataSection from './IndexDataSection.svelte';
	import InfoButton from './InfoButton.svelte';
	import LaunchButton from './LaunchButton.svelte';
</script>

<div class="flex flex-col p-10 bg-base-100 rounded-md drop-shadow-md m-10">
	<p class="font-bold pb-3 text-xl text-stone-300">Threshold Monitor</p>
  <div class="flex justify-start">
		<ul>
			<IndexDataSection factoryName={'IRS'} indexLevel={67} />
      <IndexDataSection factoryName={'ITC'} indexLevel={70} />
      <IndexDataSection factoryName={'ECO'} indexLevel={11} />
      <IndexDataSection factoryName={'IRO'} indexLevel={27} />
    </ul>
	</div>
</div>
