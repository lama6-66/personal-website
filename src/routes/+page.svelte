<script>
  import Button from "$lib/components/ui/button/button.svelte";
</script>

<div class="max-w-[100dvw] overflow-clip">
  <video src="MV.mp4" autoplay loop muted
         class="absolute -z-10 h-[calc(100dvh-3.5rem)] w-[100dvw] object-cover max-w-none">
      <source src="MV.mp4" type="MV.mp4">
  </video>
  <div class="content absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 text-5xl flex flex-col items-center justify-center">
      <h1 class="text-red-800 py-10 text-7xl">
          MAREL
      </h1>
      <Button class="">
          <a href="https://www.marvel.com/">official website</a>
      </Button>
  </div>
</div>
