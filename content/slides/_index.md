<!doctype html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

	<title>{{ .Title }}</title>

	<link rel="stylesheet" href="/css/reset.css">
	<link rel="stylesheet" href="/css/reveal.css">
	<link rel="stylesheet" href="/css/theme/black.css">

	<!-- Theme used for syntax highlighting of code -->
	<link rel="stylesheet" href="/lib/css/monokai.css">

	<style>
		code {
			color: red
		}

		.reveal {
			font-family: sans-serif;
			font-size: 35px;
		}
	</style>
</head>

<body>
	<div class="reveal">
		<div class="slides">
			<section data-markdown="/slides/01-web-intro.md"
				data-separator="^\n\n\n"
				data-separator-vertical="^\n\n"
				data-separator-notes="^Note:"></section>
		</div>
	</div>

	<script src="/js/reveal.js"></script>

	<script>
		Reveal.initialize({
			dependencies: [
				{ src: '/plugin/markdown/marked.js' },
				{ src: '/plugin/markdown/markdown.js' },
				{ src: '/plugin/notes/notes.js', async: true },
				{ src: '/plugin/highlight/highlight.js', async: true }
			],
			history: true,
		});
	</script>
</body>
</html>
