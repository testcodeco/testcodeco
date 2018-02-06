
---
layout: default
---
<div id="index">
  <div class="category_detail">
    <h1>Chuyện bên lề</h1>
    <p>Chuyện bên lề - là chuyên mục viết về mọi thứ liên quan đến cuộc sống của một thằng coder.</p>
  </div>
    {% for post in site.categories['Kinh Nghiệm'] %}

    <article class="article-item">
	<div class="post-cover">
		<a class="post-link" href="/xuyen-viet-bac-trung-bo" title="[Xuyên Việt] Bắc Trung Bộ"></a>
		<img src="https://dendosg.github.io/assets/img/upload/2017/05/kdl-suoi-mooc-quang-binh-3.jpg" alt="">
	</div>
	<section class="post-preview">
		<a class="post-link" href="/xuyen-viet-bac-trung-bo" title="[Xuyên Việt] Bắc Trung Bộ"></a>
		<h2 class="post-title">[Xuyên Việt] Bắc Trung Bộ</h2>
		<p class="post-excerpt">Bắc Trung Bộ là vùng đất của các di tích lịch sử: các lăng tẩm vua chúa ở Huế, thành cổ Quảng Trị và cầu Hiền Lương, tượng
			...</p>
	</section>
	<footer class="post-meta">
		<div class="post-tags">
			<a href="tags.html#documentation" class="post-tag">documentation</a>
			<a href="tags.html#sample" class="post-tag">sample</a>
		</div>
		<time class="post-date" datetime="17-05-21">21 May 2017</time>
	</footer>
</article>

    {% endfor %}

</div>


