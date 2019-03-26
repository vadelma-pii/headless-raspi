# headless-raspi
Template files to use a Raspberry Pi without a display. These go into the boot partition, which is the smaller one on a Raspbian card.

Installation:
 * Download zip (https://github.com/vadelma-pii/headless-raspi/archive/master.zip)
 * Unzip files
 * Edit headless-raspi-master/boot/wpa_supplicant.conf
 * Copy all files in headless-raspi-master/boot to the boot partition of your Raspbian card

Files:
 * ssh - empty file to enable ssh
 * wpa_supplicant - WiFi settings. Change the info on the following lines:
   * country=FI - put in your country code if not in Finland (SE, NO, DK, UK, US, DE, FR...)
   * ssid="YOUR_WIFI_SSID" - your WiFi SSID goes here (e.g. "My Phone Hotspot")
   * psk="YOUR_WIFI_PASSWORD" - your WiFi password goes here

Tiedostot, joita muokkaamalla Raspberry Pin saa käyntiin ilman näyttöä. Nämä laitetaan boot-osiolle, joka on Raspbian-kortin pienempi osio.

Asennusohje:
 * Lataa zip-tiedosto (https://github.com/vadelma-pii/headless-raspi/archive/master.zip)
 * Pura zip-tiedosto haluamaasi paikkaan
 * Editoi oikeat arvot tiedostoon headless-raspi-master/boot/wpa_supplicant.conf
 * Kopioi kaikki tiedostot hakemistosta headless-raspi-master/boot Raspbian-korttisi boot-osiolle

Tiedostot:
 * ssh - tyhjä tiedosto, joka sallii ssh-yhteydet
 * wpa_supplicant.conf - WLAN-yhteyden asetukset. Vaihda oikeat tiedot seuraaville riveille:
   * country=FI - jos et ole Suomessa, vaihda oikea maatunnus (SE, NO, DK, UK, US, DE, FR...)
   * ssid="YOUR_WIFI_SSID" - vaihda tekstin YOUR_WIFI_SSID tilalle WLAN-verkkosi nimi
   * psk="YOUR_WIFI_PASSWORD" - vaihda tekstin YOUR_WIFI_PASSWORD tilalle WLAN-verkkosi salasana
