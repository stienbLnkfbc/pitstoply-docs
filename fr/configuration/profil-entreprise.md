# Profil de l'entreprise

Configurez les informations de votre garage qui apparaîtront sur votre page de réservation et dans les communications.

## Accéder aux paramètres

1. Allez dans **Paramètres**
2. Cliquez sur **Identité** ou **Profil**

---

## Informations de base

### Identité du garage

| Champ | Description | Où ça apparaît |
|-------|-------------|----------------|
| **Nom du garage** | Nom commercial | Page de réservation, emails, rapports |
| **Slug** | Identifiant URL | `pitstoply.ch/votre-slug` |
| **Slogan** | Phrase d'accroche (optionnel) | Page de réservation |

### Coordonnées

| Champ | Description |
|-------|-------------|
| **Adresse** | Adresse postale complète |
| **Téléphone** | Numéro principal |
| **Email** | Email de contact public |
| **Site web** | URL de votre site (optionnel) |

{% hint style="info" %}
Ces informations apparaissent sur votre page de réservation publique et dans les emails envoyés aux clients.
{% endhint %}

---

## Modifier le slug

Le slug est l'identifiant unique de votre page de réservation.

### Règles du slug

| Règle | Exemple |
|-------|---------|
| Minuscules uniquement | ✅ `garage-martin` ❌ `Garage-Martin` |
| Tirets autorisés | ✅ `garage-martin-sa` |
| Pas d'espaces | ❌ `garage martin` |
| Pas de caractères spéciaux | ❌ `garage@martin` |

### Changer le slug

1. Dans **Identité**, modifiez le champ **Slug**
2. Vérifiez la disponibilité
3. Enregistrez

{% hint style="warning" %}
**Attention** : Si vous changez le slug, l'ancienne URL ne fonctionnera plus. Pensez à mettre à jour vos QR codes et liens partagés.
{% endhint %}

---

## Informations légales

### Données optionnelles

| Champ | Description |
|-------|-------------|
| **Numéro IDE** | Numéro d'identification des entreprises (CHE-xxx.xxx.xxx) |
| **TVA** | Numéro de TVA si assujetti |

Ces informations peuvent apparaître sur les factures et documents officiels.

---

## Langue du garage

### Langue par défaut

Définissez la langue principale de votre garage :

| Langue | Code |
|--------|------|
| Français | `fr` |
| Allemand | `de` |

Cette langue détermine :
- La langue par défaut de votre page de réservation
- La langue des emails aux nouveaux clients
- La langue des rapports

### Changement de langue

1. Dans **Paramètres > Général**
2. Sélectionnez la **Langue**
3. Enregistrez

{% hint style="info" %}
Chaque utilisateur peut aussi définir sa propre préférence de langue dans son profil personnel.
{% endhint %}

---

## Fuseau horaire

PitStoply utilise le fuseau horaire **Europe/Zurich** par défaut, adapté à la Suisse.

Les heures affichées (créneaux, rendez-vous) utilisent ce fuseau automatiquement.

---

## Vérifier vos informations

### Aperçu public

Pour voir comment vos informations apparaissent aux clients :

1. Ouvrez votre page de réservation : `pitstoply.ch/votre-slug`
2. Vérifiez que le nom, l'adresse et le contact sont corrects

### Test d'email

Envoyez-vous un email de test pour vérifier l'apparence :

1. Créez un rendez-vous de test avec votre propre email
2. Vérifiez l'email de confirmation reçu
3. Supprimez le rendez-vous de test

---

## Questions fréquentes

<details>
<summary><strong>Puis-je avoir plusieurs noms pour différentes succursales ?</strong></summary>

Le nom du garage est global. Chaque succursale peut avoir son propre nom distinct dans **Paramètres > Succursales**.

</details>

<details>
<summary><strong>Le changement de slug est-il immédiat ?</strong></summary>

Oui, le changement est instantané. L'ancien slug ne fonctionne plus immédiatement.

</details>

<details>
<summary><strong>Puis-je utiliser un emoji dans le nom ?</strong></summary>

Techniquement oui, mais ce n'est pas recommandé pour des raisons de compatibilité (emails, PDF).

</details>
