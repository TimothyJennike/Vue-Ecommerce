<template>
    <div class="row">
            <Div v-for="cat in Felines" :key="cat" class="col-4 container-fluid just">
                <div class="card" style="width: 18rem;">
                <img :src="cat.image" class="card-img-top" alt="image">
                <div class="card-body">
                  <h3 class="card-title">Name:{{cat.name }}</h3>
                  <h3 class="card-text">Age:{{ cat.age }}</h3>
                </div>
              </div>
            </Div>
    </div>
</template>
<script>
export default {
    name: "cat",
    data() {
        return {
            Felines:[
                {
                    id: 1,
                    name: 'Brandon',
                    age: 19,
                    image: 'https://i.postimg.cc/Kj5gNh94/Culture-Grumpy-Cat-487386121.webp',
                },
                {
                    id: 2,
                    name: 'Maxwill',
                    age: 21,
                    image: 'https://i.postimg.cc/QxxB3P4k/maxwillcat.jpg'
                },
                {
                    id: 3,
                    name: 'Likay',
                    age: 19,
                    image: 'https://i.postimg.cc/sx03ynxw/cinnamon.webp'
                }
            ]
        }
    }
    
}
</script>
<style>
.row {
    justify-content: space-around;
    padding-top: 100px;
}
    
</style>