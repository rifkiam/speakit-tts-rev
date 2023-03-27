<template>
    <div class="mx-auto bg-white backdrop-blur-md bg-opacity-20 w-[300px] h-[300px] rounded-2xl">
        <div class="mx-10 pt-8 text-center">
            <div class="flex justify-center mb-5">
                <img src="../assets/placeholder.png" class="w-28 h-28 rounded-full mb-2" alt="">
            </div>
            <h2 class="text-2xl">{{anggota.name}}</h2>
            <h2>{{anggota.nrp}}</h2>
        </div>
    </div>
</template>

<script setup>
    const { anggota } = defineProps(['anggota'])
</script>