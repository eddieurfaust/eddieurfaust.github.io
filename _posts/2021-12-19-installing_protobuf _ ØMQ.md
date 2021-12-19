---
published: false
layout: post
---
# C++

- [install vcpkg](https://github.com/microsoft/vcpkg#quick-start-windows)
- `vcpkg install protobuf[zlib] protobuf[zlib]:x64-windows`
- `vcpkg install zeromq:x64-windows`

# Python

- [install pip](https://phoenixnap.com/kb/install-pip-windows)
- `pip install protobuf==3.14.0`
- `pip install zeromq==4.3.3`


### Problem(s)

##### Package versioning with **vcpkg**

- with vcpkg one can't install a specific version easily, only the 'current' one
- so a workaround may be to install the vcpkg version and specify the installed version accordingly using pip
- this is probably quicker than building the libs manually
- try [conan](https://github.com/conan-io/conan) (according to [this](https://github.com/52doho/vcpkg-vs-conan))
- [conan, vcpkg or build2?](https://www.reddit.com/r/cpp/comments/9m4l0p/conan_vcpkg_or_build2/)
