<template>
	<view class="container">
		<text class="text-color-primary">My Vue Native App...!</text>
		<button
				:on-press="onPressLearnMore"
				title="Learn More"
				color="#841584"
				accessibility-label="Learn more about this purple button"
		/>
	</view>
</template>

<script>
  export default {
    methods: {
      onPressLearnMore: function () {
        alert('Hello')
      }
    }
  }
</script>

<style>
	.container {
		background-color: white;
		align-items: center;
		justify-content: center;
		flex: 1;
	}

	.text-color-primary {
		color: blue;
	}
</style>
