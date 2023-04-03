FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
cd /home
```

```bash
apt update -y && apt upgrade -y && apt autoremove -y && apt install git -y && git clone https://github.com/ricardo98349/Instalador_postgresql_local.git instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_primaria
```



ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:

```bash
cd /home
```

```bash
apt update -y && apt upgrade -y && apt autoremove -y && rm -rf instalador && git clone https://github.com/ricardo98349/Instalador_postgresql_local.git instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_instancia
```
