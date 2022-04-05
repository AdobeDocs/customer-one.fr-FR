---
title: Rôles administratifs
description: Avec Adobe Admin Console, les entreprises peuvent définir une hiérarchie administrative flexible qui permet une gestion affinée de l’accès et de l’utilisation des produits par Adobe.
source-git-commit: c0035e17cc1ca97ac511aff3515b7a8f7866f32d
workflow-type: tm+mt
source-wordcount: '1639'
ht-degree: 0%

---


# Rôles administratifs

Avec Adobe Admin Console, les entreprises peuvent définir une hiérarchie administrative flexible qui permet une gestion affinée de l’accès et de l’utilisation des produits par Adobe. Un ou plusieurs administrateurs système, configurés pendant le processus d’intégration d’entreprise, se trouvent en haut de la hiérarchie. Ces administrateurs système peuvent déléguer des responsabilités à d’autres administrateurs tout en conservant un contrôle global.

Les rôles administratifs offrent les avantages clés suivants aux entreprises :

* Délégation contrôlée des responsabilités administratives
* Aperçu rapide des affectations de produits par utilisateur et par produit
* Fonctionnalité d’affectation de quotas aux administrateurs de produit

## Arborescence administrative

S’applique à : Adobe des clients d’entreprise.

La hiérarchie administrative peut être utilisée en fonction des besoins uniques de votre entreprise. Par exemple, une entreprise peut nommer différents administrateurs pour gérer les droits aux offres Adobe Creative Cloud et Adobe Marketing Cloud. Une entreprise peut également avoir différents administrateurs pour gérer les droits des utilisateurs appartenant à différentes unités opérationnelles.

>[!NOTE]
>
>La hiérarchie administrative ne s’applique pas aux clients d’équipes. Les clients d’équipes n’ont qu’une seule **Administrateur système** rôle. Le propriétaire du contrat (_précédemment appelée **Administrateur Principal**_) est l’administrateur système ayant accès aux détails du contrat et à l’historique de facturation. Si vous êtes le propriétaire actuel du contrat, vous pouvez nommer un administrateur système existant (_ précédemment appelée **administrateur secondaire**_) comme propriétaire du contrat.

![image admin](assets/storage_admin.png)

_Hiérarchie des rôles d’administrateur_

| Rôle | Description |
|--- |--- |
| **Administrateur système** | Super utilisateur pour l’entreprise ; Permet d’effectuer toutes les tâches administratives dans le Admin Console.<br>Dispose également des autorisations nécessaires pour déléguer les fonctionnalités d’administration suivantes à d’autres utilisateurs : Administrateur de produit, administrateur de profil de produit, administrateur de groupe d’utilisateurs, administrateur de déploiement et administrateur de support. |
| **Administrateur de produit** | Gère les produits affectés à cet administrateur et toutes les fonctions administratives associées, notamment :<ul><li>Création de profils de produit</li><li>Ajouter des utilisateurs et des groupes d’utilisateurs à l’organisation sans les supprimer</li><li>Ajouter ou supprimer des utilisateurs et des groupes d’utilisateurs des profils de produit</li><li>Ajout ou suppression d’administrateurs de profil de produit à partir de profils de produit</li><li>Ajouter ou supprimer d’autres administrateurs de produit du produit</li><li>Ajouter ou supprimer des administrateurs de groupe à partir de groupes</li></ul> |
| **Administrateur de profil de produit** | Gère les descriptions de profil de produit qui lui sont affectées, ainsi que toutes les fonctions administratives associées, qui incluent :<ul><li>Ajouter des utilisateurs et des groupes d’utilisateurs à l’organisation sans les supprimer</li><li>Ajouter ou supprimer des utilisateurs et des groupes d’utilisateurs des profils de produit</li><li>Attribuer ou révoquer des autorisations de produit aux utilisateurs et aux groupes d’utilisateurs des profils de produit</li><li>Gestion des rôles de produit des utilisateurs et des groupes d’utilisateurs pour les profils de produit |
| **Administration des groupes d’utilisateurs** | Gère les descriptions de groupe d’utilisateurs qui lui sont affectées, ainsi que toutes les fonctions administratives associées, qui incluent :<ul><li>Ajout ou suppression d’utilisateurs de groupes</li><li>Ajout ou suppression d’administrateurs de groupe d’utilisateurs à partir de groupes |
| **Administrateur de déploiement** | Crée, gère et déploie des packages logiciels et des mises à jour pour les utilisateurs finaux. |
| **Administration de l’assistance** | Rôle non administratif ayant accès aux informations relatives à l’assistance, telles que les rapports de problèmes signalés par les clients. |
| **Administrateur de stockage** | Gère l’administration du stockage de l’organisation. L’administrateur peut afficher la consommation de stockage des utilisateurs principaux et inactifs et transférer le contenu à d’autres destinataires. |

Pour obtenir une liste détaillée des autorisations et des privilèges pour chaque rôle d’administrateur, voir [Autorisations](#enterprise-admins-permissions-matrix).

## Ajout d’un administrateur d’entreprise

S’applique à : Adobe des clients d’entreprise.

En tant qu’administrateur, vous pouvez affecter un rôle d’administrateur à d’autres utilisateurs, leur accordant les mêmes privilèges que vous, ou des privilèges pour un rôle sous votre rôle d’administrateur dans la hiérarchie, comme décrit [above](#administrative-hierarchy). Par exemple, en tant qu’administrateur de produit, vous pouvez accorder des privilèges d’administrateur de produit ou d’administrateur de profil de produit à un utilisateur, mais pas des privilèges d’administrateur de déploiement. Pour obtenir les autorisations sur le Admin Console, reportez-vous à la section [Matrice des autorisations](#enterprise-admins-permissions-matrix).

Pour ajouter ou inviter un administrateur :

1. Dans le [Admin Console](https://adminconsole.adobe.com/), choisissez **Utilisateurs** > **Administrateurs**.

   Vous pouvez également accéder au produit, au profil de produit ou au groupe d’utilisateurs approprié, puis au **Administrateurs** .

1. Cliquez sur **Ajouter un administrateur**.
1. Saisissez un nom ou une adresse électronique. Vous pouvez rechercher des utilisateurs existants ou ajouter un nouvel utilisateur en spécifiant une adresse électronique valide et en renseignant les informations à l’écran.
1. Cliquez sur **Suivant**. Une liste des rôles d’administrateur s’affiche.

>[!NOTE]
>
>* Les options de cet écran dépendent de votre compte et de votre rôle d’administrateur. Vous pouvez accorder les mêmes privilèges que vous, ou des privilèges pour un rôle sous le vôtre dans la hiérarchie.
>* En tant qu’administrateur système d’une équipe, vous ne pouvez affecter qu’un seul rôle d’administrateur : Administrateur système.


1. Sélectionnez un ou plusieurs rôles d’administrateur.
1. Pour les types d’administrateurs tels que Administrateur de produit, Administrateur de profil de produit et Administrateur de groupe d’utilisateurs, sélectionnez respectivement les produits, les profils et les groupes spécifiques.

>[!NOTE]
>
>Pour un administrateur de profil de produit, vous pouvez inclure des profils pour plusieurs produits.

![ajouter admin](assets/add-admin.png)

1. Vérifiez les rôles d’administrateur attribués à l’utilisateur et cliquez sur **Enregistrer**.

L’utilisateur reçoit une invitation par courrier électronique concernant les nouveaux privilèges d’administrateur de `message@adobe.com`.

Les utilisateurs doivent cliquer sur **Prise en main** dans le courrier électronique pour rejoindre l’organisation. Si de nouveaux administrateurs n’utilisent pas la variable **Prise en main** dans l’invitation par courrier électronique, ils ne pourraient pas se connecter au Admin Console.

Dans le cadre du processus de connexion, les utilisateurs peuvent être invités à configurer un profil d’Adobe s’ils n’en ont pas déjà un. Si plusieurs profils sont associés à leur adresse électronique, les utilisateurs doivent choisir &quot;Rejoindre l’équipe&quot; (si vous y êtes invité), puis sélectionner le profil associé à la nouvelle organisation.

![image des droits d&#39;administration](assets/admin-get-started-email.png)

## Ajout d’un administrateur d’équipes {#add-admin-teams}

S’applique à : Adobe équipe les clients.

En tant qu’administrateur, vous pouvez affecter le rôle d’administrateur système à d’autres utilisateurs, leur accordant les mêmes privilèges que vous.

Pour ajouter ou inviter un administrateur système :

1. Dans le Admin Console, choisissez **Utilisateurs** > **Administrateurs**.

   Une liste des administrateurs existants s’affiche.

1. Cliquez sur **Ajouter un administrateur**.

   Le **Ajouter un administrateur** s’affiche.

1. Saisissez un nom ou une adresse électronique. Vous pouvez rechercher des utilisateurs existants ou ajouter un nouvel utilisateur en spécifiant une adresse électronique valide et en renseignant les informations à l’écran.

   Par défaut, l’administrateur système est sélectionné.

1. Cliquez sur **Enregistrer**.

![image d’administration des équipes](assets/teams-admin.png)

Comme tous les utilisateurs d’une organisation d’équipes sont des utilisateurs d’identifiant professionnel, ils reçoivent une invitation par courrier électronique concernant les nouveaux privilèges d’administrateur de `message@adobe.com`.
Les utilisateurs doivent cliquer sur Commencer dans le courrier électronique pour rejoindre l’organisation.

Dans le cadre du processus de connexion, les utilisateurs peuvent être invités à configurer un profil d’Adobe s’ils n’en ont pas déjà un. Si plusieurs profils sont associés à leur adresse électronique, les utilisateurs doivent choisir &quot;Rejoindre l’équipe&quot; (si vous y êtes invité), puis sélectionner le profil associé à la nouvelle organisation.

![image des droits d&#39;administration](assets/admin-get-started-email.png)

## Modifier le rôle d’administrateur d’entreprise

S’applique à : Adobe des clients d’entreprise.

En tant qu’administrateur, vous pouvez modifier le rôle d’administrateur pour les autres administrateurs qui se trouvent en dessous de vous dans la hiérarchie d’administration. Par exemple, vous pouvez supprimer les privilèges d’administrateur d’autres administrateurs.

Pour modifier les rôles d’administrateur :

1. Dans le Admin Console, choisissez **Utilisateurs** > **Administrateurs**. La liste des administrateurs existants s’affiche.

   Vous pouvez également accéder au produit, au profil de produit ou au groupe d’utilisateurs approprié, puis au **Administrateurs** .

1. Cliquez sur le nom de l’administrateur à modifier.
1. Dans le **Détails de l’utilisateur**, cliquez sur ![icon](assets/one-console-ellipses.png) pour le **Droits d’administration** et choisissez **Modifier les droits d’administrateur**.

   ![modification des droits d’administrateur](assets/admin-rights-section.png)

1. Modifiez les droits d’administration et enregistrez vos modifications.

## Modifier le rôle d’administrateur des équipes

S’applique à : Adobe équipe les clients.

En tant qu’administrateur système d’équipes, vous pouvez supprimer les privilèges d’administrateur système des autres administrateurs.

Pour révoquer les privilèges d’administrateur système :

1. Dans le Admin Console, choisissez **Utilisateurs** > **Administrateurs**.

   La liste des administrateurs existants s’affiche.

1. Dans Détails de l’utilisateur, cliquez sur ![icon](assets/one-console-ellipses.png) à droite du **Droits d’administration** et choisissez **Modifier les droits d’administrateur**.

   ![modification des droits d’administrateur](assets/admin-rights-section.png)

1. Modifiez les droits d’administration et enregistrez vos modifications.

## Suppression d’un administrateur

S’applique à : Adobe équipes des clients d’entreprise.

1. Pour révoquer des autorisations d’administrateur, sélectionnez un utilisateur, puis cliquez sur **Supprimer l’administrateur**.

![supprimer l’image admin](assets/remove-admin.png)

>[!NOTE]
>
>La suppression d’un administrateur ne supprime pas l’utilisateur du Admin Console, mais supprime uniquement les privilèges associés au rôle d’administrateur.

## Matrice des autorisations des administrateurs d’entreprise

S’applique à : Adobe des clients d’entreprise.

Le tableau suivant répertorie toutes les autorisations pour les différents types d’administrateurs, classées selon les zones de fonctionnalités suivantes :

### Gestion des identités

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Ajouter un domaine (demander/déposer un domaine) | ✔ |  |
| Affichage des listes de domaines et de domaines | ✔ |  |
| Gestion des clés de chiffrement de domaine | ✔ |  |
| Gestion de la stratégie de mot de passe d’organisation par défaut | ✔ |  |
| Affichage de la stratégie de mot de passe d’organisation par défaut | ✔ |  |

### Gestion des utilisateurs

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Ajout d’un utilisateur à l’organisation | ✔ |  |
| Suppression d’un utilisateur de l’organisation | ✔ |  |
| Affichage des détails et de la liste des utilisateurs | ✔ |  |
| Modifier le profil utilisateur | ✔ |  |
| Ajout d’un profil de produit à un utilisateur ou à un groupe | ✔ |  |
| Suppression d’un profil de produit pour un utilisateur ou un groupe | ✔ |  |
| Ajout d’un profil de produit à plusieurs utilisateurs | ✔ |  |
| Affichage des profils de produit pour un utilisateur | ✔ |  |
| Afficher la liste des utilisateurs de produits | ✔ |  |
| Ajout en masse d’utilisateurs à l’organisation | ✔ |  |

### Gestion des administrateurs

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Octroi d’un administrateur d’organisation à un utilisateur | ✔ |  |
| Révocation de l’administrateur de l’organisation par un utilisateur | ✔ |  |
| Octroi d’un administrateur de licence de produit à un utilisateur | ✔ |  |
| Révoquer l’administrateur de licence de produit d’un utilisateur | ✔ |  |
| Octroi d’un administrateur de déploiement à un utilisateur | ✔ |  |
| Révocation de l’administrateur de déploiement par un utilisateur | ✔ |  |
| Octroi d’un administrateur de groupe d’utilisateurs à un utilisateur | ✔ |  |
| Révocation de l’administrateur de groupe d’utilisateurs par un utilisateur | ✔ |  |
| Octroi d’un administrateur de propriétaire de produit à un utilisateur | ✔ |  |
| Révocation de l’administrateur propriétaire d’un produit par un utilisateur | ✔ |  |

### Gestion de la configuration des licences de produit

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Accorder des droits de produit à l’organisation |  |  |
| Supprimer les droits de produit de l’organisation |  |  |
| Afficher le nombre total de licences détenues par l’organisation | ✔ |  |
| Afficher les produits disponibles et les familles de produits | ✔ |  |
| Modifier les descriptions/données de licence de produit | ✔ |  |
| Octroi d’une licence de produit à un utilisateur | ✔ |  |
| Défourniture d’une licence de produit à un utilisateur | ✔ |  |
| Ajout d’une nouvelle configuration de licence de produit | ✔ |  |
| Modification de la configuration du service de licence de produit | ✔ |  |
| Suppression de la configuration du service de licence de produit | ✔ |  |
| Suppression de l’accès aux produits d’un utilisateur (suppression de toutes les configurations) | ✔ |  |

### Gestion du stockage

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Affichage des dossiers d’utilisateurs Principaux et inactifs | ✔ |  |
| Suppression des dossiers d’utilisateurs inactifs et transfert de contenu | ✔ |  |

### Déploiement

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Onglet Afficher/utiliser les packages | ✔ |  |

### Assistance

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Onglet Prise en charge | ✔ |  |
| Gestion des cas d’assistance | ✔ | ✔ |

### Gestion des groupes d’utilisateurs

| Autorisation | Administrateur système | Administration de l’assistance |
|--- |--- |--- |
| Création d’un groupe d’utilisateurs | ✔ |  |
| Suppression d’un groupe d’utilisateurs | ✔ |  |
| Ajout d’un utilisateur à un groupe d’utilisateurs | ✔ |  |
| Suppression d’un utilisateur du groupe d’utilisateurs | ✔ |  |
| Attribuer un groupe d’utilisateurs à la licence de produit | ✔ |  |
| Suppression d’un groupe d’utilisateurs de la licence de produit | ✔ |  |
| Afficher le membre du groupe d’utilisateurs | ✔ | ✔ |
| Affichage de la liste des groupes d’utilisateurs | ✔ | ✔ |
