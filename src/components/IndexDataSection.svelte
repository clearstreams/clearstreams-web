<script>
  export let factoryName;
  export let indexLevel;
</script>

<div class="flex items-center justify-center">
  <span class="pr-3">{factoryName}</span>
  <progress class="progress progress-accent w-56" value={indexLevel} max="100"></progress>
  <span class="pl-3">{indexLevel} %</span>
</div>