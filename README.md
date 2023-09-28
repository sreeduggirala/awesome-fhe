# awesome-fhe [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome things related to learning fully homomorphic encryption (FHE).

## Contents

- [General introduction](#general-introduction)
- [Courses](#courses)
- [Use cases](#use-cases)
- [Comparison of homomorphic encryption types](#comparison-of-homomorphic-encryption-types)
- [Applications](#applications)
  - [Zama](#zama)
  - [Fhenix](#fhenix)
  - [Sunscreen](#sunscreen)
- [Libraries](#libraries)

## General introduction

- [Introduction to Homomorphic Encryption: Microsoft Research](https://www.youtube.com/watch?v=SEBdYXxijSo) (YouTube)
- [How would you explain homomorphic encryption? by Office of the Director of National Intelligence](https://www.youtube.com/watch?v=pXb39wj5ShI) (YouTube)
- [Introduction to FHE (Fully Homomorphic Encryption) - Pascal Paillier, FHE.org Meetup by Zama](https://www.youtube.com/watch?v=aruz58RarVA) (YouTube)
- [The (r)Evolution of FHE by Jeremy Bradley-Silverio Donato](https://medium.com/zama-ai/the-r-evolution-of-fhe-485b54a6e69c) (Medium)
- [Fully Homomorphic Encryption: Cryptography’s Holy Grail by Dr. David J. Wu](https://www.cs.utexas.edu/~dwu4/papers/XRDSFHE.pdf)
- [An Intro to Fully Homomorphic Encryption for Engineers](https://blog.sunscreen.tech/an-intro-to-fully-homomorphic-encryption-for-engineers/)

## Courses

- [UT Austin CS 346: Cryptography](https://www.cs.utexas.edu/~dwu4/courses/sp23/index.html)
- [UIUC: ECE498AC/CS498AM: Applied Cryptography, Fall 2019](https://soc1024.ece.illinois.edu/teaching/ece498ac/fall2019/)

## Use cases

- [Applications of Fully Homomorphic Encryption W/ Zama by Blockchain Acceleration Foundation](https://www.youtube.com/watch?v=RcCEQJkXee0) (YouTube)
- [Privacy-Preserving Machine Learning with Fully Homomorphic Encryption by Google TechTalks](https://www.youtube.com/watch?v=-lhn2GdHhGc) (YouTube)

## Comparison of homomorphic encryption types

## Applications

### [Zama](https://www.zama.ai/)

- [awesome-zama](https://github.com/zama-ai/awesome-zama)

### [Fhenix](https://www.fhenix.io/)

### [Sunscreen](https://sunscreen.tech/)

- [Introducing Sunscreen](https://blog.sunscreen.tech/roadmap/)
- [Building an FHE compiler for the real world](https://blog.sunscreen.tech/from-toy-programs-to-real-life-building-an-fhe-compiler/)

## Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.

- [blyss](https://github.com/blyssprivacy/sdk) - Rust FHE library specialized for private information retrieval. Includes bindings to JS & Python.
- [Concrete](https://github.com/zama-ai/concrete): TFHE Compiler that converts python programs into FHE equivalents.
- [Concrete ML](https://github.com/zama-ai/concrete-ml): Privacy Preserving ML framework built on top of Concrete, with bindings to traditional ML frameworks.
- [cuFHE](https://github.com/vernamlab/cuFHE) - CUDA-accelerated Fully Homomorphic Encryption Library.
- [cuHE](https://github.com/vernamlab/cuHE) - GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs.
- [Cupcake](https://github.com/facebookresearch/Cupcake) - Facebook's Rust library for the (additive version of the) Fan-Vercauteren scheme.
- [cuYASHE](https://github.com/cuyashe-library/cuyashe) - Based on leveled fully HE scheme YASHE for GPGPUs.
- [fhEVM](https://docs.zama.ai/fhevm): A confidential smart contracts protocol for the EVM using homomorphic encryption.
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816).
- [FINAL](https://github.com/KULeuven-COSIC/FINAL) - C++ FHE library based on [NTRU and LWE scheme](https://eprint.iacr.org/2022/074).
- [FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) - A header-only library implementing the Fan-Vercauteren scheme.
- [HEAAN](https://github.com/snucrypto/HEAAN) - Scheme with native support for fixed point approximate arithmetic.
- [HEAAN-Python](https://github.com/Huelse/HEAAN-Python) - Python binding for the [HEANN](#HEAAN) library.
- [HElib](https://github.com/HomEnc/HElib) - BGV scheme with bootstrapping and the Approximate Number CKKS scheme.
- [HEMat](https://github.com/K-miran/HEMat) - C++ implementation of matrix computation (addition, multiplication, and transposition) using [HEANN](#HEAAN).
- [krypto](https://github.com/kryptnostic/krypto) - C++ implementation of multivariate quadratic FHE.
- [Λ ○ λ](https://github.com/cpeikert/Lol) - "Lol" Haskell library for ring-based lattice cryptography that supports FHE.
- [lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
- [libScarab](https://github.com/hcrypt-project/libScarab) - C library implementing a FHE scheme using large integers.
- [libshe](https://github.com/bogdan-kulynych/libshe) - Symmetric somewhat HE library based on DGHV scheme.
- [Microsoft SEAL](https://github.com/microsoft/SEAL) - C++ FHE library implementing BFV and CKKS schemes.</a>
- [NFLlib](https://github.com/quarkslab/NFLlib) - NTT-based Fast Lattice library specialized on power-of-two polynomials.
- [node-seal](https://github.com/morfix-io/node-seal) - JavaScript/WebAssembly port of [Microsoft SEAL](#SEAL).
- [NuFHE](https://github.com/nucypher/nufhe) - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe](#tfhe) algorithms.
- [OpenFHE](https://github.com/openfheorg/openfhe-development) - FHE library with all features from [PALISADE](#PALISADE), merged with selected capabilities of [HElib](#HElib) and [HEAAN](#HEAAN) (all major FHE schemes).
- [PALISADE](https://palisade-crypto.org/software-library) - lattice encryption library (superseded by [OpenFHE](#OpenFHE)).
- [petlib](https://github.com/gdanezis/petlib) - Python library that implements a number of Privacy Enhancing Technologies.
- [Pyfhel](https://github.com/ibarrond/Pyfhel) - A Python wrapper for [SEAL](#SEAL), [HElib](#HElib), and [PALISADE](#PALISADE).
- [python-paillier](https://github.com/data61/python-paillier) - Partially HE based on Paillier scheme.
- [SEAL-python](https://github.com/Huelse/SEAL-Python/) - Python binding for the [Microsoft SEAL](#SEAL) library.
- [SparkFHE](https://github.com/SpiRITlab/spark) - Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
- [Sunscreen](https://github.com/Sunscreen-tech/Sunscreen) - Rust compiler for the BFV fully homomorphic encryption scheme.
- [TenSEAL](https://github.com/OpenMined/TenSEAL) - Library for HE operations on tensors, built on [Microsoft SEAL](#SEAL), with a Python API.
- [tfhe](https://github.com/tfhe/tfhe) - Faster fully HE: Bootstrapping in less than 0.1 seconds.</a>
- [TFHE-rs](https://github.com/zama-ai/tfhe-rs): A Pure Rust implementation of the TFHE Scheme for Boolean and Integer Arithmetics Over Encrypted Data.
