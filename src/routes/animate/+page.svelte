<script>
      import IntersectionObserver from "svelte-intersection-observer";

    let element
    let intersecting

</script>

<div class="flex flex-col">
    <div class="start">Start</div>


    <div class="h-[900px] bg-yellow-400 overflow-x-hidden">
        <IntersectionObserver {element} bind:intersecting threshold={0.3}>
            <div bind:this={element} class="bg-green-700 text-green-50 text-3xl py-6 px-2 italic">
                <p class:intersecting class={!intersecting?"green":"green show"}>3AM in Glenwood</p>
            </div>
        </IntersectionObserver>
    </div>

    <div class="end">End</div>
</div>

<style>
    .green{
        width:inherit;
        opacity: 0;
        position:relative;
        right:-40px;
        transition: all 1.2s ease-out;
    }

    .show{
        opacity:1;
        right:0;
    }
</style>