# SEO lab + Social

* Tạo trang chi tiết sản phẩm
* Sử dụng thẻ meta open graph để SEO sản phẩm đó
* Thêm chat support

## 1. Open Graph meta tags hỗ trợ các social
Ví dụ cho FB:
```
<meta property="og:url"                content="http://www.nytimes.com/2015/02/19/arts/international/when-great-minds-dont-think-alike.html" />
<meta property="og:type"               content="article" />
<meta property="og:title"              content="When Great Minds Don’t Think Alike" />
<meta property="og:description"        content="How much does culture influence creative thinking?" />
<meta property="og:image"              content="http://static01.nyt.com/images/2015/02/19/arts/international/19iht-btnumbers19A/19iht-btnumbers19A-facebookJumbo-v2.jpg" />
```

* Bước 1: Thêm section ở trong layout template
```
@RenderSection("metasocials", required:false)
```

* Bước 2: Ở mỗi trang định nghĩa phần section này
```
@section metasocials{
	<meta property="og:url" content="" />
	<meta property="og:type" content="" />
	<meta property="og:title" content="" />
	<meta property="og:description" content="" />
	<meta property="og:image" content="" />
}
```

## 2. Live Chat
* Tawk to: https://www.tawk.to/
* Subiz https://subiz.com/vi/
* ZenDesk https://www.zendesk.com/
* FB

## 3. Host lên internet
Có thể sử dụng chức năng publish page của GitHub
