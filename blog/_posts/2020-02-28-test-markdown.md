---
layout: post
title: Markdown Sample
subtitle: Each post also has a subtitle
gh-repo: seokho-son/seokho-son.github.io
gh-badge: [star, fork, follow]
tags: [test, markdown]
comments: true
---

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:  

$$
\begin{align*}
{ f }_{ t }&=\sigma ({ W }_{ xh\_ f }{ x }_{ t }+{ W }_{ hh\_ f }{ h }_{ t-1 }+{ b }_{ h\_ f })\\ { i }_{ t }&=\sigma ({ W }_{ xh\_ i }{ x }_{ t }+{ W }_{ hh\_ i }{ h }_{ t-1 }+{ b }_{ h\_ i })\\ { o }_{ t }&=\sigma ({ W }_{ xh\_ o }{ x }_{ t }+{ W }_{ hh\_ o }{ h }_{ t-1 }+{ b }_{ h\_ o })\\ { g }_{ t }&=\tanh { ({ W }_{ xh\_ g }{ x }_{ t }+{ W }_{ hh\_ g }{ h }_{ t-1 }+{ b }_{ h\_ g }) } \\ { c }_{ t }&={ f }_{ t }\odot { c }_{ t-1 }+{ i }_{ t }\odot { g }_{ t }\\ { h }_{ t }&={ o }_{ t }\odot \tanh { ({ c }_{ t }) } 
\end{align*}
$$

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
