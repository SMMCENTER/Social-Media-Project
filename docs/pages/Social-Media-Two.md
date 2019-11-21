---
title: Social Media
layout: default
excerpt: As we can now decipher the time spent by our functions at the code block level ...
hint: Place the intro paragraph ie.) the 'synopsis' here ...
repo: Social-Media-Project
ver_date: 11-20-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## Code Block Time

> **Hint**. {{ page.hint }}

Keep a-track of your coding time.

Setting the time wrapper for the execution of a function ...

```liquid
{% raw %}
{% highlight html linenos %}
console.time(programTimer,"Square It Time"); 
var programTimer; {
    Execute Function Inside This Code Block
}
console.timeEnd(programTimer,"Square It Time");
{% endhighlight %}
{% endraw %}
```

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:target="_blank"}

***

{% include patreon-link.md %}
