# Instalador do Whatsapp

   ___                _          _____          __                                 _    _              
  |_  |              (_)        |_   _|        / _|                               | |  (_)             
    | | _   _  _ __   _   ___     | |   _ __  | |_   ___   _ __  _ __ ___    __ _ | |_  _   ___   __ _ 
    | || | | || '_ \ | | / _ \    | |  | '_ \ |  _| / _ \ | '__|| '_ ` _ \  / _` || __|| | / __| / _` |
/\__/ /| |_| || | | || || (_) |  _| |_ | | | || |  | (_) || |   | | | | | || (_| || |_ | || (__ | (_| |
\____/  \__,_||_| |_||_| \___/   \___/ |_| |_||_|   \___/ |_|   |_| |_| |_| \__,_| \__||_| \___| \__,_|


- Para Instalar Tenha uma VPS de no mínimo 2GB re Ram
- Utilize o Sistema Operacional Linux Ubuntu 18 ou 20
- Para Executar os comandos utilize o Software 'Putty' ou 'Bitvise SSH Client'


Passo 1 - Atualize o Sistema
```bash
	sudo apt -y update && apt -y upgrade
```

Passo 2 - Acesse a Pasta Home
```bash
	cd /home
```

Passo 3 - Baixe o Git 
```bash
	sudo apt install -y git
```

 Passo 4 - Adicione este repertório em uma pasta em seguida mude a permissão da pasta
 ```bash
	git clone https://github.com/junioinfo/whats-sass_junioinfo.git install_whaticket && sudo chmod -R 777 install_whaticket
 ```

Passo 5 - Acesse a Pasta onde foi baixado este instalador.
 ```bash
	cd install_whaticket
 ```
 
 Passo 6 - Para a primeira instalação execute o arquivo install_primaria
  ```bash
	sudo ./install_primaria
  ```
  
  Resumindo Passo 3,4,5 e 6 em uma linha só:
  ```bash
	sudo apt install -y git && git clone https://github.com/junioinfo/whats-sass_junioinfo.git install_whaticket && sudo chmod -R 777 install_whaticket  && cd install_whaticket  && sudo ./install_primaria
  ```

	Agora é só seguir os passos do instalador e pronto.
# Whatsticket - Essas perguntas serão respondidas diretamente no Terminal.
	
	[0] Instalar WhatsPainel
	Informe um nome para a Instancia/Empresa que será instalada (Não utilizar espaços ou caracteres especiais, Utilizar Letras minúsculas;):

	Informe a Qt. de de Conexões/Whats que a poderá cadastrar: 1 a 9999

	Informe a Qt. de de Usuários/Atendentes que a poderá cadastrar: de 1 a 9999

	Digite o domínio do FRONTEND/PAINEL; Ex: appbot.cloud

	Digite o domínio do BACKEND/API; Ex: api.appbot.cloud

	Digite a porta do FRONTEND para a appbot; Ex: 3000 A 3999

	Digite a porta do BACKEND para esta instancia; Ex: 4000 A 4999

	Digite a porta do REDIS/AGENDAMENTO MSG para a appbot; Ex: 5000 A 5999 = padrão do redis é 6379
	
	