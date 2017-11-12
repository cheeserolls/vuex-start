<template>
	<div class="app-container">
		<p>{{msg}}</p>
	</div>
</template>


<script>
import _ from 'lodash';
export default {
	data: function() {
		return {
			msg: "Do you like fish sticks?"
		};
	}
};
</script>
