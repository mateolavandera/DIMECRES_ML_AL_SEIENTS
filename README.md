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
### Tercera versió (final)
![Diagrama de blocs](Diagrama%20de%20blocs%20EdD%203.jpg)

## Taula de components
| Descripció | Manufacturer Number | Package | Datasheet | Proveïdor | Unitats |
|------------|--------------------|---------|----------|----------|---------|
| Regulador Lineal 1.5 A  | LD1086V | TO-220 | [Enllaç](https://www.st.com/content/ccc/resource/technical/document/datasheet/53/db/00/58/09/98/4b/36/CD00001884.pdf/files/CD00001884.pdf/jcr:content/translations/en.CD00001884.pdf) | DigiKey | 1 |
| Microcontrolador PIC 8-bit 300mA | PIC18F4580-I/PT | 44-TQFP | [Enllaç](https://ww1.microchip.com/downloads/en/DeviceDoc/39637d.pdf) | DigiKey | 1 |
| DRV Bipolar 4.5-36 V  | L293D | 16-DIP | [Enllaç](https://www.st.com/content/ccc/resource/technical/document/datasheet/04/ac/22/f9/20/5d/43/a1/CD00000059.pdf/files/CD00000059.pdf/jcr:content/translations/en.CD00000059.pdf) | DigiKey | 2 |
| Memòria EEPROM I2C 5 mA  | 24LC512T-I/SN | 8-SOIC | [Enllaç](https://ww1.microchip.com/downloads/en/DeviceDoc/24AA512-24LC512-24FC512-512K-Bit-I2C-Serial-EEPROM-20001754Q.pdf) | DigiKey | 1 |
| Bus CAN (TRANSCEIVER) | TJA1051T	| 8-SOIC | [Enllaç](https://www.nxp.com/docs/en/data-sheet/TJA1051.pdf) | DigiKey | 1 |
| Final de carrera (Comparador) 5 V 4 mA  | LT1721 (Quad) | 16-SOIC | [Enllaç](https://www.analog.com/media/en/technical-documentation/data-sheets/17201fc.pdf) | DigiKey | 1 |
| Condicionador de temperatura (Amplificador) 30 mA  | LT6234 | 16-SSOP | [Enllaç](https://www.analog.com/media/en/technical-documentation/data-sheets/623345fc.pdf) | DigiKey | 1 |
| Sensor de temperatura 60uA | LM35 | 8-SOIC | [Enllaç](https://www.ti.com/lit/ds/symlink/lm35.pdf) | DigiKey | 1 |
| Relé 12mA | Omron G5V-1 | SIP-6 | [Enllaç](https://omronfs.omron.com/en_US/ecb/products/pdf/en-g5v_1.pdf) | DigiKey | 1 |



## Funcionalitats
- [ ] Funció 1
- [ ] Funció 2
- [ ] Funció 3

## Historial de canvis 
| Data | Autor | Branch | Descripció |
|------------|-------|--------|-----------------------------------------------------|
| 2025-03-22 | Alex | `main` | Modificació readme, concretament llistat d'elements |
| 2025-03-22 | Mateo | `main` | Correcció del diagrama de blocs |
| 2025-03-23 | Mateo | `main` | Primera versió de l'esquemàtic  |
| 2025-03-24 | Mateo | `main` | Segona versió de l'esquemàtic  |
| 2025-03-24 | Alex | `main` | Segona versió del llistat d'elements |
| 2025-03-25 | Mateo | `main` | Tercera versió de l'esquemàtic  |
| 2025-03-25 | Alex | `main` | Cuarta versió de l'esquemàtic  |
| 2025-03-25 | Alex | `main` | Segona versió del diagrama de blocs |
| 2025-03-25 | Alex | `main` | Simulacions LTSpice |
| 2025-03-25 | Alex | `main` | Assiganció net clases |
| 2025-03-26 | Alex | `main` | Canvi del comparador, modificació de diagrama i simulacions |
| 2025-03-26 | Mateo | `main` | Cinquena versió de l'esquemàtic |
| 2025-03-29 | Mateo | `main` | Modificació en taula de components: canvi opamp, afegir els sensors i relé |
| 2025-03-29 | Mateo | `main` | Sisena versió de l'esquemàtic |
| 2025-03-29 | Alex | `main` | Tercera versió diagrama de blocs |
| 2025-03-29 | Mateo | `main` | Primera versió prematura de layout |
| 2025-03-30 | Mateo | `main` | Segona versió prematura de layout |
| 2025-03-31 | Mateo | `main` | Tercera versió prematura de layout |
| 2025-03-31 | Mateo | `main` | Setena versió de l'esquemàtic |
| 2025-04-1 | Alex | `main` | Modificació components botonera a l'esquemàtic|
| 2025-04-1 | Alex | `main` | Nova simulació finals de carrera |
| 2025-04-1 | Mateo | `main` | Quarta versió de layout |
| 2025-04-6 | Alex | `main` | Afegir nova botonera a l'esquemàtic |
| 2025-04-7 | Alex | `main` | Cinquena versió layout |
| 2025-04-8 | Alex | `main` | Sisena versió layout |










