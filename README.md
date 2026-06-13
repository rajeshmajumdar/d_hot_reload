# d_hot_reload
A stb style Qt Plugin hot-reloader header for windows.

## Usage
- Include this header anywhere, e.g. in PluginManager
- In PluginManager.cpp, define `D_HOT_LOADER_IMPLEMENTATION` before including.

## Example
```cpp
// exisiting includes
#define D_HOT_LOADER_IMPLEMENTATION
#include "d_hot_reload.h"
```
