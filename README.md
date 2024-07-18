# libstdc++

Freestanding headers

## Config

You might need to create `features.h` with the following

```cpp
#pragma once

#define __GLIBC_PREREQ(maj, min) 0
#define __cpp_lib_out_ptr 0
```