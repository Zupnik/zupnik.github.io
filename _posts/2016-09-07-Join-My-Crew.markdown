---
layout: post
title:  "Join My Crew. Wolfram Test"
date:   2016-09-07 22:29:42 +0100
categories: jekyll update
---
Here's some test code:

{% highlight prolog %}
lissajous::usage = "An example Lissajous curve.\n" <>
                   "Definition: f(t) = (sin(3t + π/2), sin(t))"
lissajous = {Sin[2^^11 # + 0.005`10 * 1*^2 * Pi], Sin[#]} &;

With[{max = 2 Pi, min = 0},
    ParametricPlot[lissajous[t], {t, min, max}] /. x_Line :> {Dashed, x}
]
{% endhighlight %}

{% highlight wl %}
lissajous::usage = "An example Lissajous curve.\n" <>
                   "Definition: f(t) = (sin(3t + π/2), sin(t))"
lissajous = {Sin[2^^11 # + 0.005`10 * 1*^2 * Pi], Sin[#]} &;

With[{max = 2 Pi, min = 0},
    ParametricPlot[lissajous[t], {t, min, max}] /. x_Line :> {Dashed, x}
]
{% endhighlight %}

{% highlight wl %}
Module[{x=1},
	Sin[x]+Cos[x]
	bleh[]:
];
{% endhighlight %}

{% highlight wl %}
R[x_Integer]:=x^2
{% endhighlight %}

{% highlight wl %}
R[x_]:=x^2
{% endhighlight %}

