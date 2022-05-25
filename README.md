# NumPy

<p>NumPy нь Python хэлний сан бөгөөд том, олон хэмжээст массив болон матрицуудыг дэмждэг бөгөөд эдгээр массивууд дээр ажиллах өндөр түвшний математикийн функцуудын цуглуулгатай.</p>

## 1. Introduction

### Data Types

| Type     | Name | Bytes     | Description |
| :---        |    :----:   |   :----: | ---: |
| bool      | b       | 1   | Boolean (True or False) stored as a byte |
| int   | l        | 4-8      | Platform (long) integer (normally either int32 or int64) |
| intp | p | 4-8 | 	Integer used for indexing (normally either int32 or int64) |
| int8 |	i1 |	1 |	Byte (-128 to 127) |
| int16 |	i2 |	2	| Integer (-32768 to 32767) |
| int32 |	i4 |	4 |	Integer (-2147483648 to 2147483647) |
| int64 |	i8 |	8 |	Integer (-9223372036854775808 to 9223372036854775807) |
| uint8 |	u1 |	1 |	Unsigned integer (0 to 255) |
| uint16 | u2 | 2 |	Unsigned integer (0 to 65535) |
| uint32 |	u4 |	4 |	Unsigned integer (0 to 4294967295) |
| uint64 |	u8 |	8 |	Unsigned integer (0 to 18446744073709551615) |
| float  |	f8 |	8 |	Shorthand for float64 |
| float16 |	f2 |	2 |	Half precision float: sign bit, 5 bits exponent, 10 bits mantissa |
| float32	| f	|4	| Single precision float: sign bit, 8 bits exponent, 23 bits mantissa |
| float64	| d |	8 |	Double precision float: sign bit, 11 bits exponent, 52 bits mantissa |
| complex |	c16 |	16 |	Shorthand for complex128. |
| complex64 |	c8 | 8 | Complex number, represented by two 32-bit floats |
| complex128 | c16 | 16 | Complex number, represented by two 64-bit floats |
