# Links
- https://wiki.osdev.org/Getting_Started
- https://www.youtube.com/watch?v=1rnA6wpF0o4&list=PLHh55M_Kq4OApWScZyPl5HhgsTJS9MZ6M&index=1
- http://www.linuxfromscratch.org/lfs/view/stable/chapter05/chapter05.html

##  Development
### Build cross-compiler:
Update wget-list with latest stable LinuxFromScratch source links.
Go through https://wiki.osdev.org/GCC_Cross_Compiler
```
export BASE=$HOME/workspace/yaos
mkdir $BASE/sources
wget --input-file=wget-list --continue --directory-prefix=$BASE/sources
```

### Build yaos:
```
git clone https://github.com/ttousai/yaos
cd yaos
./qemu.sh
```
