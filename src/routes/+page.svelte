<script>
  import Card from "./components/Card.svelte";
  import Icon from "./components/Icon.svelte";
  import Nav from "./components/Nav.svelte";
  import ProfileInfo from "./components/ProfileInfo.svelte";
  import Title from "./components/Title.svelte";
</script>

<div class="mxnn-14 lg:mx-[117px] max-w-[1658px] xl:mx-[max(117px,auto)]">
  <Nav />

  <ProfileInfo />

  <div class="grid grid-cols-[15%_1fr] grid-rows-[900px] mt-4">
    <div
      class=" grid grid-cols-[100%] grid-rows-[288px_157px_288px_157px] justify-end items-center"
    >
      <div class="">
        <p class="text-right mr-8 text-xs text-[#7A9299]">Dec 2023</p>
      </div>
      <div class="justify-self-end mr-8">
        <Icon src="duggup.png" text="Duggup" len={48}>
          <p class="text-end lg:text-nowrap">San Francisco Bay Area</p>
          <p>Joined</p>
          <p>Nov 2023</p>
        </Icon>
      </div>
      <div class="">
        <p class="text-right mr-8 text-xs text-[#7A9299]">Dec 2023</p>
      </div>
      <div class="justify-self-end mr-8">
        <Icon src="betterup.jfif" text="BetterUp" len={48}>
          <p class="text-end lg:text-nowrap">San Francisco Bay Area</p>
          <p>Joined</p>
          <p>Sept 2022</p>
        </Icon>
      </div>
    </div>

    <div
      class="grid grid-cols-[1px_1fr] grid-rows-[288px_157px_288px_157px] gap-x-5 items-center max-w-fit border-dotted border-[#778FB1] border-l-2"
    >
      <div class="">
        <div
          class="relative left-[-8.5px] min-w-4 h-4 bg-white border-solid border-blue-700 border-[3px] rounded-full"
        />
      </div>
      <div class="flex gap-x-5 p-6">
        <Card
          imgSrc={"steve.jfif"}
          text="No amount of technology can convert a bad story into a good story."
        />
        <Card
          imgSrc={"sam.jfif"}
          text="Most people don't have original ideas. Here is how Sam Altman pushes himself to have unpopular ideas."
        />
      </div>
      <div class="relative h-full flex items-center">
        <svg
          class="absolute top-0 left-[-16.5px]"
          width="31"
          height="10"
          viewBox="0 0 31 10"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M22 8L15.5 2L9 8"
            stroke="#778FB1"
            stroke-width="1.5"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
        </svg>

        <div
          class="relative left-[-14.5px] min-w-7 h-7 bg-white border-solid border-blue-700 border-[9px] rounded-full"
        />
      </div>
      <div class="py-2 px-7">
        <Title title="Co-Founder and CEO" text="Full-time · Remote" />
      </div>
      <div class="">
        <div
          class="relative left-[-8.5px] min-w-4 h-4 bg-white border-solid border-blue-700 border-[3px] rounded-full"
        />
      </div>
      <div class="flex gap-x-5 p-6">
        <Card
          imgSrc="pc.jfif"
          text={`Startup Lesson I am reflecting. Don't build for the "average person".`}
        />
        <Card
          imgSrc="map.png"
          text="Your biggest regrets at 80 will be acts of omission."
        />
      </div>
      <div class="relative h-full flex items-center">
        <svg
          class="absolute top-0 left-[-16.5px]"
          width="31"
          height="10"
          viewBox="0 0 31 10"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M22 8L15.5 2L9 8"
            stroke="#778FB1"
            stroke-width="1.5"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
        </svg>
        <div
          class="relative left-[-14.5px] min-w-7 h-7 bg-white border-solid border-blue-700 border-[9px] rounded-full"
        />
      </div>
      <div class="py-2 px-7">
        <Title title="VP Engineering" text="Full-time" />
      </div>
    </div>
  </div>
</div>

<style lang="postcss">
  :global(html) {
    font-family: "Inter";
  }
</style>
