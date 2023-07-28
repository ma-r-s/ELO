<script>
	import Info from '~icons/material-symbols/info-outline-rounded';
</script>

<button class="btn btn-square btn-ghost" onclick="my_modal_5.showModal()">
	<Info class="w-6 h-6" />
</button>
<dialog id="my_modal_5" class="modal modal-bottom sm:modal-middle">
	<form method="dialog" class="modal-box">
		<h3 class="font-bold text-lg">Hello!</h3>
		<p class="py-4">Press ESC key or click the button below to close</p>
		<div class="modal-action">
			<!-- if there is a button in form, it will close the modal -->
			<button class="btn">Close</button>
		</div>
	</form>
</dialog>
