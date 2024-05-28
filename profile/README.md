## BEVE Organization
BEVE is a high performance, tagged binary data specification like JSON, MessagePack, CBOR, etc. But, designed for higher performance and scientific computing.

- Maps to and from JSON
- Schema less, fully described, like JSON (can be used in documents)
- Little endian for maximum performance on modern CPUs
- Blazingly fast, designed for SIMD
- Future proof, supports large numerical types (such as 128 bit integers and higher)
- Designed for scientific computing, supports brain floats, matrices, and complex numbers
- Simple, designed to be easy to integrate

> BEVE is designed to be faster on modern hardware than CBOR, BSON, and MessagePack, but it is also more space efficient for typed arrays.
