# Portail client (QR Code)

Chaque client possède un QR code unique qui lui donne accès à son portail personnel pour gérer ses rendez-vous et véhicules.

## Qu'est-ce que le portail client ?

Le portail client est une page web accessible via QR code où vos clients peuvent :

| Fonction | Description |
|----------|-------------|
| **Voir leurs véhicules** | Liste des véhicules enregistrés |
| **Réserver un RDV** | Sans ressaisir leurs informations |
| **Consulter l'historique** | Rendez-vous passés et à venir |
| **Modifier leurs infos** | Mettre à jour téléphone, email |

---

## Comment ça fonctionne

### Pour le client

1. Le client scanne son QR code (smartphone)
2. Il accède directement à son portail : `pitstoply.ch/c/ABC123XYZ`
3. Ses véhicules sont déjà listés
4. Il peut réserver en quelques clics

### Avantages

| Pour vous | Pour le client |
|-----------|----------------|
| Moins de saisie manuelle | Réservation rapide |
| Données client à jour | Historique accessible |
| Fidélisation | Expérience personnalisée |

---

## Générer et partager le QR code

### Depuis la fiche client

1. Allez dans **Clients**
2. Ouvrez la fiche du client
3. Cliquez sur **QR Code**

### Options disponibles

| Action | Description |
|--------|-------------|
| **Afficher** | Visualiser le QR à l'écran |
| **Télécharger** | Obtenir le fichier PNG |
| **Envoyer par email** | Le client reçoit son QR par email |

---

## Cas d'utilisation

### Carte client physique

Imprimez une carte de visite avec le QR code du client :

1. Téléchargez le QR code (PNG)
2. Intégrez-le dans un design de carte
3. Imprimez et remettez au client

### Email de bienvenue

Envoyez automatiquement le QR code aux nouveaux clients :

1. Créez le client dans PitStoply
2. Cliquez sur **Envoyer QR par email**
3. Le client reçoit son code d'accès

### Affichage en caisse

Affichez un QR code générique (votre page de réservation) pour les nouveaux clients, et le QR personnel pour les clients existants.

---

## Sécurité du QR code

### Le code est-il sécurisé ?

Oui. Chaque QR code contient un **code unique aléatoire** (ex: `ABC123XYZ`) qui :

- N'est pas devinable
- N'expose pas de données personnelles dans l'URL
- Peut être régénéré si compromis

### Régénérer un QR code

Si un client perd son QR ou si vous suspectez un accès non autorisé :

1. Ouvrez la fiche client
2. Cliquez sur **QR Code > Régénérer**
3. L'ancien code est invalidé
4. Envoyez le nouveau au client

---

## Ce que voit le client

### Page d'accueil du portail

Le client voit :

- **Ses informations** : Nom, téléphone, email
- **Ses véhicules** : Liste avec plaques
- **Bouton "Prendre RDV"** : Réservation rapide
- **Historique** : RDV passés et à venir

### Réservation depuis le portail

1. Le client clique sur **Prendre RDV**
2. Il sélectionne un véhicule (ou en ajoute un)
3. Il choisit le service, la date et le créneau
4. Il confirme - pas besoin de ressaisir ses coordonnées !

---

## Ajouter un véhicule depuis le portail

Le client peut lui-même ajouter un véhicule :

1. Dans son portail, section **Véhicules**
2. Cliquez sur **Ajouter un véhicule**
3. Renseigne la plaque, marque, modèle
4. Le véhicule apparaît dans votre base

{% hint style="info" %}
Les véhicules ajoutés par le client sont immédiatement visibles dans votre interface PitStoply.
{% endhint %}

---

## Questions fréquentes

<details>
<summary><strong>Le client peut-il modifier ses informations ?</strong></summary>

Oui, le client peut mettre à jour son téléphone et son email depuis son portail. Vous verrez les modifications dans sa fiche.

</details>

<details>
<summary><strong>Que se passe-t-il si le client perd son QR code ?</strong></summary>

Vous pouvez lui renvoyer par email depuis sa fiche client, ou régénérer un nouveau code si nécessaire.

</details>

<details>
<summary><strong>Le portail est-il accessible sans QR code ?</strong></summary>

Non, l'accès se fait uniquement via le QR code. Cela garantit que seul le client accède à ses données.

</details>

<details>
<summary><strong>Puis-je désactiver le portail pour un client ?</strong></summary>

Vous pouvez régénérer son QR code, ce qui invalide l'ancien. Il n'y a pas d'option de désactivation complète.

</details>
