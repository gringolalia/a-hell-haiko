<template lang="pug">
.hello
	h1
		i.fas.fa-chess.fa-4x
	h1._margin-bottom-1 Vue Thru Tinted Window Glass
	h2._margin-top-0 Addio Mondo Crudele
	h3._margin-top-0 Inkline and Thinkers
	._display-flex._flex-direction-row
		i-button._margin-right-1(variant='primary') Prime Rib
		i-button(variant='dark') Second Hand

</template>

<style>.hello {
	min-height: calc(100vh - 75px);
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'home',
	components: {
		HelloWorld
	}
}
</script>
