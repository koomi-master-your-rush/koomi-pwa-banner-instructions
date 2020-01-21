# Koomi PWA Banner - Instructions

A Javascript banner to promote Koomi+ PWA on client's website.

```js
<script>
(function(i,s,o,g,r,a,m){i["KoomiBannerObject"]=g;i[g]=i[g]||function(){(i[g].q=i[g].q||[]).push(arguments)};a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.id=o;a.src=r;a.async=1;m.parentNode.insertBefore(a,m);}(window,document,"script","kbanner","//order.koomi.com/widgets/pwa-banner/banner.js"));

kbanner("create", "[Enter your client folder path here (e.g. koomi-pgAzkWYKGr)]", {
	id: "koomi-pwa-banner",
	lang: "en", // "en", "fr"
	takeout: true, // true, false
	dineIn: true, // true, false
	delivery: true, // true, false
	theme: "dark", // "dark", "light"
	horizontalAlign: "right", // "left", "center", "right" (Does not apply to mobile)
	verticalAlign: "bottom", // "top", "center", "bottom"
	zIndex: 2147483647
});
</script>
```

## Demo

https://order.koomi.com/widgets/pwa-banner/demo.html
