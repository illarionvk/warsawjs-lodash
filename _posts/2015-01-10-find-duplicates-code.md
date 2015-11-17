---
---

<!-- Comment -->

{% highlight javascript linenos %}
_.chain([1, 2, 3, 4, 5, 6, 7, 3, 4, 4])
  .groupBy(function(item) {
    return item;
  })
  .pairs()
  .filter(function(pair) {
    return _.last(pair).length > 1;
  })
  .map(function(pair) {
    return _.first(pair);
  })
  .value();
   // → ["3","4"]
{% endhighlight %}


