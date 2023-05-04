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
        <ul class="an10-an100-200">
                <li ><a>anh văn</a></li>
                <li><a>tự nhiên</a>
                    <ul class="an10-an100-200-1">
                        <li><a href="">toán </a></li>
                        <li><a href="">li</a></li>
                        <li><a href="">hóa</a></li>
                        <li><a href="">sinh</a></li>
                    </ul>
                </li>
                <li><a>xa hội</a>
                    <ul class="an10-an100-200-2">
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
.an-an100 a{
    color: black;
}
.an-an100{   
    border:none;
    width: 1400px;
    height: 50px ;
    padding: 0px;
}
.an-an100{
    display: flex;
    justify-content: space-around;
    margin: 0;
    font-size: 20px;
    font-family: 'Times New Roman', Times, serif;
    transition: 200s;
    background: linear-gradient(180deg, #CD2929 0%, rgba(184, 61, 61, 0) 100%);
}
.an10-an100-100{
    border:1px solid  ;
    width: 200px;
    text-align: center;
    padding: 0%;
    position: absolute;
    display:none;
    background: linear-gradient(180deg, #d65a2dbb 0%, rgba(184, 61, 61, 0) 100%);
    border: none;
    border-radius: 10px;
    padding: 5px;
    padding-top: 12px;
    transition: 200s;
   left: 390px;
}
.an10-an100-200{
    border:1px solid  ;
    width: 200px;
    text-align: center;
    padding: 0%;
    position: absolute;
    display:none;
    background: linear-gradient(180deg, #d65a2dbb 0%, rgba(184, 61, 61, 0) 100%);
    border: none;
    border-radius: 10px;
    padding: 5px;
    padding-top: 12px;
   left: 710px;
   transition: 200s;
}
.an10-an100-100-200-1 a::after{
    content: '';
    clear: both;
    display: block;
    border-bottom:1px solid;
    border-color: white;
    margin: 5px;
}

.an10-an100-200-1{
    position:absolute ;
    top: 45px;
    left: 210px;
    border: 1px none;
    width: 200px;
    text-align: center;
    padding: 0;
    background: linear-gradient(180deg, #d65a2dbb 0%, rgba(184, 61, 61, 0) 100%);
    display: none;
   
}
.an10-an100-200-2{
    position:absolute ;
    top: 45px;
    left: 210px;
    border: 1px none;
    width: 200px;
    text-align: center;
    padding: 0;
    background: linear-gradient(180deg, #d65a2dbb 0%, rgba(184, 61, 61, 0) 100%);
    display: none;
    margin-top:5px ;
    
   
}
.an10-an100-100-200-2 a::after{
    content: '';
    clear: both;
    display: block;
    border-bottom:1px solid;
    border-color: white;
    margin: 5px;
}
.an10-an100-200 a::after{
    content: '';
    clear: both;
    display: block;
    border-bottom:1px solid;
    border-color: white;
    margin: 5px;
}
.an10-an100-100-100-1{
    position:absolute ;
    top: 45px;
    left: 210px;
    border: 1px none;
    width: 200px;
    text-align: center;
    padding: 0;
    background: linear-gradient(180deg, #d65a2dbb 0%, rgba(184, 61, 61, 0) 100%);
    display: none;
    
}
.an10-an100-100-100-1 a::after{
    content: '';
    clear: both;
    display: block;
    border-bottom:1px solid;
    border-color: white;
    margin: 5px;
}
.an10-an100-100-100-2{
    position:absolute ;
    top: 45px;
    left: 210px;
    border: 1px none;
    width: 200px;
    text-align: center;
    padding: 0;
    background: linear-gradient(180deg, #d65a2dbb 0%, rgba(184, 61, 61, 0) 100%);
    display: none;
   
}
.an10-an100-100-100-2 a::after{
    content: '';
    clear: both;
    display: block;
    border-bottom:1px solid;
    border-color: white;
    margin: 5px;
}
.an10-an100-100 a::after{
    content: '';
    clear: both;
    display: block;
    border-bottom:1px solid;
    border-color: white;
    margin: 5px;
}
.an-an100 a:hover{
    color: white;
}
.an-an100 ul>li:hover>ul{
    display: block;
}
.an10 ul>li:hover>ul{
    display: block;
}
</style>
<script>
export default{
    name: "navar"
}
</script>