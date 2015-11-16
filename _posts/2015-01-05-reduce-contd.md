---
---

## _.reduce() <em>cont'd</em>

{% highlight javascript linenos %}
_.reduce(
  [1, 2, 3],
  function(accumulator, value) {
    accumulator[value] = true;
    return accumulator;
  },
  {}
);
// → {1: true, 2: true, 3: true}
{% endhighlight %}

