<template>
<div class="an10">
    <ul class="an-an100">
       <li><a href="">trang chủ</a></li>
       <li><a href="">tài liệu</a> 
            <ul class="an10-an100-100">
                <li><a>anh văn</a></li>
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
    border: 1px solid black;
    padding: 0%;
    width: 140px;
    height: 200px;
    display: none;
}

ul.an10-an100-100:hover{
    display:block;
}
</style>
<script>
export default{
    name: "navar"
}
</script>