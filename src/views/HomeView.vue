<script setup>
import TheWelcome from '../components/TheWelcome.vue';
</script>

<template>
	<main>
		<h1 class="green">Testing Types</h1>
		<p>
			When designing your Vue application's testing strategy, you should
			leverage the following testing types:
		</p>
		<ul>
			<li>
				Unit: Checks that inputs to a given function, class, or composable are
				producing the expected output or side effects.
			</li>
			<li>
				Component: Checks that your component mounts, renders, can be interacted
				with, and behaves as expected. These tests import more code than unit
				tests, are more complex, and require more time to execute.
			</li>
			<li>
				End-to-end: Checks features that span multiple pages and makes real
				network requests against your production-built Vue application. These
				tests often involve standing up a database or other backend.
			</li>
		</ul>
		<p>
			Each testing type plays a role in your application's testing strategy, and
			each will protect you against different types of issues.
		</p>
	</main>
</template>
<style scoped>
h1 {
	font-weight: 500;
}
ul {
	margin: 0;
	padding: 0;
}
ul li {
	list-style: none;
	margin: 0.5rem 0;
}
ul li::first-letter {
	font-weight: 900;
}
</style>
