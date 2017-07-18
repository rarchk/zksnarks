Compuational Complexity of ZK-snarks
=== 

## Compuation Primitives in ZK-Snarks 
- Multiplication of polynomials and evaluation equation at a random point `s`
- Computing elleptic pairing equation for polynomials of degree d. 
- Setting up key and generating **CRS**, Verification and Prover keys.  

## Performance can be improved by  
- Parallelizing Polynomial multiplication via fft in log(n) time
- Use of architecutres like CUDA and FPGA to accelerate computations 
- Acceleration of crypto-primitives used in elleptic pairing.  
- Low cost trusted setup creation using cheap cloud instances and leveraging Kubernetes or other cluster manage services. 
