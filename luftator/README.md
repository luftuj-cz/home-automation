# Řízení zónovacího systému Luftator

## Konfigurace automatizace

- [Home Assistant](homeassistant)

## Konfigurace řídící jednotky

- Připojte řídící jednotku ke zdroji elektrické energie prostřednictvím adaptéru nebo PoE
- Podržte tlačítko na řídicí jednotce po dobu alespoň 5s dokud kontrolní dioda nezhasne, po uvolnění čekejte než začne kontrolní dioda rychle blikat
- Připojte se prostřednictvím mobilního telefonu, tabletu či notebooku k WiFi s názvem `luftator` (DŮLEŽITÉ: pokud se vám zobrazí upozornění, že v síti není k dispozici internet, potvrďte, že chcete zůstat připojeni k této síti, v některých případech je vhodné do dobu konfigurace vypnout mobilní data)
- Otevřete webový prohlížeč a zadejte adresu http://192.168.4.1/
- Vyberte, zda chcete Luftator připojit po Ethernetu či Wifi. Pro ethernet je vyžadováno automatické přidělování adres pomocí DHCP. Pro připojení po WiFi zvolte název Vaší místní WiFi sítě a zadejte heslo pro připojení k této síti.
- Zadejte adresu použitého MQTT brokeru a jméno a heslo pro komunikaci s ním
- Potvrďte kliknutím na tlačítko `Confirm`
- Pokud je připojení k MQTT brokeru úspěšné kontrolní dioda se po restartu řídící jednotky trvale rozsvítí. V opačném případě opakujte konfiguraci a ujistěte se, že vyplněné hodnoty jsou správné.

