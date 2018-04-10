# Obtaining the source archive

```
hg clone http://www.octave.org/hg/octave
cd octave
hg update stable
./bootstrap
./configure
make -j$(nproc)
make -j$(nproc) dist
cp octave-4.3.0+.tar.xz ..
```
