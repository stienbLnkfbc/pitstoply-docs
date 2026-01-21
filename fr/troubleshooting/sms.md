# Problèmes SMS

Solutions aux problèmes courants liés aux notifications SMS.

---

## SMS non envoyé

### Le client n'a pas reçu le SMS

**Vérifications à faire :**

| Vérification | Comment |
|--------------|---------|
| SMS activés ? | **Paramètres > Notifications** - SMS activé ✅ |
| Solde suffisant ? | **Paramètres > SMS** - Vérifier le solde |
| Numéro valide ? | Fiche client - Numéro au format international |
| Type de notification activé ? | Confirmation/Rappel activé dans les paramètres |

---

## Solde de crédits à zéro

### Les SMS ne partent plus

**Cause :** Vous n'avez plus de crédits SMS.

**Solution :**

1. Allez dans **Paramètres > SMS**
2. Cliquez sur **Acheter des crédits**
3. Choisissez un pack
4. Procédez au paiement

Les SMS en attente seront envoyés après rechargement (dans la limite du délai de validité).

[Voir les tarifs SMS](../facturation/credits-sms.md)

---

## Numéro de téléphone invalide

### Message "Numéro invalide" dans l'historique

**Causes possibles :**

1. **Format incorrect** : Le numéro doit être au format international
2. **Numéro incomplet** : Il manque des chiffres
3. **Numéro fixe** : Certains numéros fixes ne reçoivent pas les SMS

### Format correct pour la Suisse

| Format | Exemple | Valide |
|--------|---------|--------|
| International | +41791234567 | ✅ |
| Avec espaces | +41 79 123 45 67 | ✅ |
| Sans indicatif | 0791234567 | ⚠️ Peut ne pas fonctionner |
| Fixe | +41211234567 | ❌ SMS non supporté |

### Corriger un numéro

1. Ouvrez la fiche client
2. Modifiez le numéro de téléphone
3. Utilisez le format `+41XXXXXXXXX`
4. Enregistrez

---

## SMS en retard

### Le SMS arrive après le délai prévu

**Causes possibles :**

1. **Délai opérateur** : Quelques minutes de retard sont normaux
2. **Réseau saturé** : Périodes de forte affluence
3. **Problème opérateur** : Incident chez l'opérateur mobile

**Ce que vous pouvez faire :**

- Attendez quelques minutes
- Les rappels sont envoyés avec une marge (ex: "24h avant" = entre 24h et 23h avant)

---

## SMS reçu en double

### Le client a reçu deux fois le même SMS

**Causes possibles :**

1. **Problème technique temporaire** : Rare, contactez le support
2. **Deux actions déclenchées** : Vérifiez l'historique des SMS

### Vérifier l'historique

1. Allez dans **Paramètres > SMS > Historique**
2. Recherchez par client ou numéro
3. Vérifiez si deux SMS ont effectivement été envoyés

---

## SMS tronqué ou illisible

### Le texte du SMS est coupé

**Cause :** Les SMS sont limités à 160 caractères. Les messages longs sont découpés.

**Ce qui se passe :**
- Messages courts : 1 SMS
- Messages longs : 2-3 SMS (comptés séparément)

Les smartphones modernes recombinent généralement les SMS longs automatiquement.

---

## Caractères spéciaux incorrects

### Les accents ou caractères s'affichent mal

**Cause :** Certains caractères spéciaux peuvent poser problème selon l'opérateur ou le téléphone.

**Caractères problématiques :**
- Émojis : ⚠️ Peuvent ne pas s'afficher
- Caractères spéciaux : €, £, etc.

**Solution :** Les templates SMS standards évitent ces problèmes. Si vous personnalisez, restez simple.

---

## Sender ID non reconnu

### Le SMS vient d'un numéro inconnu

**Explication :**

Les SMS PitStoply arrivent soit :
- D'un **numéro** (+41...) : Normal, comportement par défaut
- D'un **nom** (ex: "GarageMartin") : Si Sender ID configuré

### Configurer un Sender ID

{% hint style="info" %}
Le Sender ID (nom d'expéditeur) ne fonctionne pas avec tous les opérateurs et tous les pays. Le numéro par défaut est plus fiable.
{% endhint %}

---

## Le client dit n'avoir rien reçu

### Mais l'historique montre "Envoyé"

**Vérifications côté client :**

1. Vérifier le bon numéro de téléphone
2. Vérifier les SMS bloqués/filtrés
3. Vérifier que le téléphone n'était pas éteint
4. Vérifier la couverture réseau au moment de l'envoi

**Vérifications côté PitStoply :**

1. Consultez l'historique SMS pour ce client
2. Vérifiez le statut (Envoyé, Échoué)
3. Vérifiez le numéro enregistré

---

## Statuts dans l'historique

| Statut | Signification |
|--------|---------------|
| ✅ **Envoyé** | SMS transmis à l'opérateur |
| ⏳ **En attente** | En cours d'envoi |
| ❌ **Échoué** | Erreur lors de l'envoi |

{% hint style="warning" %}
"Envoyé" signifie transmis à l'opérateur, pas nécessairement reçu par le client. La livraison finale dépend de l'opérateur mobile.
{% endhint %}

---

## Désactiver les SMS pour un client

Si un client demande à ne plus recevoir de SMS :

1. Ouvrez sa fiche client
2. Supprimez son numéro de téléphone
3. Ou désactivez les SMS dans ses préférences (si option disponible)

Les emails continueront d'être envoyés si une adresse email est renseignée.

---

## Contact support

Pour les problèmes persistants :

- **Formulaire de contact** : Consultez notre [page de feedback](../feedback.md) pour nous contacter
- Incluez :
  - Numéro de téléphone concerné (format utilisé)
  - Date et heure de l'envoi prévu
  - Capture d'écran de l'historique SMS
