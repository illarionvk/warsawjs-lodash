---
---

## _.filter() / _.reject()

{% highlight javascript linenos %}
_.filter([1, 2, 3, 4, 5, 6], function(value) {
  return value > 3;
});
// → [4, 5, 6]
{% endhighlight %}

{% highlight javascript linenos %}
_.reject([1, 2, 3, 4, 5, 6], function(value) {
  return value > 3;
});
// → [1, 2, 3]
{% endhighlight %}
