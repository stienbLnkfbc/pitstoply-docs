# Utiliser le calendrier

Le calendrier est votre outil central pour visualiser et gérer tous vos rendez-vous.

## Vue d'ensemble

### Accéder au calendrier

1. Cliquez sur **Calendrier** dans le menu principal
2. Ou depuis le Dashboard, cliquez sur **Voir le calendrier**

### Types de vues

| Vue | Idéale pour |
|-----|-------------|
| **Jour** | Planification détaillée, journée chargée |
| **Semaine** | Vue d'ensemble hebdomadaire |
| **Timeline** | Voir tous les lifts côte à côte |

{% hint style="tip" %}
**Recommandation** : La vue **Timeline** est la plus pratique pour les garages avec plusieurs lifts car elle affiche tous les postes de travail en colonnes.
{% endhint %}

---

## Navigation dans le calendrier

### Changer de date

| Action | Comment |
|--------|---------|
| Jour précédent/suivant | Flèches `<` et `>` |
| Semaine précédente/suivante | Boutons de navigation |
| Date spécifique | Cliquez sur le sélecteur de date |
| Aujourd'hui | Bouton **Aujourd'hui** |

### Filtrer par succursale

Si vous avez plusieurs succursales :
1. Utilisez le sélecteur de succursale en haut
2. Seuls les lifts de cette succursale s'affichent

---

## Lire le calendrier

### Informations affichées sur chaque RDV

Chaque bloc de rendez-vous affiche :
- **Heure** de début
- **Client** (nom/prénom)
- **Service** (icône)
- **Véhicule** (plaque)
- **Statut** (couleur du badge)

### Code couleur des statuts

| Couleur | Statut | Signification |
|---------|--------|---------------|
| 🟡 Jaune | En attente | Non confirmé |
| 🔵 Bleu | Confirmé | Prêt pour le jour J |
| 🟣 Violet | En cours | Client présent, travail en cours |
| 🟢 Vert | Terminé | Service effectué |
| 🔴 Rouge | Annulé | RDV annulé |
| ⚪ Gris | Absent | No-show |

---

## Actions rapides

### Créer un rendez-vous depuis le calendrier

1. **Double-cliquez** sur un créneau libre
2. Le formulaire de création s'ouvre avec la date/heure pré-remplie
3. Complétez les informations et enregistrez

### Modifier un rendez-vous

1. **Cliquez** sur le rendez-vous
2. Une fenêtre de détail s'ouvre
3. Cliquez sur **Modifier**
4. Effectuez vos changements
5. Enregistrez

### Déplacer un rendez-vous (drag & drop)

1. Cliquez et maintenez sur le rendez-vous
2. Faites-le glisser vers le nouveau créneau
3. Relâchez pour confirmer

{% hint style="warning" %}
**Attention** : Le déplacement n'est possible que vers des créneaux disponibles (horaires ouverts, pas de conflit).
{% endhint %}

### Changer de statut rapidement

1. Cliquez sur le rendez-vous
2. Dans le panneau de détail, changez le statut
3. Le calendrier se met à jour automatiquement

---

## Événements externes (calendriers synchronisés)

Si vous avez connecté un calendrier externe (Google, Outlook) :

### Comment ils apparaissent

- Les événements externes sont affichés en **gris clair**
- Ils bloquent le créneau (pas de réservation possible)
- Ils portent la mention "Externe" ou le nom du calendrier source

### Pourquoi synchroniser ?

| Avantage | Description |
|----------|-------------|
| Éviter les conflits | Un RDV perso bloque automatiquement |
| Vue unifiée | Tous vos événements au même endroit |
| Bidirectionnel | Les RDV PitStoply apparaissent dans votre calendrier |

[Configurer la synchronisation calendrier](../configuration/calendrier-externe.md)

---

## Blocages et fermetures

### Créneaux bloqués

Les créneaux indisponibles apparaissent :
- En **gris foncé** : Hors horaires d'ouverture
- Avec **hachures** : Blocage manuel (fermeture, congé)

### Créer un blocage depuis le calendrier

1. Double-cliquez sur le créneau à bloquer
2. Choisissez **Créer un blocage**
3. Définissez la durée et la raison
4. Confirmez

---

## Rapports et exports

### Imprimer le planning

1. En vue Jour ou Semaine, cliquez sur **Imprimer**
2. Le navigateur ouvre une version imprimable
3. Imprimez ou enregistrez en PDF

### Rapport PDF

1. Cliquez sur **Rapport**
2. Choisissez la période (jour, semaine)
3. Sélectionnez les succursales
4. Téléchargez le PDF

{% hint style="info" %}
Le rapport PDF inclut tous les détails des rendez-vous : client, véhicule, service, notes.
{% endhint %}

---

## Paramètres du calendrier

### Personnaliser l'affichage

Dans **Paramètres > Affichage calendrier** (si disponible) :
- Première heure affichée
- Dernière heure affichée
- Incrément des créneaux (15, 30, 60 min)

### Notifications de nouveau RDV

Vous pouvez recevoir une alerte quand un nouveau rendez-vous est créé (par un client en ligne) :
- Notification navigateur
- Email
- Son

---

## Raccourcis clavier

| Raccourci | Action |
|-----------|--------|
| `←` `→` | Jour précédent/suivant |
| `T` | Revenir à aujourd'hui |
| `D` | Vue Jour |
| `W` | Vue Semaine |
| `N` | Nouveau rendez-vous |

---

## Questions fréquentes

<details>
<summary><strong>Pourquoi certains créneaux sont grisés ?</strong></summary>

Les créneaux grisés sont indisponibles car :
- Hors horaires d'ouverture configurés
- Bloqués par une fermeture/congé
- Occupés par un événement externe (calendrier synchronisé)

</details>

<details>
<summary><strong>Puis-je voir le calendrier de plusieurs succursales en même temps ?</strong></summary>

Actuellement, le calendrier affiche une succursale à la fois. Utilisez le sélecteur pour basculer entre les succursales.

</details>

<details>
<summary><strong>Comment voir les RDV de la semaine prochaine rapidement ?</strong></summary>

Cliquez sur la flèche `>` ou utilisez le sélecteur de date pour naviguer directement à la semaine souhaitée.

</details>
