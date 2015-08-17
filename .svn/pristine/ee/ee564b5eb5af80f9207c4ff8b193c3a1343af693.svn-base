$(function(){
	$(".lingshan .cat-name").click(function() {
		swapClass($(this), "active");
		hideSiblings($(".dg-container[name="+$(this).attr("href")+"]"));
	});
	$(".top ul.nav li").mouseenter(function () {
		menuHeight = $(this).find(".dropdown-menu").height();
		$(this).parent(".nav").css("height",$(this).height() + menuHeight + "px");
	})
	.mouseleave(function () {
		$(this).parent(".nav").css("height",$(this).height() + "px");
	});
});



//自己添加class，兄弟节点去除class
function swapClass(item, className) {
	item.addClass(className);
	item.siblings().removeClass(className);
}

//自己出现，兄弟节点隐藏
function hideSiblings(item) {
	item.css("display","block");
	item.siblings().css("display","none");
}


