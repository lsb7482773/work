                                          沈仡立的开发报告

    本学期，我学习了web的知识，我希望能用这些知识做些我喜欢做的事，因此，我选择做了个游戏网站，来讲述我的游戏历史，

还有我最感兴趣的游戏。我不希望我的网站长篇累牍，希望能简明扼要地表达给浏览网页的人，同时希望突出游戏那种氛围。

    因此，宝生永梦的网站诞生了（滑稽），由七个网页做成，一个主页，一个个人介绍，一个介绍我的游戏历史，一个我的游戏列表

一个游戏截图，一个游戏人物介绍和游戏介绍。

    但本人还是菜鸟一枚，因此兼容性做的很差，网站只支持火狐浏览器，其他都有些问题，html和css都是最初的版本，没有用上

html5和css3。

    在做题时，需要标题因为不同背景图片而变换位置和字体大小，为了解决这个问题，我在css文件中定义了很多的标题大小和字体

如：.header h1 {
	position: absolute;
	top: 15%;
	right: 0;
	left: 0;
	width: 60%;
	margin: 0 auto;
	padding: 75px 0;
	font-size: 75px;
	letter-spacing: 3px;
	font-weight: 700;
	color: #FFF;
	background-color: rgba(0, 0, 0, 0.22);
	border: 5px solid #FFF;
}

.header h2 {
	position: absolute;
	top: 45%;
	left: 0;
	right: 0;
	width: 35%;
	margin: 0 auto;
	padding: 20px 0;
	font-size: 25px;
	letter-spacing: 2px;
	font-weight: 700;
	color: #000;
}
.header h4 {
	position: absolute;
	top: 15%;
	left: 0;
	right: 0;
	width: 35%;
	margin: 0 auto;
	padding: 20px 0;
	font-size: 25px;
	letter-spacing: 2px;
	font-weight: 700;
	color: #000;
}
.header h5 {
	position: absolute;
	text-align: center;
	top: 5%;
	left: 0;
	right: 0;
	width: 40%;
	margin: 0 auto;
	padding: 50px 0;
	font-size: 50px;
	letter-spacing: 3px;
	font-weight: 500;
	color: #FFF;
	background-color: rgba(0, 0, 0, 0.22);
	border: 5px solid #FFF;
}
.header h6 {
	position: absolute;
	text-align: center;
	top: 8%;
	left: 45%;
	width: 60%;
	margin: 0 auto;
	padding: 50px 0;
	font-size: 50px;
	letter-spacing: 3px;
	font-weight: 500;
	color: #FFF;
	background-color: rgba(0, 0, 0, 0.22);
	border: 5px solid #FFF;
}
完美的解决了这个问题。
     
    随后我也是自作自受吧，因为游戏太多，我不可能每个都做一个网站，

因此我想到了一个省时省力的方法，弄个链接去百度百科。   
<ul id="qqq">
<li><a class="scroll" href="http://baike.baidu.com/link?url=5E1mFkCIuva4jldPX2-wZwu21wjGNn9KCpWTqMoYkRMvQHJQiQxXRWxpbUvv8dvvMSF-Bmfe4d0bycZ_WXPlkKxqTAURqReyTwWrl3Lu09U6EyfTrL9D-rJx95UGM2k0">命令与征服：红警系列</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=5xw1_7cEAYQbFAzSxr-iXb5vDbXkLWK_OacIJ6PV-HbrQvDT9RZhoH4JTdWumTTf4OPVOlE9fzjljU-O9U8J-epw__kzezlPLeCSo0oQYEoEVGuvAYNYgaCIGA86SrX56URyz9ozLdYgWzEOlyjq7ytL7T7Q6SycGJ9WjhFvg_v2deyH2s0EaQPKJLnCCz85S_CpRDs5YHV08Y4jQMxF2_">命令与征服：泰伯利亚系列</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=t8SLk9TctChGdgwloqRPkoLpNnjIlGapPg2GbTAb5eWh51M8yAkfASUdIQ9bXFyotQ-Wyzyn8gREDfWNvWncaLgliHMUXKGj79E_Lr8JeQtMeb-DbnOqrUI0WhgQfebNsDRkXFDHRR6nSPP6fOJ3lqIfHa5SUVjYkex1u0DyPHK">命令与征服；将军系列</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=1gVh4nVnAEHUcj2vBqmeHnOwYPz8w2xjiF9rCc1L8Fs1HmkI6w1sV9wDKJZBY889FP_4UG7WXNwhZKHL-Fd9eQEc_pBr2oCEV5C6wiikHrTkRdmjwD4JDynkrNnYWJN4">星际争霸系列</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=AgpTMn7zpjPu45z7Zl2GcQklY0Q9diK0jJf4RHX6p4TTzx9mC-2rS4V2VPlpB8paboD-g7Ru0uoGmvxR81d5TwHFR49GkMH0oXmlnP4LJBc3v8Ss5FaajJ4LqmRk6X9P">魔兽争霸系列</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=NvUjHfJxpGQE1xZqIV9tpGvVbzGXgcuMruSIxuShtASxVIQPfFNtv1wNVBhrCujX_mS15ieWetL0Z5vmQRR6Ca">dota</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=t1pwjdZdTtaQASjOY2Z3tb-3SdIothTkofl-sBTiDjIHka1rohTIFO2kTiFYEycfePUlaKjhqGNNDSattwrNQYgJ4AalZnKB3X8k-yAuz5wW-k7lkmO1Y2d9fHv-926zRFS4-uamcZf0xjh0erogroyEOax_787MrNtjU5ZpThi">LOL</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=nvXj3h-_KhVZylYeDla6xL4Jr4XEpD5fMSkwW2HWi_x4mrSyAF5xsRPA0CkSwLIMsPW1FGteQG20aJd1WNPXEBLct_mqn5tgLuk2_NkDWtUrUhDiezi3BY-EAZvTKIUQ">使命召唤系列</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=lzXBPYINBiNyZ0bJ0EddxBNQJKJwS4heJQ6RxT7BrTpXJtHQRpeZIZwHTE9dINCFhH08mPHhGKDXo1o8WrSGXj_JMCNkkrSmh3u76EkkIUp_h1XaZdMxEgAUKoyeEMtDof6ayHOWyLEfwlFBJXRk9JwT8gDC29PXJ-t0aT4fXb8HcCXOlA0bXPtyRmFzuJky1Iqu4JLXnS4Toi13eKcltGhyFGgSJ9b1RWg32oAQGvXHAsoYj85qifMLR7OjXZJAJIpiMdfzZfQHYdOexGUSASgTRUwlFbycnhJCJaW_iZu">炉石传说</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=wj0H6u4bywQkXwG_i7jsrYPOb9gshiH3_9ST2hkSgWZdYSQPVcR7CRllY0fOcyPvKXuBSROOae2Pw0fM_ghL3Ibe_1CeGH0pHM2cIOiJ7-CZ8ZV3M1Uo83GSolZ1qRO0wq4hL6JJMvjEMIrGzoN5nK">猎天使魔女</a></li>
<li><a class="scroll" href="http://baike.baidu.com/link?url=g0r6gNQT7vHw8pHmuPHLanzzeh5XIynkvPLb1-PWfKcyCytU78Z9migfAjBY7Y9UWbPKsaK4GbhFiulP2BfmcLsQEL-31LEMmC0qn-D67WKtaJsIkJ0Mm2aQGWfxPh_DyuGV2jlsqpO6Tc5dcoaXaObwsAXx667tKLRcjXw_9nq">尼尔机械纪元</a></li>
</ul>

ok，又解决了。

     然后做人物介绍时，我从网上找了个模板，修改借鉴后发现打开太慢，于是我仔细查看代码，原来源码为了减小文件大小，引用了一个网站的js，而那个网站打开很慢，因此，我复制了网站的代码，新建了个js，修改复制一下，更改引用代码

<script src="js3/jsrua.js" type="text/javascript"></script>

最后网站能很快响应，终于解决了这个问题。

通过学习web，让我拥有了可以制作网站的能力，将来我也能有在这条路上有个作为，写博客，做些网站，在自己开心之余，也实现了自己的价值。
