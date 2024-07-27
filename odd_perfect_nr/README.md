# Background

All perfect numbers so far are even, but it cannot yet be proven that odd numbers cannot be perfect.

definition of divisors: each natural number N has a list of divisors div(N) = {1, D1, D2, ..., Dk, N}

definition of perfect number: Sum(div(N)) = 2N, or Sum(div(N) w/o N) = N

# Approach

A new (or old, I dont know??) approach shall prove that odd numbers cannot be perfect!

Each natural number N (also primes) have at least two divisors: 1 and N!


I call **proper divisors** all divisors that are not 1 and N, so D(N) = {D1, D2, .. , Dk} (compare to div(N) above).

So for perfect numbers Sum(D(N)) = (N-1)

If D1 = 2, N is even -> if N is odd, D1 must be an odd prime, at lowest D1 = 3.
If the count of proper divisors k is > 1, Dk and D1 alway correspond via: D1*Dk = N.

If D1 = 3 (lowest possible prime) and k > 2, then Sum(D2, .., Dk-1) must be > 2/3N - 4. 

I want to prove that this is not possible!! And it is even less possible for D1 > 3
