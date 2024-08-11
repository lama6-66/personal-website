<script >
  import  Input  from "$lib/components/ui/input/input.svelte";
  import  Label  from "$lib/components/ui/label/label.svelte";
  import Textarea from "$lib/components/ui/textarea/textarea.svelte";
  import Button from "$lib/components/ui/button/button.svelte";
</script>  
  
  
  <div class="max-w-screen-sm mx-auto pt-16 px-4 min-h-screen flex flex-col gap-8">
    <h1 class="mx-auto w-fit text-4xl font-bold flex items-center">
        <div class="bg-black w-5 h-5 me-4" />
        <span class="text-red-800">Contact us</span>
    </h1>

<form action="https://formsubmit.co/alotaibilama196@gmail.com"
method="POST" 
class="bg-black p-8 flex flex-col gap-8 m-4 ">
    
<div>
    <Label for="name" class="text-red-800  ">
        Full Name
    </Label>
    <Input required name="name" id="name" placeholder="Enter your name "  />
</div>

<div>
    <Label for="email" class="text-red-800 ">
        Email
    </Label>
    <Input required type="email" name="email" id="email" placeholder="email@gmail.com "  />
</div>

<div>
    <Label for="message" class="text-red-800 ">
       Suggestions and Complaints
    </Label>
    <Textarea required  name="message" id="message" placeholder="How can I help you ? "  />
</div>

<Button type="submit" class="bg-red-800 text-black text-md">
SEND
</Button>

</form>






</div>

<footer class="" >
    <header class=" bg-black px-4 py-8 relative">
        <nav class=" flex justify-between mx-12 text-red-800 flex-col lg:flex-row">
            <span class="flex items-center text-lg">© {new Date().getFullYear()}</span>
            <div class="flex flex-col lg:flex-row ">
                <div >
                    <span class="text-lg my-2 ">Email- </span>
                    <span class="flex items-center">
                    <a class="mx- flex text-lg  " href="mailto:alotaibilama196@gmail.com"> alotaibilama196@gmail.com</a>
                  </span>
                </div>
            </div>


            <span class="flex flex-row my-4 items-center ">
                <a href="https://x.com/Marvel?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor" class="px-3">
                    <svg class="h-6 w-8" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 14 14">
                        <g fill="none">
                            <g clip-path="url(#primeTwitter0)">
                                <path fill="currentColor"
                                    d="M11.025.656h2.147L8.482 6.03L14 13.344H9.68L6.294 8.909l-3.87 4.435H.275l5.016-5.75L0 .657h4.43L7.486 4.71zm-.755 11.4h1.19L3.78 1.877H2.504z" />
                            </g>
                            <defs>
                                <clipPath id="primeTwitter0">
                                    <path fill="#fff" d="M0 0h14v14H0z" />
                                </clipPath>
                            </defs>
                        </g>
                    </svg>
                </a>
                <a href="https://www.instagram.com/marvel/?hl=ar" class="">
                    <svg class="h-6 w-8" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 24 24">
                        <path fill="currentColor"
                            d="M17.318.077c1.218.056 2.06.235 2.838.537a5.4 5.4 0 0 1 1.956 1.274a5.4 5.4 0 0 1 1.274 1.956c.302.779.481 1.62.537 2.838C23.992 8.192 24 8.724 24 12s-.008 3.808-.077 5.318c-.056 1.218-.235 2.06-.537 2.839a5.4 5.4 0 0 1-1.274 1.955a5.4 5.4 0 0 1-1.956 1.274c-.779.302-1.62.481-2.838.537c-1.51.069-2.041.077-5.318.077s-3.809-.008-5.318-.077c-1.218-.056-2.06-.235-2.839-.537a5.4 5.4 0 0 1-1.955-1.274a5.4 5.4 0 0 1-1.274-1.956c-.302-.779-.481-1.62-.537-2.838C.008 15.81 0 15.278 0 12s.008-3.81.077-5.318c.056-1.218.235-2.06.537-2.838a5.4 5.4 0 0 1 1.274-1.956A5.4 5.4 0 0 1 3.843.614C4.623.312 5.464.133 6.682.077C8.19.008 8.722 0 12 0s3.81.008 5.318.077M12 2.667c-3.24 0-3.736.007-5.197.074c-.927.042-1.483.16-1.994.359c-.435.17-.712.35-1.036.673S3.27 4.374 3.1 4.81c-.198.51-.317 1.067-.359 1.994c-.067 1.46-.074 1.956-.074 5.196s.007 3.736.074 5.197c.042.927.16 1.483.359 1.993c.17.436.35.713.673 1.037s.601.504 1.036.673c.51.198 1.067.317 1.994.359c1.462.067 1.958.074 5.197.074c3.24 0 3.735-.007 5.197-.074c.927-.042 1.483-.16 1.994-.359c.435-.17.712-.35 1.036-.673s.504-.601.673-1.036c.198-.51.317-1.067.359-1.994c.067-1.462.074-1.958.074-5.197s-.007-3.735-.074-5.197c-.042-.927-.16-1.483-.359-1.993a2.7 2.7 0 0 0-.673-1.037A2.7 2.7 0 0 0 19.19 3.1c-.51-.198-1.067-.317-1.994-.359c-1.461-.067-1.957-.074-5.197-.074m0 15.555a6.222 6.222 0 1 1 0-12.444a6.222 6.222 0 0 1 0 12.444m0-2.666a3.556 3.556 0 1 0 0-7.112a3.556 3.556 0 0 0 0 7.112m6.222-8.445a1.333 1.333 0 1 1 0-2.667a1.333 1.333 0 0 1 0 2.667" />
                    </svg>
                </a>

                <a href="https://www.youtube.com/user/MARVEL" class="px-3">
                    <svg class="h-6 w-8" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 16 16">
                        <path fill="currentColor"
                            d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104l.022.26l.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105l-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006l-.087-.004l-.171-.007l-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103l.003-.052l.008-.104l.022-.26l.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007l.172-.006l.086-.003l.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z" />
                    </svg>
                </a>

            </span>

            <div class="flex flex-row  gap-x-4">
                <img class="h-10 w-8" src="pngwing.com.png" />
                <img class="h-10 w-8" src="green).png" />
              </div>
  

        </nav>
    </header>
</footer>