## 百度前端技术学院任务

[toc]



### 百度前端技术学院2016任务

#### 任务Part1 Demo(html/css)

 1. xxxxx

 2. xxxxx

 3. [三栏三式布局](./2016-part1/task3.html)

 4. [定位和居中问题](./2016-part1/task4.html)

 5. [零基础HTML及CSS编码](./2016-part1/task5.html)

 6. [任务六：通过HTML及CSS模拟报纸排版](./2016-part1/task6.html)

    ```js
    1.块元素中左右两个行内块, 右侧如果没有设置这vertical-align:top 这个行内块元素会下移.
    
    2.calc(8.5px - 122px) 运算符两侧需要有空格
    
    3.font-size:0;后br的高度为0
    
    4. margin全为负值
    ```

    

 7. [任务七：实现常见的技术产品官网的页面架构及样式布局](./2016-part1/task7/task7.html)

    1. <li>转换成行内块做导航后,没有使用line-height. 文字没有移动,反而是ul整体向下移动了.  基线?

    2. 通用兄弟选择器 ~

    3. ul与li实现导航. 使用另外的li实现底部红色border
      3.1 div中的ul整体下移2px,已经加了padding/margin为0. 父元素<nav>使用vertical-align:top; 默认设置为baseline
      //https://stackoverflow.com/questions/13390220/why-does-an-inline-block-div-get-positioned-lower-when-it-has-content/

    4. background-size: 100% auto;

    5. form元素中的input自动上移2px   使用vertical-align解决. 
     原因: https://www.cnblogs.com/starof/p/4512284.html https://mxd.tencent.com/1862.html

    6. letter-spacing:30px;
      7.p标签的padding与margin均为0,line-height也为0, 那么p的高度为0.但文字还能显示一部分; 如果line-height不设置为0,p的高度为字体高度+基线高度?
      
    7. 图片一侧三角形实现
      7.1 伪元素+border
      7.2 伪元素

      ```css
      //8.1 用border比较好吧. 可以少写一些. 虽然都由可能覆盖右侧内容,
      section#part6 .left:after{
        position: absolute;
        top: 50%;
        margin-top: -20px;
        top: -20px;
        content: "";
        border: 40px solid;
        border-color: transparent #fff trasparent transparent;
      }
      
      //8.2
      section#part6 .left.after{
        position: absolute;
        top: 50%;
        margin-top: -20px;
        top: -20px;
        content: '';
        width: 40px;
        height: 40px;
        background: #fff;
      }
      ```

    8. section6的右侧的div设置宽度后, 左侧的div下移道最底部. 左侧行内块设置vertical-align:top

    9. 两个行内块中间有缝隙的解决方法: font-size; letter-spacing:-0.33333em;负值; margin负值; 使用注释(\<!-- -->); 改变html结构,换行时标签首尾相连. 

    10. 3个input元素使用绝对定位以后,发生重叠现象

    11. 单选按钮+空div+display:none实现多个模块的切换

 8. xxxx

 9. 







### 百度前端技术学院2017任务



### 百度前端技术学院2018任务



<hr style="background:red;"/>



