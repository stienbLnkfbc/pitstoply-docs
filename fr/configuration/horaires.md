# Horaires d'ouverture

Configurez précisément vos horaires pour que les créneaux de réservation correspondent à votre disponibilité réelle.

## Comprendre la hiérarchie des horaires

PitStoply gère les horaires à deux niveaux :

```
Succursale (défaut)
    └── Lift 1 (peut avoir ses propres horaires)
    └── Lift 2 (peut avoir ses propres horaires)
    └── Lift 3 (utilise les horaires de la succursale)
```

{% hint style="info" %}
**Par défaut**, tous les lifts utilisent les horaires de leur succursale. Vous pouvez définir des horaires spécifiques par lift si nécessaire.
{% endhint %}

---

## Configurer les horaires de la succursale

### Accéder aux paramètres

1. Allez dans **Paramètres > Horaires**
2. Sélectionnez la succursale concernée

### Définir les horaires par jour

Pour chaque jour de la semaine :

| Champ | Description |
|-------|-------------|
| **Ouvert** | Le jour est-il travaillé ? |
| **Heure d'ouverture** | Début des créneaux disponibles |
| **Heure de fermeture** | Fin des créneaux disponibles |

**Exemple typique :**

| Jour | Ouverture | Fermeture |
|------|-----------|-----------|
| Lundi | 08:00 | 18:00 |
| Mardi | 08:00 | 18:00 |
| Mercredi | 08:00 | 18:00 |
| Jeudi | 08:00 | 18:00 |
| Vendredi | 08:00 | 17:00 |
| Samedi | 08:00 | 12:00 |
| Dimanche | Fermé | - |

### Jour fermé

Pour marquer un jour comme fermé :
1. Décochez la case **Ouvert** pour ce jour
2. Ou laissez les heures vides

---

## Configurer les horaires d'un lift spécifique

Si un lift a des horaires différents de la succursale :

### Pourquoi des horaires par lift ?

| Situation | Solution |
|-----------|----------|
| Un lift disponible uniquement le matin | Horaires spécifiques |
| Un lift avec un employé à temps partiel | Horaires réduits |
| Un lift réservé à certains services | Horaires adaptés |

### Comment configurer

1. Allez dans **Paramètres > Succursales**
2. Cliquez sur la succursale
3. Sélectionnez le lift
4. Activez **Horaires personnalisés**
5. Définissez les horaires spécifiques

{% hint style="tip" %}
Les horaires du lift **remplacent** ceux de la succursale. Si le lift est ouvert 8h-12h le lundi mais la succursale 8h-18h, seul 8h-12h sera disponible pour ce lift.
{% endhint %}

---

## Pause déjeuner

Pour bloquer une pause déjeuner :

### Option 1 : Via les fermetures récurrentes

1. Allez dans **Paramètres > Fermetures**
2. Créez un blocage récurrent :
   - Heure : 12:00 - 14:00
   - Récurrence : Tous les jours ouvrés
   - Raison : Pause déjeuner

### Option 2 : Horaires fractionnés

Créez deux plages horaires par jour :
- Matin : 08:00 - 12:00
- Après-midi : 14:00 - 18:00

{% hint style="warning" %}
**Note** : La gestion des plages horaires multiples par jour dépend de votre version. Contactez le support si cette option n'est pas disponible.
{% endhint %}

---

## Horaires saisonniers

Si vos horaires changent selon la saison (été/hiver) :

### Comment procéder

1. Modifiez les horaires au début de chaque saison
2. Ou utilisez des blocages pour les périodes exceptionnelles

### Exemple : Horaires d'été

| Jour | Hiver | Été |
|------|-------|-----|
| Samedi | 08:00 - 12:00 | 07:00 - 14:00 |

{% hint style="info" %}
**Astuce** : Planifiez une alerte dans votre agenda pour vous rappeler de changer les horaires aux changements de saison.
{% endhint %}

---

## Impact sur les réservations

### Créneaux affichés

Les clients ne voient **que** les créneaux correspondant à vos horaires :
- Hors horaires = invisible
- Pendant les horaires = visible (sauf si déjà pris)

### Durée des services

Un créneau n'est proposé que si le service peut être **entièrement réalisé** avant la fermeture.

**Exemple** :
- Fermeture à 18:00
- Service de 45 minutes
- Dernier créneau proposé : 17:15

---

## Vérifier la configuration

### Test rapide

1. Ouvrez votre page de réservation publique
2. Naviguez vers différents jours
3. Vérifiez que les créneaux correspondent à vos attentes

### Points à vérifier

- [ ] Les jours fermés n'affichent aucun créneau
- [ ] Les créneaux commencent à l'heure d'ouverture
- [ ] Les derniers créneaux respectent l'heure de fermeture
- [ ] Les lifts avec horaires spécifiques fonctionnent

---

## Questions fréquentes

<details>
<summary><strong>Puis-je avoir des horaires différents chaque semaine ?</strong></summary>

Non, les horaires sont définis par jour de la semaine et s'appliquent à toutes les semaines. Pour des exceptions ponctuelles, utilisez les **Fermetures**.

</details>

<details>
<summary><strong>Comment bloquer un créneau précis sans fermer toute la journée ?</strong></summary>

Utilisez **Paramètres > Fermetures** pour créer un blocage sur un créneau spécifique (ex: 10:00-11:00 le 15 janvier).

</details>

<details>
<summary><strong>Les changements d'horaires affectent-ils les RDV existants ?</strong></summary>

Non, les rendez-vous déjà pris restent valides. Les nouveaux horaires s'appliquent uniquement aux nouvelles réservations.

</details>

<details>
<summary><strong>Comment gérer un employé à temps partiel ?</strong></summary>

Créez un lift dédié à cet employé avec ses propres horaires. Ainsi, ce lift ne sera disponible que quand l'employé est présent.

</details>
