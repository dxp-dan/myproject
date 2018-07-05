<template>
    <div class="carousel">
        <div class="show">
            <img :src="picSrc[num]"/>
        </div>
        <span @click.prevent="pre" class="btn-pre"></span>
        <span @click.prevent="next" class="btn-next"></span>
        <div class=""></div>
    </div>
</template>
<script>
    export default{
        name:"Carousel",
        data(){
            return {
                picSrc:[require("../assets/img/index/slider-bg1.jpg"),
                    require("../assets/img/index/slider-bg2.jpg"),
                    require("../assets/img/index/slider-bg3.jpg"),
                ],
                num:1
            }
        },
        methods: {
            pre(){
                this.num--;
                this.num==-1?this.num=2:this.num;
                console.log(this.num);
            },
            next(){
                this.num++;
                this.num==3?this.num=0:this.num;
                console.log(this.num);
            }
        },
        mounted(){

        }
    }
</script>
<style>

</style>