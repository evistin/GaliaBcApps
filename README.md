# Implementace modelu ResNetV2


Repozitář obsahuje řešení problému klasifikace obrazu nasazením modelu InceptionResNetV2 ve dvou prostředích. Jedná se o praktickou část mé bakalářské práce "Možnosti nasazení neuronových sítí".

## Webová aplikace
U webové aplikace bylo využito API Keras pro práci s modelem a webový framework Flask pro komunikaci se serverem hostující model. 
### Obsah složky Webová aplikace
* Ve složce templates se nachází html soubor, který se zobrazí při spuštění aplikace.
* Složka testPictures obsahuje obrázky, na kterých se může aplikace otestovat.
* Python soubor slouží ke spuštění aplikace za pomocí `python predict_app.py`.

## Mobilní aplikace
Pro nasazení na mobilní aplikaci byl využit framework TensorFlow Lite, zde se nachází originální a optimalizovaný model, kde byla demonstrována funkce po-tréninkové kvantifikace.
Z důvodu velkého množství souborů bylo využito komprese pomocí ZIP.


