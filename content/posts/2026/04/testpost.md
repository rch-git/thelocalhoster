---
date: '2026-04-04T07:04:52-05:00'
draft: true
title: 'test post'
cover:
  image: "img/helloworld.jpg"
  alt: 'Hello World'
  caption: 'Hello World Cover Caption'
  relative: false # ← explicit for static folder images
tags: ["test", "post"]
---

<!-- http://localhost:1313/posts/2026/04/first/ -->
Hello World!

<!--This is being loaded from  /home/sysuser/git/thelocalhoster/static/img/helloworld.jpg -->
![Hello World](/img/helloworld.jpg)

<!-- resized image -->
{{< figure src="/img/helloworld.jpg" width="128" caption="hello world" >}}

<!-- this is an example from https://github.com/9EED/Markdown-guide -->
{{< figure src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="128" caption="github" >}}

From github repo with center align and a clickable image.

{{<
    figure
    src="https://cdn.jsdelivr.net/gh/rch-git/staticcontent@master/images/helloworld.jpg"
    width="256"
    align="center"
    caption="from staticcontent repo"
    link="https://cdn.jsdelivr.net/gh/rch-git/staticcontent@master/images/helloworld.jpg"
>}}


{{< details summary="See the details" >}}
This is a **bold** word.
{{< /details >}}



This is a code block

```
# this is code

System.out.println("Hello world!");

```
<!-- test new line -->
test
test2

<div class="italic-block">

<p>this is a test</p>
<p>this is a test</p>
<p>this is a test</p>
</div>

youtube video
<p>
{{< youtube GdmQzi6I0oo >}}
</p>

How to escape symbols

\+

"double quotes inside double quotes \""

Open link in a new tab
{{< newtab href="https://www.amazon.com/Intel-Pentium-1-7GHz-400MHz-Socket/dp/B000YA9FM0" text="Pentium 4 1.7 GHz" >}}

link to another page in the blog

{{< newtab href="/posts/2010/01/reviews/lotrbfme-review/" text="Lord of the Rings Battle For Middle Earth" >}}

_First published on GameSpot_


_This post is published on _
