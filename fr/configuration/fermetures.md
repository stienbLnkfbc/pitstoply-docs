# Fermetures et congés

Bloquez les créneaux indisponibles pour éviter les réservations pendant vos fermetures.

## Types de blocages

| Type | Exemple | Utilisation |
|------|---------|-------------|
| **Date unique** | 1er août 2026 | Jour férié |
| **Période** | 24-31 décembre | Vacances |
| **Récurrence** | Tous les dimanches | Jour de fermeture hebdomadaire |
| **Créneau** | 15 janv. 10h-12h | Réunion, RDV perso |

---

## Créer un blocage

### Accéder aux fermetures

1. Allez dans **Paramètres > Fermetures**
2. Cliquez sur **Nouvelle fermeture**

### Blocage ponctuel (1 jour)

1. Sélectionnez **Date unique**
2. Choisissez la date
3. Indiquez une raison (ex: "Fête nationale")
4. Choisissez le scope (tous les lifts ou un lift spécifique)
5. Enregistrez

**Exemple : 1er août**
- Type : Date unique
- Date : 01.08.2026
- Raison : Fête nationale
- Scope : Toutes les succursales

### Blocage période (plusieurs jours)

1. Sélectionnez **Période**
2. Définissez la date de début
3. Définissez la date de fin
4. Indiquez une raison
5. Enregistrez

**Exemple : Vacances de Noël**
- Type : Période
- Début : 24.12.2026
- Fin : 02.01.2027
- Raison : Fermeture annuelle

### Blocage récurrent

Pour les fermetures régulières (chaque dimanche, chaque lundi, etc.) :

1. Sélectionnez **Récurrence**
2. Choisissez le pattern :
   - Chaque semaine (ex: tous les dimanches)
   - Chaque mois (ex: le premier lundi du mois)
3. Définissez la période d'application (optionnel)
4. Enregistrez

**Exemple : Fermé le dimanche**
- Type : Récurrence hebdomadaire
- Jour : Dimanche
- Raison : Repos hebdomadaire

{% hint style="tip" %}
**Astuce** : Pour les jours régulièrement fermés (dimanche), utilisez plutôt les **horaires** en marquant le jour comme fermé. Les blocages récurrents sont utiles pour des patterns moins standards.
{% endhint %}

### Blocage créneau spécifique

Pour bloquer quelques heures seulement :

1. Sélectionnez **Créneau**
2. Choisissez la date
3. Définissez l'heure de début et de fin
4. Indiquez une raison
5. Enregistrez

**Exemple : Réunion d'équipe**
- Type : Créneau
- Date : 15.01.2026
- Heure : 08:00 - 10:00
- Raison : Réunion d'équipe
- Scope : Tous les lifts

---

## Scope du blocage

### Toutes les succursales

Le blocage s'applique à l'ensemble de votre garage.

### Succursale spécifique

Le blocage ne s'applique qu'à une succursale (les autres restent ouvertes).

### Lift spécifique

Le blocage ne s'applique qu'à un lift (les autres lifts restent disponibles).

**Cas d'usage :**
- Un lift en maintenance
- Un employé absent
- Une zone temporairement inutilisable

---

## Visualisation des blocages

### Dans la liste

**Paramètres > Fermetures** affiche tous vos blocages :
- Actifs (date future)
- Passés (historique)

### Dans le calendrier

Les blocages apparaissent :
- En gris foncé avec hachures
- Avec le label de la raison

---

## Modifier un blocage

1. Ouvrez le blocage dans la liste
2. Modifiez les informations
3. Enregistrez

{% hint style="info" %}
Modifier un blocage n'affecte pas les rendez-vous déjà pris en dehors de la période bloquée.
{% endhint %}

---

## Supprimer un blocage

1. Ouvrez le blocage
2. Cliquez sur **Supprimer**
3. Confirmez

Le créneau redevient disponible pour les réservations.

---

## Jours fériés suisses

### Jours fériés recommandés à bloquer

| Date | Jour férié |
|------|------------|
| 1er janvier | Nouvel An |
| 2 janvier | Lendemain Nouvel An (certains cantons) |
| Vendredi Saint | Variable (mars/avril) |
| Lundi de Pâques | Variable |
| 1er mai | Fête du travail (certains cantons) |
| Ascension | Variable (mai/juin) |
| Lundi de Pentecôte | Variable |
| 1er août | Fête nationale |
| 25 décembre | Noël |
| 26 décembre | Saint-Étienne |

{% hint style="warning" %}
Les jours fériés varient selon les cantons. Vérifiez les jours applicables dans votre canton.
{% endhint %}

---

## Impact sur les réservations

### Nouveaux rendez-vous

Les créneaux bloqués sont **invisibles** pour les clients. Ils ne peuvent pas réserver pendant ces périodes.

### Rendez-vous existants

{% hint style="danger" %}
**Important** : Si vous créez un blocage sur une période où des RDV existent déjà, ces RDV **ne sont pas automatiquement annulés**. Vous devez les gérer manuellement.
{% endhint %}

### Vérification recommandée

Avant de créer un blocage :
1. Consultez le calendrier pour la période concernée
2. Contactez les clients si des RDV sont prévus
3. Annulez ou déplacez les RDV si nécessaire
4. Puis créez le blocage

---

## Bonnes pratiques

### Planifier à l'avance

- Créez vos blocages de vacances plusieurs semaines à l'avance
- Cela évite les réservations de dernière minute à déplacer

### Documenter les raisons

- Utilisez des raisons claires ("Vacances", "Maintenance")
- Cela vous aide à retrouver pourquoi un jour était bloqué

### Vérifier régulièrement

- Supprimez les blocages obsolètes
- Mettez à jour les récurrences si vos habitudes changent

---

## Questions fréquentes

<details>
<summary><strong>Puis-je bloquer un créneau déjà réservé ?</strong></summary>

Oui, mais le rendez-vous existant n'est pas automatiquement annulé. Vous devez le gérer manuellement (annuler ou déplacer).

</details>

<details>
<summary><strong>Comment bloquer rapidement plusieurs jours non consécutifs ?</strong></summary>

Créez un blocage séparé pour chaque date. Il n'est pas possible de sélectionner plusieurs dates non consécutives en une fois.

</details>

<details>
<summary><strong>Les blocages affectent-ils les événements du calendrier externe ?</strong></summary>

Non, les blocages PitStoply sont indépendants de votre calendrier externe. Ils se cumulent : si un créneau est bloqué dans l'un OU l'autre, il est indisponible.

</details>

<details>
<summary><strong>Puis-je voir l'historique des blocages passés ?</strong></summary>

Oui, dans **Paramètres > Fermetures**, vous pouvez voir les blocages passés et actifs. Les blocages passés sont conservés pour référence.

</details>
