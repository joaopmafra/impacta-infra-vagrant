# Infraestrutura: Atividade 01 - Vagrant e MySQL
[MBA em Engenharia de Software - Impacta](https://www.impacta.edu.br/mba/engenharia-de-software)

## Instalação
 1. [Instale o Vagrant](https://www.vagrantup.com/downloads)
 1. [Instale o VirtualBox](https://www.virtualbox.org/wiki/Downloads)
 1. Clone este repositório: \
 `git clone https://github.com/joaopmafra/impacta-infra-vagrant.git`
 1. Entre no diretório do repositório e execute no terminal `vagrant up`

## Conectar-se ao MySQL
Após a máquina subir, para se conectar ao MySQL, use os dados:
 - endereço: 10.80.4.10
 - usuário: petclinic
 - senha: myprecious

Ou use o comando e insira a senha "myprecious": `mysql -u petclinic -p -h 10.80.4.10`

## Desligar, destruir e iniciar vm:
 - desligar: `vagrant halt`
 - destruir: `vagrant destroy`
 - criar: `vagrant up`
