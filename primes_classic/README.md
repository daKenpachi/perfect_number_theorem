# Classic approach

A natural number is prime if it can only be divided by 1 and itself.

Therefore, all multiples of a prime cannot be prime, and all primes expect 2 must be odd.

A classic algorithm should provide a list of primes up to a limit X calculatable by normal PCs (eg uint32 max as limit)
for further experiments on primes, to provide ground truth and a fast *IsPrime*-function.
