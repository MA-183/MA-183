---
draft: "true"
title: 📄 Den antideriverte
---
> [!info] Den antideriverte, definisjon 7
>  En *antiderivert* til en funksjon $f$ på et interval $I$, er en annen funksjon $F$ som oppfyller
>  $$F'(x) = f(x) \quad \quad \text{ for } x \text{ i } I$$

> [!info] Eksempel 
>  1. $F(x) = x$ er en antiderivert til funksjonen $1$ på $\mathbb{R}$, fordi $F'(x) = 1$ for alle $x$.
>  2. $G(x) = x$ er antiderivert til funksjonen $g(x) =\frac{x^2}{2}$ fordi $G'(x) = \frac{2x}{2}= x$ for alle $x$. 
>  3. $H(x) = x+5$ er antiderivert til funksjonen $g(x)=\frac{x^2 }{2 }$ fordi $H'(x) = \frac{2x }{2 }=x$ for alle $x$.

Fra 2. og 3. ser vi at antideriverte kan ha hvilken som helst konstant lagt til, fordi $(F(x) + C)' = F'(x)+0$. Dermed kan vi snakke om generelle antideriverte, $F(x)+C$, der $F(x)$ er en en vilkårlig antiderivert til $f$ og $C$ er en konstant i $\mathbb{R}$.

> [!info] Det ubestemte integralet 
>  Det *ubestemte integralet* til $f(x)$ på et interval $I$ er 
>  $$\begin{aligned} \int{ }^{ } f(x) dx = F(x) + C  \end{aligned}$$ på $I$. Gitt at $F'(x) = f(x)$ for alle $x$ i $I$.