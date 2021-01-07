# libtpng
libtpng is a trusted version of [libpng](https://github.com/glennrp/libpng) running on Intel SGX environment.  
Up to now, this library can be compiled as a static library with the Intel SGX C library, however, command I/O and FILE I/O are currently disabled given that it is impossible in the enclave. I may write a OCALL wrapper later to implement the full-stack I/O function and replace the naive C standard I/O code in the libpng, but not now. (quitely busy in recent days:()
## Compilation
TBA  
The original README of libpng is [here](https://github.com/xymeng16/libtpng/blob/main/README).
