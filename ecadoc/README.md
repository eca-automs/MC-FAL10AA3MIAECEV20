# MC-FAL10AA3MIAECEV20
Schema quadro elettrico per ascensore serie `mcpx`. Impianto a fune con emergenza, gestione emendamento A3 e EN8120.

Puoi trovare il repository dello schema su
<a href="https://github.com/eca-automs/MC-FAL10AA3MIAECEV20" target="_blank">GitHub</a>.

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
