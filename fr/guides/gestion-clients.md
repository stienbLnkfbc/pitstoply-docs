# Gérer vos clients

PitStoply vous permet de centraliser toutes les informations de vos clients et leurs véhicules.

## Accéder à la liste des clients

1. Dans le menu principal, cliquez sur **Clients**
2. Vous voyez la liste de tous vos clients avec :
   - Nom et prénom
   - Entreprise (si renseigné)
   - Téléphone
   - Nombre de véhicules
   - Dernier rendez-vous

### Rechercher un client

Utilisez la **barre de recherche** pour trouver rapidement un client par :
- Nom ou prénom
- Numéro de téléphone
- Nom d'entreprise
- Plaque d'immatriculation d'un véhicule

{% hint style="tip" %}
**Recherche globale** : Appuyez sur `Ctrl+K` (ou `Cmd+K` sur Mac) pour ouvrir la recherche globale depuis n'importe quelle page.
{% endhint %}

---

## Créer un nouveau client

### Depuis la liste clients

1. Cliquez sur **Nouveau client**
2. Remplissez les informations :

| Champ | Obligatoire | Description |
|-------|-------------|-------------|
| Prénom | ✅ | Prénom du client |
| Nom | ✅ | Nom de famille |
| Téléphone | ✅ | Pour SMS et contact |
| Email | ❌ | Pour notifications email |
| Entreprise | ❌ | Si client professionnel |
| Notes | ❌ | Informations internes |

3. Cliquez sur **Enregistrer**

### Lors d'une réservation

Si le client n'existe pas, vous pouvez le créer directement lors de la création d'un rendez-vous.

---

## Ajouter un véhicule

Chaque client peut avoir plusieurs véhicules.

### Depuis la fiche client

1. Ouvrez la fiche du client
2. Dans la section **Véhicules**, cliquez sur **Ajouter un véhicule**
3. Remplissez les informations :

| Champ | Obligatoire | Description |
|-------|-------------|-------------|
| Plaque d'immatriculation | ✅ | Format suisse (ex: VD 123456) |
| Marque | ❌ | Ex: BMW, Audi, VW |
| Modèle | ❌ | Ex: Golf, A3, Série 3 |
| Type | ❌ | Voiture, SUV, Utilitaire |
| Pneus en stock | ❌ | Case à cocher si pneus stockés |

4. Cliquez sur **Enregistrer**

{% hint style="info" %}
**Pneus en stock** : Cochez cette option si vous stockez les pneus du client entre les saisons. Cette information apparaîtra sur les fiches de rendez-vous.
{% endhint %}

---

## QR Code client

Chaque client possède un **QR code unique** qui lui donne accès à son portail personnel.

### À quoi sert le QR code ?

| Fonction | Description |
|----------|-------------|
| **Portail client** | Le client accède à son historique de RDV |
| **Réservation rapide** | Il peut réserver sans ressaisir ses infos |
| **Véhicules enregistrés** | Ses véhicules sont déjà disponibles |

### Comment l'utiliser ?

1. **Carte client** : Imprimez une carte avec le QR code
2. **Email** : Le QR code peut être envoyé par email
3. **Affichage** : Le client scanne depuis votre comptoir

### Générer/Afficher le QR code

1. Ouvrez la fiche client
2. Cliquez sur **QR Code**
3. Options :
   - **Afficher** : Visualiser à l'écran
   - **Télécharger** : Format PNG pour impression
   - **Envoyer** : Par email au client

---

## Importer des clients (CSV)

Si vous avez une base de clients existante, vous pouvez l'importer en masse.

### Format du fichier CSV

Votre fichier doit contenir les colonnes suivantes :

```
prenom,nom,telephone,email,entreprise
Jean,Dupont,+41791234567,jean@email.com,
Marie,Martin,+41791234568,marie@email.com,Garage Martin SA
```

### Procédure d'import

1. Allez dans **Clients > Importer**
2. Téléchargez le modèle CSV (facultatif)
3. Sélectionnez votre fichier
4. Vérifiez l'aperçu des données
5. Cliquez sur **Importer**

{% hint style="warning" %}
**Attention aux doublons** : Les clients avec le même numéro de téléphone seront ignorés pour éviter les doublons.
{% endhint %}

---

## Fiche client détaillée

Cliquez sur un client pour voir sa fiche complète :

### Informations affichées

- **Coordonnées** : Téléphone, email, adresse
- **Véhicules** : Liste avec plaques et statut pneus
- **Historique RDV** : Tous les rendez-vous passés et à venir
- **Notes** : Vos notes internes sur le client

### Actions disponibles

| Action | Description |
|--------|-------------|
| **Modifier** | Éditer les informations |
| **Créer RDV** | Nouveau rendez-vous pour ce client |
| **QR Code** | Afficher/envoyer le QR code |
| **Supprimer** | Supprimer le client (après confirmation) |

---

## Modifier un client

1. Ouvrez la fiche client
2. Cliquez sur **Modifier**
3. Effectuez vos modifications
4. Cliquez sur **Enregistrer**

{% hint style="info" %}
La modification d'un client n'affecte pas les rendez-vous passés.
{% endhint %}

---

## Supprimer un client

{% hint style="danger" %}
**Attention** : La suppression d'un client supprime également tous ses véhicules. Les rendez-vous passés sont conservés mais le lien avec le client est perdu.
{% endhint %}

1. Ouvrez la fiche client
2. Cliquez sur **Supprimer**
3. Confirmez la suppression

---

## Questions fréquentes

<details>
<summary><strong>Comment fusionner deux fiches client en doublon ?</strong></summary>

Actuellement, la fusion n'est pas automatique. Vous devez :
1. Noter les véhicules du doublon
2. Les ajouter au client principal
3. Supprimer le doublon

</details>

<details>
<summary><strong>Puis-je exporter ma liste de clients ?</strong></summary>

L'export CSV est prévu dans une future version. En attendant, vous pouvez utiliser les rapports PDF.

</details>

<details>
<summary><strong>Les clients peuvent-ils modifier leurs informations ?</strong></summary>

Oui, via leur portail QR code, ils peuvent mettre à jour leurs coordonnées et véhicules.

</details>
