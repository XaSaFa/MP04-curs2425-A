# Activitat 4 - Ús de diskpart

Entrega un pdf amb les solucions demanades, has de justificar les respostes amb text i imatges (captures de pantalla).

## Part 1 - Teoria.

Contesta les següents preguntes:

1. Investiga i explica les principals diferències entre discos durs HDD i SSD, adjunta una imatge de cada tipus on es vegin les diferències.

SSD - Solid State Drive. No té parts mòbils la velocitat d'accés a la informació és més alta. Es pot connectar també per un port PCIExpress a més de per SATA.
HDD - Hard Disc Drive. Té parts mòbils. Velocitat menor d'accés a la informació.

2. Busca dues ofertes de venda d'ordinadors diferents per cada tipus de disc.
3. Quines diferències hi ha entre les taules de partició MBR i GPT?
MBR - permet 4 particions primàries com a màxim, fins a 23 particions lògiques a Windows, fins a 15 particions totals a Linux. Particions de fins a 2TB.
GPT - permet fins a 128 particions primàries. Discos de fins a 9,4ZB.

4. Als equips actuals quina es fa servir?
GPT.

Busca una imatge d'un ordinador modern on es vegi la BIOS i una altra on es vegi UEFI i relaciona-ho amb l'apartat anterior.

UEFI és compatible amb GPT i BIOS amb MBR.

5. Quin és el tamany màxim d'una partició primària a GPT en GB?

18.000.000.000 GB

6. Quin és el tamany màxim d'un disc a GPT en GB?

9.400.000.000.000.000 GB

7. Si utilitzo Windows: Quantes particions màximes entre tots els tipus tindré en un disc dur amb taula MBR. Indica quantitat i tipus.

3 primàries.
1 estesa.
23 lògiques.

8. Investiga i explica breument què són els volums en mirall.

Són volums que tenen guardada la **mateixa informació**, per tal de que la informació no es perdi.

9. Investiga i explica breument què són els volums RAID. Identificant tots els casos possibles.

- RAID 0: Distribueix dades entre discos per millorar la velocitat.
- RAID 1: És exactament igual que els volumns mirall, la mateixa informació està als dos discos.
- RAID 5: Distribueix dades entre 3 o més discos.

## Part 2 - Pràctica.

Mostra en tots els casos les captures de pantalla i si fa falta raona la resposta.

1. Crea un disc virtual de 10GB i afegeix-lo a la MV.

2. Crea 3 particions primàries que convertiràs a volums simples amb les següents característiques:
  - Primera: Tamany de 1GB, lletra X, etiqueta "Cognom-1".
  - Segona: Tamany de 512MB, lletra Y, etiqueta "Cognom-2".
  - Tercera: Tamany de 2GB, lletra Z, etiqueta "Cognom-3".
  - Quarta: Tamany de 3GB, lletra W, etiqueta "Cognom-4".

3. Intenta crear una nova partició primària de 1GB. Què passa?
   
5.  Esborra la partició amb la lletra d'unitat W.

6. Crea una partició estesa amb la resta de disc dur, no et deixis res lliure.

7. Crea les següents particions lògiques:
  - Primera: Tamany de 5GB, lletra W, etiqueta "Cognom-4".
  - Segona: Tamany la resta, lletra V, etiqueta "Cognom-5".

6. Mostra els volums a l'explorador de Windows i al Panell d'administració del server.

7. Esborra el disc sencer.

8. Crea una partició primària de tamany de 3GB, lletra U, etiqueta "Cognom-1".

9. Amplia la partició per a que el seu tamany total sigui de 9GB.

10. Redueix la partició en 1024MB.

11. Crea una nova partició lògica que ocupi la resta del espai, lletra T, etiqueta "Cognom-2"

12. Mostra els volums a l'explorador de Windows i al Panell d'administració del server.
