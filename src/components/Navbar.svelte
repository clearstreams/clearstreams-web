<script>
	import HamburgerSvg from './svg/HamburgerSvg.svelte';
	import BellSvg from './svg/BellSvg.svelte';
	import ClearStreamsLogoSvg from './svg/ClearStreamsLogoSvg.svelte';
</script>

<div class="navbar bg-base-100">
	<div class="navbar-start">
		<div class="dropdown">
			<label tabindex="0" class="btn btn-ghost btn-circle">
				<HamburgerSvg />
			</label>
			<ul
				tabindex="0"
				class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
			>
				<li><a>Overview</a></li>
				<li><a>Reports</a></li>
				<li><a>About</a></li>
			</ul>
		</div>
	</div>
	<div class="navbar-center">
		<a class="btn btn-ghost normal-case text-xl"><ClearStreamsLogoSvg /></a>
	</div>
	<div class="navbar-end">
		<button class="btn btn-ghost btn-circle">
			<div class="indicator">
				<BellSvg />
				<span class="badge badge-xs badge-primary indicator-item" />
			</div>
		</button>
	</div>
</div>
