# HomeAssistant Atrea RD5

Nastavení automatizace pro rekuperační jednotku Atrea s řízením RD5 přes platformu Home Assistant

![Lovelace UI](../imgs/atrea-rd5-homeassistant.png)

- Zkontrolujte, zda máte pro jednotku Atrea s řízením RD5 povolený modbus protokol (viz [návod](../README.md))
- Do souboru configuration.yaml v Home Assistantu přidejte obsah souboru [configuration.yaml](configuration.yaml) a řetězec `IP_ADDRESS` nahraďte skutečnou IP adresou Vaší rekuperační jednotky (např. 192.168.0.10) 
- Přidejte soubor [automations-atrea-rd5.yaml](automations-atrea-rd5.yaml)
- Přidejte soubor [scripts-atrea-rd5.yaml](scripts-atrea-rd5.yaml)
