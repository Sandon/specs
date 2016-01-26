# 编码规范 - HTML

页面结构如下所示：

    <!DOCTYPE html>
	<html>
	<head lang="en">
	    <meta charset="UTF-8">
	    <title></title>
	</head>
	<body>
		<!--公共头部-->
	    <div id="header">
	    </div>

	    <!--内容区-->
	    <div id="content">

	        <!--一个横向布局-->
	        <div class="layout">

	            <!--一个模块-->
	            <div class="mod-xx">
	                <!--模块头-->
	                <div class="mod-header">
	                </div>
	                <!--模块内容区-->
	                <div class="mod-content">

	                    <!--可以将内容划分为多个part-->
	                    <div class="part-yy1">
	                    </div>
	                    <div class="part-yy2">
	                    </div>

	                </div>
	                <!--模块底部-->
	                <div class="mod-footer">
	                </div>
	            </div>

	        </div>

	    </div>

	    <!--公共底部-->
	    <div id="footer">
	    </div>
	</body>
	</html>

* `页面整体` 分为 `公共头部`， `内容区`， `公共底部`三大块；
* `内容区`中包含`布局（layout）`，可以包含多个`布局`；
* `布局`中包含`模块`，可以包含多个`模块`；
* `模块`有一个CLASS值以`mod-`作为前缀；
* *[optional]*`模块`分为`模块头部`，`模块内容区`，`模块底部`三个部分，分别对应CLASS值`mod-header`，`mod-content`，`mod-footer`；
* *[optional]*`模块内容区`中的内容可以划分为多个`部分（part）`，各个`部分`有一个CLASS值以`part-`作为前缀；




