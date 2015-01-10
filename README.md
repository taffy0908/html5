# html5 学习，也涉及javascript的示例

======

* jquery中$(window).load VS $(document).ready

$(window).load必须等待网页中所有的内容加载完毕后 ( 包括图片 ) 才能执行，
$(document).ready只要网页中所有 DOM 结构绘制完毕后就执行，可以能 DOM 元素关联的内容并没有加载完

* window.onload VS $(window).load()

js: window.onload页面一运行就执行该函数，执行该函数时，可能页面中的图片还没有加载完成！
jquery：  $(window).load()页面中的图片或其它东西加载完成之后，执行该函数。 