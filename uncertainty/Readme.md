### Uncertainty

**Sum or subtsract**: z = x+y -> u(z) = sqrt(u(x)^2 + u(y)^2)
**mean**: mean(u(x)) = u(x)/sqrt(N)
**multiplication**: u(z) / z = sqrt((u(x)/x)^2 + (u(y)/y)^2)
**power**: z = x^n  => u(z) / z = n*u(x) / x    . careful, here z = x^n different from the above, (multiplication)
**multiplication with constant**: z = a*x => u(z) = a u(x)
**composition function**: u(z) = f(x,y) => u(z) = sqrt((df/dx u(x))^2 + (df/dy u(y))^2)
