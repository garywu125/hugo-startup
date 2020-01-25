---
title: "連結不同的媒體/文件"
date: 2020-01-23T12:38:08+08:00
tags: 
draft: false
---

<!-- 學習連結 -->
<!-- https://www.w3schools.com/tags/tag_a.asp -->

# 大手 <a id="bighand"></a> 
{{< visualdata id="a61ee370-7907-4bdb-b3c1-4451ded983fb">}}
SlideShow :幻燈片放映   
來源:https://speakerdeck.com/ 製作:https://iframely.com/
  
slide one : introducing golang
  
{{< slideshow id="3ac1e22dd4ce43fb9bd0fe93b619f67d" >}}
  
slide two : rust for web application 

{{< slideshow id="bb517be21638439fa4854c23c5b793fa" >}}

網頁執行 Dart Code
  
{{< dartpad id="5a36b484ff9587f47de5f05c501adeed" >}}
  
網頁執行 Go Code
  
{{< goplayground id="6ooBt8Mvcf0" >}}

<!-- ??? how to make figure responsive -->
<!-- image
{{< figure src="/media/sunshine.jpg" title="Steve Francia">}} -->

embedded code snippets via gist
{{< gist garywu125 4c83bdb30996163508e2cd4a900cda55 >}}

tweet
{{< tweet 1219591726924320771 >}}
vimo 
   
{{< vimeo id="157715456"  >}}
   
youtube
  
{{< youtube w7Ft2ymGmfc >}}
   
## 可憐蟲 <a id="insect"></a>   
highlight dartlang static code 
   
{{< highlight dart >}} 
import 'package:flutter/material.dart';

final Color darkBlue = Color.fromARGB(255, 18, 32, 47);

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme: ThemeData.dark().copyWith(scaffoldBackgroundColor: darkBlue),
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        body: Center(
          child: MyWidget(),
        ),
      ),
    );
  }
}

class MyWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Text('Hello, World! God bless you!!', style: Theme.of(context).textTheme.display1);
  }
}

{{< /highlight >}}

highlight golang static code 
   
{{< highlight go >}}
package main

import (
	"fmt"
)

func main() {
	fmt.Println("Hello, playground")
}

{{< /highlight >}}

<!-- ref description-a-id<id名稱>a -->
[Jump to 可憐蟲]({{< ref "#可憐蟲-a-idinsecta" >}})
[Jump to 大手]({{< ref "#大手-a-idbighanda" >}})


