<script lang="ts">
import content from "$lib/content.json";
import { PAGE_SECTION_SPACE, PAGE_TOP_MARGIN, PAGE_SIDE_MARGIN, SAME_SECTION_SPACE} from "$lib/constants";
import {onMount} from "svelte";

</script>

<img src="{content.images.paddington_bear_link}" alt="{content.images.paddington_bear_alt}"/>

<div class="{PAGE_TOP_MARGIN} {PAGE_SECTION_SPACE} {PAGE_SIDE_MARGIN}">
	<div class="">
		<h1 class="h1"> {content.intro.quote} </h1>
		<h5 class="h5"> {content.intro.longer_quote} </h5>
	</div>
	<div class="">
	</div>
</div>
