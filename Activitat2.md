# INTAL·LACIÓ OWNCLOUD

## REQUISITS S'INSTAL·LACIÓ

- Sistema operatiu Ubuntu 20.04 LTS o superior.
- 512 MB de RAM.

## GUIA D'INTAL·LACIÓ

Primer hem d'intal·lar el servidor apache2 amb la comanda 
```sh

sudo apt install apache2

```



Despres instl·lem MariaDB amb la comanda 
```sh

sudo apt-get install mariadb-server mariadb-client -y

```



Ara configurem la instal·lació amb 

```sh

sudo mysql_secure_installation

```



Un cop executada ens demanará configurar.
Aquí està la meva configuració:



