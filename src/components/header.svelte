<script>
    // import { goto } from '$app/navigation';
    let li ='text-blue-50 text-sm cursor-pointer font-bold  hover:text-yellow-400 transition duration-150'
</script>

<section class="texture">
    <div class="desktop hidden sm:block bg-indigo-900 bg-opacity-0 ">
        <div class="grid grid-cols-1 ">
            <div class="hidden sm:block h-6 w-full bg-blue-500 text-xs text-red-100 px-8 py-1 cursor-pointer">
                <p class="underline">Get the latest update and NIS's response to COVID-19</p>
            </div>
            <div class="h-12 flex justify-center items-center px-8 relative">

                
                <ul class="hidden sm:flex text-gray-500 space-x-6">
                    <li class={li}>Home</li>
                    <li class={li}>About Us</li>
                    <li class={li}>Gallery</li>
                    <li class={li}>Contacts</li>
                    <li class={li}>Admission</li>
                </ul>
            </div>
        </div>
        <div class=""></div>
    </div>
</section>


<!-- <section class="mobile bg-blue-900 flex sm:hidden justify-end relative">
    <div class="z-50 absolute right-0 top-0">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-12 my-4 mx-1 text-blue-100 " fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
    </div>
    <div class="absolute right-0 top-0 flex w-full h-screen z-10">
        <div class="w-1/3 backdrop-blur-sm"></div>
        <div class="w-2/3 bg-blue-300"></div>


    </div>

</section> -->

<style>
    .texture{
        background-color: #1a0369;
        background-color: #6B6FFD;
background-image: url("data:image/svg+xml,%3Csvg width='42' height='44' viewBox='0 0 42 44' xmlns='http://www.w3.org/2000/svg'%3E%3Cg id='Page-1' fill='none' fill-rule='evenodd'%3E%3Cg id='brick-wall' fill='%233b58d5' fill-opacity='0.14'%3E%3Cpath d='M0 0h42v44H0V0zm1 1h40v20H1V1zM0 23h20v20H0V23zm22 0h20v20H22V23z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
    }
</style>