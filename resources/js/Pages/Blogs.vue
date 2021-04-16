<template>
    <app-layout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Blogs
            </h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
            <button class="btn btn-primary">Add Blog</button>
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">                
                   <div class="card py-3 px-5">
                    <div class="card-body">
                        <h5 class="card-title">Special title treatment</h5>
                        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                        
                    </div>
                    </div>
                </div>
            </div>
        </div>
     
    </app-layout>
</template>

<script>
    import AppLayout from '@/Layouts/AppLayout'
    export default {
        components: {
               AppLayout,
             
        },
    }
</script>
