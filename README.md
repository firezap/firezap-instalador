ATUALIZANDO VPS

```bash
sudo apt -y update && apt -y upgrade
```

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):
```bash
sudo apt install -y git && git clone https://github.com/firezap/autoinstalador && sudo chmod -R 777 ./instalador && cd ./instalador && sudo ./install_primaria

```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./instalador && sudo ./install_instancia


