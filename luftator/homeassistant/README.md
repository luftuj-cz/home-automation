# HomeAssistant Luftator

Nastavení automatizace pro zónování Luftator přes platformu Home Assistant

- V Home Assistantu [Nastavení | Doplňky](https://my.home-assistant.io/redirect/supervisor/) klikněte na `Obchod s doplňky`, vyhledejte a nainstalujte doplněk [Mosquitto broker](https://github.com/home-assistant/addons/tree/master/mosquitto) (pokud již používáte nějaký MQTT broker, tento krok můžete vynechat)
- Do souboru configuration.yaml v Home Assistantu přidejte obsah souboru [configuration.yaml](configuration.yaml) a jednotlivé klapky si pojmenujte podle pokojů, do kterých vede potrubí, které každý klapka ovládá
- Nadefinujte si jednotlivé scény podle příkladu v souboru [scenes.yaml](scenes.yaml)
