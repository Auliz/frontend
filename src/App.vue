<template>
	<v-app>
    <!-- <v-toolbar app>

    </v-toolbar> -->

		<v-main>
			<OurMessages />
		</v-main>
	</v-app>
</template>

<script>
import OurMessages from './components/OurMessages';

export default {
	name: 'App',

	components: {
		OurMessages,
	},

	data: () => ({
		//
	}),
};
</script>
