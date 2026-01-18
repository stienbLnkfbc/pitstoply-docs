# Gérer mon abonnement

Consultez et gérez votre abonnement PitStoply : changement de plan, mise à jour des informations de paiement, factures.

## Accéder à la facturation

1. Allez dans **Paramètres** ou **Facturation**
2. Cliquez sur **Abonnement** ou **Billing**

{% hint style="info" %}
Seul le **propriétaire** du compte a accès à la section facturation.
{% endhint %}

---

## Informations de l'abonnement

### Ce que vous voyez

| Information | Description |
|-------------|-------------|
| **Plan actuel** | Independent, Multi-Lift ou Network |
| **Statut** | Actif, En période d'essai, Expiré |
| **Prochaine facturation** | Date du prochain prélèvement |
| **Moyen de paiement** | Carte enregistrée |

---

## Portail client Stripe

PitStoply utilise **Stripe** pour la gestion des paiements. Vous pouvez accéder au portail Stripe pour :

- Voir vos factures
- Mettre à jour votre carte
- Télécharger les reçus

### Accéder au portail

1. Dans **Facturation**, cliquez sur **Gérer l'abonnement**
2. Vous êtes redirigé vers le portail Stripe
3. Effectuez vos modifications
4. Revenez à PitStoply

---

## Changer de plan

### Upgrade (passer à un plan supérieur)

1. Dans **Facturation > Plans**, sélectionnez le nouveau plan
2. Confirmez le changement
3. **Effet immédiat** : Vous avez accès aux nouvelles fonctionnalités tout de suite
4. La différence de prix est calculée au prorata

**Exemple :**
- Vous passez de Independent (290 CHF) à Multi-Lift (490 CHF)
- En milieu d'année, vous payez la différence proratisée
- À la prochaine échéance, le nouveau prix s'applique

### Downgrade (passer à un plan inférieur)

1. Sélectionnez le plan inférieur
2. Confirmez le changement
3. **Effet différé** : Le changement s'applique à la fin de la période en cours

{% hint style="warning" %}
**Avant un downgrade**, vérifiez que vous respectez les limites du nouveau plan (nombre de succursales, lifts, utilisateurs). Vous devrez peut-être supprimer des éléments en excès.
{% endhint %}

---

## Mettre à jour le moyen de paiement

### Changer de carte

1. Accédez au **Portail Stripe** (via Gérer l'abonnement)
2. Section **Moyens de paiement**
3. Ajoutez une nouvelle carte
4. Supprimez l'ancienne si souhaité

### Cartes acceptées

| Type | Accepté |
|------|---------|
| Visa | ✅ |
| Mastercard | ✅ |
| American Express | ✅ |
| TWINT | ⚠️ Selon disponibilité |

---

## Factures

### Consulter les factures

1. Accédez au **Portail Stripe**
2. Section **Historique des factures**
3. Téléchargez les factures en PDF

### Contenu d'une facture

- Période facturée
- Détail du plan
- Montant HT et TVA
- Total payé

---

## Annuler l'abonnement

### Procédure d'annulation

1. Dans **Facturation**, cliquez sur **Annuler l'abonnement**
2. Confirmez votre choix
3. L'abonnement reste actif jusqu'à la fin de la période payée
4. Après expiration, l'accès est restreint

### Ce qui se passe après annulation

| Période | Accès |
|---------|-------|
| Jusqu'à expiration | Accès complet |
| Après expiration | Accès en lecture seule |
| 30 jours après | Données archivées |

{% hint style="warning" %}
**Attention** : Après 90 jours d'inactivité, les données peuvent être supprimées. Exportez vos données avant annulation si nécessaire.
{% endhint %}

### Réactiver un abonnement

Si vous changez d'avis :

1. Reconnectez-vous à PitStoply
2. Allez dans **Facturation**
3. Sélectionnez un plan et procédez au paiement
4. Votre compte est réactivé avec vos données

---

## Période d'essai

### Pendant l'essai

- Accès complet aux fonctionnalités du plan choisi
- Pas de prélèvement
- Rappel avant la fin de l'essai

### Fin de l'essai

À la fin de la période d'essai :
- Si une carte est enregistrée : prélèvement automatique
- Si pas de carte : accès restreint jusqu'au paiement

---

## Questions fréquentes

<details>
<summary><strong>Puis-je obtenir un remboursement ?</strong></summary>

Les abonnements annuels ne sont généralement pas remboursables. Contactez support@pitstoply.ch pour les cas exceptionnels.

</details>

<details>
<summary><strong>Que se passe-t-il si le paiement échoue ?</strong></summary>

Stripe réessaie automatiquement plusieurs fois. Vous recevez des notifications pour mettre à jour votre carte. Après plusieurs échecs, l'accès est suspendu.

</details>

<details>
<summary><strong>Puis-je payer par facture/virement ?</strong></summary>

Le paiement par carte est standard. Pour les grands comptes (Network), des arrangements peuvent être discutés avec le support.

</details>

<details>
<summary><strong>La TVA est-elle incluse ?</strong></summary>

Les prix affichés incluent la TVA suisse (si applicable). Les factures détaillent le montant HT et la TVA.

</details>

<details>
<summary><strong>Puis-je changer la fréquence de paiement ?</strong></summary>

Actuellement, les abonnements sont annuels. Des options mensuelles pourraient être disponibles à l'avenir.

</details>
