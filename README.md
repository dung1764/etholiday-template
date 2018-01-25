# 相關說明
中台美化產品頁使用
## 額外設定
### 美化中台html
可以點擊 [美化html](https://www.cleancss.com/html-beautify/ "html beautifier") 彌補中台編碼亂相.
### 展開中台css設定
```css
//外層背景顏色
#et-column{
    background: url(https://www.transparenttextures.com/patterns/ecailles.png) repeat;
}
//內層背景+文顏色
.et-bg{
    background-color: #b5b5b5;
    color: white;
}
```
## html標簽說明
### 最外層，所有html元件都要放在這裡面
```html
<!-- all -->
<div id="et-column">

</div>
<!-- end all -->
```
### 滿版圖一般用來放大圖
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
### 2:3比例
```html
<!-- 2:3 -->
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
<!-- end 2:3 -->
```
### 3:2比例
```html
<!-- 3:2 -->
<div class="et-column mr">
	<div>
		<div class="pad">
			<img src="https://picsum.photos/g/600/400/?random" alt="">
		</div>
	</div>
	<div>
		<div class="pad">
			<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" alt="">
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap 
			</p>
		</div>
	</div>
</div>
<!-- end 3:2 -->
```
### 1:1比例
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
### 輪播，可以放在各比例的 pad div 底下
```html
<!-- 輪播圖片 -->
<div class='slider'>
	<div class='slide1' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
	<div class='slide2' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
	<div class='slide3' style="background: url(https://picsum.photos/g/600/400/?random) no-repeat center;"></div>
</div>
<!-- end 輪播圖片 -->
```
### 圖片上層，通常在大圖上放這個物件
```html
<!-- 浮動png圖片 -->
	<img src="https://cdn.bloomnation.com/media/vendor/1110/f/l/300X100/floral-heights-logo_1.png" class="f">
<!-- end 浮動png圖片 -->
```
