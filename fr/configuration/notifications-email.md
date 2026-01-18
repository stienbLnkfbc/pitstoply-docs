# Notifications Email

Configurez les emails automatiques envoyés à vos clients pour les tenir informés de leurs rendez-vous.

## Types d'emails

| Email | Déclencheur | Contenu |
|-------|-------------|---------|
| **Confirmation** | Nouvelle réservation | Détails du RDV, lien de modification |
| **Rappel 24h** | 24h avant le RDV | Rappel avec détails |
| **Rappel Jour J** | 2h avant le RDV | Rappel de dernière minute |
| **Modification** | RDV modifié | Nouveaux détails |
| **Annulation** | RDV annulé | Confirmation d'annulation |

---

## Accéder aux paramètres

1. Allez dans **Paramètres**
2. Cliquez sur **Notifications**
3. Section **Email**

---

## Activer/Désactiver les emails

### Par type d'email

Pour chaque type d'email, vous pouvez :

1. **Activer** : L'email est envoyé automatiquement
2. **Désactiver** : L'email n'est pas envoyé

{% hint style="tip" %}
**Recommandation** : Gardez au minimum la **confirmation** et le **rappel 24h** activés pour réduire les no-shows.
{% endhint %}

### Configuration recommandée

| Email | Recommandation |
|-------|----------------|
| Confirmation | ✅ Toujours actif |
| Rappel 24h | ✅ Toujours actif |
| Rappel Jour J | ⚡ Optionnel (utile si beaucoup de no-shows) |
| Modification | ✅ Actif |
| Annulation | ✅ Actif |

---

## Contenu des emails

### Email de confirmation

Envoyé immédiatement après une réservation.

**Contenu :**
- Détails du rendez-vous (date, heure, service)
- Informations de la succursale (adresse)
- Véhicule concerné
- **Lien de modification/annulation**
- Coordonnées de contact

### Email de rappel

Envoyé automatiquement selon le délai configuré.

**Contenu :**
- Rappel des détails du RDV
- Adresse de la succursale
- Lien de modification si besoin

### Email de modification

Envoyé quand un rendez-vous est modifié (par vous ou le client).

**Contenu :**
- Ancienne date/heure
- Nouvelle date/heure
- Détails mis à jour

### Email d'annulation

Envoyé quand un rendez-vous est annulé.

**Contenu :**
- Confirmation de l'annulation
- Détails du RDV annulé
- Invitation à reprendre rendez-vous

---

## Expéditeur des emails

### Adresse par défaut

Les emails sont envoyés depuis `noreply@pitstoply.ch` avec le nom de votre garage.

**Exemple :**
```
De: Garage Martin SA <noreply@pitstoply.ch>
```

### Expéditeur personnalisé (Custom Mailer)

{% hint style="info" %}
**Fonctionnalité avancée** : Vous pouvez configurer votre propre serveur SMTP pour envoyer les emails depuis votre domaine (ex: `rdv@garage-martin.ch`).

[Voir configuration Custom Mailer](#) (disponible prochainement)
{% endhint %}

---

## Langue des emails

Les emails sont envoyés dans la langue du garage par défaut.

Si le client a une préférence de langue différente (via son portail), l'email sera envoyé dans sa langue.

---

## Vérifier les emails

### Tester l'envoi

1. Créez un rendez-vous de test avec votre propre email
2. Vérifiez que vous recevez la confirmation
3. Vérifiez le contenu et la mise en forme
4. Supprimez le rendez-vous de test

### Problèmes de réception

Si les emails n'arrivent pas :

1. Vérifiez le dossier spam/indésirables
2. Vérifiez que l'adresse email du client est correcte
3. [Consultez le guide de dépannage](#)

---

## Questions fréquentes

<details>
<summary><strong>Puis-je personnaliser le texte des emails ?</strong></summary>

Actuellement, les templates sont standardisés. Une personnalisation du contenu est prévue dans une future version.

</details>

<details>
<summary><strong>Les emails sont-ils envoyés en HTML ou texte ?</strong></summary>

Les emails sont envoyés en HTML avec une version texte de secours pour les clients email qui ne supportent pas le HTML.

</details>

<details>
<summary><strong>Puis-je voir l'historique des emails envoyés ?</strong></summary>

L'historique détaillé des emails n'est pas disponible actuellement. Vous pouvez voir les SMS envoyés dans **Paramètres > SMS > Historique**.

</details>

<details>
<summary><strong>Que faire si un client dit ne pas recevoir les emails ?</strong></summary>

1. Vérifiez l'adresse email dans sa fiche client
2. Demandez-lui de vérifier ses spams
3. Essayez de renvoyer manuellement si possible
4. En dernier recours, activez les SMS pour ce client

</details>

<details>
<summary><strong>Puis-je envoyer un email manuellement ?</strong></summary>

Actuellement, les emails sont automatiques. Pour un contact manuel, utilisez votre propre messagerie.

</details>
