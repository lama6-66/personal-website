<script>
    import Button from "$lib/components/ui/button/button.svelte";
</script>

<footer class=" bg-black py-4 relative">
    <div
        class=" max-w-screen-2xl   flex justify-between items-end mx-12 text-red-800 font-bold"
    >
    
        <span class="">
            © {new Date().getFullYear()}
        </span>

        <span class="flex flex-col items-center mx-0 gap-2 px-6">
            <span class="text-lg">Email</span>
            <a href="mailto:alotaibilama196@gmail.com"
                >alotaibilama196@gmail.com</a
            >
        </span>
        
    </div>
</footer>
