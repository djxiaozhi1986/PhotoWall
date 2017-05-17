# PhotoWall
这是一个带3D倒影效果的照片墙案例，遵循前端开发规范
实现思路：
1、通过js添加要求数目的img。     
2、将所有的img编号，选定中间序号的图片定位到屏幕的中间位置。        
3、通过序号以及中间位置给每一个图片设置left进行定位，使得保持中间图片位置不变，其他图片两两之间间距100px，并将这些left保存到数组中。      
4、中间序号之前和之后位置的图片分别进行样式倾斜。       
5、点击某张图片，将该图片(减去或加上一个距离）通过left定位到屏幕中间，其他所有的图片移动相同的距离，更行left数组。       
6、更新中间图片序号。      
[点击这里](https://sanchunpeng.github.io/PhotoWall/)