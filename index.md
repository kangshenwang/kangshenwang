## 套用模板太没意思了，王小胖的尝试

首先一个超链接，<a href='https://space.bilibili.com/386198165'>我的B站账号</a>，我的邮箱地址:kangshenwang@gmail.com
### 第一部分
<p style="color:#00FF00">老年人</p>

<img src='https://github.com/kangshenwang/kangshenwang/blob/master/wang1.png' alt='老年人的英姿1' />	
<img src='https://github.com/kangshenwang/kangshenwang/blob/master/wang1.jpg' alt='老年人的英姿2' />	


### 第二部分
家父格言
<blockqoute style="color:#66CCFF">
   <big>
   <p>我四五点起来就跑步，练功</p>
   <p>人活年老树活皮，你个驴哈蛋</p>
   </big>
</blockqoute>



<!--侧栏页面设计-->
<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="#">About</a>
  <a href="#">Services</a>
  <a href="#">Clients</a>
  <a href="#">Contact</a>
</div>
 
<h2>右侧侧边栏</h2>
<p>点击以下菜单图标打开侧边栏，并显示在右侧。</p>
<span style="font-size:30px; cursor:pointer" onclick="openNav()">&#9776; 打开</span>

<script type="text/ecmascript">
    /*改变原始宽度（0）*/
    function openNav() {
        document.getElementById("mySidenav").style.width = "250px";
    }
    /*恢复原始宽度0*/
    function closeNav() {
        document.getElementById("mySidenav").style.width = "0";
    }
</script>

@charset "utf-8";
/* CSS Document */
 
body {
    font-family: "Lato", sans-serif;
}
 
/*侧边栏选择器*/
.sidenav {
    height: 100%;
    width: 0; /*原始宽度为0*/
    position: fixed;
    z-index: 1;
    top: 0;
    right: 0;
    background-color: #111;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}
 
/*侧边栏选项选择器*/
.sidenav a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    color: #818181;
    display: block;
    transition: 0.3s;
}
 
/*侧栏标签和关闭按钮光标的效果*/
.sidenav a:hover, .offcanvas a:focus{
    color: #f1f1f1;
}
 
/*侧栏和关闭按钮的位置选择器*/
.sidenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-left: 50px;
}
 
/*当文档高度小于450px时，改变侧栏的padding属性和字体大小*/
@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
