# Activitat 1 - Gestió de disc a Linux

Per a fer les activitats següents mostra a cada sortida el prompt on es veu que la màquina es diu **MP-04-X** (on X és el teu cognom).


1. Canvia el nom de l'equip tant amb hostnamectl com a /etc/hosts.

![image](https://github.com/user-attachments/assets/06e9bcbd-e750-4592-841c-146208c927f4)

2. Mira si hi ha una versió LTS nova de Linux

![image](https://github.com/user-attachments/assets/edb92afe-8eff-4d2e-b09b-b342bab15f46)

3. Utilitza la comanda df i mostra la sortida amb lectura per a humans.

![image](https://github.com/user-attachments/assets/f11ca362-9b8d-490b-bd2e-727d9fb4a2b4)

4. Personalitza la comanda df per que mostri a la sortida tota la informació normal i també el tipus de sistema de fitxers.

![image](https://github.com/user-attachments/assets/ed917ccd-0875-460a-9019-d2805235dfb9)

5. Personalitza la comanda df fent que les dades que es mostrin siguin, origen de dades, espai disponible i sistema de fitxers, només per als que utilitzin ext4 (fes servir grep).

![image](https://github.com/user-attachments/assets/aa773067-fb44-4421-aae1-994fdabc187e)

6. Afegeix, si no ho has fet, un segon disc dur virtual de 1GB a la MV.

7. Fent servir fdisk mostra el tamany del segon disc.

![image](https://github.com/user-attachments/assets/9940ed3f-3050-46d1-bf37-1a10e8d3c1ed)

8. Crea una nova partició primària de 256MB al segon disc.

![image](https://github.com/user-attachments/assets/96ac5650-da02-44db-a199-23a4e0f8325c)

9. Mostra la nova partició creada amb fdisk.

![image](https://github.com/user-attachments/assets/caa3e937-5be9-4792-a527-c1c0873d0d14)

10. Mostra l'espai lliure del disc amb fdisk.

![image](https://github.com/user-attachments/assets/1f4df29d-0dbf-4411-8de4-8d3ae3493d4f)

11. Esborra la partició amb fdisk.

![image](https://github.com/user-attachments/assets/7aca5a0e-f45b-468e-a1f9-cd2aa59e8fe3)

12. Crea les següents particions al segon disc.
  - Primària 100MB.
  - Primària 400MB.
  - Estesa de tot el tamany restant (uns 500MB).
  - Lògica de 250MB.
  - Lògica de la resta del tamany de disc.

![image](https://github.com/user-attachments/assets/679e2e97-6f1d-4c2c-b9c8-1fdddde0b277)
![image](https://github.com/user-attachments/assets/74b5afcc-249e-491c-acde-5af69c4c7678)

13. Mostra les particions creades i escriu-les amb la comanda w.

14. Formateja les particions primàries com ext4.

![image](https://github.com/user-attachments/assets/7ff38efb-bbdd-47ff-b95c-c0228022aeb3)

15. Formateja les particions esteses com NTFS.

16. Munta les particions a les carpetes següents:
  - /dev/sdb1 a /disc1-X (on X és el teu cognom)
  - /dev/sdb2 a /disc2-X (on X és el teu cognom)
  - /dev/sdb5 a /disc3-X (on X és el teu cognom)
  - /dev/sdb6 a /disc4-X (on X és el teu cognom)

![image](https://github.com/user-attachments/assets/3a682fc5-e309-48ae-a075-14fc87372c57)

17. Prova que pots accedir als discos (accedeix i utilitza la comanda pwd).

18. Mostra les particions i punt de muntatge amb la comanda lsblk

![image](https://github.com/user-attachments/assets/5d4cb727-1cc3-4c2d-9fc0-8bd319fed448)
