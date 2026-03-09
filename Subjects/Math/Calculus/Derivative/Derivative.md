[[Math MOC]]


Fundemental Idea of Derivative


[[Math Calculus Home note]]


**Sort of definition**:
 Let there be a continuos, function f(x) defined at every point.
 <mark class="hltr-green">A derivative is essentially the instaneous rate of change at a  point, or otherwise, the slope of a tangent line at a point</mark>:
 
```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2025.7.6 - 14.02pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```

  
Lets Break it down:
At a point a,
On the function,
f(a) gives some y
From the point in the graph, you zoom in until the curve(or the graph) becomes very close to a straight line.
say you take some teeny tiny step forward, and lets call that dx, a small change in x,
now, the resulting change in the y value, <mark class="hltr-red">some dy, over dx is called a derivative</mark>,

```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2025.7.6 - 14.06pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```

Now the idea is that, as you take smaller and smaller values of dx, dx/dy will approach the slope of a tangent line to the point



## Formal definition of a limit


Suppose you have a graph of f(x), defined at all points

Suppose h is some arbitarily small number,

You mark out f(x), f(x+h)

```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2025.7.7 - 16.16pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```


Now, our h is like dx, while f(x+h)-f(x) is just or dy. Hence, as our h approaches 0, we should get the derivative at x, by dividing dy/dx,
in other words:
$$
\frac{dy}{dx}=\lim_{h \to 0 }\frac{f(x+h)-f(x)}{h}

$$
[[Math Limits]]
