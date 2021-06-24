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
git clone \
  --depth 1  \
  --filter=blob:none  \
  --sparse \
  https://github.com/RebornOS-Developers/pkgbuilds \
;
cd pkgbuilds
git sparse-checkout init --cone
git sparse-checkout set peony-extensions
cd poeny-extensions
```
### to build this package
```
makepkg --syncdeps 
```
