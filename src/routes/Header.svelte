<script lang="ts">
	import header_icon from '/rosie-icon.png'
</script>

<header>
	<div class="header-icon-container">
		<img src={header_icon} alt="Header Icon for Rosie">
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: center;
	}

	.header-icon-container {
		padding: 64px 0px 32px 0px;
	}

	.header-icon-container img {
		width: 400px;
	}
</style>
