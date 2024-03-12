<script>
  export let src;
  export let text;
  export let len;
</script>

<div class="w-fit flex flex-col items-end">
  <img class="rounded-full" width={len} height={len} {src} alt="" />
  <h2 class="font-bold my-1 text-base/5">{text}</h2>
  <div class="text-xs text-[#7A9299] flex flex-col items-end">
    <slot />
  </div>
</div>
