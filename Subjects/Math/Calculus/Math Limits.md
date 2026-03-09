Under [[Math Calculus Home note]]
also [[Math MOC]]

```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2025.6.25 - 13.02pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```
## Limits: Informal definition:
Lets take 
$$
f(x)=x^2+1
$$
So now, 
$$
\lim_{ x \to 2 }f(x)= 4 
$$

That is to say, as x approaches 2, f(x) approaches 4, Now this is very easy to compute as you can sub in x=2 in f(x)
## Limits Epsilon-Delta Definition
Let I be an open interval containing C, and let $$
f(x) \space be \space defined \space on\space I \space except\space possibly \space at \ C, then:
$$ 
$$
\lim_{ x \to C } f(x)=L 
$$


means that given any ϵ>0ϵ>0, there exists δ>0δ>0 such that for all x≠cx≠c, if |x−c|<δ|x−c|<δ, then |f(x)−L|<ϵ|f(x)−L|<ϵ
0<∣x−a∣<δ⟹∣f(x)−L∣<ϵ
$$
0<|x-a|<\delta \implies |f(x)-L|<\epsilon
$$

## Computing Limits

- Handy little trick:L'Hopital Rule
	- $$ 
	\lim_{ x \to a } \frac{f(a)}{g(a)}=\lim_{ x \to a } \frac{f'(a)}{g'(a)}  
	 $$
- 
	1. **Start with ∣f(x)−L∣ and manipulate it to relate to ∣x−a∣.**
    
	2. **Sometimes restrict δδ (e.g., δ≤1δ≤1) to control extra terms.**
    
	3. **Choose δδ as the minimum of multiple constraints (if needed).**
