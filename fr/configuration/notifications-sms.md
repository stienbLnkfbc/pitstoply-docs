# Notifications SMS

Envoyez des SMS automatiques à vos clients pour réduire les absences et améliorer l'expérience.

## Prérequis

Pour utiliser les notifications SMS :
1. Avoir des **crédits SMS** disponibles ([acheter des crédits](../facturation/credits-sms.md))
2. **Activer** les notifications SMS dans les paramètres
3. Vos clients doivent avoir un **numéro de téléphone valide**

---

## Activer les notifications SMS

### Configuration générale

1. Allez dans **Paramètres > Notifications**
2. Dans la section **SMS**, activez :

| Option | Quand l'activer |
|--------|-----------------|
| **SMS de confirmation** | Pour confirmer chaque nouvelle réservation |
| **SMS de rappel** | Pour rappeler le RDV avant la date |
| **SMS de modification** | Quand un RDV est modifié |
| **SMS d'annulation** | Quand un RDV est annulé |

{% hint style="tip" %}
**Recommandation** : Activez au minimum le **SMS de rappel** - c'est le plus efficace pour réduire les no-shows.
{% endhint %}

### Délai de rappel

Configurez quand le rappel est envoyé :
- **24 heures avant** (recommandé)
- **48 heures avant**
- **Le jour même**

---

## Configurer les paramètres SMS avancés

### Accéder aux paramètres détaillés

1. Allez dans **Paramètres > SMS**
2. Configurez les options disponibles

### Sender ID (expéditeur)

Le **Sender ID** est le nom qui apparaît comme expéditeur du SMS.

| Option | Affichage | Disponibilité |
|--------|-----------|---------------|
| Numéro par défaut | +41 79 xxx xx xx | Toujours |
| Nom personnalisé | "GarageMartin" | Selon opérateur |

{% hint style="warning" %}
**Note** : Les Sender ID personnalisés (noms) ne fonctionnent pas sur tous les opérateurs et tous les pays. Le numéro par défaut est recommandé pour une compatibilité maximale.
{% endhint %}

---

## Contenu des SMS

### SMS de confirmation

Envoyé immédiatement après une réservation.

**Exemple :**
```
Votre RDV est confirmé !
📅 15.01.2026 à 10:00
📍 Garage Martin - Lausanne
🚗 Changement de roues

Modifier/Annuler : [lien]
```

### SMS de rappel

Envoyé selon le délai configuré (ex: 24h avant).

**Exemple :**
```
Rappel : votre RDV demain !
📅 15.01.2026 à 10:00
📍 Garage Martin - Lausanne
À bientôt !
```

### SMS de modification

Envoyé quand le RDV est modifié.

**Exemple :**
```
Votre RDV a été modifié.
Nouvelle date : 16.01.2026 à 14:00
📍 Garage Martin - Lausanne
```

---

## Suivi des SMS

### Consulter l'historique

1. Allez dans **Paramètres > SMS > Historique**
2. Vous voyez tous les SMS envoyés avec :
   - Date et heure
   - Destinataire
   - Contenu
   - Statut

### Statuts possibles

| Statut | Signification |
|--------|---------------|
| ✅ Envoyé | SMS transmis à l'opérateur |
| ⏳ En attente | En cours d'envoi |
| ❌ Échoué | Erreur (numéro invalide, etc.) |

---

## Solde et recharge

### Vérifier le solde

Votre solde SMS est visible :
- Dashboard (widget notifications)
- Paramètres > SMS
- Lors de l'envoi (alerte si solde bas)

### Recharger

1. Allez dans **Paramètres > SMS**
2. Cliquez sur **Acheter des crédits**
3. Choisissez un pack
4. Procédez au paiement

[Voir les tarifs des packs SMS](../facturation/credits-sms.md)

---

## Cas particuliers

### Client sans numéro de téléphone

Si un client n'a pas de numéro :
- Le SMS n'est pas envoyé
- Aucun crédit n'est débité
- Un email est envoyé à la place (si activé)

### Numéro étranger

| Pays | Support |
|------|---------|
| Suisse (+41) | ✅ Optimal |
| France (+33) | ✅ Fonctionnel |
| Allemagne (+49) | ✅ Fonctionnel |
| Autres | ⚠️ Non garanti |

### SMS longs

Un SMS standard = 160 caractères.
Si le message dépasse, il compte comme plusieurs SMS.

---

## Désactiver les SMS

### Temporairement

Décochez les options dans **Paramètres > Notifications** sans supprimer vos crédits.

### Définitivement

Désactivez toutes les options SMS. Vos crédits restent disponibles si vous changez d'avis.

---

## Questions fréquentes

<details>
<summary><strong>Les SMS sont-ils envoyés automatiquement ?</strong></summary>

Oui, selon vos paramètres :
- Confirmation : automatique à la réservation
- Rappel : automatique selon le délai configuré
- Modification/Annulation : automatique à l'action

</details>

<details>
<summary><strong>Puis-je personnaliser le texte des SMS ?</strong></summary>

Actuellement, les templates sont prédéfinis pour garantir la clarté et la conformité. Une personnalisation avancée est prévue dans une future version.

</details>

<details>
<summary><strong>Le client peut-il répondre au SMS ?</strong></summary>

Non, les SMS sont envoyés depuis un système automatisé. Pour contacter votre garage, le client doit utiliser votre numéro de téléphone habituel.

</details>

<details>
<summary><strong>Que se passe-t-il si mon solde est à 0 ?</strong></summary>

Les SMS ne sont pas envoyés. Les emails continuent de fonctionner si activés. Vous recevez une alerte de solde bas avant d'atteindre 0.

</details>

<details>
<summary><strong>Les SMS fonctionnent-ils le week-end ?</strong></summary>

Oui, les SMS sont envoyés 24h/24, 7j/7 selon les événements déclencheurs (réservation, rappel programmé, etc.).

</details>
