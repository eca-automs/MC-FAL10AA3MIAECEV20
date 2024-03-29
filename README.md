# MC-FAL10AA3MIAECEV20
Schema quadro elettrico per ascensore serie `mcpx`. Impianto a fune con emergenza, gestione emendamento A3 e EN8120.

## Licenza
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licenza Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Quest'opera è distribuita con Licenza <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribuzione - Condividi allo stesso modo 4.0 Internazionale</a>.

Fatta eccezione del logo

![logo](./assets/images/eca-logo.png)

e del nome `Eca di Belardi Roberto`.

Copyright (C) 2018  Eca di Belardi Roberto.

### Scheda controllo
MCPX2015-SMD - PER16B-SMD

###### Firmware
[P](https://docs.ecaq.in/it/info/mcpx-board-manual-p).

### Tipo impianto
Fune.

### Manovra
Universale.

### Collegamento vano / cabina
| Vano | Cabina     |
| :------------- | :------------- |
| parallelo | parallelo |


### Operatore porte
* manuale
* automatico trifase
* automatico elettronico

### Avviamento / controllo motore
VVVF Yaskawa L1000A.

### Potenza massima motore / taglie compatibili
| Taglia | Potenza |
| :------------- | :------------- |
| S10 | 6CV-400VAC |
| S15 | 9CV-400VAC |
| S20 | 13CV-400VAC |
| S30 | 19CV-400VAC |
| S35 | 24CV-400VAC |
| S40 | 29CV-400VAC |

### Allarme
* 12VDC
* legge 13

### Emergenza
Emergenza totale con riapertura porte tramite inverter SMS miae.

### Emendamento A3
Gestione movimento incontrollato secondo emendamento A3 tramite CEV.

### EN8120
Gestione circuito manutenzione secondo normativa EN8120.
