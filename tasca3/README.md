## Seguretat Lògica: recuperant accés a sistemes

# README.md

## Informació de l'activitat

Després de la primera feina exitosa, us arriba un encàrrec urgent que obliga a que us hi poseu per donar-li solució.

Com a fase prèvia rebreu una formació sobre la **seguretat lògica** que us permetrà tenir els coneixements necessaris per afrontar la tasca.

Han arribat a la consultora un equip provinent d’un client que demana que els hi solucionem el problema.

Tenen un portàtil amb **Zorin OS** (un Linux amb entorn gràfic) que usava habitualment un directiu. El problema és que ha oblidat la contrasenya i és necessari poder recuperar l’accés perquè hi ha documentació molt important que cal recuperar. Per evitar que una acció catastròfica pugui danyar l’equip original, ens han **clonat el disc** en un disc virtual perquè hi treballeu.

Per tant, el primer pas serà crear una màquina virtual a la que connectareu aquest disc. A continuació, cal que entreu a la màquina virtual, trobeu el nom de l’usuari existent i assigneu-li una contrasenya nova.

Quan el client és informat del senzill que és accedir a l’equip, demana si n’hi ha alguna manera de fortificar el sistema, ja que té por que si algú roba el portàtil hi pugui accedir a la informació que hi conté. Per tant, ara ens demanen que cerquem solucions per tal d’evitar que es pugui reiniciar la contrasenya amb el procediment anterior.

Investigueu el procediment per tal que l’accés al **GRUB** quedi protegit per contrasenya per evitar canvis de configuració.


---

## Procediment individual (resum i requisits)

- El disc corresponent al sistema a vulnerar el teniu a la **Comuna** dins la carpeta `ISO/seguretat`.
- Descarregueu l'arxiu del disc clonat a la vostra màquina de treball.
- Creeu una màquina virtual Linux amb les següents característiques:
  - **RAM:** 8 GB
  - **CPU:** 2 vCPU
  - **Disc:** crear la VM **sense disc** (s'hi connectarà el disc clonat)
- Un cop creada la màquina virtual:
  1. Moveu el fitxer del disc clonat a la carpeta de la màquina virtual.
  2. Connecteu el disc clonat a la màquina virtual des del gestor de la VM.
  3. Inicieu la màquina virtual i accediu a la consola/entorn per procedir amb la recuperació de l'accés.

## Imatges del procediment 
[solucio.md](Projecte2/tasca3/solucio.md)
---



---



