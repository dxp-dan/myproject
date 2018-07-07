<template>
    <div class="row">
        <Promotion></Promotion>
        <NewPro></NewPro>
    </div>
</template>
<script>
    import Promotion from "@/components/product_list/Promotion.vue";
    import NewPro from "@/components/product_list/NewPro.vue";
    export default{
        name:"Navbar",
        data(){
            return{}
        },
        methods:{},
        components:{
            Promotion,
            NewPro 
        }
    }
</script>
<style scoped>
    .row{
        height:435px;
    }
</style>

