<script>
  import { createEventDispatcher } from "svelte";

  export let cls = "";

  const dispatch = createEventDispatcher();
</script>

<button
  on:click={() => dispatch("follow")}
  class={`px-6 py-2 rounded-[4px] bg-white border-solid border-[0.5px] border-[#4D4D4D] hover:bg-[#0066FF] hover:border-[#0066FF] hover:text-white hover:shadow-[0_2px_0_0_rgba(0,58,145,1)] ${cls}`}
>
  <slot />
</button>
