# Calendrier externe

Synchronisez vos calendriers externes (Google, Outlook) pour éviter les doubles réservations et centraliser votre planning.

## Pourquoi synchroniser ?

| Avantage | Description |
|----------|-------------|
| **Éviter les conflits** | Vos RDV perso bloquent automatiquement les créneaux |
| **Vue unifiée** | Tous vos événements au même endroit |
| **Pas de double saisie** | Un seul calendrier à gérer |

---

## Calendriers supportés

PitStoply se synchronise via **OneCal** avec :

| Calendrier | Support |
|------------|---------|
| Google Calendar | ✅ |
| Microsoft Outlook | ✅ |
| Apple iCloud | ✅ |
| Autres (CalDAV) | ⚠️ Selon compatibilité |

---

## Connecter un calendrier

### Étape 1 : Accéder aux paramètres

1. Allez dans **Paramètres**
2. Cliquez sur **Calendrier externe** ou **Intégrations**

### Étape 2 : Ajouter une connexion

1. Cliquez sur **Connecter un calendrier**
2. Choisissez le provider (Google, Outlook, etc.)
3. Vous êtes redirigé vers la page d'autorisation

### Étape 3 : Autoriser l'accès

1. Connectez-vous à votre compte (Google, Microsoft, etc.)
2. Autorisez PitStoply à accéder à votre calendrier
3. Vous êtes redirigé vers PitStoply

### Étape 4 : Sélectionner les calendriers

1. Choisissez quels calendriers synchroniser
2. Définissez le sens de synchronisation
3. Enregistrez

---

## Options de synchronisation

### Sens de la synchronisation

| Option | Description |
|--------|-------------|
| **Import seulement** | Les événements externes bloquent les créneaux PitStoply |
| **Export seulement** | Les RDV PitStoply apparaissent dans votre calendrier externe |
| **Bidirectionnel** | Les deux sens (recommandé) |

### Fréquence de synchronisation

La synchronisation se fait automatiquement :
- À chaque connexion
- Toutes les 15-30 minutes en arrière-plan
- Manuellement via le bouton **Synchroniser**

---

## Comment ça fonctionne

### Événements externes → PitStoply

Quand vous avez un événement dans votre calendrier externe :

1. PitStoply détecte l'événement
2. Le créneau correspondant est **bloqué**
3. Les clients ne peuvent pas réserver à ce moment

**Affichage dans le calendrier :**
- Événements externes en gris clair
- Label "Externe" ou nom du calendrier source

### PitStoply → Calendrier externe

Quand un rendez-vous est créé dans PitStoply :

1. L'événement est créé dans votre calendrier externe
2. Détails inclus : client, service, véhicule
3. Mise à jour automatique si le RDV change

---

## Gérer les connexions

### Voir les calendriers connectés

Dans **Paramètres > Calendrier externe**, vous voyez :
- Liste des comptes connectés
- Calendriers sélectionnés
- Statut de la dernière synchronisation

### Déconnecter un calendrier

1. Trouvez la connexion à supprimer
2. Cliquez sur **Déconnecter**
3. Confirmez

{% hint style="warning" %}
Déconnecter un calendrier ne supprime pas les événements existants dans votre calendrier externe.
{% endhint %}

### Resynchroniser manuellement

Si vous pensez que la synchronisation n'est pas à jour :

1. Cliquez sur **Synchroniser maintenant**
2. Attendez quelques secondes
3. Vérifiez votre calendrier

---

## Cas d'utilisation

### Bloquer vos vacances

1. Créez un événement "Vacances" dans Google Calendar
2. PitStoply bloque automatiquement ces jours
3. Pas besoin de créer un blocage manuellement dans PitStoply

### Réunions et RDV personnels

1. Vos réunions d'équipe bloquent les créneaux
2. Vos RDV médicaux bloquent aussi
3. Aucun client ne peut réserver pendant ces moments

### Partager avec l'équipe

1. Partagez votre calendrier PitStoply (via export)
2. L'équipe voit les RDV dans leur propre agenda
3. Coordination simplifiée

---

## Dépannage

### La synchronisation ne fonctionne pas

1. Vérifiez que la connexion est active
2. Essayez de déconnecter et reconnecter
3. Vérifiez les permissions accordées

### Les événements n'apparaissent pas

1. Vérifiez que le bon calendrier est sélectionné
2. Attendez quelques minutes (cache)
3. Forcez une synchronisation manuelle

### Doublons d'événements

Si vous voyez des doublons :
1. Vérifiez les paramètres de synchronisation
2. Ne synchronisez qu'un calendrier par compte

---

## Questions fréquentes

<details>
<summary><strong>La synchronisation est-elle instantanée ?</strong></summary>

Non, il peut y avoir un délai de quelques minutes. Pour les changements urgents, utilisez la synchronisation manuelle.

</details>

<details>
<summary><strong>Puis-je synchroniser plusieurs calendriers ?</strong></summary>

Oui, vous pouvez connecter plusieurs comptes et sélectionner plusieurs calendriers par compte.

</details>

<details>
<summary><strong>Les détails des clients sont-ils visibles dans mon calendrier externe ?</strong></summary>

Oui, les événements exportés incluent le nom du client, le service et le véhicule. Assurez-vous que votre calendrier externe est sécurisé.

</details>

<details>
<summary><strong>Que se passe-t-il si je supprime un événement externe ?</strong></summary>

Le créneau redevient disponible dans PitStoply à la prochaine synchronisation.

</details>
