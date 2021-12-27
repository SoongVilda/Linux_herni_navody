# Jak spustit FlatOut: Ultimate Carnage
Většinou nefunguje po instalaci z obchodu Steam, je nutné udělat malou úpravu. 

## 1. Nainstalujeme FlatOut: Ultimate Carnage
Můžete zkusit hru zapnout, ale ve většině případů se nespustí.
![Screenshot_20211227_182302](https://user-images.githubusercontent.com/61845673/147493962-62e6a07d-6f3d-410d-8d83-e7bb2fe30e48.png)

## 2. Oprava umožňující zapnutí hry
1. Stáhni Ultimate-ASI-Loader.zip, NEstahuj Ultimate-ASI-Loader_x64.zip (Pozor, musí se jednat o 32-bit!). <dd> https://github.com/ThirteenAG/Ultimate-ASI-Loader </dd>
2. Extrahuj archiv, ukáže se ti soubor ```dinput8.dll```
3. Přejmenuj ```dinput8.dll``` na ```xlive.dll```
4. Přejmenovaný soubor ```xlive.dll``` vlož do složky, kde je nainstalovaný FlatOut: Ultimate Carnage. <dd>V mém případě ```/home/vilda/.steam/steam/steamapps/common/FlatOut Ultimate Carnage/```</dd>
5. Přeji příjemné hraní!
![Screenshot_20211227_184251](https://user-images.githubusercontent.com/61845673/147495257-90b251b7-d013-4155-949e-20bdaafec0b8.png)

## Testováno na zařízení: Dell Inspiron 14z (5406)
```
Operační systém: Arch Linux
Verze KDE Plasma: 5.23.4
Verze KDE Frameworks: 5.89.0
Verze Qt: 5.15.2
Verze jádra: 5.15.11-zen1-1-zen (64-bit)
Grafická platforma: Wayland
Procesorů: 8 × 11th Gen Intel® Core™ i5-1135G7 @ 2.40GHz
Paměť: 7,5 GiB RAM
Grafický procesor: Mesa Intel® Xe Graphics
```
## Zdroje - použito při tvorbě návodu
https://www.protondb.com/app/12360
