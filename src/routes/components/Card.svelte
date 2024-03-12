<script>
  export let imgSrc = "pc.jfif";
  export let text = "";
</script>

<div class="card w-[344px] h-[226px] rounded-xl">
  <div
    class={`h-[136px] w-[344px] bg-center bg-cover rounded-t-xl`}
    style={`background-image: url(${imgSrc})`}
  ></div>
  <div class="content p-6 bg-[#FFFFFF] rounded-b-xl">
    <p class="text-sm line-clamp-2">{text}</p>
  </div>
</div>
