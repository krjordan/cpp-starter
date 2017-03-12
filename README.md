## C++ Starter for VS Code on Mac

Once cloned, run the following commands inside the project to get up and running:

```
mkdir Debug
cd Debug
cmake -DCMAKE_BUILD_TYPE=Debug ..
```

This will generate a `Makefile` which can build an executable file from `main.cpp` using XCode's C++ compiler (AppleClang).

Use the `make` command to build the executable named `MAIN`.

To run the executable, use `./MAIN`.

This configuration was set up using a [blog post](http://www.suodenjoki.dk/us/archive/2016/vscode-cpp-mac.htm) by [Michael Suodenjoki](http://www.suodenjoki.dk/us/information/about_michael_suodenjoki.htm).
