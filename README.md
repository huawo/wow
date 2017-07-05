# wow
live


<!doctype html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>wow</title>
	<link rel="stylesheet" href="jquery-ui.css">
	<link rel="stylesheet" href="wow.css">
	<link rel="stylesheet" href="bootstrap.min.css">
	<script  src="jquery.js"></script>
	<script  src="jquery-ui.js"></script>
	<script  src="bootstrap.min.js"></script>
	<script src="wow.js"></script>
	<script src="vue.js"></script>
</head>
<body style="background:#ff6666">

	<div class="htabs">
			<ul>
				<li><a href="#hhtml">HTML</a></li>
				<li><a href="#hcss">CSS</a></li>
				<li><a href="#hjs">JAVASCRIPT</a></li>
				<li><a href="#hjquery">JQUERY</a></li>
				<li><a href="#hbootstrap">BOOTSTRAP</a></li>
				<li><a href="#hswiper">SWIPER</a></li>
				<li><a href="#hangularjs">ANGULARJS</a></li>
				<li><a href="#hvue">VUE</a></li>
				<li><a href="#hsvg">SVG</a></li>
			
			</ul>

			<div id="hhtml">
					<div class="horde">
						window是只浏览器对象，JS中的点击作用域，一切方法和属性都是这个对象的子集；<br>
						document文档或对象，是window的子集。
						<br>
						<b>怪异模式-<span>混乱模式</span> 和 标准模式-<span>严格模式</span></b><br>
						没有《！doctype html》文档申明浏览器会用老版本的浏览器使用规则来渲染页面；有则以W3C标准
						<br>
						<b>区别：</b> <br>
						<b>盒模型-</b>怪异模式盒模型=IE盒模型；<span>width="content+paddingLeft+paddingRight+borderLeft+borderRight"</span><br>标准模式盒模型；<span>width=content</span>




						<hr>
						<b>外边距合并 竖向取最大值，横向相加</b><br>
						<del>sublime一行点击三次可直接复制粘贴</del>
						<hr><!-- 分割线 -->
						
						background:linear-gradient(to left top,rgb(),rgb())//渐变阴影 ;<br>
						background:url() no-repeat top center; 图片居顶 居中；
						<h2>javascript javascript javascript javascript javascript;</h2><br>
						<del>canvasHTML5新标签用于创建自定义图形</del>

						
						
						
					</div>

					<hr style="width:80%">

					<div style="width:200px;height:30px;background-color:red;display:block">block 块级元素</div>
					<div style="width:200px;height:30px;background-color:blue;display:block">block 块级元素</div>
					<div style="width:200px;height:30px;background-color:orange;display:block">block 块级元素</div>

					<!-- 可指定长宽，独占一行 -->
					
					<hr>
					<div style="width:200px;height:30px;background-color:red;display:inline-block">inline-block 内联块</div>
					<div style="width:200px;height:30px;background-color:blue;display:inline-block">inline-block 内联块</div>
					<div style="width:200px;height:30px;background-color:orange;display:inline-block">inline-block 内联块</div>
					<!-- 可指定长宽，放在一行 -->
					
					<hr>
					<div style="width:200px;height:30px;background-color:red;display:inline">inline 内联</div>
					<div style="width:200px;height:30px;background-color:blue;display:inline">inline 内联</div>
					<div style="width:200px;height:30px;background-color:orange;display:inline">inline 内联</div>
					<!-- 不可指定长宽，放在一行 -->
					<div class="after">
						<br>white-space:normal/nowrap；<span>正常换行/不换行</span>
						<br>overflow:hidden;<span>超出隐藏</span>
						<br>text-overflow:ellipsis;<span>显示省略</span>
						<br>white-space:nowrap;<span>不换行</span>
						<br>outline：none；<span>取消按钮、表单轮廓</span>
						<br>vertical-align：middle；<span>图片垂直居中</span>
						<br>letter-spacing：xxpx；<span>字间距</span>
						<br>cursor:pointer；<span>鼠标手型</span>


					</div>
					

					<br> <b>响应式</b>
					<br>当页面长度设为100%自适应时，缩小网页会产生空白所以min-width：1263px；最小长度。
					<br> 

					<h2>块级元素和内联元素（inline行内元素）</h2>
					div是块级元素，在没有任何属性布局时，默认排序方式是换行排序；<br>
					span是内联元素，在没有任何属性布局时，默认是同行排序 直到超出容器宽度则自动换行。<span>内联元素可通过displayblock装转换为块级元素</span><br>
					<span>（a ; img ; span ; small ; ） 其中input是内联块 元素既可以设置长宽又可以放在同一行</span>





						

			</div>

			<div id="hcss">
				<div class="flex box"><!-- css3盒模型 -->
					<h2>css3盒模型</h2>
						<b>百分比元素居中</b><br>
						   在HTML和body中设置宽高，
						   position:fixed; top:50%; left:50%;
						   transform:translate(-50%,-50%);
							<!-- 浏览器兼容 -->
							<br>浏览器兼容
						   .flex-container {
							 display: -webkit-box;
							 display: -moz-box;
							 display: -ms-flexbox;
							 display: -webkit-flex;
							 display: flex;
							}
							<br>
							<br>


						
					    <b>弹性布局</b><br>:父元素设置 display：flex；  					子元素flex：1，flex:1；<br>

					   			父元素     flex-direction：row(默认的)  ;
					    	  			  flex-direction：column（垂直）;
					    	  			  flex-wrap：wrap（超出换行）   ;

					    	  			  flex-flow: column wrap;(连写);

						<br>
					   条目尺寸的弹性由三个css属性来确定；flex-basis；flex-grow；flex-shrink；
					   flex-basis与width一样；
					   flex： 1 1 auto；<!-- 默认值；可以连写上面三个 --> 	 


					   <br>
					   <br>

					<div style="display:flex;flex-flow:row ;width:500px">
						<div style="border:1px solid orange;height:100px;flex:1"></div>
						<div style="border:1px solid red;height:100px;flex:5"></div>   
						<div style="border:1px solid red;height:100px;flex:4"></div>
						<div style="border:1px solid red;height:100px;flex:100px"></div>
				    </div>
				</div>
				<h2>伪类</h2>
					<div class="after">
						:hover； <br>
						:first-child； <br>
						:link； <span>未访问链接</span><br>
						:visited；  <span>已访问链接</span><br>
						:active；  <span>已选中链接</span><br>
						<br>
						<b>transform变形</b> <br><br>	
						transform:rotate(xdeg); <span>10deg=10度 旋转</span> <br>
						transform:skew(xdeg);  <span>倾斜</span> <br>
						transform:scale(1); <span>缩放</span> <br>
						transform:translate(1px,1px); <span>位移</span> <br><br>
						<b>transition过渡</b><br><br>
						transition:width 2s,hieght 2s;<br><br>
						dl{clear：left};dd,dt{float:left};

					</div>
					


			</div>

			


			<div id="hjs">
					<b>1语法. js有两个主要的语法类型；不就是表达式和语句嘛，if语句知道吧；而表达式产生值 var知道吧</b><br>
					<del>2.变量和赋值 js中变量使用前必须提前声明</del><br>
					<b>3.值 </b><br>
					<div class="function">
					<!-- 函数 -->

					<b>var hua=null;声明一个初始化变量，以供后面函数使用！</b><br>
						<del>声明变量分为显示声明和隐式声明；javascript把隐式声明的变量当成全局变量来使用（即不使用var）</del><br>
						<b>在局部作用域内给全局变量赋值会改变全局变量的值（见上面的鼠标延迟触发）</b> 
						<b>按照约定事件处理程序属性的名字是以on开始的(window.onload)</b><br><hr>
					<b>构造函数</b><br>
					<!-- function hua(){} -->  <!-- 函数构成：function后面跟个函数名称标识符 --> 
					<del>构造函数前面带有关键字new；</del>
					构造函数在没有形参时可以省略括号 var 0=new object(<!-- 括号可省略 -->)；<br>
					构造函数通常不使用return关键字，他们通常初始化新对象
					构造函数首字母大写 var 0=new Object();

					</div>

					<h2>闭包</h2>
						<b>闭包就是一个函数把外部不属于自己的对象也包含进来了（闭合）；函数内的嵌套函数能使用自己外部的局部变量</b><br><br>						
						<div class="after">
							&&  ||  !   <span>与或非</span>

						
						<h2>循环语句</h2>
						<b>switch 基于不同的条件来执行不同的动作</b><br>
						switch(box){	<br>
							case1:         <span>执行代码块1</span> <br>
							<i></i>	alert();  <br>
							<i></i>	break;		<span>打断，执行下一个</span> <br>
							case2:  <br>
							<i></i>	alert(); <br>
							<i></i>	break; <br>
							default:	<br>
							<i></i>	alert();	<span>与if语句的else相同</span> <br>
						} <br><br>

						<b>while 只要条件为true，循环就可以一直执行</b><br>
						while(条件){ <br>
						<i></i>	alert()； <br>
						}
						<br>
						<b>do/while 先执行一次，在判断是否循环</b>	<br>
						do{ <br>
						<i></i>	alert() <br> 
						}while(条件)； <br><br>
						<b>for 可以将代码块执行指定的次数</b> <br>
						for (var i=0;i<5;i++){

				
						}
						

						</div>
						<br>
						
						普通函数，被其他函数调用时，是在调用者内部直接写函数名调;
						回调函数，通常是作为参数传递给调用者，调用者并不知道自己调用的到底是什么
						<br>

			</div>

			<div id="hjquery">
					<div class="after">
					<b>speed与callback参数可选， 速度，完成后执行的函数</b><br>
					.toggle(speed,callback);<span> 切换hide(),show()效果;  参数可选</span> <br>

					.fadeIn(speed,callback);<span>淡入</span> <br>
					.fadeOut(speed,callback);<span>淡出</span> <br>
					.fadeToggle(speed,callback);<span>切换淡入淡出</span><br><br>

					.slideDown(speed,callback);<span>下滑</span><br>
					.slideUp(speed,callback);<span>上滑</span><br>
					.slidetoggle(speed,callback);<span>切换</span><br><br>


					<b>animate</b><br>
					animate({},speed,callback); margin-left写为marginLeft；
					width+=可在原基础上加；{height：“toggle”} <br>


					stop(stopAll,goToEnd);可用于停止动画，在他们完成之前。
					<br>//stopall是否清楚所有列队动画，默认是false，仅停止当前动画
					<br>//gotoend是否立即完成当前动画，默认是false，


					<br><b>！如果你希望在一个动画完成之后来执行语句，请使用callbback函数；</b> <br><br>

					<b>DOM</b>（文档对象模型）是为了操作文档document出现的一个API，document是其一个对象；<br>
					<b>BOM</b>（浏览器对象模型）为了操作浏览器出现的API，window是其的一个对象；


					input.val(); //value的方法 获取value；


					<br>
					<b>DOM遍历</b><br>
					向上遍历DOM树
					.parent();选择父元素；
					.parents();选择所有祖先元素 直到html；
					.parentsUntil();选择之间的所有祖先元素 直到html
					<br>
					向下遍历DOM树
					.children();直接子元素
					.find();
					<br>
					同胞元素遍历
					.siblings();所有同胞元素；
					.next();下一个同胞；
					...
					... 


					过滤
					first();
					last();
					eq();

					<br>
					<b>AJAX是与服务器交换数据的艺术，不重新加载全部页面的情况下，实现了对局部网页的更新</b>
					<br>
					.load(url,data,callback);
					//data规定与请求一同发送的查询字符串键值对集合


					GET从指定的资源请求数据（基本用于取回数据，可能返回缓存数据）；
					POST向指定的资环提交要处理的数据（也可用于从服务器获取数据	，不会缓存数据）

					$.get(URL,callback);





					<div class="zhushi">
					<h2>控制鼠标延迟触发 轮播器</h2>
					

					var hua=null; 		<p>设置定时器,声明一个定义为null空的变量</p>
					$function(){  			<p>匿名函数包起来</p>
						$(".box").hover(function(){<br>
							hua=setTimeout(function(){},1000)  
							<p>此函数与下面函数作用域不同，所以不能把第一句放这里</p> 
							<p>再此局部变量内给全局变量赋值会改变全局变量的值</p>
							<p>若换成 var hua=set... 重新声明则不会</p>
						},function(){<br>
							if(hua){<br>
								clearTimeout(hua); <br><p>清除定时器！鼠标移开则清除settimeout函数。不停留两秒不执行！</p>
							} <br>	
						}); <br>
					} <br>

					</div>
				</div>

			</div>

			<div id="hbootstrap"> <br>
				<h2> 在父元素加入col-lg-5调整大小</h2>
					btn下拉菜单: <br>
					input里面form-control必加<br>
					navbar-left向左居中对齐<br>
					breadcrumb 面包屑导航<br>
					分割线 < li class="divider">< /li> <br>
					标题< li class="dropdown-header">< /li> <br>
					<b>input一行</b> <br>
					< div class="input-group"> <br>
					< span class="input-group-addon">@< /span> <br>
					< input type="text" class="form-control	"> <br>
					< /div> <br>


			</div> 

			<div id="hswiper">

			</div>

			<div id="hangularjs">
			
					<div class="after">
					<!-- 开发动态web应用的框架 -->
					<b>angularjs通过了指令扩展了HTML，切通过表达式绑定数据到HTML；</b><br>
					
					从下面苦海中解脱出来；<br>
					使用回调函数；以编程的方式操作HTML DOM；<br>
					在用户界面中读写数据；<br>
					在开始前写大量初始化代码；<br>
					<hr>
					什么是angularjs；<br>
					<b>angularjs把应用程序数据绑定到HTML元素；</b>
					<br>
					可以克隆和重复HTML元素；<br>
					可以隐藏和显示HTML元素；<br>
					可以再HTML元素背后添加代码；<br>	
					支持输入验证；<br>
					< div ng-app=""> <span>ng-app指令定义一个angular应用程序</span><br>
						< p>名字：< input type="text" ng-model="name">< /p><span>ng-model指令把元素值（如输入域的值）绑定到应用程序(变量name)；</span><br>
						< h2>Hellp{{name}}< /h2> <span>angularJs表达式写在双大括号内{{expression}}；</span><br>
					< /div><br>


					
					ang-app指令标记了angularjs脚本的作用域，在<html></html>中添加则说明了整个HTML都是angular的作用域；<br>

					ng-bind指令吧应用程序数据绑定到HTML视图；f可用{{}}代替 <br>
					< h1>{{name}}< /h1>==< h1>< span ng-bind="name">< /span>< /h1> <br> <br>

					ng-init指令初始化angularjs应用程序变量<!-- 。不是很常见 --> <br>
					ng-repeat指令会重复一个HTML元素： <br>
					
					<p>nothing here{{"yet"+"!"}}</p>
					angularJs表达式很像javascript表达式：可以包含文字，运算符和变量；

	    
					如果你想让你的应用自启动的话 那么就把ng-app放在应用跟节点，通常是<html>标签中
					< html ng-app>< /html>
							<br>
					自动初始化：
					 两个情况下自动初始化：一个是DOMcontentLoaded事件触发时；
					 或者在angular.js脚本被执行的同

					<h1> 视频输出格式，h.264。输出为MP4</h1>

					</div>

			</div>
			<div id="hvue">
				每个vue.js应用都是通过构造函数vue创建一个vue根实例启动的：<span>var vm=new Vue({})</span>	<br>
				指令：扩展html标签属性;<br>
				常用指令：v-model:一般用在表单元素上 input； <br>
				双向数据绑定！
					<div class="hvue">
						<input type="text" v-model="msg">
						{{msg}}
					</div>
				<hr>
				常用指令： v-for循环遍历《li v-for="name in arr"》 {{name}}
				<br>  v-on 绑定事件；v-onclick点击事件	
				<br><h2>new Vue({el:"element元素 选择器",data:"数据",methods:"方法函数"})</h2>

				参数：
				一些指令能接受一个参数，在指令的后面以冒号指明。<br>
				两个最为常用的指令缩写v-bind:href---：href && v-on:click----@click








			</div>



















































			<div id="hsvg">
					<div class="SVG">
						svg意为可缩放矢量图形；使用xml格式定义图像；SVG是使用xml来描述二维图形和绘图程序的预言；<br>
						svg用来定义用于网络的基于矢量图形；<br>
						svg是万维网联盟的基础；<br>
						svg除了ie浏览器都兼容；<br>

						一些预订图形：矩形  < rect>;<br>
									 圆形  < circle>;<br>
									 椭圆  < ellipse>;<br>
									 线	   < line>;<br>
									 折线  < polyline>;<br>
									 多边形< polygon>;<br>
									 路径  < path>;<br>	
									 feXXXXX 滤镜；<br>
									 <div></div>
					
						<b>例子：</b>
								<?xml version="1.0" standalone="no"?> 
									<!-- 包含xml声明，standalon属性规定svg文件是否独立，有无外部文件引用 -->

								<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" 
								"http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
									<!-- 引用的外部文件这里是DTD文件 -->

								<svg width="100%" height="100%" version="1.1"
								xmlns="http://www.w3.org/2000/svg">
									<!-- width和height设置svg文档的宽高，version定义所使用的svg版本 -->

								<circle cx="100" cy="50" r="40" stroke="black"
								stroke-width="2" fill="red"/>
									<!-- 设置图形的大小；stroke边框；fill颜色 -->

								</svg>	
								<hr>
								<div class="zhushi">

									< ?xml version="1.0" standalone="no"?> 
									<p>包含xml声明，standalon属性规定svg文件是否独立，有无外部文件引用 </p>
										

									< !DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" 
									"http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd"> 
									<p>引用的外部文件这里是DTD文件</p>
										<!--  -->

									< svg width="100%" height="100%" version="1.1"
									xmlns="http://www.w3.org/2000/svg"> 
									<p>width和height设置svg文档的宽高，version定义所使用的svg版本</p>
										<!--  -->

									< circle cx="100" cy="50" r="40" stroke="black"
									stroke-width="2" fill="red"/> 
									<p>设置图形的大小；stroke边框；fill颜色</p>
										<!--  -->

									< /svg>
								</div>								
					</div>
			</div>
	

	</div>
</div>


<!-- 	<div id="w">
		<ul>
			<li></li>
			<li></li>
			<li></li>
		</ul>

	</div>
 -->




</html>
	
</body>











