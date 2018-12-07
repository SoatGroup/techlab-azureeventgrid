# Instructions

## Enregistrement du provider Event Grid

Sur le portail Azure, dans la blade **Subscriptions > Resource providers** recherchez puis activez le provider **Microsoft.EventGrid**

![](01.png)

## Création des ressources

Créez les ressources Azure suivantes :

- Storage Accounts de type **StorageV2**, **Hot**
- Azure Function

## Azure Function

Via le portail Azure, créez une Azure Function de type **Azure Event Grid Trigger**

![](02.png)

Configurez votre Event Grid via le bouton disponible dans le portail d'édition d'Azure Function

![](03.png)

Configurer votre Event Grid de la manière suivante : 

![](04.png)

Ouvrez la console de Log de votre Azure Function, et dans une autre fenêtre ajouter un Blob à votre compte de stockage.

![](05.png)

Votre fonction sera déclenché à chaque ajout ou suppression de Blob