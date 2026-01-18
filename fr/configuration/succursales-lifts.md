# Succursales et Lifts

Organisez votre garage en définissant vos lieux (succursales) et postes de travail (lifts).

## Concepts clés

### Qu'est-ce qu'une succursale ?

Une **succursale** représente un lieu physique où vous exercez votre activité :
- Un garage
- Un atelier
- Un centre technique

Même si vous n'avez qu'un seul site, vous avez une succursale.

### Qu'est-ce qu'un lift ?

Un **lift** représente un poste de travail capable de traiter un rendez-vous :
- Un pont élévateur
- Une baie de service
- Une zone de travail

{% hint style="info" %}
**Le nombre de lifts détermine votre capacité** : 3 lifts = 3 rendez-vous simultanés possibles au même créneau.
{% endhint %}

---

## Limites selon votre plan

| Plan | Succursales | Lifts |
|------|-------------|-------|
| **Independent** | 1 | 1 |
| **Multi-Lift** | 1-3 | Illimité |
| **Network** | Illimité | Illimité |

[Voir les plans d'abonnement](../facturation/plans.md)

---

## Gérer les succursales

### Accéder aux paramètres

1. Allez dans **Paramètres > Succursales**
2. Vous voyez la liste de vos succursales

### Créer une succursale

1. Cliquez sur **Nouvelle succursale**
2. Remplissez les informations :

| Champ | Description |
|-------|-------------|
| **Nom** | Nom affiché aux clients (ex: "Lausanne Centre") |
| **Adresse** | Adresse complète |
| **Téléphone** | Numéro de contact |
| **Email** | Email de contact |

3. Cliquez sur **Enregistrer**

### Modifier une succursale

1. Cliquez sur la succursale
2. Modifiez les informations
3. Enregistrez

### Supprimer une succursale

{% hint style="danger" %}
**Attention** : La suppression d'une succursale supprime tous ses lifts et affecte les rendez-vous associés.
{% endhint %}

1. Ouvrez la succursale
2. Cliquez sur **Supprimer**
3. Confirmez

---

## Gérer les lifts

### Accéder aux lifts

1. Dans **Paramètres > Succursales**
2. Cliquez sur une succursale
3. Vous voyez la liste des lifts

### Créer un lift

1. Cliquez sur **Nouveau lift**
2. Remplissez les informations :

| Champ | Description |
|-------|-------------|
| **Nom** | Identifiant du lift (ex: "Lift 1", "Pont A") |
| **Description** | Notes internes (optionnel) |
| **Horaires personnalisés** | Si différents de la succursale |
| **Actif** | Le lift accepte-t-il des réservations ? |

3. Cliquez sur **Enregistrer**

### Nommer ses lifts

Conseils pour des noms clairs :

| ✅ Bon | ❌ À éviter |
|--------|-----------|
| "Lift 1", "Lift 2" | "a", "b" |
| "Pont élévateur", "Baie rapide" | "test" |
| "Zone A", "Zone B" | Noms trop longs |

{% hint style="tip" %}
Les noms des lifts apparaissent dans le calendrier. Gardez-les courts et identifiables.
{% endhint %}

### Désactiver un lift

Si un lift est temporairement indisponible (en panne, maintenance) :

1. Ouvrez le lift
2. Décochez **Actif**
3. Enregistrez

Le lift n'acceptera plus de réservations mais les RDV existants sont conservés.

### Supprimer un lift

{% hint style="warning" %}
Les rendez-vous existants sur ce lift seront affectés. Préférez désactiver plutôt que supprimer.
{% endhint %}

---

## Horaires des lifts

Par défaut, chaque lift utilise les horaires de sa succursale.

### Définir des horaires spécifiques

1. Ouvrez le lift
2. Activez **Horaires personnalisés**
3. Définissez les horaires par jour
4. Enregistrez

### Cas d'usage

| Situation | Solution |
|-----------|----------|
| Lift dédié au matin | Horaires 8h-12h |
| Lift weekends only | Horaires samedi uniquement |
| Lift maintenance le lundi | Fermé le lundi |

---

## Organisation multi-succursales

### Comment les clients choisissent

Lors de la réservation en ligne :
1. Le client voit d'abord les succursales
2. Il sélectionne celle souhaitée
3. Puis choisit date et créneau

### Calendrier par succursale

Dans votre calendrier :
- Utilisez le sélecteur pour basculer entre succursales
- Chaque succursale affiche ses lifts en colonnes

---

## Bonnes pratiques

### Pour un garage simple (1 succursale)

```
Succursale : "Mon Garage"
├── Lift 1
├── Lift 2
└── Lift 3
```

### Pour un garage avec zones spécialisées

```
Succursale : "Garage Martin"
├── Lift Pneus 1
├── Lift Pneus 2
├── Lift Mécanique (horaires différents)
└── Baie rapide (15 min par RDV)
```

### Pour un réseau de garages

```
Succursale : "Lausanne Centre"
├── Lift 1
├── Lift 2

Succursale : "Morges"
├── Lift 1

Succursale : "Nyon"
├── Lift 1
├── Lift 2
├── Lift 3
```

---

## Questions fréquentes

<details>
<summary><strong>Puis-je renommer une succursale sans perdre les données ?</strong></summary>

Oui, le renommage ne supprime aucune donnée. Les rendez-vous existants sont conservés.

</details>

<details>
<summary><strong>Comment déplacer un lift d'une succursale à une autre ?</strong></summary>

Il n'est pas possible de déplacer un lift. Vous devez :
1. Créer un nouveau lift dans la succursale cible
2. Supprimer l'ancien lift (ou le désactiver)

</details>

<details>
<summary><strong>Combien de lifts dois-je créer ?</strong></summary>

Créez un lift par poste de travail réel capable de traiter un rendez-vous. Si vous avez 2 ponts élévateurs, créez 2 lifts.

</details>

<details>
<summary><strong>Un lift peut-il gérer plusieurs types de services ?</strong></summary>

Oui, par défaut tous les lifts peuvent traiter tous les services. Une attribution spécifique par type de service est prévue dans une future version.

</details>
