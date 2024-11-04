### Number Theoric

  - Divisor

    m|n, n=km 라고 한다. m is a factor of n; or n is a multiple of m
    a|b and b|a then, a=b; a|b, b = ak for some k; b|a, a = bk for some k. 

    Division algorithm: given any two positivie integers a and b, there exist integers q and respectively called the quotient and the remainder
     - a = bq + r, 0 <= r < b.
    
    This known as "division algorithm," even though it isn't real algorithm.
    gcd(a,b) = gcd(b, a mod b)

  - Extended Euclid (very important!)


### RSA algorithm

  - Ciphertext: The encrypted, unreadable message
  - Encryption: Converting plaintext to ciphertext
  - Decryption: Converting ciphertext back to plaintext

Turing'code  
  C = M * e (Mod n)  
  decryption: Multiply the multiplicative inverse d of e
  M * e * d (Mode n)

  우리가 암호문과 매세지를 알고있을 때,  
  j, inverse of M  
  j * M * e (Mod n) = e (Mod n)

  #### Modular exponentiation (지수) 
  a^b (mod n), a >= 0, b >= 0, n> 0

  ##### Euler's phi function  
   phi(n) = the number of positive integers
  
    
