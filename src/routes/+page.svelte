<script>
	import { currentUser } from '$lib/pocketbase';
</script>

{#if $currentUser}
	<div class="flex justify-center">
		<!-- The button to open modal -->
		<label for="my-modal-4" class="btn-primary btn">Create Post</label>

		<!-- Put this part before </body> tag -->
		<input type="checkbox" id="my-modal-4" class="modal-toggle" />
		<label for="my-modal-4" class="modal cursor-pointer">
			<label class="modal-box relative" for="">
				<h3 class="text-lg font-bold">Hello!</h3>
				<p class="py-4">Hi</p>
			</label>
		</label>
	</div>
{/if}
