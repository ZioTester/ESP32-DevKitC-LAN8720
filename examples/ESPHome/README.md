Esempio con ESPHome & Home Assistant
===

* Connetti l'ESP32 tramite usb al pc
* Nel pannello ESPHome in Home Assistant aggiungi un nuovo device e segui le indicazioni
* Edita la configurazione del device appena creato e sostiuisci il suo contenuto con quello del file [lan8720-test.yaml](./lan8720-test.yaml)
* Non dimenticare di settare ota_password ed api_password (cliccando in alto a destra nel pannelloESPHome
* Nell'esempio vengono configurati uno switch ed un sensore DHT22 (temperatura ed umidità) sui pin 32 e 33

<img src="ESPHome-device.jpg" width="800">
