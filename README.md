# Peony-extensions
Peony-extensions is made from https://github.com/ukui/peony-extensions their version must match the peony file manager to work to build peony

```
git clone https://github.com/ukui/peony-extensions.git
cd peony-extensions.git
(comment out computerview module in the .pro file)
mkdir build
cd build
qmake ..
make 
```
Afterwards copy the .so file into this

### To clone this repository 
```
git clone https://github.com/RebornOS-Developers/peony-extensions.git
```
### to build this package
```
makepkg --syncdeps 
```
