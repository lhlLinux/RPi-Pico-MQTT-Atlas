## Projet Final

Les trois répertoires représentent ma partie du code pour un projet final. Il s'agit essentiellement d'une preuve de concept pour un réseau de capteurs, envoyant leur données vers un nuage pour stocker les données (sur une certaine période), soit pour un historique, consultation en temps réel, ou analyses.

L'autre partie du projet (non disponible) est une site utilisant les services *Steamlit* pour permettre de visualiser les données sur un site web, que ce soit en temps réel ou non. Le site permet de choisir les bases de données, spécifier la période de temps, la fréquence de mise-à-jour ainsi que de choisir les capteurs ou nœuds que l'on désire visualiser.


#### Description des répertoires

- code_atlas: alimente directement une bdd Atlas. Utilisé principalement pour des tests et le développement de mon autre coéquipier.
- code_passerelle: acheminer les données vers un cluster Atlas
- code_pico: roule sur le RPI Pico. Génère les données réelles et simulées.


#### Développement
- Systèmes: Linux Mint et Windows 8.1
- Matériel: Raspberry Pi Pico W (WiFi intégré)
- Éditeurs: Thonny (Linux), PyScripter (Windows)
- Capteurs: Capteur de température intégré au RPi Pico W
- Outils: MongoDB Compass


#### Technologies
- MongoDB : service infonuagique pour stockage des données
- MQTT : envoi des données du RPi Pico vers une passerelle
- MicroPython : requis pour le RPI Pico


#### Lien vidéo vers la démonstration (de ma partie)
https://youtu.be/nbUIbEYL434