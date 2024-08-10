<script lang="ts">
    import Button from "$lib/components/ui/button/button.svelte";
</script>

<div class="max-w-screen-sm mx-auto pt-16 px-4">
    <h1 class="mx-auto w-fit text-4xl font-bold flex items-center">
        <div class="bg-black w-5 h-5 me-4" />
        <span class="text-red-800">Projects</span>
    </h1>

    <div class="pt-12 flex flex-col gap-6">
        <div class="flex justify-center text-red-800 font-semibold py-1">
            Discover my work that sets me apart.
        </div>

        <div class="bg-black gap-x-5  shadow-2xl flex">
            <div class="flex flex-col gap-6 pt-6">
                <div class="border-s-8 border-red-800 ps-6 flex flex-col">
                    <span class="font-bold text-lg text-red-800">
                        Calculator</span
                    >
                    <span class="text-red-800">Project</span>
                </div>
                <div class="text-red-800 ps-8 flex">
                    <p>fffff</p>
                </div>
            </div>
            <img src="calculate.jpg" class="w-44 ml-auto object-cover" />
        </div>
    </div>
</div>

