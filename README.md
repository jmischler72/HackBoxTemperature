# HackBoxTemperature

## Dépendances
- NodeRed
`sudo apt-get update
sudo apt-get install npm
sudo apt-get install -y build-essential
npm install -g --unsafe-perm node-red
`
- Mosquitto
`sudo apt install mosquitto
sudo apt install mosquitto_clients`

## Repertoires
- Importer le fichier flows_temp_central.json dans l'interface Node Red
- Déplacer les fichiers mosquitto.conf et passwordfile dans /etc/mosquitto/

## Utilisation
Node Red est disponible par défaut sur : localhost:1880 et le dashboard sur localhost:1880/ui
