View this project on [CADLAB.io](https://cadlab.io/project/28988). 

# DIMECRES_ML_AL_SEIENTS
## Autors
- Mateo Lavandera Mulet (@mateolavandera)
- Alex Lara Bailon (@AlexLB4)

## Versió - v1.0 ## Curs - Assignatura de Disseny de PCBs amb KiCad - [Curs 2024-2025]

## Objectiu Descripció breu de l'objectiu del projecte.
L’objectiu del nostre projecte és dissenyar un sistema que sigui capaç d'executar correctament les diferents funcions que controlen uns seients elèctrics d’un cotxe qualsevol.

## Requisits i especificacions
→ 3 motors (posició, alçada, reclinació) amb els seus finals de carrera. 
→ Calefacció del seient. 
→ Sensor digital de cinturons. 
→ Memòria externa no volàtil per guardar posicions preprogramades.

## Diagrama de blocs (Afegiu una imatge del diagrama de blocs)
### Primera versió
![Diagrama de blocs](Diagrama%20de%20blocs%20EdD%20(1).jpg)

## Taula de components
| Descripció | Manufacturer Number | Package | Datasheet | Proveïdor | Unitats |
|------------|--------------------|---------|----------|----------|---------|
| Regulador Lineal 1.5 A  | LD1086V | TO-220 | [Enllaç](https://www.st.com/content/ccc/resource/technical/document/datasheet/53/db/00/58/09/98/4b/36/CD00001884.pdf/files/CD00001884.pdf/jcr:content/translations/en.CD00001884.pdf) | DigiKey | 1 |
| Microcontrolador PIC 8-bit | PIC18F4580-I/PT | 44-TQFP | [Enllaç](https://ww1.microchip.com/downloads/en/DeviceDoc/39637d.pdf) | DigiKey | 1 |
| Sensor Analog 0C-100C | LM35DMX | 8-SOIC | [Enllaç](https://www.ti.com/lit/ds/symlink/lm35.pdf?HQS=dis-dk-null-digikeymode-dsf-pfnullwwe&ts=1742666999263&ref_url=https%253A%252F%252Fwww.ti.com%252Fgeneral%252Fdocs%252Fsuppproductinfo.tsp%253FdistId%253D10%2526gotoUrl%253Dhttps%253A%252F%252Fwww.ti.com%252Flit%252Fgpn%252Flm35) | DigiKey | 1 |
| DRV Bipolar 4.5-36 V  | L293D | 16-DIP | [Enllaç](https://www.st.com/content/ccc/resource/technical/document/datasheet/04/ac/22/f9/20/5d/43/a1/CD00000059.pdf/files/CD00000059.pdf/jcr:content/translations/en.CD00000059.pdf) | DigiKey | 2 |
| Memòria EEPROM I2C 5 mA  | 24LC512T-I/SN | 8-SOIC | [Enllaç](https://ww1.microchip.com/downloads/en/DeviceDoc/24AA512-24LC512-24FC512-512K-Bit-I2C-Serial-EEPROM-20001754Q.pdf) | DigiKey | 1 |
| Bus CAN (TRANSCEIVER) | TJA1051T	| 8-SOIC | [Enllaç](https://www.nxp.com/docs/en/data-sheet/TJA1051.pdf) | DigiKey | 1 |
| Final de carrera (Comparador) 5 V 2 mA  | LM393DT | 8-SOIC | [Enllaç](https://www.st.com/content/ccc/resource/technical/document/datasheet/group1/b4/cc/cf/13/18/28/44/f5/CD00000465/files/CD00000465.pdf/jcr:content/translations/en.CD00000465.pdf) | DigiKey | 3 |

## Funcionalitats
- [ ] Funció 1
- [ ] Funció 2
- [ ] Funció 3

## Historial de canvis 
| Data | Autor | Branch | Descripció |
|------------|-------|--------|-----------------------------------------------------|
| 2025-03-22 | Alex | `main` | Modificación readme, concretament llistat d'elements |
| 2025-03-22 | Mateo | `main` | Correcció del biagrama de blocs |
| 2025-03-23 | Mateo | `main` | Primera versió de l'esquemàtic  |
| 2025-03-24 | Mateo | `main` | Segona versió de l'esquemàtic  |






