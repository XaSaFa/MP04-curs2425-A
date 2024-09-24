# Activitat 3 - Instal·lació de Windows Server 2016

**OBJECTIUS DE L'ACTIVITAT**

Conèixer i documentar la instal·lació d'un Windows Server en mode d'escriptòri.

**MATERIAL NECESSARI**

- Una imatge ISO de Microsoft Windows Server 2016 instal·lable o els arxius d'instal·lació.
- El software de virtualització Virtual Box.
- Un processador de text per documentar el procés d'instal·lació.

**TASQUES A REALITZAR**

**MOLT IMPORTANT:**  Recorda que hauràs de documentar tot el procés. Fes les captures de pantalla i pren les notes que consideris necessàries.

1. Crea una màquina virtual amb els requisit mínims per instal·lar el Windows Server amb experiència d'escriptori indicat i aquests paràmetres:

RAM recomanada.
CPUs recomanades.
Crea un nou disc dur de la mida recomanada (50 GB).
Utilitza el mètode d’emmagatzematge amb expansió dinàmica.
128 MB de memòria de vídeo.
Crea 1 interfície de xarxa:
Xarxa NAT

2. Realitza la instal·lació de Windows Server a la MV seguint les següents indicacions:

- Tria la versió Estàndard amb Experiència d'Escriptori.
- Instal·la les "Guest Additions" de Virtual Box.
- Canvia les dades de l’equip a les següents:
  - Contrasenya de l’administrador: Qwerty1
  - Nom de l’equip: SVR-NomCognom (p.e. SVR_JosepRovira)
  - Tria la versió Estàndard amb Experiència d'Escriptori.
  - Fes que el servidor no sigui membre de cap domini i que sigui membre del grup següent: IABSMX2.
  - Paràmetres de la xarxa NAT:
    - IPde xarxa: 192.168.XX.0/24 on XX és el teu número d'ordre a la classe.
    - DNS: automàtic.
    - Porta d'enllaç: automàtica.

3. Documentació.

Crea un document de text que inclogui com a mínim (però no necessàriament limitat) els següents apartats:

- Portada: Instal·lació de Windows Server 2016 a una MV.
  
- Índex.
  
- Característiques del software.
  - Nom.
  - Propòsit o tipus d'aplicatiu.
  - Versió/compilació.
  - Requisits mínims/recomanables.
    
- Entorn d'instal·lació
  - Característiques de la màquina amfitrió (Màquina real) (CPU, RAM, GPU, HDD, SO)
  - Característiques de la màquina hoste (màquina virtual) (Threads assignats, RAM, memòria de video, espai de disc)
    
- Procediment d'instal·lació.
  - Indiqueu tots els passos de la instal·lació des de el moment en que poseu la imatge a la unitat òptica virtual.
  - Feu una entrada per cada quadre de diàleg o interacció amb l'instal·lador.
  
- [Opcional] Troubleshooting: informa dels problemes que hagis detectat durant la instal·lació i les solucions que has fet servir.

**ENTREGA DE L'ACTIVITAT**

- Documentació: Adjunta el document resultant en format **PDF** a la  tasca de Moodle corresponent.
