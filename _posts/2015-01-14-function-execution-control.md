---
---

## Function Execution Control

{% highlight javascript linenos %}
// avoid costly calculations while the window size is in flux
jQuery(window).on('resize', _.debounce(calculateLayout, 150));
{% endhighlight %}

{% highlight javascript linenos %}
// avoid excessively updating the position while scrolling
jQuery(window).on('scroll', _.throttle(updatePosition, 100));
{% endhighlight %}


