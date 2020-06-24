# Linux From Stratch Super Turbo Giga Hyper Omega Astro Mega Ultra Bongoszaja XD Deluxe Edition prealpha release 0.1 early demo version

## Zalozenia
- pretty much [this](http://archive.is/zI5l0)
- ubuntu bad arch good void gooder gentoo better lfs best bsd bestest plan9 the absolute top best
- stallman to wariat ekstremista sympatyk pedofilii i boomer vim > nano > emacs a glibc ma bugi wgl jest wolne i jak krowa a musl libc jest supci
- lennart poettering to corporate shill pewnie sponsoruje go microsoft systemd jest okropny boze fujka ble omg (to nie tak ze uzywam archa jako daily driver i lubie systemd i systemd-boot cnie przysiegam) a sysv init jest dla starych dziadow
- haha budowanie ze zrodla jest super kompilator robi brrrr :D rolling release jest super a potencjalnie unstable system to najlepszy system
- najlepszy system to taki system gdzie jest <20 paczek (btw na ubuntu defaultowo jest z 2-3 tysiace paczek obrzydliwe) im mniej paczek tym lepiej kocham miec komputer z 2020 intel kor i69 50 paczek na krzyz [i ponizej 100mb ram consumption bedac na pulpicie :D](https://www.wykop.pl/cdn/c3201142/comment_rKQ6nslA6spAbP6l2a9Nu1BFP8ihzHX3,w400.jpg) przynajmniej wlacza sie w 2 sekundy na nvme ale super
- nie chce mi sie wiecej wymyslac

## Setup
### Host
- i7 9700k @ 5.1GHz
- 16 GB DDR4 3000MHz
- Windows 10 Pro Version 1903
- VMware Workstation Pro 15.5.1

### Guest / build environment
- Arch Linux
- 6/8 rdzeni
- 12/16GB
- linux-zen-5.7.5.zen1-1
- zsh 5.8
- gcc 10.1.0
- glibc 2.31-5
- systemd 245.6-8
- ```CFLAGS="-O3 -pipe -march=native"```
- ```CXXFLAGS="$CFLAGS"```
- ```MAKEFLAGS="-j6"```
