<script>
	import '../app.css';
    import * as Tooltip from "$lib/components/ui/tooltip/index.js";
	// let { children } = $props();
</script>

<!--{@render children()}-->

<div class="w-[350px] mx-auto pt-[350px]">
    <Tooltip.Provider delayDuration={150}>
        <Tooltip.Root>
            <Tooltip.Trigger class="border border-gray-300 p-4 rounded-md">
                Hover for tooltip
            </Tooltip.Trigger>

            <Tooltip.Content>
                <p>Add to library</p>
            </Tooltip.Content>
        </Tooltip.Root>
    </Tooltip.Provider>
</div>