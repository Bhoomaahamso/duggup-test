<script>
    export let imgSrc = "pc.jfif";
    export let text = "";
  
    $: bg = `bg-[url("${imgSrc}")]`;
    $: cls = `h-[136px] w-[344px] bg-[url('${imgSrc}')] bg-center bg-cover rounded-t-xl`;
  </script>
  
  <div class="card w-[344px] h-[226px] rounded-xl">
    <div
      class={`h-[136px] w-[344px] bg-[url('${imgSrc}')] bg-center bg-cover rounded-t-xl`}
    ></div>
    <!-- <div class={`h-[136px] w-[344px] bg-[url('steve.jfif')] bg-center bg-cover rounded-t-xl`} ></div> -->
    <!-- <div class={`h-[136px] w-[344px] bg-[url('pc.jfif')] bg-center bg-cover rounded-t-xl`} ></div> -->
    <!-- <div class={`h-[136px] w-[344px] bg-[url('sam.jfif')] bg-center bg-cover rounded-t-xl`} ></div> -->
    <!-- <div class={`h-[136px] w-[344px] bg-[url('map.png')] bg-center bg-cover rounded-t-xl`} ></div> -->
    <div class="content p-6 bg-[#FFFFFF] rounded-b-xl">
      <p class="text-sm line-clamp-2">{text}</p>
    </div>
  </div>
  