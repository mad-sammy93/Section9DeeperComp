<template>
    <form @submit.prevent="submitSearch">
        <p>{{ username }}</p>
        <input type="text" placeholder="Search">
        
        <button>Search</button>
    </form>
</template>
<script>
export default{
    // data(){
    //     return{ 
    //         searchvalue:{
    //             type:String,
    //             required:true,
    //         }
    //     },
    // },
    props:{
        username:{
            type:String,
            required:true,
        },
    },
    methods:{
            submitSearch(){
                alert('search');
            }
        }
}
</script>
<style>
button{
    border-radius: 10px;
    border: 1px solid transparent;
    height: 20px;
}
input{
    border-radius: 3px;
    border: 1px solid black;
    height: 20px;
}
</style>