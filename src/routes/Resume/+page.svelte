<script lang="ts">
    import Button from "$lib/components/ui/button/button.svelte";
</script>

<div class="max-w-screen-sm mx-auto pt-16 px-4 min-h-screen flex flex-col">
    <h1 class="mx-auto w-fit text-4xl font-bold flex items-center">
        <div class="bg-black w-5 h-5 me-4" />
        <span class="text-red-800">Projects</span>
    </h1>

    <div class="pt-12 flex flex-col gap-6 flex-grow">
        <div class="flex justify-center text-red-800 font-semibold py-1">
            Discover my work that sets me apart.
        </div>

        <div class="bg-black gap-x-5 shadow-2xl flex flex-col sm:flex-row mb-8 ">
            <div class="flex flex-col gap-6 pt-6">
                <div class="border-s-8 border-red-800 ps-6 flex flex-col">
                    <span class="font-bold text-lg text-red-800">
                        Calculator</span
                    >
                    <span class="text-red-800">Project</span>
                </div>
                <div class="text-red-800 ps-4 flex flex-col">
                    <p>
                        Calculate easily and accurately with our simple
                         
                    </p>
                    <p>
                        calculator – instant solutions for your everyday
                        calculations.
                    </p>

                    <Button class="h-8 w-20 my-4 bg-red-800" href="https://cute-starlight-e0bdd2.netlify.app/">
                     Try it!
                    </Button>
                </div>
            </div>
            <img src="C2.png" class="w-auto sm:w-44 ml-auto object-cover mt-4 sm:mt-0" />
        </div>
    </div>

    <div class="bg-black gap-x-5 shadow-2xl flex flex-col sm:flex-row mb-8">
        <div class="flex flex-col gap-6 pt-6">
            <div class="border-s-8 border-red-800 ps-6 flex flex-col">
                <span class="font-bold text-lg text-red-800"> Task</span>
                <span class="text-red-800">Project</span>
            </div>
            <div class="text-red-800 ps-4 flex flex-col">
                <p>
                    Organize your time and track your tasks effortlessly 
                </p>
                <p>–
                    always stay on top of what needs to be done.</p>

                <Button class="h-8 w-20 my-4 bg-red-800" href="https://todolistlama.netlify.app/">
                    Try it!
                   </Button>
            </div>
        </div>
        <img src="T2.png" class="w-auto sm:w-44 ml-auto object-cover mt-4 sm:mt-0" />
    </div>
</div>

<header class=" bg-black px-4 py-8 relative">
    <nav class=" flex justify-between mx-12"></nav>
</header>
