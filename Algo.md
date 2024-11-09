### Number Theoric

  - Divisor

    m|n, n=km 라고 한다. m is a factor of n; or n is a multiple of m
    a|b and b|a then, a=b; a|b, b = ak for some k; b|a, a = bk for some k. 

    Division algorithm: given any two positivie integers a and b, there exist integers q and respectively called the quotient and the remainder
     - a = bq + r, 0 <= r < b.
    
    This known as "division algorithm," even though it isn't real algorithm.
    gcd(a,b) = gcd(b, a mod b)

  - Extended Euclid (very important!)  어떠한 d 값에 대하여 d = ax + by임을 성립하는 것을 보여주는 것이다. 이후 RSA에서 사용될 것이다
  
  - gcd  
    gcd(a,b) = gcd(b,a mod b)

  - modular arithmetic  
    a ≡ b(mod n) => n|(a-b) => a-b = kn
    gcd(e,n) = 1일때 de = 1 (mod n) 울 만족하는 d는 extended Euclid를 활용하면 된다 (ex + ny = 1)
    


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
   gcd(a,n) = 1 일때, a^phi(n) ≡ 1(mod n)  
   phi(mn) = phi(m)*phi(m) when gcd(m,n) = 1  

   #### RSA akgorithm  
       ```
         1. 두 소수 p,q 선택, ㅜ = p*q 계산  
         2. gcd(e,phi(n))을 만족하는 e 선택
         3. e*d = 1(mod phi(n))을 만족하는 d 찾기
         4. public key(e,n) private key(d,n)
       ```   
  encryption     
    c = m^e(mod n)  
  decryption          
    m = c^d(mod n)
    
       
         
  
    
