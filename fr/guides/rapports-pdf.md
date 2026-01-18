# Générer des rapports PDF

PitStoply vous permet de générer des rapports PDF pour planifier vos journées et suivre votre activité.

## Types de rapports disponibles

| Rapport | Contenu | Utilisation |
|---------|---------|-------------|
| **Planning journalier** | RDV du jour, par lift | Affichage atelier |
| **Planning hebdomadaire** | RDV de la semaine | Planification équipe |
| **Export multi-branches** | Tous les plannings en ZIP | Réseaux multi-sites |

---

## Générer un rapport journalier

### Depuis le calendrier

1. Allez dans **Calendrier**
2. Sélectionnez la date souhaitée
3. Cliquez sur **Rapport PDF** ou l'icône imprimante
4. Le PDF se télécharge

### Contenu du rapport journalier

Le rapport inclut :

- **En-tête** : Logo, nom du garage, date
- **Par lift** : Liste des RDV avec :
  - Heure de début/fin
  - Client (nom, téléphone)
  - Véhicule (plaque, marque)
  - Service demandé
  - Notes éventuelles
- **Résumé** : Nombre total de RDV

### Utilisation typique

- Imprimez le planning et affichez-le dans l'atelier
- Distribuez à chaque technicien son planning du jour
- Gardez une trace papier des rendez-vous

---

## Générer un rapport hebdomadaire

### Depuis le calendrier

1. Allez dans **Calendrier**
2. Passez en vue **Semaine**
3. Cliquez sur **Rapport PDF**
4. Choisissez la semaine à exporter

### Contenu du rapport hebdomadaire

- Vue condensée de toute la semaine
- Rendez-vous groupés par jour
- Statistiques de la semaine :
  - Nombre total de RDV
  - Répartition par service
  - Taux d'occupation

---

## Export multi-branches (ZIP)

Si vous avez plusieurs succursales, exportez tous les plannings en une fois :

1. Allez dans **Calendrier** ou **Rapports**
2. Cliquez sur **Export multi-branches**
3. Sélectionnez :
   - La période (jour ou semaine)
   - Les succursales à inclure
4. Téléchargez le fichier ZIP

Le ZIP contient un PDF par succursale.

---

## Personnalisation des rapports

### Éléments personnalisés

Les rapports reprennent automatiquement :

| Élément | Source |
|---------|--------|
| **Logo** | Paramètres > Apparence |
| **Nom du garage** | Paramètres > Identité |
| **Coordonnées** | Paramètres de la succursale |

### Langue du rapport

Le rapport est généré dans la langue de votre compte (FR ou DE).

---

## Imprimer le rapport

### Conseils d'impression

| Paramètre | Recommandation |
|-----------|----------------|
| **Format** | A4 |
| **Orientation** | Portrait (journalier) ou Paysage (hebdo) |
| **Marges** | Normales |
| **Couleur** | Noir et blanc suffit |

### Impression directe

Depuis le PDF téléchargé :
1. Ouvrez le fichier
2. `Ctrl+P` (ou `Cmd+P` sur Mac)
3. Sélectionnez votre imprimante
4. Imprimez

---

## Automatisation (à venir)

{% hint style="info" %}
**Fonctionnalité prévue** : Envoi automatique du planning par email chaque matin.
{% endhint %}

En attendant, vous pouvez générer manuellement le rapport chaque jour.

---

## Questions fréquentes

<details>
<summary><strong>Puis-je personnaliser le contenu du rapport ?</strong></summary>

Actuellement, le format est standardisé. Une personnalisation avancée est prévue dans une future version.

</details>

<details>
<summary><strong>Les rapports sont-ils sauvegardés ?</strong></summary>

Non, les rapports sont générés à la demande. Vous pouvez les sauvegarder localement après téléchargement.

</details>

<details>
<summary><strong>Puis-je générer un rapport pour une période passée ?</strong></summary>

Oui, naviguez vers la date ou semaine passée dans le calendrier, puis générez le rapport normalement.

</details>

<details>
<summary><strong>Le rapport inclut-il les RDV annulés ?</strong></summary>

Non, seuls les rendez-vous confirmés et en attente apparaissent dans les rapports.

</details>
