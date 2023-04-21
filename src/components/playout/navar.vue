<template>
<div class="an10">
    <ul class="an-an100">
       <li><a href="">trang chủ</a></li>
       <li><a href="">tài liệu</a> 
            <ul class="an10-an100-100">
                <li ><a>anh văn</a></li>
                <li><a>tự nhiên</a>
                    <ul class="an10-an100-100-100-1">
                        <li><a href="">toán </a></li>
                        <li><a href="">li</a></li>
                        <li><a href="">hóa</a></li>
                        <li><a href="">sinh</a></li>
                    </ul>
                </li>
                <li><a>xa hội</a>
                    <ul class="an10-an100-100-100-2">
                        <li><a href="">sữ </a></li>
                        <li><a href="">địa</a></li>
                        <li><a href="">cd</a></li>
                        <li><a href="">ngữ văn</a></li>
                    </ul>
                </li>
            </ul>
        </li>
       <li><a href=""> thi thử</a>
            <ul class="an100-100">
                    <li><a>anh văn</a></li>
                    <li><a>tự nhiên</a>
                        <ul class="an10-an100-100-100-3">
                            <li><a href="">toán </a></li>
                            <li><a href="">li</a></li>
                            <li><a href="">hóa</a></li>
                            <li><a href="">sinh</a></li>
                        </ul>
                    </li>
                    <li><a>xa hội</a>
                        <ul class="an10-an100-100-100-4">
                            <li><a href="">sữ </a></li>
                            <li><a href="">địa</a></li>
                            <li><a href="">cd</a></li>
                            <li><a href="">ngữ văn</a></li>
                        </ul>
                    </li>
                </ul>
        </li>
       <li><router-link to="">đăng nhập /đăng kí</router-link></li>
    
    </ul>
</div>
</template>
<style>
ul {
   
    list-style: none;
}
a{
    text-decoration: none;
}
.an-an100{
    display: flex;
    justify-content: space-between;
}
ul.an10-an100-100{
    padding: 0%;
    display: none;
    position: absolute;
    right: 888px;
    margin: 5px;
    transition: all 0.2s ease-in;
}
.an10-an100-100 li{
    margin-left: 0px;
    margin-top:5px;
    margin-bottom:10px;
}
.an-an100>li:hover>ul{
    display:block;
}
.an10-an100-100-100-1{
    padding: 0%;
    display: none;
    position: absolute;
    right: 0px;
    top: 17px;
    left: 65px;
    transition:4s;
    
}
.an-an100 ul>li:hover>ul{
    display: block;
    
}
.an10-an100-100-100-2{
    padding: 0%;
    display: none;
    position: absolute;
    right: 0px;
    top: 60px;
    left: 65px;
}
</style>
<script>
export default{
    name: "navar"
}
</script>