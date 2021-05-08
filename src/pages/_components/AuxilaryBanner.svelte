<script>
	import { url } from "@roxi/routify";
	export let title, pageName;
</script>

<section class="banner">
	<h1 class="title">
		{title}
	</h1>
</section>

<section class="fake-pagination">
	<p>
		<a href="./index" use:$url>Greenland Farms</a> > {pageName}
	</p>
</section>

<style lang="scss">
	.banner {
		height: 240px;
		width: 100%;
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 0 100px;
		margin-bottom: 20px;
		background: linear-gradient(
				0deg,
				rgba(0, 0, 0, 0.45),
				rgba(0, 0, 0, 0.45)
			),
			url(imgs/cover-img.jpg);
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;
		color: white;
	}

	.title {
		font-size: var(--huge);
	}

	.fake-pagination {
		width: 100%;
		padding: 30px 100px;

		a:hover {
			color: var(--green);
			text-decoration: underline;
		}
	}
</style>
