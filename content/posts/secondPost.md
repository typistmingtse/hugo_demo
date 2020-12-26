---
title: "SecondPost"
date: 2020-12-26T18:23:12+08:00
draft: flase
tags: ['hugo', 'C sharp','程式設計']
---

測試文章內容，\
第一行\
第二行\
第三行\
用二個空格換行  
有換行嗎?

來段C#程式碼:
{{< highlight cs >}}
	Console.WriteLine("hello world");
{{< / highlight >}}  
\
\
\
\
\
放上圖片有二種方法\
第一種方式是放在部落格專案的static資料夾中，\
這邊多在static資料夾中建立一層images資料夾，

![](way1.png)

使用程式碼:
{{<highlight md>}}
	![](/images/HelloWorld.png)
{{</ highlight>}}  
<!-- ![](/images/HelloWorld.png) -->
\
\
\
\
\
第二種方式是使用相對路徑的方式，
這邊把圖片放在跟文章相同的目錄下，建立一個跟此篇文章secondpost相同名字的資料夾(注意資料夾需要小寫)，這種方法個人覺得管理圖片比較容易。

![](way2.png)

使用程式碼:
{{<highlight md>}}
	![](HelloWorld.png)
{{</ highlight>}}
<!-- ![](HelloWorld.png) -->