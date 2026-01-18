# Page de réservation publique

Votre page de réservation permet à vos clients de prendre rendez-vous en ligne, 24h/24.

## Accéder à votre page

### URL de votre page

Votre page de réservation est accessible à :

```
https://pitstoply.ch/votre-slug
```

**Exemple :** `https://pitstoply.ch/garage-martin-sa`

### Trouver votre slug

1. Allez dans **Paramètres > Identité**
2. Le champ **Slug** affiche votre identifiant

---

## Ce que voient vos clients

### Étape 1 : Sélection du service

Le client voit les services que vous proposez :
- Changement de roues
- Changement de pneus
- Autres services configurés

Chaque service affiche :
- Le nom
- La durée estimée
- Le prix indicatif (si configuré)

### Étape 2 : Sélection de la succursale (si plusieurs)

Si vous avez plusieurs succursales, le client choisit où il souhaite venir :
- Nom de la succursale
- Adresse

### Étape 3 : Choix de la date

Un calendrier s'affiche avec :
- Les jours disponibles en couleur
- Les jours complets ou fermés grisés
- Le mois en cours et les suivants

### Étape 4 : Choix du créneau

Les créneaux disponibles pour la date choisie s'affichent :
- Horaires sous forme de boutons
- Seuls les créneaux libres sont cliquables

### Étape 5 : Informations client

Le client remplit ses coordonnées :
- Prénom et nom
- Téléphone (obligatoire)
- Email (pour la confirmation)
- Plaque d'immatriculation du véhicule
- Marque et modèle (optionnel)
- Notes/commentaires

### Étape 6 : Confirmation

Un récapitulatif s'affiche avec toutes les informations. Le client confirme sa réservation.

---

## Personnalisation de la page

### Éléments personnalisés

Votre page reflète votre identité :

| Élément | Source |
|---------|--------|
| **Logo** | Paramètres > Apparence |
| **Couleurs** | Thème personnalisé |
| **Nom du garage** | Paramètres > Identité |
| **Adresse** | Paramètres de la succursale |

### Informations affichées

- Nom de votre garage
- Logo
- Services disponibles
- Coordonnées de contact

---

## Partager votre page

### Méthodes de partage

| Méthode | Comment |
|---------|---------|
| **Lien direct** | Copiez `pitstoply.ch/votre-slug` |
| **QR Code** | Générez un QR pointant vers l'URL |
| **Bouton site web** | Intégrez un lien sur votre site |
| **Réseaux sociaux** | Partagez le lien sur Facebook, Instagram |
| **Email** | Ajoutez le lien dans votre signature |
| **SMS** | Envoyez le lien à vos clients |

### Générer un QR Code

1. Utilisez un générateur de QR code gratuit (ex: qr-code-generator.com)
2. Entrez votre URL : `https://pitstoply.ch/votre-slug`
3. Téléchargez le QR code
4. Imprimez-le pour votre vitrine ou carte de visite

### Bouton pour votre site web

Exemple de code HTML :

```html
<a href="https://pitstoply.ch/votre-slug"
   style="background: #007bff; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">
   Prendre rendez-vous
</a>
```

---

## Options de réservation

### Modification par le client

Après réservation, le client reçoit un email avec un lien pour :
- Modifier la date/heure
- Annuler le rendez-vous

### Rappels automatiques

Selon votre configuration, le client reçoit :
- Email de confirmation (immédiat)
- SMS de confirmation (si activé)
- Rappel 24h avant (si activé)

---

## Vérifier que tout fonctionne

### Test recommandé

1. Ouvrez votre page dans un navigateur privé
2. Testez une réservation complète avec vos infos
3. Vérifiez :
   - Les créneaux correspondent à vos horaires
   - Le design est correct
   - L'email de confirmation arrive
4. Supprimez votre RDV de test après vérification

### Points de contrôle

- [ ] Le logo s'affiche correctement
- [ ] Les couleurs sont cohérentes
- [ ] Les services sont corrects
- [ ] Les créneaux correspondent aux horaires
- [ ] La confirmation par email fonctionne
- [ ] Le SMS arrive (si activé)

---

## Optimisation pour les moteurs de recherche

### Référencement naturel

Votre page bénéficie d'éléments SEO de base :
- Titre avec le nom de votre garage
- Description avec votre activité
- Balises structurées

### Améliorer votre visibilité

- Ajoutez le lien sur Google My Business
- Mentionnez-le sur vos réseaux sociaux
- Intégrez-le dans votre signature email

---

## Domaine personnalisé (optionnel)

{% hint style="info" %}
Cette fonctionnalité est disponible avec les plans **Multi-Lift** et **Network**.
{% endhint %}

Vous pouvez utiliser votre propre domaine :
- `rdv.votre-garage.ch` au lieu de `pitstoply.ch/votre-slug`

[Configurer un domaine personnalisé](../configuration/domaine-personnalise.md)

---

## Questions fréquentes

<details>
<summary><strong>Puis-je désactiver temporairement ma page de réservation ?</strong></summary>

Actuellement, il n'y a pas de bouton on/off global. Vous pouvez :
- Bloquer tous les créneaux via les fermetures
- Réduire les horaires d'ouverture à zéro

</details>

<details>
<summary><strong>Les clients peuvent-ils réserver plusieurs RDV à la suite ?</strong></summary>

Chaque réservation est indépendante. Le client doit refaire le processus pour chaque rendez-vous.

</details>

<details>
<summary><strong>Comment limiter le nombre de réservations par jour ?</strong></summary>

Le nombre est limité par le nombre de lifts × les créneaux disponibles. Pour réduire la capacité, vous pouvez :
- Réduire les horaires d'ouverture
- Désactiver certains lifts
- Augmenter la durée des services

</details>

<details>
<summary><strong>La page est-elle adaptée aux mobiles ?</strong></summary>

Oui, la page est responsive et s'adapte automatiquement aux smartphones et tablettes.

</details>

<details>
<summary><strong>Puis-je personnaliser le texte de la page ?</strong></summary>

Actuellement, les textes sont standardisés. Une personnalisation avancée est prévue dans une future version.

</details>
