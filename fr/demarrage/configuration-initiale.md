# Configuration initiale

Ce guide vous accompagne dans la configuration de votre compte PitStoply en quelques minutes.

## Étape 1 : Informations de l'entreprise

Après votre première connexion, vous serez guidé par un assistant de configuration.

### Informations requises

| Champ                   | Description                     | Exemple                           |
| ----------------------- | ------------------------------- | --------------------------------- |
| **Nom de l'entreprise** | Le nom affiché à vos clients    | Garage Martin SA                  |
| **Identifiant URL**     | URL personnalisée de votre page | garage-martin-sa                  |
| **Adresse**             | Adresse complète                | Rue du Commerce 12, 1003 Lausanne |
| **Téléphone**           | Numéro de contact principal     | +41 21 123 45 67                  |
| **Email**               | Email de contact                | contact@garage-martin.ch          |
| **Logo**                | Logo de votre entreprise        | logo.png                          |

{% hint style="info" %}
**Le slug** définit l'adresse de votre page de réservation publique. Par exemple : `pitstoply.ch/garage-martin-sa`
{% endhint %}

## Étape 2 : Succursales et Lifts

### Qu'est-ce qu'une succursale ?

Une succursale représente un lieu physique (un garage, un atelier). Si vous n'avez qu'un seul site, vous n'aurez qu'une succursale.

### Qu'est-ce qu'un lift ?

Un lift représente un poste de travail où un rendez-vous peut être effectué (pont élévateur, baie de service, etc.). Les rendez-vous sont attribués à des lifts spécifiques.

### Configuration

1. **Créez votre succursale** avec son nom et adresse
2. **Ajoutez vos lifts** (au minimum 1)
3. **Définissez les horaires** pour chaque lift

{% hint style="warning" %}
**Important** : Le nombre de succursales et lifts dépend de votre plan d'abonnement.
{% endhint %}

| Plan                     | Succursales | Lifts    |
| ------------------------ | ----------- | -------- |
| Independent              | 1           | 1        |
| Multi-Lift               | 1           | Illimité |
| Succursale Additionnelle | +1          | -        |

## Étape 3 : Services et durées

Configurez les types de services que vous proposez :

| Service type                  | Description               | Durée par défaut |
| ----------------------------- | ------------------------- | ---------------- |
| Changement de pneus           | Montage/démontage complet | 60 min           |
| Changement de roues complètes | 2 jeux de jantes          | 30 min           |

### Personnaliser les durées

Vous pouvez ajuster la durée de chaque service selon votre organisation. Ces durées déterminent les créneaux disponibles sur votre calendrier.

## Étape 4 : Notifications

Configurez comment vos clients sont notifiés :

### Email (inclus)

* **Confirmation** : Envoyée automatiquement après réservation
* **Annulation** : Envoyée automatiquement après l'annulation du rendez-vous
* **Rappel** : Envoyé 24h avant le rendez-vous
* **Rappel Jour J** : Envoyé 2h avant le rendez-vous
* **Report** : Envoyée si le RDV est modifié

### SMS (crédits requis)

* Même principe que les emails
* Nécessite d'acheter des crédits SMS
* Configurable dans Paramètres > SMS

{% hint style="info" %}
**Recommandation** : Activez au minimum les rappels par email pour réduire les no-shows.
{% endhint %}

## Étape 5 : Lancez-vous !

Une fois ces étapes complétées :

1. ✅ Votre page de réservation est accessible à `pitstoply.ch/votre-slug`
2. ✅ Vous pouvez créer des rendez-vous depuis le dashboard
3. ✅ Vos clients peuvent réserver en ligne

***

## Prochaines étapes recommandées

* [ ] [Personnaliser votre apparence](../configuration/apparence.md) (logo, couleurs)
* [ ] [Configurer les fermetures](../configuration/fermetures.md) (congés, jours fériés)
* [ ] [Ajouter des utilisateurs](../configuration/utilisateurs.md) (employés)
* [ ] [Tester une réservation](../guides/premier-rendez-vous.md) côté client
