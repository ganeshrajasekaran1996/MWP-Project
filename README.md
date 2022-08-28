# MWP-Project

MULTIPLICATION OF POLYNOMIALS USING FFT
Multiplication of polynomials usually takes O(n*m where one polynomial has n and other has m terms. This can be reduced to O(n*log(m)) by using FFT.
We are using the Cooley-Tukey FFT Algorithm which is a type of FFT to perform multiplication. 

The naive approach uses the coefficient form of the polynomial to calculate the product.
But a better approach is to convert from the coefficient form to point value representation.


OUTPUT
Parallel vs Sequential Comparison for input N=10000


![out](https://user-images.githubusercontent.com/47692164/187071202-aac6a72c-a488-466f-a52f-4ae4a51a24da.jpg)
