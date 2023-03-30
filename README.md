FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
cd /home
```

```bash
apt update -y && apt upgrade -y && apt autoremove -y && apt install git -y && git clone https://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:x-oauth-basic@github.com/whamulti/instalador_whamulti instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_primaria
```



ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:

```bash
cd /home
```

```bash
apt update -y && apt upgrade -y && apt autoremove -y && rm -rf instalador && git clone https://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:x-oauth-basic@github.com/whamulti/instalador_whamulti instalador && sudo chmod -R 777 instalador && cd instalador && sudo ./install_instancia
```
