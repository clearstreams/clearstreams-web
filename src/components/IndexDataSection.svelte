<script>
  export let factoryName;
  export let indexLevel;
  import InfoButton from "./InfoButton.svelte";
  import LaunchButton from "./LaunchButton.svelte";
</script>

<div class="flex items-center justify-center">
  <span class="pr-3 font-mono">{factoryName}</span>
  <progress class="progress progress-accent w-56" value={indexLevel} max="100"></progress>
  <span class="pl-3">{String(indexLevel) + "%"}</span>
  <div class="flex px-2 items-center">
    <InfoButton/>
		<LaunchButton />
  </div>
</div>