---
layout: post
title:  "0 A hundred algorithms in a hundred days"
date:   2014-08-10 13:26:45
categories: julia starts
redirect_from: /0/
---

This seems like a kind of crazy idea, but I'm hoping it will be both a good
exercise and a fun read. I've written a list of algorithms (and data structures)
which to implement, I've not quite got 100 yet and am happy to take suggestions!
(Please check out [the Trello board][trello] and post an
[issue on the github page][issues] if you think something is missing.)

I thought I'd start with some smaller sorting algorithms and then move to more
involved datastructures... among others I'm hoping to cover:

- sorting algorithms (mergesort, quicksort)
- some graphs (A*, travelling salesman)
- trees (binary, red and black, balancing),
- hash tables (including implementations using trees)

*Perhaps some probability and machine learning algorithms, I'm not quite sure
where this will end up.*

My aim is to spend an hour a day learning, implementing and writing a short
post. I suspect as this project progresses (as algorithms get a bit trickier
this may take somewhat longer...

I'm going to coding these in [julia][julia], which is a great language yet young
enough that many of these examples may not already be implemented (or at least
written up online).

{% highlight julia %}
function print_hi(name)
  println("Hello $name")
end
print_hi("Sweetie")
#=> prints "Hello Sweetie" to STDOUT.
{% endhighlight %}

[issues]: https://github.com/hayd/HundredAlgos/issues
[julia]: http://julialang.org/
[trello]: https://trello.com/b/HiLAIwv4/100algos
