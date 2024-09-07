# hacking-scripts
Este repositório contém uma coleção de scripts úteis para desafios de CTF e programas de Bug Bounty que eu mesmo programei. Os scripts são projetados para facilitar a exploração, automação de tarefas e descoberta de vulnerabilidades.

## Shodan Dork Search Script

O `shodanDorkSearch.py` é um script Python que utiliza a API do Shodan para realizar buscas com base em dorks e enviar os resultados para o Telegram.

### Requisitos

- **Python 3.x**
- **API Key do Shodan** (obtenha em [Shodan.io](https://account.shodan.io/))
- **Bot do Telegram** para envio das mensagens (obtenha a API Key via [@BotFather](https://t.me/BotFather))
- **ID do Chat do Telegram** (pode ser obtido usando bots como o [@userinfobot](https://t.me/userinfobot))

### Instalação

1. **Clone ou baixe** o script.
2. **Instale as dependências** do Python:

   ``` bash
   pip install shodan requests
   ```

