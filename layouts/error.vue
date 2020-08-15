<template>
<div>
	<div class="container error-container">
		<div v-if="error.statusCode === 404">
			<h1>Sorry, we couldn't find that page.</h1>
		</div>
		<div v-else-if="error.statusCode === 500">
			<h1>Internal Server error</h1>
		</div>
		<div v-else-if="error.statusCode === 503">
			<h1>503 Service Unavailable</h1>
		</div>
		<div v-else>
			<h1>An unknown error occured</h1>
		</div>
		<div v-if="$props.error.message" class="error-textarea">
			<p>
				<b>Details:</b>
			</p>
			<p>{{ $props.error.message }}</p>
		</div>
	</div>
  <br><br><br><br><br>
</div>
</template>

<script>
	export default {
		props: ["error"],
		head: {
			title: `Error | SlayBot`
		},
		mounted() {
			console.log(this.$props.error);
		},
		methods: {
			reload() {
				location.reload();
			}
		}
	};
</script>