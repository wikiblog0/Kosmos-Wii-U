Paquete todo en uno de aplicaciones homebrew de Wii U.

## Como Usarlo
Ve a la seccion "release" para descargar la ultima actualizacion del paquete. Una vez descargado, descomprima el paquete .zip y los archivos que aparezcan paselos a la raiz de la tarjeta sd que esta utilizando para la Wii U.

## Aplicaciones Incluidas en el paquete.
* [ftpiiu everywhere](https://github.com/wiiu-controller-mods/ftpiiu-everywhere)
* [HID to VPAD](https://github.com/wiiu-controller-mods/hid_to_vpad)
* [Homebrew App Store](https://github.com/fortheusers/hb-appstore)
* [Homebrew Launcher](https://github.com/dimok789/homebrew_launcher)
* [NUSspli](https://github.com/V10lator/NUSspli)
* [vWii Decaffenaitor](https://github.com/GaryOderNichts/vWii-Decaffeinator)
* [NAND Dumper](https://github.com/koolkdev/wiiu-nanddumper)
* [SaveMii Mod Wut Port](https://github.com/Xpl0itU/savemii)
* [Bloopair](https://github.com/GaryOderNichts/Bloopair)
* [WUP Installer GX2](https://github.com/wiiu-controller-mods/wup-installer-gx2)
* [Disc2App](https://github.com/Xpl0itU/disc2app)
* [WiiU-Shell](https://github.com/kenny1983/WiiU-Shell)
* [UFDiine](https://github.com/GaryOderNichts/UFDiine)
* [fixyourstick](https://github.com/Xpl0itU/fixyoustick)

## Canales Incluidos en el paquete.
* [Homebrew Launcher Channel](https://github.com/GaryOderNichts/homebrew_launcher/releases)

## Observaciones
*En este paquete no estaran los archivos de Tiramisu u otro programa de liberacion, ya que aun hay usuarios de Wii U que no se han migrado a Tiramisu y por lo tanto este paquete subira las versiones de las aplicaciones que sean compatibles con todos los CFW de Wii U.
Para aquellas personas que tengan problemas para poner el paquete en la tarjeta de memoria o quieran hacer sugerencias de aplicaciones que quieran que pongan en el paquete lo pueden hacer en la seccion "issues".

*Una vez que hayan pasado los archivos del paquete a la memoria sd pueden instalar el canal de homebrew launcher con la aplicacion Wup Installer GX y pueden instalarlo tanto en la Nand como en el disco duro/USB.

*La version de NUSspli incluida en el paquete es la 1.58 por considerarla la mas estable. Tambien hay que destacar que para los otros exploits como indexiine, haxchi,etc. la ultima version soportada por NUSspli es la 1.77, a partir de la 1.78 para arriba solo es para Tiramisu.

*Si desean visitar los repositorios oficiales de las aplicaciones que estan incluidas en el paquete, pueden darle click al nombre de las aplicaciones que se encuntran en la seccion "aplicaciones incluidas en el paquete" que estan de color azul, asi podran conocer mas informacion acerca de la aplicacion y de las demas versiones que tiene la aplicacion.

## Para los Nuevos Usuarios
* Para los nuevos usuarios de una Wii U que quieran liberar/modificar su Wii U, recomiendo visitar la "Guia de Piloncillo" en la cual estan las instrucciones a detalle de como liberar su Wii U a traves de Tiramisu. Link: https://piloncillo.github.io/
*Tambien dejo la guia oficial inglesa de liberacion/modificacion de Wii U para aquellos usuarios de habla inglesa nativa: https://wiiu.hacks.guide/#/

# Para los Nuevos Programadores
Para los usuarios de Wii U o emulador CEMU que tengan conocimiento en programacion y quieren entrar al mundo de desarrollo de aplicaciones o emuladores homebrew de Wii U, les dejo el link a la guia de programacion de Yawt donde se explica al detalle como comenzar a programar y lo que se necesita. Link: https://github.com/yawut/ProgrammingOnTheU/blob/master/tutorial/Chapter%201.md

Les dejo el blog de Clownacy donde explica de manera general como hacer ports de aplicaciones o juegos android a Wii U. Link: https://clownacy.wordpress.com/2021/02/12/porting-sonic-cd-2011-to-the-wii-u/

Tambien adjunto links de las herramientas y librerias necesarias para comenzar a programar en Wii U y para hacer las pruebas de ejecucion y rendimiento de las aplicaciones homebrew: 

## Librerias que se ocupan para hacer aplicaciones en Wii U
- [pacman](https://github.com/devkitPro/pacman/releases) Libreria de devkitpro que descarga la sublibreria de devkitppc que va ser necesaria para hacer el port de 
Wii U.
- [Wii U Toolkit (WUT)](https://github.com/devkitPro/wut/releases) libreria para crear los ejecutables de las aplicaciones homebrew de Wii U rpx/rpl
- [SDL](https://github.com/yawut/SDL/releases) port de la libreria sdl2 para su uso en homebrew de Wii U.

## Posibles herramientas que se puedan ocupar en Wii U:
- [gx2textureShader](https://github.com/rw-r-r-0644/gx2textureShader) es una simple aplicacion para renderizar graficos 2D en Wii U.
- [librw](https://github.com/GaryOderNichts/librw) reimplementacion de la RenderWare Graphics engine en los renderizados 3D de los graficos gx2 de la Wii U. Esta libreria se utilizo para renderizar los graficos de los ports de Wii U de los GTA 3 y GTA Vice City.

## Para las herramientas de devkitpro dejo los siguientes enlaces que le serviran de guia para su uso: 
- https://devkitpro.org/wiki/Getting_Started
- https://devkitpro.org/wiki/devkitPro_pacman

## Para hacer pruebas al ejecutable rpx/rpl de Wii U se ocupan estas herramientas:
- [RPL Studio](https://github.com/BullyWiiPlaza/RPL-Studio)
- [RPL2elf](https://gbatemp.net/threads/tutorial-how-to-decompress-and-repack-rpx-rpl-files.399934/) Para mas informacion visitar este link:https://github.com/Relys/rpl2elf
- [RPXReader](https://github.com/phacoxcll/RPXReader)

Por ultimo, para aquellas personas que quieran hacer ports de juegos hechos con pixealart como [Celeste Classic 2](https://github.com/ExOK/Celeste2) pueden usar la herramienta [GB Studio](https://github.com/chrismaltby/gb-studio) que permite crear o editar juegos en formato gb,gbc y gba para que puedan ser ejecutados en emuladores, Virtual Console de Wii U o si tienen los recursos a traves de inyectar el juego en un cartucho y ejecutarlos en la consola.
