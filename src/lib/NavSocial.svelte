<nav>
	<a target="_blank" rel="noopener noreferrer" href="https://github.com/willswats">
		<img alt="GitHub" src="svg/github.svg" />
	</a>
	<a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/willswats/">
		<img alt="LinkedIn" src="svg/linkedin.svg" />
	</a>
</nav>

<style>
	nav {
		position: fixed;
		bottom: 0;
		left: 0;
		right: 0;
		display: flex;
		justify-content: center;
		align-items: center;
		background-color: #2a2a2a;
		border-top: 1px solid #4a4a4a;
	}

	nav a {
		display: flex;
		justify-content: center;
		align-items: center;
		padding: 1rem;
		transition: background-color 0.1s;
		border-left: 1px solid #4a4a4a;
	}

	nav a:last-child {
		border-right: 1px solid #4a4a4a;
	}

	nav a:hover {
		background-color: #3a3a3a;
	}

	nav a img {
		width: 2rem;
		height: 2rem;
	}

	@media screen and (min-width: 768px) {
		nav {
			position: fixed;
			left: 0;
			z-index: 3;
			flex-direction: column;
			justify-content: end;
			border-top: 0;
			border-right: 1px solid #4a4a4a;
			height: 100%;
			width: 4rem;
		}

		nav a {
			width: 100%;
			border-left: 0;
			border-top: 1px solid #4a4a4a;
		}

		nav a:last-child {
			border-right: 0;
		}
	}
</style>
