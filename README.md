Le code contenu dans ce repository est le code d'un proscreener basé sur la Moyenne mobile 100.
Il utilise également d'autres indicateurs comme la Moyenne mobile 200 et les volumes.
Il détecte les actifs qui répondent aux actifs :


1- Dont l'une des conditions d'entrées suivantes est valide :
* La dernière bougie croise à la hausse la moyenne mobile 100.
* Le cours de clôture clôture de la dernière bougie est égal à la moyenne mobile 100.
* Le plus bas de la dernière bougie est égal ou croise la moyenne mobile 100.
* Le cours de clôture de la dernière bougie est proche (3% ou moins)et supérieur à SMA100.

Et on a une reprise potentielle de la tendance (dernière bougie haussière suite à une baisse).


2- Dont la tendance de fond répond aux conditions suivantes :
* La moyenne mobile 100 est supérieure à la moyenne mobile 200.
* La moyenne mobile 100 est haussière.
* Le volume minimum est de 10 000.
* Les moyennes mobiles 100 et 200 sont alignées à la hausse. 

Le langage utilisé est ProRealcode, un langage propre à la plateforme de Trading Prorealtime.
Ci-dessous des exemples d'actions détectées par le screener.

Exemple sur l’action Michelin au 30/07/2024 :

![Capture d’écran 2024-07-30 à 20 44 23](https://github.com/user-attachments/assets/39e84acc-4ead-48a7-a9c7-c7a43ef3f9ab)


Exemple sur l’action BAM GROEP KON au 30/07/2024 :

![Capture d’écran 2024-07-30 à 20 44 36](https://github.com/user-attachments/assets/d9ad1567-9cad-45f4-97d3-f67dd2f87918)


Exemple sur l’action Google au 30/07/2024 :

![Capture d’écran 2024-07-30 à 20 45 08](https://github.com/user-attachments/assets/ba45d3b5-0536-42bb-af1c-1effcbdb324b)
