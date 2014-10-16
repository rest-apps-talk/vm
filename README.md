#vm-minicursos

Máquina virtual com os recursos para acompanhar palestra

## Recursos

* Ubuntu Trusty 32bit
* PHP 5.6 (mysql-nd, curl, intl, mcrypt, apcu, xdebug)
* Composer
* Apache 2.4
* Mysql 5.5 (root pass = admin)
* Git + git-flow
* NodeJS

## Instalação

Para instalar você deve ter o [Virtualbox 4.3.*](https://www.virtualbox.org) e o [Vagrant 1.6.*](https://www.vagrantup.com) instalados.
Em máquinas windows, é desejável que seja instalado o plugin "vagrant-winnfsd" através do comando ```vagrant plugin install vagrant-winnfsd```.


Após clonar o repositório, entre na pasta e execute o comando ```vagrant up```.

Assim que finalizar o processo de instalação adicione ao arquivo de configuração de hosts do seu sistema operacional:

```
192.168.56.101  blogmv-frontend
192.168.56.101  blogmv-backend
```

E você poderá acessar a aplicação cliente em [http://blogmv-frontend](http://blogmv-frontend).

