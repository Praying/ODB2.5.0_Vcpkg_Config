## What's this
This is an <b>unofficial</b> vcpkg portfile of ODB to someone who need to update your c++ compiler to c++17,
 because that, the ODB 2.4.0  will not compile with c++17 (c++14 is ok)

## How to use
just 
replace the libodb/portfile.cmake to your_vcpkg_path/ports/libodb/portfile.cmake,
replace the libodb-mysql/portfile.cmake to your_vcpkg_path/ports/libodb-mysql/portfile.cmake,
after you replace these files, just run
```
./vcpkg install libodb
./vcpkg install libodb-mysql
```
## BTW
the version is 2.5.0-b9, and the odb compiler (version 2.5.0 but not b9) can be downloaded in [here](https://codesynthesis.com/~boris/tmp/odb/pre-release/b.3/)
if you didn't use vcpkg, these file may not help.
thanks!
