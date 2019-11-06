<div class="post-content">
    <p>新手搭建 SS 翻墙看这篇文章就够啦！百分百成功搞定搭建SS！这是完全为新手而准备的 Shadowsocks 搭建详细图文教程。</p>

<h2 id="shadowsocks-简介">Shadowsocks 简介</h2>

<p>官网：<a href="https://shadowsocks.org/en/index.html" rel="nofollow" target="_blank">https://shadowsocks.org/en/index.html</a></p>

<p>简介：<br />
Shadowsocks 可以指：一种基于 Socks5 代理方式的加密传输协议，也可以指实现这个协议的各种开发包。目前包使用 Python、C、C++、C#、Go 语言等编程语言开发，大部分主要实现（iOS平台的除外）采用 Apache 许可证、GPL、MIT 许可证等多种自由软件许可协议开放源代码。<br />
Shadowsocks 分为服务器端和客户端，在使用之前，需要先将服务器端部署到服务器上面，然后通过客户端连接并创建本地代理。<br />
在中国大陆，本工具也被广泛用于突破防火长城（GFW），以浏览被封锁、遮蔽或干扰的内容。<br />
2015年8月22日，Shadowsocks 原作者 Clowwindy 称受到了中国政府的压力，宣布停止维护此计划（项目）并移除其个人页面所存储的源代码。<br />
简介来源：<a href="https://zh.wikipedia.org/wiki/Shadowsocks" rel="nofollow" target="_blank">https://zh.wikipedia.org/wiki/Shadowsocks</a></p>

<h2 id="购买一个vps">购买一个VPS</h2>

<p><strong>想要搭建 Shadowsocks 必须拥有一个 VPS。</strong><br />
我们推荐使用：<a href="https://affpass.com/go/bwg" rel="nofollow" target="_blank">搬瓦工（Bandwagon Host）</a> VPS 来搭建ss，搬瓦工是一个对中国用户极度友好的 VPS 商家，有香港，CN2 GIA 优化线路，并且支持支付宝付款，当然也是支持退款的！</p>

<p>推荐购买的搬瓦工套餐如下</p>

<table>
<thead>
<tr>
<th align="center">线路</th>
<th align="center">CPU</th>
<th align="center">内存</th>
<th align="center">硬盘</th>
<th align="center">带宽</th>
<th align="center">流量</th>
<th align="center">价格</th>
<th align="center">链接</th>
</tr>
</thead>

<tbody>
<tr>
<td align="center">香港</td>
<td align="center">2 核</td>
<td align="center">2048 MB</td>
<td align="center">40 GB</td>
<td align="center">1 G</td>
<td align="center">500GB / 月</td>
<td align="center"><strong>$89.99 / 月</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/95" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">香港</td>
<td align="center">4 核</td>
<td align="center">4096 MB</td>
<td align="center">80 GB</td>
<td align="center">1 G</td>
<td align="center">1000GB / 月</td>
<td align="center">$155.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/96" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">香港</td>
<td align="center">6 核</td>
<td align="center">8192 MB</td>
<td align="center">160 GB</td>
<td align="center">1 G</td>
<td align="center">2000GB / 月</td>
<td align="center">$299.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/97" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">香港</td>
<td align="center">8 核</td>
<td align="center">16384 MB</td>
<td align="center">320 GB</td>
<td align="center">1 G</td>
<td align="center">4000GB / 月</td>
<td align="center">$589.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/98" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">2 核</td>
<td align="center">1 GB</td>
<td align="center">20 GB</td>
<td align="center"><strong>2.5 G</strong></td>
<td align="center">1000GB / 月</td>
<td align="center"><strong>$65.99 / 半年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/87" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">3 核</td>
<td align="center">2 GB</td>
<td align="center">40 GB</td>
<td align="center"><strong>2.5 G</strong></td>
<td align="center">2000GB / 月</td>
<td align="center">$69.99 / 季</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/88" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">4 核</td>
<td align="center">4 GB</td>
<td align="center">80 GB</td>
<td align="center"><strong>2.5 G</strong></td>
<td align="center">3000GB / 月</td>
<td align="center">$49.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/89" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">6 核</td>
<td align="center">8 GB</td>
<td align="center">160 GB</td>
<td align="center"><strong>5 G</strong></td>
<td align="center">5000GB / 月</td>
<td align="center">$75.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/90" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">8 核</td>
<td align="center">16 GB</td>
<td align="center">320 GB</td>
<td align="center"><strong>5 G</strong></td>
<td align="center">8000GB / 月</td>
<td align="center">$139.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/91" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">10 核</td>
<td align="center">32 GB</td>
<td align="center">640 GB</td>
<td align="center"><strong>10 G</strong></td>
<td align="center">10000GB / 月</td>
<td align="center">$249.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/92" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">12 核</td>
<td align="center">64 GB</td>
<td align="center">1280 GB</td>
<td align="center"><strong>10 G</strong></td>
<td align="center">12000GB / 月</td>
<td align="center">$479.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/93" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">1 核</td>
<td align="center">512 MB</td>
<td align="center">10 GB</td>
<td align="center">1 G</td>
<td align="center">300GB / 月</td>
<td align="center"><strong>$39.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/71" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">1 核</td>
<td align="center">512 MB</td>
<td align="center">10 GB</td>
<td align="center">1 G</td>
<td align="center">500GB / 月</td>
<td align="center"><strong>$49.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/94" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">2 核</td>
<td align="center">1024 MB</td>
<td align="center">20 GB</td>
<td align="center">1 G</td>
<td align="center">1000GB / 月</td>
<td align="center"><strong>$25.99 / 季</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/72" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">3 核</td>
<td align="center">2048 MB</td>
<td align="center">40 GB</td>
<td align="center">1 G</td>
<td align="center">2000GB / 月</td>
<td align="center">$51.99 / 季</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/73" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">4 核</td>
<td align="center">4096 MB</td>
<td align="center">80 GB</td>
<td align="center">1 G</td>
<td align="center">3000GB / 月</td>
<td align="center">$32.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/74" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">6 核</td>
<td align="center">8GB</td>
<td align="center">160 GB</td>
<td align="center">1 G</td>
<td align="center">5000GB / 月</td>
<td align="center">$62.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/75" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">8 核</td>
<td align="center">16GB</td>
<td align="center">320 GB</td>
<td align="center">1 G</td>
<td align="center">8000GB / 月</td>
<td align="center">$119.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/76" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>

<tr>
<td align="center">CN2</td>
<td align="center">1 核</td>
<td align="center">1024 MB</td>
<td align="center">20 GB</td>
<td align="center">1 G</td>
<td align="center">1000GB / 月</td>
<td align="center"><strong>$49.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/57" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2</td>
<td align="center">1 核</td>
<td align="center">2048 MB</td>
<td align="center">40 GB</td>
<td align="center">1 G</td>
<td align="center">2000GB / 月</td>
<td align="center">$52.99 / 半年</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/58" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2</td>
<td align="center">2 核</td>
<td align="center">4096 MB</td>
<td align="center">80 GB</td>
<td align="center">1 G</td>
<td align="center">3000GB / 月</td>
<td align="center">$59.99 / 季</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/59" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2</td>
<td align="center">2 核</td>
<td align="center">8 GB</td>
<td align="center">160 GB</td>
<td align="center">1 G</td>
<td align="center">5000GB / 月</td>
<td align="center">$39.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/67" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2</td>
<td align="center">3 核</td>
<td align="center">16 GB</td>
<td align="center">320 GB</td>
<td align="center">1 G</td>
<td align="center">8000GB / 月</td>
<td align="center">$79.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/68" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
<td align="center">-</td>
</tr>

<tr>
<td align="center">普通</td>
<td align="center">2 核</td>
<td align="center">1024 MB</td>
<td align="center">20 GB</td>
<td align="center">1 G</td>
<td align="center">1 TB / 月</td>
<td align="center"><strong>$49.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/44" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">普通</td>
<td align="center">3 核</td>
<td align="center">2 GB</td>
<td align="center">40 GB</td>
<td align="center">1 G</td>
<td align="center">2 TB / 月</td>
<td align="center">$52.99 / 半年</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/45" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">普通</td>
<td align="center">4 核</td>
<td align="center">4 GB</td>
<td align="center">80 GB</td>
<td align="center">1 G</td>
<td align="center">3 TB / 月</td>
<td align="center">$19.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/46" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">普通</td>
<td align="center">5 核</td>
<td align="center">8 GB</td>
<td align="center">160 GB</td>
<td align="center">1 G</td>
<td align="center">4 TB / 月</td>
<td align="center">$39.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/47" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">普通</td>
<td align="center">6 核</td>
<td align="center">16 GB</td>
<td align="center">320 GB</td>
<td align="center">1 G</td>
<td align="center">5 TB / 月</td>
<td align="center">$79.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/48" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">普通</td>
<td align="center">7 核</td>
<td align="center">24 GB</td>
<td align="center">480 GB</td>
<td align="center">1 G</td>
<td align="center">6 TB / 月</td>
<td align="center">$119.99 / 月</td>
<td align="center"><a href="https://on.affpass.com/go/bwg/49" rel="nofollow" target="_blank">购买</a></td>
</tr>
</tbody>
</table>

<p>选择哪个套餐？如果你不知道选择哪个套餐<br />
下面这是最常见的购买套餐</p>

<table>
<thead>
<tr>
<th align="center">线路</th>
<th align="center">CPU</th>
<th align="center">内存</th>
<th align="center">硬盘</th>
<th align="center">带宽</th>
<th align="center">流量</th>
<th align="center">价格</th>
<th align="center">链接</th>
</tr>
</thead>

<tbody>
<tr>
<td align="center">普通</td>
<td align="center">2 核</td>
<td align="center">1024 MB</td>
<td align="center">20 GB</td>
<td align="center">1 G</td>
<td align="center">1 TB / 月</td>
<td align="center"><strong>$49.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/44" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2</td>
<td align="center">1 核</td>
<td align="center">1024 MB</td>
<td align="center">20 GB</td>
<td align="center">1 G</td>
<td align="center">1000GB / 月</td>
<td align="center"><strong>$49.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/57" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">1 核</td>
<td align="center">512 MB</td>
<td align="center">10 GB</td>
<td align="center">1 G</td>
<td align="center">300GB / 月</td>
<td align="center"><strong>$39.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/71" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">1 核</td>
<td align="center">512 MB</td>
<td align="center">10 GB</td>
<td align="center">1 G</td>
<td align="center">500GB / 月</td>
<td align="center"><strong>$49.99 / 年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/94" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">2 核</td>
<td align="center">1024 MB</td>
<td align="center">20 GB</td>
<td align="center">1 G</td>
<td align="center">1000GB / 月</td>
<td align="center"><strong>$25.99 / 季</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/72" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">CN2 GIA</td>
<td align="center">2 核</td>
<td align="center">1 GB</td>
<td align="center">20 GB</td>
<td align="center"><strong>2.5 G</strong></td>
<td align="center">1000GB / 月</td>
<td align="center"><strong>$65.99 / 半年</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/87" rel="nofollow" target="_blank">购买</a></td>
</tr>

<tr>
<td align="center">香港</td>
<td align="center">2 核</td>
<td align="center">2048 MB</td>
<td align="center">40 GB</td>
<td align="center">1 G</td>
<td align="center">500GB / 月</td>
<td align="center"><strong>$89.99 / 月</strong></td>
<td align="center"><a href="https://on.affpass.com/go/bwg/95" rel="nofollow" target="_blank">购买</a></td>
</tr>
</tbody>
</table>


<p>没有找到合适的套餐？你可以前往官网详细查看：<a href="https://affpass.com/go/bwg" rel="nofollow" target="_blank">https://bwh88.net/cart.php</a></p>

<p>哪个套餐好？<br />
一般来说，<strong>推荐购买 香港线路</strong> 或 <strong>CN2 GIA 线路</strong>，或者哪个便宜选择那个，说着当然如果你使用量比较多或者想要分享给同学和朋友一起用的话，选择合适的套餐即可。又或者你土豪的话，选择最贵的也行。</p>

<p><strong>VPS 速度：香港线路 &gt; CN2 GIA 线路 &gt; CN2 线路 &gt; 普通线路</strong></p>

<p><strong>香港套餐 VPS 的速度最快。</strong> 如果你非常在乎速度的话，建议购买香港线路的 VPS，当然，但价格贵，流量相对其他套餐来说也是比较少的……退一步的选择是 CN2 GIA 线路，这个线路的速度也比较好。</p>

<p>当然啦！记住一分钱一分货。</p>

<p>我本人比较推荐 CN2 GIA 线路，稳定性，速度与价格适中选择，当然啦！如果你觉得价格太贵了，推荐你查看一下 <a href="https://affping.com/to/bwgjms/post/how-to-buy-justmysocks/" target="_blank">
     搬瓦工 Just My Socks  
</a>
，搬瓦工官方出品的 Shadowsocks 代理服务，同样是 CN2 GIA 线路，<strong>每月仅需 $2.88 起！</strong> 再也不用自己折腾搭建了，<strong>最最最最重要的是：被墙自动换 IP，无须担心 IP 被墙！</strong></p>

<p>Just My Socks 购买教程在这里：<a href="https://affping.com/to/bwgjms/post/how-to-buy-justmysocks/" target="_blank">
     搬瓦工 Just My Socks 详细图文购买教程  
</a>
</p>

<blockquote>
<p>如果出现 out of stock 这样的提示，那就是这个套餐卖完了，选择其他套餐即可。</p>
</blockquote>

<h2 id="添加到购物车">添加到购物车</h2>

<p>在上面表格中选择想要购买的套餐，然后点击 <code>购买</code> 即可。<br />
将 VPS 添加到购物车</p>


<img src="https://i.loli.net/2018/11/18/5bf1684742682.png" alt="Add to Cart" loading="lazy">


<p>说明一下，在Billing Cycle选项那里选择：<code>$xxxx USD Annually</code>，按年付的意思<br />
<strong>推荐按年付，比按月付最高可省55%的钱</strong><br />
Location 选择: <code>HK - Hong Kong xxxxx</code> （如果你购买的是香港线路的话）<br />
否则选择: <code>US - Los Angeles xxxxx</code><br />
然后点击<code>Add To Cart</code></p>

<h2 id="结算">结算</h2>

<p>推荐使用搬瓦工 6.38% 优惠码：<a href="https://affpass.com/go/bwg" rel="nofollow" target="_blank">BWH34QMFYT2R</a></p>

<p>这个优惠码是搬瓦工目前最高优惠的优惠码<br />
输入优惠码之后点击 <code>Validate Code &gt;&gt;</code></p>


<img src="https://i.loli.net/2018/11/18/5bf168474423c.png" alt="输入优惠码" loading="lazy">


<p>然后点击 <code>Checkout</code><br />
如下图所示：已经使用搬瓦工优惠码</p>


<img src="https://i.loli.net/2018/11/18/5bf1684703cec.png" alt="Checkout" loading="lazy">


<p>然后会提示你注册账号 （如果你没账号或者还没登录）<br />
请按照下面图片提示来填写~</p>


<img src="https://i.loli.net/2018/11/18/5bf16da6832c6.png" alt="Checkout now" loading="lazy">


<p>要注意的是，Country 选项记得选择 <code>China</code>，Payment Method 选择 <code>Alipay</code><br />
不要忘了勾上 I have read and agree to the Terms of Service<br />
然后 <code>Complete Order</code></p>

<h2 id="付款">付款</h2>

<p>点击 <code>Pay now</code><br />
之后便会跳转到支付宝付款界面，完成付款即可</p>


<img src="https://i.loli.net/2018/11/18/5bf1684732175.png" alt="Pay now" loading="lazy">


<h2 id="获取vps信息">获取VPS信息</h2>

<p>确保你已经成功付款之后<br />
打开：<a href="https://bwh88.net/clientarea.php?action=products" rel="nofollow" target="_blank">https://bwh88.net/clientarea.php?action=products</a><br />
选择 <code>KiwiVM Control Panel</code><br />
如果出现以下界面，稍等一会，等待资源分配即可。</p>


<img src="https://i.loli.net/2017/09/05/59ae8a8fc83e2.jpg" alt="Task in progress" loading="lazy">


<p>等待两三分钟，刷新一下。<br />
这是已经在运行的界面，请记下 <code>IP address</code> 然后点击 <code>stop</code></p>


<img src="https://i.loli.net/2018/11/18/5bf1684733cec.png" alt="停止VPS" loading="lazy">


<p>当出现：Great Success! Virtual server will stop in a few seconds. 相关提示<br />
证明 VPS 已经停止了，我们需要重装一个系统。点击左边的 <code>Install new OS</code><br />
之后选择 <code>debian-9-x86_64</code><br />
再勾上：I agree that all existing data on my VPS will be lost.<br />
然后点击 <code>Reload</code></p>


<img src="https://i.loli.net/2018/11/12/5be904c32f31b.jpg" alt="Install new OS" loading="lazy">


<p>当点击 <code>Reload</code> 之后，稍等片刻将会出现下图所示的界面，<br />
请务必记下： <code>You will need a new root password to access your VPS：xxxx</code><br />
还有：<code>New SSH Port:</code><br />
一个是root密码，一个是SSH端口</p>


<img src="https://i.loli.net/2018/11/18/5bf168473b33d.png" alt="Reload" loading="lazy">


<p>OK，这时我们已经获取到VPS的信息了。</p>


    


<h2 id="安装-xshell">安装 Xshell</h2>

<p>Xshell 是一个易用的 SSH 客户端，要登录 VPS，当然需要 SSH 客户端</p>

<p><a href="https://fingerit-my.sharepoint.com/:u:/g/personal/ai_fingertc_com/EeP_cDRqGvpMtLoaJc1zk5AB-nDlc71rt9fQWIH4I5ShPg?e=jvAzk6" rel="nofollow" target="_blank">Xshell 下载链接点我</a></p>

<p>这是一个绿色版本的 Xshell ，打开链接后，就点击 <code>下载</code>，下载好了之后，就双击打开，然后点击 <code>浏览...</code> 可以选择解压的路径，比如说 D 盘，之后再选择 <code>解压</code> 即可。</p>


<img src="https://i.loli.net/2018/12/27/5c24f0c995b84.jpg" alt="解压 Xshell" loading="lazy">


<p>然后在解压的目录找到 <code>Xshell+Xftp 绿色版本</code> 文件夹，打开它，之后找到 <code>!安装.bat</code> 并且右键选择 <code>以管理员身份运行</code>，安装完成后会有一个提示窗口，关闭即可。这样来就安装好了 Xshell</p>


<img src="https://i.loli.net/2018/12/27/5c24f0c9994a4.jpg" alt="安装 Xshell" loading="lazy">


<h2 id="登录vps">登录VPS</h2>

<p>在桌面找到 Xshell ，打开它，新建一个会话。</p>


<img src="https://i.loli.net/2018/12/27/5c24f0c8d78f6.jpg" alt="新建会话" loading="lazy">


<p>主机写上你的 VPS IP 地址，端口写上 SSH 端口。</p>


<img src="https://i.loli.net/2018/11/18/5bf1684735776.png" alt="new" loading="lazy">


<p>之后点击 用户身份验证，用户名：<code>root</code>，密码：你的 root 密码。然后点击确定</p>


<img src="https://i.loli.net/2018/11/18/5bf1684737f3c.png" alt="user-and-passwd" loading="lazy">


<p>之后选择连接。</p>


<img src="https://i.loli.net/2018/11/18/5bf1684739aab.png" alt="连接" loading="lazy">


<p>然后会提示SSH安全警告，选择，接受并保存。</p>


<img src="https://i.loli.net/2018/11/18/5bf15f4b04c72.png" alt="SSH 安全警告" loading="lazy">


<p>这是登录成功后的界面</p>


<img src="https://i.loli.net/2018/11/18/5bf15f4b0cd33.png" alt="登陆成功" loading="lazy">


<p>OK，搞定了登录那么就可以开始安装 Shadowsocks 了。</p>

<h2 id="安装shadowsocks">安装Shadowsocks</h2>

<p>输入下面的命令并回车，开始安装 Shadowsocks</p>

<pre><code>bash &lt;(curl -s -L https://git.io/ss.sh)
</code></pre>

<p>提示：你可以复制安装命令，然后在 Xshell 5 界面按一下 <code>鼠标滚轮</code>键或者按 <code>Shift+Insert</code> 即可粘贴，不能按 Ctrl+V 的。。。</p>

<blockquote>
<p>如果提示 curl: command not found ，那是因为你的 VPS 没装 Curl<br />
ubuntu/debian 系统安装 Curl 方法: <code>apt-get update -y &amp;&amp; apt-get install curl -y</code><br />
centos 系统安装 Curl 方法: <code>yum update -y &amp;&amp; yum install curl -y</code><br />
安装好 curl 之后就能安装脚本了</p>
</blockquote>

<p>在你正确输入上面的安装命令之后，便会显示下图的界面<br />
先选择安装，即是输入 <code>1</code> ，然后你需要配置一下 Shadowsocks，端口，密码，协议</p>


<img src="https://i.loli.net/2018/11/15/5bed24b2c4522.png" alt="配置 Shadowsocks" loading="lazy">


<p>备注：协议建议使用默认的，也就是 chacha20-ietf-poly1305，端口或者密码的话，随便你喜欢咯。<br />
如果没有什么问题，按回车键继续<br />
之后等待安装完成，一般来说，大概需要一分钟左右即可。</p>

<h2 id="shadowsocks安装完成">Shadowsocks安装完成</h2>

<p>当出现下图所示证明 Shadowsocks 已经安装完成，你可以尝试使用客户端去连接一下是否可用了。</p>


<img src="https://i.loli.net/2018/11/15/5bed24b2b5ac1.png" alt="Shadowsocks 配置信息" loading="lazy">


<h2 id="shadowsocks-管理面板">Shadowsocks 管理面板</h2>

<p>为了方便你管理 Shadowsocks，此脚本有一个管理面板，输入 <code>ss</code> 即可查看</p>


<img src="https://i.loli.net/2018/11/15/5bed24b2b5c84.png" alt="Shadowsocks 管理面板" loading="lazy">


<h2 id="快速管理">快速管理</h2>

<p><code>ss menu</code> 管理 Shadowsocks (同等于直接输入 ss)</p>

<p><code>ss info</code> 查看 Shadowsocks 配置信息</p>

<p><code>ss config</code> 更改 Shadowsocks 配置</p>

<p><code>ss qr</code> 生成 Shadowsocks 配置二维码链接</p>

<p><code>ss status</code> 查看 Shadowsocks 运行状态</p>

<p><code>ss start</code> 启动 Shadowsocks</p>

<p><code>ss stop</code> 停止 Shadowsocks</p>

<p><code>ss restart</code> 重启 Shadowsocks</p>

<p><code>ss update</code> 更新 Shadowsocks</p>

<p><code>ss update.sh</code> 更新 Shadowsocks 管理脚本</p>

<p><code>ss uninstall</code> 卸载 Shadowsocks</p>

<h2 id="优化-shadowsocks-速度">优化 Shadowsocks 速度</h2>

<p>此脚本会自动开启 BBR 优化。如果你是使用 Debian9 系统，或者系统内核支持开启 BBR 优化的话。<br />
当然，你可以使用 BBR 魔改版本或者 锐速 等方式去优化。</p>

<h2 id="卸载-shadowsocks">卸载 Shadowsocks</h2>

<p>如果你需要卸载 Shadowsocks。<br />
使用命令：<code>ss uninstall</code>，然后输入 y 即可。</p>

<h2 id="更新-shadowsocks">更新 Shadowsocks</h2>

<p>如果你需要更新 Shadowsocks 服务器端，使用命令：<code>ss update</code>，脚本便会更新 Shadowsocks 版本。</p>

<h2 id="结束">结束</h2>

<p>一键安装脚本说明：<a href="https://233blog.com/post/36/" target="_blank">
     Shadowsocks-Go 一键安装脚本 &amp; 管理脚本  
</a>
</p>

<h2 id="分享">分享</h2>

<p>如果这篇文章对你帮助的话，记得分享给你的小伙伴们哦。</p>

<h2 id="提示">提示</h2>

<p>由于使用了 chacha20-ietf-poly1305 加密算法，如果你的客户端没有这个加密算法选择的话，那么你就应该更新 Shadowsocks 客户端啦。<br />
Shadowsocks 客户端下载：<a href="https://shadowsocks.org/en/download/clients.html" rel="nofollow" target="_blank">https://shadowsocks.org/en/download/clients.html</a><br />
加密算法相关：<a href="https://shadowsocks.org/en/spec/AEAD-Ciphers.html" rel="nofollow" target="_blank">https://shadowsocks.org/en/spec/AEAD-Ciphers.html</a></p>

<h2 id="其他">其他</h2>

<p>请勿违反国家法律法规，否则后果自负！<br />
由于已经多次对文章内容修正和更新，你的实际操作可能会和截图有少许不同，但不会影响你对这个教程的理解。</p>
</div>
