<script>
	import "../app.css";
	import "$lib/cantarell.css";
	import "@fontsource-variable/noto-sans-jp";
	import Icon from "@iconify/svelte";
</script>

<nav class="fixed flex flex-col gap-2 p-2 h-full w-fit border-r bg-white dark:bg-zinc-900 border-zinc-200 dark:border-zinc-700 text-4xl">
	<a href="/" title="ホーム"><Icon icon="pixelarticons:home" /></a>
	<a href="/notification" title="通知"><Icon icon="pixelarticons:notification" /></a>
	<a href="/friends" title="フレンド"><Icon icon="pixelarticons:users" /></a>
	<a href="/send" title="送信"><Icon icon="pixelarticons:plus" /></a>
</nav>

<main>
	<slot />
</main>
