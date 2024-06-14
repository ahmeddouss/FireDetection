# Fire Detection

Ce projet implique un système de surveillance IoT utilisant un Raspberry Pi, un Arduino avec un shield LoRa et divers capteurs. Le système communique les données via LoRaWAN et Wi-Fi, les envoyant sur Internet via MQTT pour une visualisation sur Ubidots.
![image](https://github.com/ahmeddouss/FireDetection/assets/118319834/9a5f30b5-9fda-41a5-960c-c6a9bb6afef4)

## Aperçu

![Screenshot 2024-06-gfh192546](https://github.com/ahmeddouss/FireDetection/assets/118319834/de64e6a3-1d7e-4051-8ddd-8c02e85cf9e7)

## Composants

### Appareils

- **Raspberry Pi**
- **Arduino avec Shield LoRa**
- **Passerelle Dragino**

### Capteurs

- **Caméra**
  - Intégrée au Raspberry Pi
- **Capteur de feu**
  - Intégré à l'Arduino avec le shield LoRa
- **Capteur de gaz**
  - Intégré à l'Arduino avec le shield LoRa
- **Module GPS**
  - Intégré à l'Arduino avec le shield LoRa

## Plateforme Internet

Les données sont visualisées et gérées en utilisant :
- **Ubidots**
- **MQTT**

![Screenshot_20230110_081852](https://github.com/ahmeddouss/FireDetection/assets/118319834/91041dd5-5850-45e2-9cc3-3c002ff3b91f)

## Instructions d'Installation

1. **Connexions Matérielles**
   - Connectez la caméra au Raspberry Pi.
   - Connectez les capteurs de feu, de gaz et le module GPS à l'Arduino avec le shield LoRa.
  
     ![image](https://github.com/ahmeddouss/FireDetection/assets/118319834/52ac2072-a046-4d13-9755-20a1db4a1e49)

2. **Configuration Logicielle**
   - Installez les bibliothèques et dépendances nécessaires sur le Raspberry Pi et l'Arduino.
   - Configurez les paramètres LoRaWAN sur l'Arduino pour communiquer avec la passerelle Dragino.
   - Configurez la passerelle Dragino pour transférer les données vers le broker MQTT.

3. **Visualisation des Données**
   - Créez un compte sur Ubidots.
   - Configurez les paramètres MQTT sur Ubidots pour recevoir les données de la passerelle Dragino.
   - Configurez des tableaux de bord sur Ubidots pour visualiser les données des capteurs.

## Utilisation

1. **Allumez le Raspberry Pi et l'Arduino**
   ![image](https://github.com/ahmeddouss/FireDetection/assets/118319834/df21e399-9612-47d3-8258-2e510051e4e7)

2. **Démarrez la communication LoRaWAN**
   
   ![image](https://github.com/ahmeddouss/FireDetection/assets/118319834/f7686f45-32f0-4ac0-b19b-f1f4f649c13c)

3. **Surveillez les données sur les tableaux de bord Ubidots**
   ![image](https://github.com/ahmeddouss/FireDetection/assets/118319834/d26ae882-8dca-4c8d-9a98-3f67c886ad57)

## Dépendances

- Raspberry Pi
- Arduino IDE
- Compte Ubidots
- Broker MQTT

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Remerciements

Un grand merci à la communauté open-source pour les bibliothèques et les outils utilisés dans ce projet.
[Ubidots_IoT_Server_Connection.pdf](https://github.com/user-attachments/files/15841617/Ubidots_IoT_Server_Connection.pdf)
[LG01N_LoRa_Gateway_User_Manual_v1.1-1545886.pdf](https://github.com/user-attachments/files/15841620/LG01N_LoRa_Gateway_User_Manual_v1.1-1545886.pdf)



## Contact

Pour toute question, veuillez contacter [ahmeddouss35@gmail.com].
