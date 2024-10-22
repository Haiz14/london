<script lang="ts">
import content from "$lib/content.json";
import { PAGE_SECTION_SPACE, PAGE_TOP_MARGIN, PAGE_SIDE_MARGIN, SAME_SECTION_SPACE} from "$lib/constants";
import {onMount} from "svelte";

</script>

<img src="{content.images.paddington_bear_link}" alt="{content.images.paddington_bear_alt}"/>

<div class="{PAGE_TOP_MARGIN} {PAGE_SECTION_SPACE} {PAGE_SIDE_MARGIN}">
	<div class="{SAME_SECTION_SPACE}">
		<h1 class="text-slate-900 dark:text-slate-100 text-4xl"> {content.intro.quote} </h1>
		<h3 class="text-slate-800 dark:text-slate-200 text-xl"> {content.intro.longer_quote} </h3>
	</div>
	<div>
	</div>
</div>
