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


