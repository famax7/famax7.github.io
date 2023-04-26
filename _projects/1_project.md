---
layout: page
title: 陈艺舟别睡了
description: 陈艺舟和地理课的爱恨情仇
img: assets/img/dontsleep.gif
importance: 1
category: 学校篇
---

每次上地理课，赵阳的讲解就像是一场催眠表演，对于陈艺舟来说，他的眼皮仿佛有几个西瓜一样沉重，无法抵御睡意的侵袭。不幸的是，陈艺舟总是坐在第一排，每当他闭上眼睛，赵阳总能准确地发现他的状态并大声喊道：“陈艺舟，别睡了！”几乎每节地理课，陈艺舟都会成为赵阳的点名对象，让他感到十分尴尬。即使有时他没有入睡，赵阳的口头警告仍然不时响起，成为了地理课堂上的一道常规操作。



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dontsleep.gif" title="陈艺舟别睡了" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    由赵冠宇创作的陈艺舟别睡了的梗图。出自2010年香港电视广播有限公司制作的连续剧《读心神探》中的一句对白。
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="center" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
