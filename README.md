# Workstations de Gaia
### 2x Sun Ultra 10
- UltraSPARC IIi
- los dos tienen onboard VGA pero uno no tiene grafica chula 13W3
- puerto de teclado propietario Sun Tipo 5
- sin teclado no saca video, modo consola
- consola puerto serie 'A' DB-25

#### 10 Sin grafica
- NVRAM mal
- Casi arranca Solaris 9, UFS con alguna inconsistencia

#### 10 Con grafica
- no droppea a OBP, NVRAM ok???
- intenta arrancar un linux loool, pero SILO (SPARC bootloader for linux) no puede leer su config, error ext2, disco mal? falta otro disco?


https://github.com/tmk/tmk_keyboard/wiki/Sun-Keyboard-Protocol
https://forum.vcfed.org/index.php?threads/how-to-workaround-when-your-sun-ultra-5-10-nvram-no-longer-works.52997/
http://www.lib.ru/TXT/faqsunnvram.txt

Creative 3D driver: https://gitlab.freedesktop.org/xorg/driver/xf86-video-sunffb
deps: build-essential autoconf libtool xserver-xorg-dev x11proto-dev

Debian sparc64/sun4u

### Sun Enterprise 250 "servidor torre gordo"
- 2x UltraSPARC II
- sin salida de video
- dos puertos serie 'A' 'B' DB-25
- supongo que consola en A
- puerto de teclado propietario Sun Tipo 5

### TOSHIBA T6400DX "portatil '93"
- 486DX con 4MB :D
- lo tipico
- pantalla (plasma?) muerta, saca video por VGA ok
- CMOS muerta
- disquetera estandar rota(?)
- disco asumido muerto

### SunBlade 100 "parece muyyyy PC"
- UltraSPARC IIe
- tiene una grafica VGA PCIx "Intense3D" chipset XILINX Spartan con pegatina de Sun, de fabrica lol
- boton de arranque no hace nada
- fuente ok(?)
- NVRAM probablemente muerta?, modulo de esos integrado
- pila CMOS aparte

### Sun Netra T1 105
- UltraSPARC IIi
- no salida de video
- puerto consola RJ45 propietario Sun (of course) diferente a Cisco
	
### IBM eServer xSeries 232 "otro server gordote"
- Pentium III :/
	
	
### SGI Indy
- arranca, falta contraseña
- update: HDD muerto
### SGI O2
- arranca, falta contraseña

### Monitor VGA coaxial raro (DB13W3)
- funciona

## TODO	
Falta encontrar teclado Sun Tipo 5 y raton Sun Tipo 5 o emularlo con arduino

### ideas chulas
- repos de software
  - https://es.tldp.org/mirror/sunfreeware/
  - https://ftp.deu.edu.tr/pub/Solaris/sunfreeware/
  - http://www.sunfreeware.net/programlistsparc7.html
  - https://fsck.technology/software/Sun%20Microsystems/Solaris%20Applications/
  - http://www.cilinder.be/archive/
- IRC
- netscape
- web server

### CDs quemados
- Sun Solaris 9 SPARC
- SGI IRIX 5.3 for Indy
- Debian 12 sparc64 netinst
- Debian 10.13 mips
- OpenBSD 7.4 sparc64
- OpenBSD 6.9 sgi
- NetBSD 9.3 sgimips

### Pedir a reciclATICA
- 2x disqueteras 3.5"
- 2x disco IDE minimo 9GB, otro minimo 3GB
- 2x disco SCSI
- 2x CD IDE ~24x
- si hubiera, perifericos Sun y SGI (prioridad teclado y raton Sun)

### Comprar
- CR2032 holders
- CR2032 baterias
- 3x NVRAM M48T59Y-70PC1 (Ultra 10)
- teclado Sun
  - https://www.ebay.es/itm/235320822046?hash=item36ca36c91e:g:RuMAAOSwZMJlZu9x
  - https://www.ebay.es/itm/335164745147?hash=item4e096025bb:g:uIQAAOSw6G9lergu
- Raton Sun
  - https://www.ebay.es/itm/276299573527?hash=item4054bce917:g:tMsAAOSwz-ZlE~zQ
  - https://www.ebay.es/itm/295729721640?hash=item44dadd7128:g:XYoAAOSwoSNkdorC
  - https://www.ebay.es/itm/126280807995?hash=item1d66ec363b:g:e24AAOSw5QhloufS
- conversor 13W3 VGA
  - https://www.amazon.es/Premium-Cord-Sun-Adaptador-13W3/dp/B07NSMVDB2/ref=sr_1_1
- RAM DIMM EDO ECC 256MB para Ultra 10 370-3201
  - https://www.ebay.es/itm/334969192246?hash=item4dfdb83f36:g:fc0AAOSwqyRkxrJo
  - https://www.ebay.es/itm/145031313084?hash=item21c48a36bc:g:lRkAAOSwRwhkNfI6
- almacenamiento SCSI
  - HDDs (caro)
  - https://amigastore.eu/es/600-zuluscsi-rp2040-adaptador-scsi-a-sd.html
  - bluescsi https://bluescsi.com/
  - interfaz SCSI USB

