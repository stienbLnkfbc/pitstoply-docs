# Problèmes de paiement

Solutions aux problèmes courants liés à l'abonnement et aux paiements.

---

## Paiement refusé

### Ma carte a été refusée

**Causes courantes :**

| Cause | Solution |
|-------|----------|
| Fonds insuffisants | Vérifiez le solde de votre compte |
| Carte expirée | Mettez à jour la carte dans le portail Stripe |
| Limite de paiement | Contactez votre banque |
| Paiement en ligne bloqué | Activez les paiements en ligne auprès de votre banque |
| 3D Secure échoué | Réessayez et validez l'authentification |

### Comment réessayer

1. Allez dans **Facturation > Gérer l'abonnement**
2. Accédez au portail Stripe
3. Mettez à jour votre moyen de paiement
4. Réessayez le paiement

---

## Carte expirée

### Mon abonnement a été suspendu

**Ce qui se passe :**
1. Stripe tente de prélever avec la carte enregistrée
2. Le paiement échoue (carte expirée)
3. Stripe réessaie automatiquement plusieurs fois
4. Après plusieurs échecs, l'abonnement est suspendu

### Solution

1. Accédez au **portail Stripe** (via Facturation)
2. Ajoutez une nouvelle carte valide
3. Stripe réessaiera automatiquement
4. Ou cliquez sur **Payer maintenant** si disponible

---

## Je ne trouve pas mes factures

### Où sont mes factures ?

1. Allez dans **Facturation**
2. Cliquez sur **Gérer l'abonnement**
3. Dans le portail Stripe, section **Historique des factures**
4. Téléchargez les factures en PDF

### Facture pour la comptabilité

Les factures Stripe incluent :
- Numéro de facture
- Détail de la prestation
- Montant HT et TVA
- Vos coordonnées et celles de PitStoply

---

## Prélèvement inattendu

### J'ai été prélevé alors que je pensais avoir annulé

**Vérifications :**

1. **Annulation effective ?** Vérifiez dans Facturation que l'abonnement est bien annulé
2. **Date d'effet ?** L'annulation prend effet à la fin de la période payée
3. **Crédits SMS ?** Un prélèvement peut être pour un achat de crédits SMS

### Contestation

Si vous pensez qu'un prélèvement est injustifié :
1. Contactez support@pitstoply.ch avec les détails
2. Ne faites pas d'opposition bancaire directement (cela peut bloquer votre compte)

---

## Changement de plan non effectif

### J'ai changé de plan mais rien n'a changé

**Pour un upgrade (plan supérieur) :**
- L'effet est **immédiat**
- Rafraîchissez la page
- Déconnectez-vous et reconnectez-vous

**Pour un downgrade (plan inférieur) :**
- L'effet est **différé** à la fin de la période en cours
- Vous gardez les fonctionnalités actuelles jusqu'à l'échéance

---

## Période d'essai terminée

### Je n'ai plus accès après l'essai

**Ce qui se passe :**
- La période d'essai est terminée
- Aucune carte n'était enregistrée
- L'accès est restreint

**Solution :**
1. Connectez-vous à PitStoply
2. Allez dans **Facturation**
3. Choisissez un plan
4. Entrez vos informations de paiement
5. Votre accès est rétabli

---

## Remboursement

### Puis-je être remboursé ?

**Politique générale :**
- Les abonnements annuels ne sont généralement pas remboursables
- Les crédits SMS ne sont pas remboursables

**Exceptions possibles :**
- Problème technique majeur de notre côté
- Double facturation par erreur
- Cas exceptionnels étudiés au cas par cas

**Demander un remboursement :**
1. Contactez support@pitstoply.ch
2. Expliquez votre situation
3. Joignez les factures concernées

---

## TVA et facturation

### Questions fréquentes

<details>
<summary><strong>La TVA est-elle incluse dans les prix ?</strong></summary>

Oui, les prix affichés incluent la TVA suisse (7.7%). Le détail apparaît sur les factures.

</details>

<details>
<summary><strong>Puis-je avoir une facture avec mon numéro de TVA ?</strong></summary>

Vos informations de facturation peuvent être mises à jour dans le portail Stripe. Ajoutez votre numéro IDE/TVA dans les paramètres de facturation.

</details>

<details>
<summary><strong>Puis-je payer par virement bancaire ?</strong></summary>

Le paiement par carte est standard. Pour les grands comptes (plan Network), des arrangements peuvent être discutés. Contactez-nous.

</details>

---

## Accès restreint

### Message "Abonnement expiré"

**Causes :**
1. Paiement échoué non résolu
2. Abonnement annulé et période terminée
3. Période d'essai terminée sans paiement

**Solution :**
1. Connectez-vous
2. Allez dans **Facturation**
3. Régularisez votre situation (paiement ou nouveau plan)

### Ce que vous pouvez encore faire

En mode restreint :
- ✅ Voir vos données (lecture seule)
- ❌ Créer de nouveaux rendez-vous
- ❌ Modifier les paramètres

---

## Sécurité des paiements

### Mes données de carte sont-elles sécurisées ?

**Oui.** PitStoply utilise **Stripe** pour tous les paiements :

| Aspect | Protection |
|--------|------------|
| Stockage carte | Stripe (pas PitStoply) |
| Transmission | Chiffrée (HTTPS/TLS) |
| Conformité | PCI-DSS Level 1 |
| Authentification | 3D Secure supporté |

PitStoply ne voit jamais votre numéro de carte complet.

---

## Contact support

Pour les problèmes de paiement :

- **Email** : support@pitstoply.ch
- **Informations à fournir** :
  - Nom du garage
  - Email du compte
  - Date du problème
  - Montant concerné (si applicable)
  - Capture d'écran de l'erreur
