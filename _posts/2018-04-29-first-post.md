---
layout: post
published: false
date: '2018-04-29'
title: My first post
Subtitle: Even with a subtitle
tags: [first post, markdown]
---

Here is my first post, testing out 'markdowm' for creating blog posts.

I am brand new to using markdown, but the general idea seems simple enough.  
So lets test out a Powershell codeblock:

```powershell
Get-ADgroupMember -filter * | foreach {
	Get-ADsuer -identity $_
}
```

And then a codeblock with lines mubers: 

{% highlight javascript linenos %}
Get-ADgroupMember -filter * | foreach {
	Get-ADsuer -identity $_
}
{% endhighlight %}
