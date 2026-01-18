# Créer votre premier rendez-vous

Ce guide vous montre comment créer un rendez-vous, que ce soit depuis le dashboard ou pour un client qui réserve en ligne.

## Méthode 1 : Depuis le Dashboard (vous)

### Étape 1 : Accéder à la création

1. Connectez-vous à PitStoply
2. Depuis le **Dashboard**, cliquez sur **Nouveau rendez-vous**
   - Ou allez dans **Rendez-vous > Créer**

### Étape 2 : Sélectionner le client

Deux options :

| Option | Quand l'utiliser |
|--------|------------------|
| **Client existant** | Le client est déjà dans votre base |
| **Nouveau client** | Première visite du client |

**Pour un client existant :**
1. Tapez le nom, prénom ou numéro de téléphone
2. Sélectionnez le client dans la liste
3. Choisissez le véhicule concerné (ou ajoutez-en un)

**Pour un nouveau client :**
1. Cliquez sur **Nouveau client**
2. Remplissez les informations de base (nom, téléphone)
3. Ajoutez un véhicule (plaque d'immatriculation obligatoire)

### Étape 3 : Choisir le service

Sélectionnez le type de service :

| Service | Description | Durée type |
|---------|-------------|------------|
| Changement de roues | Échange roues complètes | 30 min |
| Changement de pneus | Montage/démontage sur jantes | 45 min |

{% hint style="info" %}
La durée et le prix peuvent être personnalisés dans **Paramètres > Services**.
{% endhint %}

### Étape 4 : Choisir le créneau

1. Sélectionnez la **succursale** (si plusieurs)
2. Choisissez la **date** dans le calendrier
3. Sélectionnez un **créneau disponible**
   - Les créneaux grisés sont déjà pris ou hors horaires

{% hint style="tip" %}
**Astuce** : Si aucun créneau n'est disponible, vérifiez :
- Les horaires configurés pour ce jour
- Les blocages/fermetures éventuels
- La synchronisation calendrier externe
{% endhint %}

### Étape 5 : Confirmer

1. Vérifiez le récapitulatif
2. Choisissez si vous souhaitez envoyer une notification au client
3. Cliquez sur **Créer le rendez-vous**

Le rendez-vous apparaît maintenant dans votre calendrier !

---

## Méthode 2 : Réservation en ligne (par le client)

### Comment ça marche pour vos clients

1. Le client accède à votre page : `pitstoply.ch/votre-slug`
2. Il sélectionne le service souhaité
3. Il choisit la date et le créneau
4. Il remplit ses coordonnées
5. Il valide la réservation

### Ce que vous voyez

- Le rendez-vous apparaît automatiquement dans votre calendrier
- Vous recevez une notification (si configuré)
- Le client reçoit une confirmation par email (et SMS si activé)

### Partager votre lien de réservation

| Méthode | Avantage |
|---------|----------|
| **QR Code** | Idéal pour affichage en vitrine |
| **Lien direct** | Pour emails, site web, réseaux sociaux |
| **Bouton intégré** | Pour votre site web existant |

---

## Méthode 3 : Via le QR Code client

Si vous avez déjà des clients dans votre base :

1. Chaque client possède un **QR code unique**
2. Le client scanne son QR (depuis sa carte client ou email)
3. Il accède directement à son portail personnel
4. Il peut réserver avec ses véhicules déjà enregistrés

{% hint style="success" %}
**Avantage** : Le client n'a pas à ressaisir ses informations à chaque réservation.
{% endhint %}

---

## Après la création

### Modifier un rendez-vous

1. Cliquez sur le RDV dans le calendrier
2. Modifiez les informations souhaitées
3. Enregistrez

Une notification de modification peut être envoyée au client.

### Annuler un rendez-vous

1. Ouvrez le rendez-vous
2. Cliquez sur **Annuler**
3. Confirmez l'annulation

Le créneau redevient disponible pour d'autres réservations.

### Marquer comme effectué

Après avoir réalisé le service :
1. Ouvrez le rendez-vous
2. Changez le statut en **Terminé**

Cela met à jour vos statistiques et libère le créneau définitivement.

---

## Statuts des rendez-vous

| Statut | Signification | Couleur |
|--------|---------------|---------|
| **En attente** | Réservé, pas encore confirmé | Jaune |
| **Confirmé** | Confirmé par vous ou le système | Bleu |
| **En cours** | Le client est là, travail en cours | Violet |
| **Terminé** | Service effectué | Vert |
| **Annulé** | Rendez-vous annulé | Rouge |
| **Absent** | Client ne s'est pas présenté | Gris |

---

## Questions fréquentes

<details>
<summary><strong>Le client peut-il modifier son RDV lui-même ?</strong></summary>

Oui ! Chaque email de confirmation contient un lien de modification. Le client peut changer la date/heure ou annuler.

</details>

<details>
<summary><strong>Comment bloquer un créneau sans créer de RDV ?</strong></summary>

Utilisez la fonction **Blocages** dans Paramètres > Fermetures pour bloquer des créneaux spécifiques.

</details>

<details>
<summary><strong>Puis-je créer un RDV récurrent ?</strong></summary>

Actuellement, chaque rendez-vous doit être créé individuellement. Une fonction de récurrence est prévue.

</details>
