---
comments: true
---

在您开始发挥您的想象力之前，请务必阅读[如何参与](https://chocolateater.github.io/FD-Class/Joinin/)和[格式手册](https://chocolateater.github.io/FD-Class/Format/)，以避免一些不必要的麻烦。

如果您认为您已经准备好了，那么请点击下方的 开始编辑 按钮，进入编辑页面。

<a id="btn-startedit" style="padding: 0.75em 1.25em; display: inline-block; line-height: 1; text-decoration: none; white-space: nowrap; cursor: pointer; border: 1px solid #6190e8; border-radius: 5px; background-color: #6190e8; color: #fff; outline: none; font-size: 0.75em;">开始编辑</a>

<script>
	function getQueryVariable(name, dft)
	{
		var reg = new RegExp('(^|&)' + name + '=([^&]*)(&|$)', 'i');
		var r = window.location.search.substr(1).match(reg);
		if (r != null)
		{
			return unescape(r[2]);
		}
		return dft;
	}
	document.getElementById("btn-startedit").href = "https://github.com/chocolateater/FD-Class/edit/master/docs" + getQueryVariable("ref", "");
</script>