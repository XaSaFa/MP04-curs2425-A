# Activitat 1 - Permisos a Linux

1. Ves al teu directori personal i crea una carpeta anomenada "directori_permisos".

mkdir directori_permisos

2. Canvia els permisos del directori perquè només el propietari tingui tots els permisos.
sudo chmod 700 directori_permisos/

3. Crea un arxiu anomenat "arxiu1.txt" dins del directori anterior i verifica quins permisos té.

cd directori_permisos/
touch arxiu1.txt
ls -l

4. Crea un grup anomenat "proves".

sudo addgroup proves
 
5. Dona-li permisos de lectura i escriptura sobre "arxiu1.txt" al grup.

sudo chown xavi:proves arxiu1.txt

6. Crea un subdirectori anomenat "subdirectori_permisos".  

mkdir subdirectori_permisos

7. Deixa el subdirectori anterior amb permisos només per al propietari (rwx).  

sudo chmod 700 subdirectori_permisos/

8. Concedeix permisos d'execució al grup "proves" sobre "subdirectori_permisos".

sudo chown xavi:proves subdirectori_permisos/
sudo chmod 710 subdirectori_permisos/

10. Crea un usuari anomenat "convidat".

sudo adduser convidat

11. Canvia els permisos del directori "directori_permisos" perquè l'usuari "convidat" pugui accedir.

sudo chown convidat:xavi directori_permisos/

12. Canvia els permisos de l'arxiu "arxiu1.txt" perquè tots els usuaris tinguin només permís de lectura.

chmod 444 arxiu1.txt

13.  Comprova que l'usuari "convidat" no pot accedir al subdirectori "subdirectori_permisos".


14.  Afegeix convidat al grup "proves" i comprova que sí té accés a "subdirectori_permisos". (POTSER NECESSITES REINICIAR EL SISTEMA).

# Activitat 2 - umask

1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte.
2. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i els directoris amb rwxr-xr-x.
3. Comprova que la màscara anterior funciona.
4. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i els directoris amb rwxrwxrwx.
5. Comprova que la màscara anterior funciona.
6. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els directoris amb r-xr-xr-x.
7. Comprova que la màscara anterior funciona.
8. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i els directoris amb rwx--x--x.
9. Comprova que la màscara anterior funciona.
10. Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r--------
11. Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x.
12. Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x.
13. Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del grup proves.
14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo)
15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior.

16. 
