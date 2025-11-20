# **Elliptic Curve & RSA Cryptography Algorithms**
### *Computational Number Theory & Applied Cryptography – SageMath + Python*

This repository contains a collection of Jupyter notebooks exploring foundational algorithms in **integer factorization, RSA encryption**, and **elliptic curve cryptography (ECC)**.  
The work demonstrates practical implementations of classical and modern cryptographic techniques, as well as the mathematical reasoning behind their security.

---

## 📂 **Contents**

### **1. RSA Cryptosystem**
- RSA key generation with large primes  
- Modular exponentiation for encryption/decryption  
- Chinese Remainder Theorem (CRT) optimization  
- Demonstrations of RSA correctness and message recovery  

### **2. Integer Factorization Techniques**
- Trial division and Pollard-style methods  
- Use of number-theoretic tools to break small RSA keys  
- Insights into how factorization difficulty underpins RSA security  

### **3. Elliptic Curves Over Finite Fields**
- Computing rational points on elliptic curves  
- Visualizing curve structure and point group behavior  
- Point addition, doubling, and scalar multiplication  
- Determining group order and point orders using SageMath  

### **4. Elliptic Curve Discrete Logarithm Problem (ECDLP)**
- Baby-step Giant-step implementation for ECC  
- ECM-style (Elliptic Curve Method) factorization concepts  
- Observations on algorithmic efficiency and runtime scaling  

---

## 🛠️ **Tech Stack**
- **SageMath** — number theory, finite fields, elliptic curves  
- **Python** — algorithm implementation  
- **Jupyter Notebook** — interactive computation and visualization  

---

## 🚀 **Key Learning Outcomes**
- Implemented RSA and ECC from first principles  
- Gained hands-on experience with number-theoretic algorithms  
- Computed point groups, orders, and curve operations  
- Used computational tools for algebraic structures in cryptography  

---

## 📘 **How to Use**

### **Open in SageMath**
If you have Sage installed locally:
```bash
sage -n jupyter
```
Upload any `.ipynb` file and run the cells.

### **Open in Standard Jupyter (Python)**
Some notebooks run in Python 3 alone, but ECC notebooks require SageMath.  
To open standard notebooks:
```bash
jupyter notebook
```

---

## 🧩 **Project Background**
These notebooks were originally created as part of advanced coursework in **Number Theory, Cryptography, and Elliptic Curve Mathematics**.  
They serve as both learning material and reference implementations for anyone studying modern cryptographic foundations.

---

## 📄 **License**
Released under the **MIT License**.  
Feel free to use, modify, and extend the code.
