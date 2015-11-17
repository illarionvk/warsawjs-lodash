---
---

## Object Manipulation

{% highlight javascript linenos %}
var item = {"a":{"b":{"c":3}}};

_.get(item, 'a.b.c', 3);
// → 3

_.set(item, 'a.b.c', 5);
// → {"a":{"b":{"c":5}}}

_.has(item, 'a.b.c.d');
// → false
{% endhighlight %}

