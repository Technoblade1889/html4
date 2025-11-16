# html4
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML练习4-表单</title>
</head>
<body>
    <!-- form标签通常用于创建表单。只要将想写的内容写在内部即可。
     目前我只是稍微了解，没有深入学 -->
    <form action=""></form>
    <form>
        <input type="text">
        <!-- input是最常用的，对它也有很多的属性。
         text的作用就是出现搜索框 -->

         <input type="text" placeholder="请输入文本">
         <!-- placeholder的作用就是实现隐藏字体 -->

         <input type="text" value="请输入文本"><br><br>

         <!-- value则是不会隐藏 -->

          <!-- 然后结合span就可以对搜索框进行定义，比如名字。
          ps：span可以用label代替，但label只能用于和input同时进行 -->
         <label >name:</label>
         <input type="text" placeholder="请输入文本"><br><br>
         <span>密码：</span>
         <input type="text" valuer="请输入文本"><br>

         <!-- 选择项 -->  
         <label for="">性别</label><br>
         <input type="radio" name="gender">男<br>
         <input type="radio"name="gender">女<br>
         <input type="radio"name="gender">武装直升机<br>
         <input type="radio"name="gender">沃尔玛购物袋<br>
         <!-- name是用于锁定单选 -->

         <input type="password" placeholder="请输入文本"><br>
         <!-- password用于隐藏密码 -->


         <!-- 多选 -->
          <label>爱好：</label>
          <input type="checkbox" name="hobbby">唱歌<br>
          <input type="checkbox" name="hobbby">跳舞<br>
          <input type="checkbox" name="hobbby">rap<br>

          <input type="submit">


    </form>




</body>
</html>
