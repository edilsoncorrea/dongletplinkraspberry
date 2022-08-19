# Compilar o driver do Dongle TpLink no Raspberry

## Compilar o driver
https://www.raspberrypi.org/forums/viewtopic.php?t=62371&start=1550

## Ajustar permissão do arquivo wpa_supplicant
https://www.raspberrypi.org/documentation/configuration/wireless/wireless-cli.md

## Reconfigurar wpa

https://raspberrypi.stackexchange.com/questions/67311/failed-to-connect-to-non-global-ctrl-ifname-when-running-wpa-cli-reconfigure


## Editar o arquivo Interfaces

https://unix.stackexchange.com/questions/400101/how-to-get-the-wifi-working-with-r8188eu-driver-on-my-raspberry-pi

## Site com os drivers

http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/

https://repo.volumio.org/?dir=wifi-drivers/8188eu-drivers


## Rodar o comando na linha do Putty
````
sudo uname -a
````
descobrir a versão


rodar sudo su para ficar em root

procurar a pasta lib\modules 

procurar as subpastas com nome 5.4.51-v*

baixar um driver para cada coincidindo os nomes



### Quando instalei a última vez, a versão era:
8188eu-4.19.97-v7-1294.tar.gz

## Montar a url para o wget, que ficaria assim
````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-4.19.97-v7-1294.tar.gz
````
````
tar xzf 8188eu-4.19.97-v7-1294.tar.gz
````
````
./install.sh
````


https://www.raspberrypi.org/forums/viewtopic.php?t=62371

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.4.49-v7-1323.tar.gz
````
````
tar xzf 8188eu-5.4.49-v7-1323.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.4.51-v7l-1333.tar.gz
````
````
tar xzf 8188eu-5.4.51-v7l-1333.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.4.51-v8-1333.tar.gz
````
````
tar xzf  8188eu-5.4.51-v8-1333.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.4.51-v7-1333.tar.gz
````
````
tar xzf  8188eu-5.4.51-v7-1333.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.4.51-v8-1333.tar.gz
````
````
tar xzf  8188eu-5.4.51-v8-1333.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.4.51-v7l-1333.tar.gz
````
````
tar xzf 8188eu-5.4.51-v7l-1333.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.4.51-v7-1333.tar.gz
````
````
tar xzf 8188eu-5.4.51-v7-1333.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.10.52-v7l-1445.tar.gz
````

````
tar xzf 8188eu-5.10.52-v7l-1445.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.10.52-v8-1445.tar.gz
````

````
tar xzf 8188eu-5.10.52-v8-1445.tar.gz
````

````
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.10.52-v7-1445.tar.gz
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.10.52-v7l-1445.tar.gz
wget http://downloads.fars-robotics.net/wifi-drivers/8188eu-drivers/8188eu-5.10.52-v8-1445.tar.gz


tar xzf 8188eu-5.10.52-v7-1445.tar.gz
tar xzf 8188eu-5.10.52-v7l-1445.tar.gz
tar xzf 8188eu-5.10.52-v8-1445.tar.gz
````


## Desinstalar drive
https://github.com/mfruba/kernel/issues/1
