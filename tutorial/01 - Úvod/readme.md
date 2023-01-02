# Úvod do programování mikrokontrolérů AVR
V této části tutoriálu se seznámíme s programováním mikrokontrolérů AVR. Přečtěte si prosím [toto](/readme.md).

## Vyžadované předchozí znalosti
* **Základy elektroniky** - je dobré znát nějaké základní veličiny, definice, zákony elektřiny atd.
* **Programování** v jazyce C.

## Potřebné hardwarové, softwarové i firmwarové vybavení
Abychom mohli programovat mikrokontrolér, budeme potřebovat
* **Funkční počítač** - Ideálně počítač s operačním systémem **Linux**, zkuste vybrat Linuxovou distrubuci, která nemá specifické využití (doporučuji **Arch Linux**).  
Pokud nechcete používat Linux, použijte Microsoft **Windows XP** nebo novější;
* **Programátor - Zařízení používané k manipulaci s paměti mikrokontroléru**. -  Dají se sehnat nejen za pár tisíců, ale i stovek. Doporučuji používat
programátor USB-ASP za pár stovek;
* **Mikrokontrolér** ATMega architektury AVR - Nejlépe několik (2 až 4) mikrokontrolérů **ATMega 168P-PU**;
* **Základní elektronické komponenty** - LED diody, rezistory, kapacitátory, propojovací drátky atd.;
* **Nepájivé kontaktní pole** (breadboard) - Snadné vkládání a vyjímání součástek z obvodu, není potřeba pájka;  
* **SW: Kompilátor jazyka C** s podporou AVR - Ke kompilaci zdrojového kódu. Použijte např. **MPLAB XC8** nebo avr-gcc (pro systém Linux);
* **SW: Vývojové prostředí** - **Microchip/ATMEL Studio**, [Code::Blocks IDE](http://www.codeblocks.org/) nebo MPLAB IDE. Může však posloužit jakýkoliv obyčejný textový editor, ale doporučuje se použít IDE jako je Microchip Studio
* **SW: Program pro manipulaci s pamětí mikrokontroléru** - **avrdude**, pokud používáte Microsoft Windows, použijte nástroje vestavěné ve vývojovém prostředí, případně použijte **MPLAB IPE**.
* **FW: Drivery pro programátor** - pok

### Instalace (archlinux)
```sh
sudo pacman -Sy avrdude nano avr-binutils avr-gcc avr-libc avr-gdb
