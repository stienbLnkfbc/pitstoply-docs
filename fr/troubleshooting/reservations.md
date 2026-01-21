# Problèmes de réservation

Solutions aux problèmes courants liés aux réservations et au calendrier.

***

## Aucun créneau disponible

### Le client ne voit aucun créneau

**Causes possibles :**

| Cause                   | Solution                                                                       |
| ----------------------- | ------------------------------------------------------------------------------ |
| Horaires non configurés | Vérifiez **Paramètres > Horaires**                                             |
| Horaires -> Jour fermé  | Vérifiez que le jour ou le lift n'est pas marqué comme fermé dans les horaires |
| Blocage actif           | Vérifiez **Paramètres > Fermetures**                                           |
| Tous les lifts occupés  | Les créneaux sont réellement complets                                          |
| Calendrier externe      | Un événement externe bloque le créneau                                         |

### Vérifications à faire

1. **Horaires configurés ?**
   * Allez dans **Paramètres > Horaires**
   * Vérifiez que le jour concerné a des heures d'ouverture
2. **Blocages actifs ?**
   * Allez dans **Paramètres > Fermetures**
   * Vérifiez qu'il n'y a pas de blocage sur cette période
3. **Calendrier externe ?**
   * Si vous avez synchronisé un calendrier externe
   * Vérifiez qu'un événement ne bloque pas le créneau
4. **Tous les lifts ?**
   * Vérifiez que vous avez au moins un lift actif
   * Vérifiez les horaires spécifiques de chaque lift

***

## Le créneau a disparu

### Un créneau était disponible, il ne l'est plus

**Causes possibles :**

1. **Quelqu'un d'autre a réservé** : Premier arrivé, premier servi
2. **Vous avez créé un RDV** : Le créneau est maintenant occupé
3. **Calendrier externe mis à jour** : Un nouvel événement bloque
4. **Blocage ajouté** : Un blocage manuel a été créé

### Solution

Consultez le calendrier à cette date pour voir ce qui occupe le créneau.

***

## Impossible de créer un rendez-vous

### Message d'erreur lors de la création

**Erreurs courantes :**

| Message                  | Cause                             | Solution                        |
| ------------------------ | --------------------------------- | ------------------------------- |
| "Créneau non disponible" | Déjà réservé                      | Choisissez un autre créneau     |
| "Client requis"          | Pas de client sélectionné         | Sélectionnez ou créez un client |
| "Véhicule requis"        | Pas de véhicule                   | Ajoutez un véhicule au client   |
| "Hors horaires"          | Créneau hors horaires d'ouverture | Vérifiez les horaires           |

### Le formulaire ne se charge pas

1. Rafraîchissez la page (F5)
2. Videz le cache du navigateur
3. Essayez un autre navigateur
4. Vérifiez votre connexion internet

***

## Rendez-vous non visible dans le calendrier

### Le RDV a été créé mais n'apparaît pas

**Vérifications :**

1. **Bonne date ?** Naviguez vers la date du RDV
2. **Bonne succursale ?** Sélectionnez la bonne succursale dans le filtre
3. **Bon lift ?** Le RDV est peut-être sur un autre lift
4. **Statut ?** Un RDV annulé peut être masqué

### Utiliser la recherche

1. Utilisez la recherche globale (`Ctrl+K`)
2. Tapez le nom du client ou la plaque
3. Cliquez sur le RDV pour y accéder directement

***

## Le client ne peut pas modifier son RDV

### Le lien de modification ne fonctionne pas

**Causes possibles :**

1. **Lien expiré** : Les liens ont une durée de validité limitée
2. **RDV déjà passé** : On ne peut pas modifier un RDV passé
3. **RDV annulé** : Le RDV a peut-être été annulé
4. Délais modifiable dépassé : Le RDV est trop proche dans le temps (paramètre généraux -> général)

### Solutions

1. Renvoyez un email de confirmation avec un nouveau lien
2. Modifiez le RDV vous-même depuis le dashboard
3. Créez un nouveau RDV si nécessaire

***

## Conflit de rendez-vous

### Deux RDV au même moment sur le même lift

Cela ne devrait pas arriver car PitStoply vérifie les conflits. Si cela se produit :

1. **Vérifiez les heures exactes** : Peut-être que les RDV ne se chevauchent pas réellement
2. **Déplacez un RDV** : Modifiez l'un des deux pour résoudre le conflit
3. **Contactez le support** si le problème persiste

***

## Notifications non envoyées

### Le client n'a pas reçu de confirmation

1. Vérifiez que les notifications sont **activées** dans les paramètres
2. Vérifiez l'**adresse email du client** (pas de faute)
3. Demandez au client de vérifier ses **spams**
4. Pour les SMS, vérifiez votre **solde de crédits**

[Voir le guide de dépannage SMS](sms.md)

***

## Problèmes avec la page de réservation publique

### La page ne se charge pas

1. Vérifiez l'URL : `pitstoply.ch/votre-slug`
2. Vérifiez que le slug est correct dans vos paramètres
3. Essayez de vider le cache du navigateur

### La page est vide (aucun service/créneau)

1. Vérifiez qu'au moins un **service est actif**
2. Vérifiez qu'au moins un **lift est actif**
3. Vérifiez les **horaires** de la succursale/lift

***

## Performance lente

### Le calendrier ou les créneaux chargent lentement

**Solutions :**

1. Patientez quelques secondes (normal pour beaucoup de données)
2. Rafraîchissez la page
3. Évitez d'ouvrir plusieurs onglets PitStoply
4. Vérifiez votre connexion internet

{% hint style="info" %}
Si les problèmes de performance persistent, contactez le support avec des détails sur votre situation (nombre de RDV, navigateur utilisé).
{% endhint %}

***

## Contact support

Si aucune solution ne fonctionne :

* **Email** : support@pitstoply.ch
* Incluez :
  * Description du problème
  * Date et heure concernées
  * Captures d'écran si possible
  * Navigateur et appareil utilisés
