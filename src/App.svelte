<script lang="ts">
	const message : string = 'Learn Svelte';
</script>

<style>
	:global(body) {
		margin: 0;
		font-family: Arial, Helvetica, sans-serif;
	}
	.App {
		text-align: center;
	}
	.App-header {
		background-color: #F9F6F6;
		color: #333;
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		font-size: calc(10px + 2vmin);
	}
	.App-link {
		color: #ff3e00;
	}
	.App-logo {
		height: 40vmin;
		pointer-events: none;
		margin-bottom: 1.0rem;
		animation: App-logo-spin infinite 1.6s ease-in-out alternate;
	}

  .small {
    font-size: calc(10px + 1vmin);
  }

  .padding {
    padding: 1.0rem
  }
	@keyframes App-logo-spin {
		from {
			transform: scale(1);
		}
		to {
			transform: scale(1.06);
		}
	}
</style>

<div class="App">
	<header class="App-header">
		<img src="/logo.svg" class="App-logo" alt="logo" />
		<p>
			Edit <code>src/App.svelte</code> and save to reload.
		</p>
		<a
			class="App-link padding"
			href="https://svelte.dev"
			target="_blank"
			rel="noopener noreferrer"
		>
			{message}
		</a>
		<a
			class="App-link small padding"
			href="https://vaishnavsm.github.io"
			target="_blank"
			rel="noopener noreferrer"
		>
			Check Me Out :)
		</a>
	</header>
</div>