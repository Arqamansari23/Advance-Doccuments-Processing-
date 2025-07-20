Work : If a force of   F x moves an object

$$\text{Average Function Value} \, : The \, \cdot$$

The average value

$$\text{in} \, a \leq x \leq b \,, \, \text{the work done is } W = \int _ { a } ^ { b } F ( x ) \, d x$$

$$\alpha \quad \text{ of } f ( x ) \text{ on } a \leq x \leq b \text{ is } f _ { a v g } = \frac { 1 } { b - a } \int _ { a } ^ { b } f ( x ) d x$$

Arc Length  Surface Area : Note that this is often a Calc II topic.  The three basic formulas are,

$$L = \int _ { a } ^ { b } d s ^ { - 1 } \quad S A = \int _ { a } ^ { b } 2 \pi y \, d s \ \text{(rotate about $x$-axis)} \quad S A$$

$$S A = \int _ { a } ^ { b } 2 \pi x d s \text{ (rotate about $y$-axis)}$$

where ds is dependent upon the form of the function being worked with as follows.     2 1 if , dy dx ds dx y f x a x b          2 1 if , dx dy ds dy x f y a y b              2 2 if , , dy dx dt dt ds dt x f t y g t a t b           2 2 if , dr d ds r d r f a b         

With surface area you may have to substitute in for the x or y depending on your choice of ds to match the differential in the ds .  With parametric and polar you will always need to substitute.

## Improper Integral

An improper integral is an integral with one or more infinite limits and/or discontinuous integrands. Integral is called convergent if the limit exists and has a finite value and divergent if the limit doesn't exist or has infinite value.  This is typically a Calc II topic.

## Infinite Limit

1.     lim t a a t f x dx f x dx     

$$2. \ \int _ { - \infty } ^ { b } f ( x ) d x = \lim _ { t \to - \infty } \int _ { t } ^ { b } f ( x ) d x$$

3.       c c f x dx f x dx f x dx            provided BOTH integrals are convergent.

## Discontinuous Integrand

1. Discont. at a :     lim b b a t t a f x dx f x dx     

$$2. \ D i s c o n t. \, a t \, b \, \colon \int _ { a } ^ { b } f ( x ) \, d x = \lim _ { t \rightarrow b ^ { - } } \int _ { a } ^ { t } f ( x ) \, d x$$

3. Discontinuity at a c b   :       b c b a a c f x dx f x dx f x dx      provided both are convergent.

Comparison Test for Improper Integrals : If     0 f x g x   on   , a  then,

1. If   a f x dx   conv. then   a g x dx   conv. 2. If   a g x dx   divg. then   a f x dx   divg. Useful fact : If 0 a  then 1 a p x dx   converges if 1 p  and diverges for 1 p  .

## Approximating Definite Integrals

For given integral   b a f x dx  and a n (must be even for Simpson's Rule) define b a n x    and divide   , a b into n subintervals   0 1 , x x ,   1 2 , x x , … ,   1 , n n x x  with 0 x a  and n x b  then,

Midpoint Rule :

$$\cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cdot \cd.$$

Trapezoid Rule :

            0 1 2 1 2 2 2 2 b n n a x f x dx f x f x f x f x f x              

Simpson's Rule :

$$\text{son} ^ { \text{s} } Rule \colon \int _ { a } ^ { b } f ( x ) d x \approx \frac { \Delta x } { 3 } \left [ f ( x _ { _ { 0 } } ) + 4 f ( x _ { _ { 1 } } ) + 2 f ( x _ { _ { 2 } } ) + \dots + 2 f ( x _ { _ { n - 2 } } ) + 4 f ( x _ { _ { n - 1 } } ) + f ( x _ { _ { n } } ) \right ]$$