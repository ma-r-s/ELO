<script>
	import Menu from '~icons/material-symbols/menu-rounded';
	import Info from './Info.svelte';
</script>

<div class="drawer lg:drawer-open">
	<input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
	<div class="drawer-content flex flex-col items-center justify-center">
		<!-- Page content here -->
		<div class="navbar bg-base-300 lg:hidden">
			<div class="navbar-start">
				<label for="my-drawer-2" class="btn btn-square btn-ghost">
					<Menu class="w-6 h-6" />
				</label>
			</div>
			<p class="navbar-center text-2xl font-serif">ELO Everything</p>
			<div class="navbar-end">
				<Info />
			</div>
		</div>
	</div>
	<div class="drawer-side">
		<label for="my-drawer-2" class="drawer-overlay" />
		<ul class="menu p-4 w-80 h-full bg-base-200 text-base-content">
			<!-- Sidebar content here -->
			<p class=" text-2xl font-serif p-4">ELO Everything</p>
			<li><a>Sidebar Item 1</a></li>
			<li><a>Sidebar Item 2</a></li>
		</ul>
	</div>
</div>
