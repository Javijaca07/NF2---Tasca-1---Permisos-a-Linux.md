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
![Captura desde 2025-02-25 12-39-31](https://github.com/user-attachments/assets/db823bc7-1168-4fed-951b-2346f8481b5c)

11. Crea un subdirectori anomenat "sub-X" on X és el teu cognom.
![Captura desde 2025-02-27 11-11-49](https://github.com/user-attachments/assets/a78c5882-1791-4c27-af0b-3e5222ffb680)

13. Deixa el subdirectori anterior amb permisos només per al propietari (rwx).
![Captura desde 2025-02-27 11-15-03](https://github.com/user-attachments/assets/2c59669e-f297-40d4-bde2-de16ca306d05)

15. Concedeix permisos d'execució al grup "proves" sobre "sub-X".
![Captura desde 2025-02-27 11-19-33](https://github.com/user-attachments/assets/13d4a91b-6c24-486e-aaa9-369cade2781d)

17. Crea un usuari anomenat "convidat".
![Captura desde 2025-02-27 11-23-03](https://github.com/user-attachments/assets/804bc8e2-85f5-47e8-b390-3f451d18053f)

10.Canvia els permisos del directori "Exercici-X" perquè l'usuari "convidat"
pugui accedir.
![Captura desde 2025-02-27 11-24-51](https://github.com/user-attachments/assets/5f869de2-afa6-49e6-b98f-06612c92b180)

11.Canvia els permisos de l'arxiu "arxiu1.txt" perquè tots els usuaris tinguin
només permís de lectura.
![Captura desde 2025-02-27 11-28-59](https://github.com/user-attachments/assets/e2ca6a73-fd37-4a94-b397-da0515bbd6b4)


12.Comprova que l'usuari "convidat" no pot accedir al subdirectori "sub-X".
![Captura desde 2025-02-27 11-34-52](https://github.com/user-attachments/assets/47e4bd5e-da3a-40a0-ae31-030656cd6a06)

19. Afegeix convidat al grup "proves" i comprova que sí té accés a "sub-X".
(POTSER NECESSITES REINICIAR EL SISTEMA).
![Captura desde 2025-02-27 12-37-04](https://github.com/user-attachments/assets/8963b652-18a6-47eb-aece-a34bc681656f)



Activitat 2 – umask

1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte.
![Captura desde 2025-02-27 12-38-59](https://github.com/user-attachments/assets/d61c343e-2ffc-4006-9ffe-c8137c7ffddf)

3. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i els
directoris amb rwxr-xr-x.
4. Comprova que la màscara anterior funciona.
5. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i
els directoris amb rwxrwxrwx.
6. Comprova que la màscara anterior funciona.
7. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els
directoris amb r-xr-xr-x.
8. Comprova que la màscara anterior funciona.
9. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i
els directoris amb rwx--x--x.
10. Comprova que la màscara anterior funciona.
10.Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r-
-------
11.Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x.
12.Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x.
13.Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del
grup proves.
14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo)
15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior.
