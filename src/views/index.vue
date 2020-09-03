<template>
    <div>
         <!--第二导航栏开始-->
   <div class="sub-nav clearfloat">   
	  <div class="sub-logo-left"><a href="">美食圈</a></div>
	  <div class="sub-serch-right right-float">	 
	   <div class="search-box">
			<a href="#" class="search-bth">搜索</a>
			<input type="text" class="search-text" placeholder="请输入搜索标题">	
		</div>
	  </div>
	   
	  <div class="sub-nav-title" id="subgatter">
	  	<ul class="sub-title-flex">
	  		<li><a class="active subNavchange" href="">首页</a></li>
	  		<li><a class="subNavchange" href="">菜谱</a></li>
	  		<li><a class="subNavchange" href="">食材</a></li>
	  		<li><a class="subNavchange" href="">珍选</a></li>
	  		<li><a class="subNavchange" href="">健康</a></li>
	  		<li><a class="subNavchange" href="">专题</a></li>
	  		<li><a class="subNavchange" href="">社区</a></li>
	  		<li><a class="subNavchange" href="">话题</a></li>
	  	</ul>
	  </div>	  
   </div>
   <!--第二导航栏结束-->
   <!--主体内容开始-->
	<div class="mian-content">	
		<div class="carousel-box">
		<ul class="carousel-img">
			<li><a href=""><img src="/img/banner/banner_2.jpg" alt=""></a></li>
			<li><a href=""><img src="/img/banner/banner_1.jpg" alt=""></a></li>
			<li><a href=""><img src="/img/banner/banner_3.jpg" alt=""></a></li>
			<li><a href=""><img src="/img/banner/banner_4.jpg" alt=""></a></li>
			<li><a href=""><img src="/img/banner/banner_5.jpg" alt=""></a></li>
		</ul>	
		<a href="#" class="prevBtn"><i></i></a>
		<a href="#" class="nextBtn"><i></i></a>
		<ul class="hollow-circle">
			<li></li>
			<li></li>
			<li></li>
			<li></li>
			<li></li>
		</ul>
		<div class="broadside">
			<ul>			
					<li class="i1"><a href="#"><i></i>菜谱大全<b></b></a></li>					
					<li class="i2"><a href="#"><i></i>食材大全<b></b></a></li>
					<li class="i3"><a href="#"><i></i>饮食健康<b></b></a></li>
					<li class="i4"><a href="#"><i></i>专题专区<b></b></a></li>
					<li class="i5"><a href="#"><i></i>一起红<b></b></a></li>
			</ul>						
		</div>
	 </div>
<!--实时美食新闻开始-->
<div id="foodNew" class="food-new-box">
		<div class="food-text-box">
			<div class="control">
				<a href="#" class="small-preBtn"><i>&nbsp;</i></a>
				<a href="#" class="small-nextBtn"><i>&nbsp;</i></a>
			</div>
			<div class="subtotal">
					<ul>
						<li>
							<a class="change-style" href="#">解馋又下酒的花生做法</a>						
						</li>
						<li>
							<p class="small-text">小美的菜单</p>
						</li>
						<li>
						<p class="main-text">新鲜的花生已经下来了，又可以做水煮花生了，水煮花生是一道很普遍很受欢迎的家常凉菜</p>
						</li>
					</ul>
			</div>
			<div class="subtotal">
				<ul>
					<li>
						<a class="change-style" href="#">解馋又下酒的花生做法</a>						
					</li>
					<li>
						<p class="small-text">小美的菜单</p>
					</li>
					<li>
					<p class="main-text">新鲜的花生已经下来了，又可以做水煮花生了，水煮花生是一道很普遍很受欢迎的家常凉菜</p>
					</li>
				</ul>	

			</div>
			<div class="subtotal">
				<ul>
					<li>
						<a class="change-style" href="#">解馋又下酒的花生做法</a>						
					</li>
					<li>
						<p class="small-text">小美的菜单</p>
					</li>
					<li>
					<p class="main-text">新鲜的花生已经下来了，又可以做水煮花生了，水煮花生是一道很普遍很受欢迎的家常凉菜</p>
					</li>
				</ul>	
			</div>
		</div>			
</div>


<!--实时美食新闻结束-->

</div>
   <!--主体内容结束-->     
    </div>
</template>
<style  scoped>
    /*第二部分导航栏样式*/
div.sub-nav{
	width: 990px;
	margin: 50px auto 0;	
	height: 65px;
	position: relative;
}
div.sub-logo-left{
	float: left;
	
}
div.sub-logo-left,div.sub-serch-right{
line-height: 65px;	
}
div.sub-serch-right{
	float: right;
}
div.sub-nav-title{
	/* float: right; */
	line-height: 65px;	
	/* padding: 0 65px 0 0; */
	position: absolute;
	left: 200px;
	
}

div.sub-nav-title>ul li{
	display: inline-block;
	padding-left: 10px;	
}
div.sub-nav-title>ul li a{
	color: #000;
	font-size: 20px;
}
div.sub-nav-title>ul li a.active{
	color:#ff6767;
	background-color: #fff;
}
div.sub-nav-title>ul li a:hover{
	color: #ff0000;
	background-color: #fff;
}
div.sub-logo-left a{
	font-size: 20px;
	color:#1E90FF;
}
div.sub-nav-title>ul li:last-child{
	padding-right: 50px;
}
.sub-serch-right>div.search-box>.search-text{
	width: 160px;
	border: 1px solid #ccc;
	border-right: none;
	border-radius: 3px 0 0 3px;
	height: 20px;
	line-height: 20px;
	padding: 3px;
	text-indent: 16px;
}
div.search-box>.search-text:focus{
	outline: #ccc;
	
}
	a.search-bth{
	float: right;
	border-radius: 0 3px 3px 0;
    width: 80px;
    height: 28px;
    font-size: 14px;
    text-indent: 35px;
    line-height: 28px;	
	background:#999 url(/img/font-img/search.png)no-repeat scroll 12px center/16px auto;
	margin-top: 21px;
	color: #fff;
	
	}
/*主体内容开始*/
div.mian-content{
	width: 990px;	
	border: 1px solid red;
	margin: 0 auto;
	
	
}
div.carousel-box{
	position: relative;
	overflow: hidden;
	height: 360px;
}
/*空心圆指示器*/
ul.hollow-circle {	
	position: absolute;
	right: 0;
	bottom: 0;
}
ul.hollow-circle li{
	width: 10px;
	height: 10px;
	border-radius: 50%;	
	border: 3px solid #999;
	margin: 10px;
	display: inline-block;
}
/*轮播图左右箭头*/
a.prevBtn,a.nextBtn{
	width: 40px;
	height: 60px;
	position: absolute;
	cursor: pointer;
	overflow: hidden;
	z-index: 5;
	border: 1px solid lawngreen;
}
/*侧边栏*/
div.broadside{
	position: absolute;
	left: 0;
	top: 0;
	width: 220px;
	height: 330px;
	padding: 30px 0 0;
	background: #444;
	background: rgba(68,68,68,.4);
	z-index: 4;
}
div.broadside>ul li{
   
}
div.broadside>ul li a{
	    display: block;
	    color: #fff;
	    height: 20px;
	    line-height: 20px;
	    padding: 20px 0;
	
}
div.broadside>ul li i,div.broadside>ul li b{
	width: 20px;
    height: 20px;
    float: left;
    margin: 0 10px 0 20px;	
	background: rgba(0,0,0,0) url(/img/banner/icon.png)no-repeat scroll 0 0/auto 20px;
}
div.broadside>ul li b{
	float: right;
	background-position: -100px 0;
}
div.broadside>ul .i2 i{
	background-position: -20px;
}
div.broadside>ul .i3 i{
	background-position: -120px;
}
div.broadside>ul .i4 i{
	background-position: -60px;
}
div.broadside>ul .i5 i{
	background-position: -80px;
}
/*美食实时新闻开始*/
.food-new-box{
	width: 990px;	
	background-color: #eee;
	margin: 10px auto 0;
	padding: 15px 0;
	position: relative;

}
div.control a.small-preBtn,div.control a.small-nextBtn{
	position: absolute;
	width: 30px;
	height: 30px;
	overflow: hidden;
	cursor: pointer;
	border-radius: 50%;	
	z-index: 100;
}

div.control a.small-preBtn{
	top: 45px;
	left: 5px;
}
div.control a.small-preBtn i,div.control a.small-nextBtn i{
	display: inline-block;
	background: url(/img/font-img/arrow.png)no-repeat scroll 0 0/auto 21px;
	width: 12px;
	height: 21px;
	margin: 4.5px 9px;
}
div.control a.small-nextBtn{
	top: 45px;
	right: 5px;
}
div.control a.small-nextBtn i{
	background-position: -12px 0;
}

.food-text-box{
width: 100%;
display: flex;
flex-flow: row nowrap;
justify-content: space-around;

}
.food-text-box .subtotal{	
	width: 255px;	
}
a.change-style{
	color:#333;
	font-size: 20px;
}
div.subtotal ul li p{
	margin: 0;
}
a.change-style:hover{
	color: #ff6767;
	text-decoration: underline;
	cursor: pointer;

}
div.subtotal ul li p.small-text{
	color: #999;
	font-size: 12px;
	margin:10px 0 5px;
}
p.main-text{
	color:#333;
	font-size: 12px;
}
/*美食实时新闻结束*/
/*主体内容结束*/
</style>>
<script>

export default {  
		data(){
			return{
				data:[]	
			}	
		},
		methods:{
		mounted(){
			this.axios.get('/food').then(result=>{
				console.log(1);
			})
		}
	}

}
</script>