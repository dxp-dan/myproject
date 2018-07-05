<template>
    <div class="row">
        <Promotion></Promotion>
    </div>
</template>
<script>
    import Promotion from "@/components/product_list/Promotion.vue";
    export default{
        name:"Navbar",
        data(){
            return{}
        },
        methods:{},
        components:{
            Promotion   
        }
    }
</script>
<style scoped>
    .row{
        margin-top:30px;
    }
</style>

