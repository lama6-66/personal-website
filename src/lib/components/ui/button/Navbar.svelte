<script>
    import Button from "$lib/components/ui/button/button.svelte";
    import { page } from "$app/stores";
    import * as Sheet from "$lib/components/ui/sheet";
    import ThemeSwitch from "./ThemeSwitch.svelte";
    $: console.log($page.url.pathname);

    const links = [
        {
            taxt: "MAIN",
            href: "/",
        },

        {
            taxt: "MOVIES",
            href: "/movies",
        },

        {
            taxt: "GAMES",
            href: "/games",
        },
    ];

    let issheetopen=false;
</script>

<div class=" bg-black px-4 py-2 ">
    <nav class=" flex justify-between mx-12">
        
        <div
            class="bg-red-800 h-10 w-24 py-1 flex justify-center font-bold text-2xl text-white"
        >
            MAREL
        </div>

        <div class="flex gap-3">
            
            <div class="gap-2 uppercase hidden lg:flex">
                {#each links as link}
                    <Button
                        class=" {$page.url.pathname == link.href &&
                            'text-white'}"
                        href={link.href}
                        variant="link"
                    >
                        {link.taxt}
                    </Button>
                {/each}
            </div>
         
            <Sheet.Root bind:open={issheetopen}>
                <Sheet.Trigger class="bg-red-800 text-white  flex lg:hidden" >
                    <Button variant="ghost"  size="icon" class="">
                        <svg
                        class="h-6 w-6"
                            xmlns="http://www.w3.org/2000/svg"
                            
                            viewBox="0 0 24 24"
                            ><path
                                fill="none"
                                stroke="currentColor"
                                stroke-linecap="round"
                                stroke-miterlimit="10"
                                stroke-width="1.5"
                                d="M4.5 12h15m-15 5.77h15M4.5 6.23h15"
                            /></svg
                        >
                    </Button>
        

                </Sheet.Trigger>
                <Sheet.Content class="flex flex-col">
                    {#each links as link}
                    <Button
                        class=" {$page.url.pathname == link.href &&
                            'text-white'}"
                        href={link.href}
                        variant="link"
                        on:click={() => issheetopen= false}
                    >
                        {link.taxt}
                    </Button>
                {/each}
                  
                </Sheet.Content>
              </Sheet.Root>
              <ThemeSwitch/>
        </div>
    </nav>
    <div></div>
</div>

