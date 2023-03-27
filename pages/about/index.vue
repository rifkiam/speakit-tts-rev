<template>
  <div class="lg:bg-[url('assets/bg.jpg')] sm:bg-blue-400 bg-cover min-h-screen bg-no-repeat">
    <div class="container mx-auto grid gap-y-16 md:grid-cols-2 lg:grid-cols-3 translate-y-1/4">
        <div v-for="ang in anggota" :key="ang.nrp">
            <cards :anggota="ang" />
        </div>
    </div>
  </div>

</template>

<script>

  export default {
    data() {
        return {
            anggota: [
                {
                    name: "Fatikha Afrine Azaruddin",
                    nrp: "5027211016"
                },
                {
                    name: "Andyana Muhandhatul Nabila",
                    nrp: "5027211029"
                },
                {
                    name: "Rifqi Akhmad Maulana",
                    nrp: "5027211035"
                },
                {
                    name: "Caroline Permatasari Pramestita G. K.",
                    nrp: "5027211048"
                },
                {
                    name: "Rakha Aldo Nirwasita",
                    nrp: "5027211054"
                },
                {
                    name: "Made Gde Krisna Wangsa",
                    nrp: "5027201047"
                }
            ]
        }
    }
  }

</script>

<style>

</style>