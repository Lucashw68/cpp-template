# cpp-template

![Linux](https://github.com/Lucashw68/cpp-template/workflows/Linux/badge.svg)
![Macos](https://github.com/Lucashw68/cpp-template/workflows/Macos/badge.svg)
![Windows](https://github.com/Lucashw68/cpp-template/workflows/Windows/badge.svg)

 - Cross-platform C++ boilerplate with meson build system

# Linux / MacOS

 - Build
```
chmod +x ./build
./build
```

 - Clean
```
chmod +x ./clean
./clean
```
# Windows

 - Build
 ```
 meson setup Dist/
 cd Dist/ && ninja
 ```

 - Clean
 ```
 rd /s /q "Dist"
 ```
