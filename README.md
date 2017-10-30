# Data relation plotting


Pairs output in simulated data to see how different relations look.
one can observe which relations are easily observable and which are not.
Also these can be used for future references to know if not easy relation can be deduced with this help.


Need to verify, so maybe you can try as i lost the script file.
A <- is a uniform distributed data with 100 generated values in range (0,100) with some noise around N(0,1)
B <- is another uniform distributed data with 100 generated values in range (0,100) with some noise around N(0,1)
aa <- linearly derived from a
bb <- linearly derived from a*b
cc<- derived from b/a
dd<- derived from a/b
ee<- derived from log(a*b)
ff<- derived from log(a)
gg<- derived from a^2
hh<- derived from a+a^2
ii<- derived from a^2 + b^2
jj<- derived from a^2+b^2+ab
kk<- derived from a^2-b^2
ll<- derived from sin(a*b)
mm<- derived from sin(a)