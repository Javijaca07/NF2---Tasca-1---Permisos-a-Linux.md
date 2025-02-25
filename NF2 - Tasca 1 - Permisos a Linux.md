Activitat 1 - chmod

1. Ves al teu directori personal i crea una carpeta anomenada "Exercici-X" on
X és el teu cognom.
![Captura desde 2025-02-25 12-21-48](https://github.com/user-attachments/assets/f3b0d4ca-86da-4ec9-8188-c01608db5568)

3. Canvia els permisos del directori perquè només el propietari tingui tots els
permisos.
![Captura desde 2025-02-25 12-26-22](https://github.com/user-attachments/assets/0b2849d2-c111-4151-ad23-4d1645978226)

5. Crea un arxiu anomenat "arxiu1.txt" dins del directori anterior i verifica els
permisos.
![Captura desde 2025-02-25 12-28-48](https://github.com/user-attachments/assets/d0109520-d4b3-498d-b413-a42c309aa39f)

7. Crea un grup anomenat "proves".
![Captura desde 2025-02-25 12-32-23](https://github.com/user-attachments/assets/0042d44d-0b80-442f-aebc-14cf0c1d96e8)
   
9. Dona-li permisos de lectura i escriptura sobre "arxiu1.txt" al grup.
    ![Uploading Captura desde 2025-02-25 12-39-31.png…]()

11. Crea un subdirectori anomenat "sub-X" on X és el teu cognom.

13. Deixa el subdirectori anterior amb permisos només per al propietari (rwx).
    
15. Concedeix permisos d'execució al grup "proves" sobre "sub-X".
    
17. Crea un usuari anomenat "convidat".
    
10.Canvia els permisos del directori "Exercici-X" perquè l'usuari "convidat"
pugui accedir.

11.Canvia els permisos de l'arxiu "arxiu1.txt" perquè tots els usuaris tinguin
només permís de lectura.

12.Comprova que l'usuari "convidat" no pot accedir al subdirectori "sub-X".

19. Afegeix convidat al grup "proves" i comprova que sí té accés a "sub-X".
(POTSER NECESSITES REINICIAR EL SISTEMA).



Activitat 2 – umask

1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte.
2. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i els
directoris amb rwxr-xr-x.
3. Comprova que la màscara anterior funciona.
4. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i
els directoris amb rwxrwxrwx.
5. Comprova que la màscara anterior funciona.
6. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els
directoris amb r-xr-xr-x.
7. Comprova que la màscara anterior funciona.
8. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i
els directoris amb rwx--x--x.
9. Comprova que la màscara anterior funciona.
10.Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r-
-------
11.Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x.
12.Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x.
13.Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del
grup proves.
14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo)
15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior.
