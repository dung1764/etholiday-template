# 相關說明
中台美化產品頁使用
## 額外設定
### 美化中台html
可以點擊 [美化html](https://www.cleancss.com/html-beautify/ "html beautifier") 彌補中台編碼亂相.
### 展開中台css設定
```css
/* 整各精進背景顏色 */
#et-column{
    background: url(https://www.transparenttextures.com/patterns/ecailles.png) repeat;
}
/* 欄位背景顏色 */
.et-bg{
    background-color: #b5b5b5;
    color: white;
}
```
## html標簽說明
### 一定要先放最外層，後面所有html元件都要放在這中間
```html
<!-- all -->
<div id="et-column">

</div>
<!-- end all -->
```
### 滿版圖一般用來放大圖
![Alt text](/images/005.jpg)
```html
<!-- 1 full -->
<div class="et-column">
	<!-- 圖片 -->
	<img src="https://picsum.photos/g/1000/400/?random" alt="">
  	<!-- 浮動png圖片 -->
	<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" class="f">
</div>
<!-- end 1 full -->
```
### 2:3比例 (圖大)
![Alt text](/images/001.jpg)
```html
<!-- 2:3 圖大 -->
<div class="et-column ml">
	<div>
		<div class="pad">
			<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" alt="">
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap 
			</p>
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
</div>
<!-- end 2:3 圖大 -->
```
### 2:3比例 (圖小)
![Alt text](/images/007.jpg)
```html
<!-- 2:3 圖小 -->
<div class="et-column mls">
	<div>
		<div class="pad">
			<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" alt="">
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap 
			</p>
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>	
</div>
<!-- end 2:3圖小 -->
```
### 3:2比例 (圖大)
![Alt text](/images/003.jpg)
```html
<!-- 3:2 圖大 -->
<div class="et-column mrb">
	<div>
		<div class="pad">
			<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" alt="">
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap 
			</p>
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>	
</div>
<!-- end 3:2 圖大 -->
```
### 3:2比例 (圖小)
![Alt text](/images/006.jpg)
```html
<!-- 3:2 圖小 -->
<div class="et-column mrs">
	<div>
		<div class="pad">
			<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" alt="">
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap 
			</p>
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
</div>
<!-- end 3:2 圖小 -->
```
### 1:1比例
![Alt text](/images/002.jpg)
```html
<!-- 1:1 -->
<div class="et-column mm">
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
</div>
<!-- end 1:1 -->
```
### 1:1:1比例
![Alt text](/images/004.jpg)
```html
<!-- 1:1:1 -->
<div class="et-column mt">
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
</div>
<!-- end 1:1:1 -->
```
### 輪播，可以替換掉一般圖片
![Alt text](/images/008.jpg)
```html
<!-- 輪播圖片 2張 -->
<div class='slider'>
	<div class='slide2-1' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
	<div class='slide2-2' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
</div>
<!-- end 輪播圖片 2張 -->
```
```html
<!-- 輪播圖片 3張 -->
<div class='slider'>
	<div class='slide3-1' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
	<div class='slide3-2' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
	<div class='slide3-3' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
</div>
<!-- end 輪播圖片 3張 -->
```
### 圖片上層，通常在大圖上放這個物件
```html
<!-- 浮動png圖片 -->
	<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" class="f">
<!-- end 浮動png圖片 -->
```
### 表格搭配圖片標題
![Alt text](/images/009.jpg)
```html
<!-- 表格 -->
<div class="et-column">
	<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png">
	<table>
		<thead>
			<tr>
				<th>均溫</th>
				<th>1月</th>
				<th>2月</th>
				<th>3月</th>
				<th>4月</th>
				<th>5月</th>
				<th>6月</th>
				<th>7月</th>
				<th>8月</th>
				<th>9月</th>
				<th>10月</th>
				<th>11月</th>
				<th>12月</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>平均高溫</td>
				<td>22</td>
				<td>23</td>
				<td>24</td>
				<td>25</td>
				<td>26</td>
				<td>27</td>
				<td>28.5</td>
				<td>25.5</td>
				<td>24.5</td>
				<td>22</td>
				<td>24</td>
				<td>20</td>
			</tr>
		</tbody>
	</table>
</div>	
<!-- end 表格 -->
```
