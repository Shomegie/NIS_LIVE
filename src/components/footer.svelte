<script>
    import { goto } from '$app/navigation';
    
        let li ='text-gray-700 text-xs cursor-pointer underline hover:text-gray-500 transition duration-100'
        let tx1 ='text-gray-700'
    </script>
    
    <div class="h-1 w-full bg-gray-500"></div>
    <div class="h-1 w-full bg-blue-900"></div>
    <div class="texture w-full pt-8  relative">
        <div class="w-5/6 mx-auto hidden md:flex flex-col px-4">
            <div class="flex w-full">
                <div class="space-y-2 w-2/3">
                    <p class="text-xs {tx1}">Address: <br>Lorem ipsum dolor sit amet consectetur.</p>
                    <p class="text-xs {tx1}">Phone:<br>0803 555 5555</p>
                    <p class="text-xs {tx1}">Email:<br> mail@gmail.com</p>
                    <p class="text-xs {tx1}">Facebook:<br>www.facebook/user.com</p>
                </div>
                <div class="w-1/3 flex justify-end pr-8">
                    <img class = "image h-44 opacity-90" src="/png/NIS_6.png" alt="temp logo">   
                </div>
            </div>
    
            <div class="h-full w-1/2">
                <div class="h-12 flex items-center">
                    <ul class="text-amber-50 flex space-x-10">
                        <li class={li} on:click={()=>goto("/home")}>Home</li>
                        <li class={li}>About Us</li>
                        <li class={li}>Gallery</li>
                        <li class={li}>Contacts</li>
                        <li class={li}>Admission</li>
                    </ul>
                </div>
            </div>
    
            
        </div>
    
            
        <div class="w-full text-gray-700">
            <div class="flex w-full lg:w-5/6 mx-auto text-xs pb-4 px-4">
                <p class="w-2/3">@2022 Nithalos International School</p>
                <div class="hidden w-1/3 md:flex justify-end pr-8"><p>Developer: github.com/Shomegie</p></div>
            </div>
        </div>
    
    </div>
    
    <style>
        .texture{
            background-color: #010101;
            background-image: url("data:image/svg+xml,%3Csvg width='42' height='44' viewBox='0 0 42 44' xmlns='http://www.w3.org/2000/svg'%3E%3Cg id='Page-1' fill='none' fill-rule='evenodd'%3E%3Cg id='brick-wall' fill='%23303032' fill-opacity='0.46'%3E%3Cpath d='M0 0h42v44H0V0zm1 1h40v20H1V1zM0 23h20v20H0V23zm22 0h20v20H22V23z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
    </style>
    
    