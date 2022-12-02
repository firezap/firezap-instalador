ATUALIZANDO VPS

```bash
sudo apt -y update && apt -y upgrade
```

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):
```bash
sudo apt install -y git && git clone https://github.com/firezap/firezap-instalador && sudo chmod -R 777 ./firezap-instalador && cd ./firezap-instalador && sudo ./install_primaria

```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./firezap-instalador && sudo ./install_instancia


