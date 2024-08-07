<script>
    import Button from "$lib/components/ui/button/button.svelte";
</script>

<footer class=" bg-black py-4 relative">
    <div
        class=" max-w-screen-2xl flex justify-between items-end mx-12 text-red-800 font-bold"
    >
        <span class="">
            © {new Date().getFullYear()}
        </span>

        <span class="flex flex-col items-center mx-0 gap-2 px-6">
            <span>Email</span>
            <a href="mailto:alotaibilama196@gmail.com"
                >alotaibilama196@gmail.com</a
            >
        </span>
        <div class="flex gap-8 flex items-center ">
            

            

            <span class="text-red-800 flex flex-col items-center mx-0 gap-2 mx-0 ">
                <span class="gap-2 text-md flex-row"> FOLLOW </span>
      <div>
                <button class=" h-6 w-5 py-2">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        
                        viewBox="0 0 128 128"
                        fill="currentColor"
                        ><path
                            d="M75.916 54.2L122.542 0h-11.05L71.008 47.06L38.672 0H1.376l48.898 71.164L1.376 128h11.05L55.18 78.303L89.328 128h37.296L75.913 54.2ZM60.782 71.79l-4.955-7.086l-39.42-56.386h16.972L65.19 53.824l4.954 7.086l41.353 59.15h-16.97L60.782 71.793Z"
                            stroke-width="1"
                        /></svg
                    >
                </button>

                <span class="text-red-800">
                    <button class="h-6 w-6 py-2">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            
                            viewBox="0 0 24 24"
                            ><path
                                fill="currentColor"
                                d="M18.437 20.937H5.563a2.5 2.5 0 0 1-2.5-2.5V5.563a2.5 2.5 0 0 1 2.5-2.5h12.874a2.5 2.5 0 0 1 2.5 2.5v12.874a2.5 2.5 0 0 1-2.5 2.5M5.563 4.063a1.5 1.5 0 0 0-1.5 1.5v12.874a1.5 1.5 0 0 0 1.5 1.5h12.874a1.5 1.5 0 0 0 1.5-1.5V5.563a1.5 1.5 0 0 0-1.5-1.5Z"
                            /><path
                                fill="currentColor"
                                d="M12 16.594A4.595 4.595 0 1 1 16.6 12a4.6 4.6 0 0 1-4.6 4.594M12 8.4a3.595 3.595 0 1 0 3.6 3.6A3.6 3.6 0 0 0 12 8.4"
                            /><circle
                                cx="17.2"
                                cy="6.83"
                                r="1.075"
                                fill="currentColor"
                            /></svg
                        >
                    </button>
                </span>
       
            </span>
       
            
        </div>
    </div>
</footer>
