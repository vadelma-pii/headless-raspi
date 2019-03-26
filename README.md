# headless-raspi
Template files to use a Raspberry Pi without a display. These go into the /boot partition, which is the smaller one on a Raspbian card.
 * ssh - empty file to enable ssh
 * wpa_supplicant - WiFi settings. Change the info on the following lines:
 country=FI - put in your country code (SE, NO, DK, UK, US, DE, FR...)
    ssid="YOUR_WIFI_SSID" - your WiFi SSID goes here (e.g. "My Phone Hotspot")
    psk="YOUR_WIFI_PASSWORD" - your WiFi password goes here

Tiedostot, joita muokkaamalla Raspberry Pin saa käyntiin ilman näyttöä. Nämä laitetaan /boot-osiolle, joka on Raspbian-kortin pienempi osio.
 * ssh - tyhjä tiedosto, joka sallii ssh-yhteydet
 * wpa_supplicant.conf - WLAN-yhteyden asetukset. Vaihda oikeat tiedot seuraaville riveille:
 country=FI - jos et ole Suomessa, vaihda oikea maatunnus (SE, NO, DK, UK, US, DE, FR...)
    ssid="YOUR_WIFI_SSID" - vaihda tekstin YOUR_WIFI_SSID tilalle WLAN-verkkosi nimi
    psk="YOUR_WIFI_PASSWORD" - vaihda tekstin YOUR_WIFI_PASSWORD tilalle WLAN-verkkosi salasana
