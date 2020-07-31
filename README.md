# galiaBcApps
Repozitář obsahuje řešení problému klasifikace obrazu nasazením modelu InceptionResNetV2 ve dvou prostředích. 
U webové aplikace bylo využito API Keras pro práci s modelem a webový framework Flask pro komunikaci se serverem hostující model. 
Pro nasazení na mobilní aplikaci byl využit framework TensorFlow Lite, zde se nachází originální a optimalizovaný model, kde byla demonstrována funkce po-tréninkové kvantifikace.
Z důvodu velkého množství souborů bylo využito komprese pomocí ZIP.
--

The repository contains two aplications that solves the image classification problem by deploying the InceptionResNetV2 model in two environments.
The web application used the Keras API to work with the Flask web framework to communicate with the server hosting the model.
The TensorFlow Lite framework was created for deployment on a mobile application, here you will find an original and optimized model, where the function of post-training quantification was shown. Due to size limit the mobile app was packaged via ZIP.
