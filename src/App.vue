<template lang="pug">
#app
	i-navbar
		i-navbar-brand(to="/") 
			i.fas.fa-sun.fa-2x._margin-right-1
			| Engenho Novo LLP
		i-navbar-items
			i-nav
				i-nav-item(:to='{ name: \'index\' }') Home
				i-nav-item(:to='{ name: \'about\' }') About
			i-nav
				i-input.item(placeholder='Type something..')
					i-button(variant='primary' slot='append')
						font-awesome-icon(icon='search').
								
								
	router-view
</template>

<style lang="scss">
#app {
	font-family: 'News Cycle', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}

i-navbar > i-navbar-brand {
	font-siz: 25px;
}

</style>
