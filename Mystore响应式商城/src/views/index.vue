<template>
    <div>
        <div class="header-top">
            <div class="container">
                <div class="row">
                    <div class="col-sm-4 hidden-xs">
                        <div class="welcome">
                            <p>欢迎来到XX商城网上购物</p>
                        </div>
                    </div>
                    <div class="col-xs-12 col-sm-8 col-md-offset-3 col-md-5 header-menu">
                        <ul>
                            <li><a href="" class="glyphicon glyphicon-user"><span class="hidden-xs">我的账户</span></a></li>
                            <li><a href="" class="glyphicon glyphicon-shopping-cart"><span class="hidden-xs">购物车</span></a></li>
                            <li><a href="" class="glyphicon glyphicon-heart-empty"><span class="hidden-xs">收藏夹</span></a></li>
                            <li><a href="" class="glyphicon glyphicon-star-empty"><span class="hidden-xs">登录</span></a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-sm-4 col-xs-12 logo">
                    <a href="#"><img src="../assets/img/index/logo.png" alt=""></a>
                </div>
            </div>
        </div>
        <div class="nav">
            <div class="container">
                <div class="row">
                    <div  class="col-xs-6 hidden-sm hidden-md hidden-lg">
                        <div class="glyphicon glyphicon-align-justify drop-sm">

                        </div>
                    </div>
                    <div class="col-sm-4 col-md-3  hidden-xs">
                        <div class="drop">
                            <h3 class="hidden-xs">按类别购物</h3>
                            <span class="glyphicon glyphicon-align-justify"></span>
                            <ul style="display: none">
                                <li class=""><a href=""><i class="glyphicon glyphicon-blackboard"></i>家用电器 <span class="glyphicon glyphicon-menu-right"></span></a></li>
                                <li class=""><a href=""><i class="glyphicon glyphicon-blackboard"></i>家用电器 <span class="glyphicon glyphicon-menu-right"></span></a></li>
                                <li class=""><a href=""><i class="glyphicon glyphicon-blackboard"></i>家用电器 <span class="glyphicon glyphicon-menu-right"></span></a></li>
                                <li class=""><a href=""><i class="glyphicon glyphicon-blackboard"></i>家用电器 <span class="glyphicon glyphicon-menu-right"></span></a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-xs-9 col-sm-6 hidden-xs">
                        <div class="input-group">
                            <input type="text" class="form-control">
                            <select name="" id="" class="cate-dropdown">
                                <option value="">所有类别</option>
                                <option value="">1</option>
                                <option value="">2</option>
                                <option value="">3</option>
                                <option value="">4</option>
                                <option value="">5</option>
                                <option value="">6</option>
                            </select>
                            <button class="btn-search"><i class="glyphicon glyphicon-search"></i></button>
                        </div>
                    </div>
                    <div class="col-md-3 col-sm-2 col-xs-6">
                        <div class="cart">
                            <p class="glyphicon glyphicon-shopping-cart"></p>
                            <div class="hidden-sm hidden-xs ib">
                                <p>购物车</p>
                                <span>1件商品:$520.00</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <Carousel></Carousel>
        <div class="container">
            <Navbar></Navbar>
        </div>
    </div>
</template>
<script>
    import "../assets/css/base.css"
    import "../assets/css/bootstrap.css"
    import "../assets/css/index.css"
    import Carousel from "@/components/Carousel"
    import Navbar from "@/components/Navbar"
    export default{
        data(){
            return {}
        },
        methods: {},
        mounted(){

        },
        components:{
            Carousel,
            Navbar
        }
    }
</script>
<style>

</style>