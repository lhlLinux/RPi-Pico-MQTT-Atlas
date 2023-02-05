## Projet Final

Les trois r�pertoires repr�sentent ma partie du code pour un projet final. Il s'agit essentiellement d'une preuve de concept pour un r�seau de capteurs, envoyant leur donn�es vers un nuage pour stocker les donn�es (sur une certaine p�riode), soit pour un historique, consultation en temps r�el, ou analyses.

L'autre partie du projet (non disponible) est une site utilisant les services *Steamlit* pour permettre de visualiser les donn�es sur un site web, que ce soit en temps r�el ou non. Le site permet de choisir les bases de donn�es, sp�cifier la p�riode de temps, la fr�quence de mise-�-jour ainsi que de choisir les capteurs ou n�uds que l'on d�sire visualiser.


#### Description des r�pertoires

- code_atlas: alimente directement une bdd Atlas. Utilis� principalement pour des tests et le d�veloppement de mon autre co�quipier.
- code_passerelle: acheminer les donn�es vers un cluster Atlas
- code_pico: roule sur le RPI Pico. G�n�re les donn�es r�elles et simul�es.


#### D�veloppement
- Syst�mes: Linux Mint et Windows 8.1
- Mat�riel: Raspberry Pi Pico W (WiFi int�gr�)
- �diteurs: Thonny (Linux), PyScripter (Windows)
- Capteurs: Capteur de temp�rature int�gr� au RPi Pico W
- Outils: MongoDB Compass


#### Technologies
- MongoDB : service infonuagique pour stockage des donn�es
- MQTT : envoi des donn�es du RPi Pico vers une passerelle
- MicroPython : requis pour le RPI Pico


#### Lien vid�o vers la d�monstration (de ma partie)
https://youtu.be/nbUIbEYL434