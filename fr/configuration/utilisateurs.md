# Utilisateurs et accès

Gérez les personnes qui ont accès à votre compte PitStoply et définissez leurs permissions.

## Types d'utilisateurs

| Rôle | Description | Permissions |
|------|-------------|-------------|
| **Propriétaire (Owner)** | Créateur du compte | Accès complet, facturation |
| **Employé (Employee)** | Membre de l'équipe | Accès opérationnel, pas de facturation |

---

## Accéder à la gestion des utilisateurs

1. Allez dans **Paramètres**
2. Cliquez sur **Utilisateurs**

---

## Ajouter un utilisateur

### Inviter un employé

1. Cliquez sur **Ajouter un utilisateur**
2. Remplissez les informations :

| Champ | Description |
|-------|-------------|
| **Nom** | Nom complet de l'employé |
| **Email** | Adresse email (servira d'identifiant) |
| **Rôle** | Employee |

3. Cliquez sur **Inviter**

### Processus d'invitation

1. L'employé reçoit un email d'invitation
2. Il clique sur le lien pour créer son mot de passe
3. Il peut ensuite se connecter à PitStoply

{% hint style="info" %}
L'invitation expire après 7 jours. Vous pouvez la renvoyer si nécessaire.
{% endhint %}

---

## Permissions par rôle

### Propriétaire (Owner)

Accès complet à toutes les fonctionnalités :

| Fonction | Accès |
|----------|-------|
| Dashboard | ✅ |
| Calendrier / RDV | ✅ |
| Clients | ✅ |
| Paramètres | ✅ |
| Facturation / Abonnement | ✅ |
| Gestion des utilisateurs | ✅ |

### Employé (Employee)

Accès opérationnel sans fonctions administratives :

| Fonction | Accès |
|----------|-------|
| Dashboard | ✅ |
| Calendrier / RDV | ✅ |
| Clients | ✅ |
| Paramètres | ⚠️ Limité |
| Facturation / Abonnement | ❌ |
| Gestion des utilisateurs | ❌ |

{% hint style="warning" %}
Un employé ne peut pas voir ni modifier les informations de facturation ou ajouter d'autres utilisateurs.
{% endhint %}

---

## Limites selon le plan

Le nombre d'utilisateurs dépend de votre abonnement :

| Plan | Utilisateurs max |
|------|------------------|
| Independent | 2 |
| Multi-Lift | 5 |
| Network | Illimité |

Pour ajouter plus d'utilisateurs, [mettez à niveau votre plan](../facturation/plans.md).

---

## Gérer les utilisateurs existants

### Modifier un utilisateur

1. Dans la liste des utilisateurs, cliquez sur l'utilisateur
2. Modifiez les informations (nom, email)
3. Enregistrez

### Désactiver un utilisateur

Pour retirer l'accès à un employé :

1. Ouvrez la fiche de l'utilisateur
2. Cliquez sur **Désactiver** ou **Supprimer**
3. Confirmez

{% hint style="info" %}
Un utilisateur désactivé ne peut plus se connecter mais son historique d'actions est conservé.
{% endhint %}

### Renvoyer une invitation

Si un employé n'a pas reçu ou a perdu son invitation :

1. Trouvez l'utilisateur dans la liste
2. Cliquez sur **Renvoyer l'invitation**

---

## Préférences utilisateur

Chaque utilisateur peut personnaliser ses préférences :

### Langue

1. Cliquez sur votre nom/profil
2. Sélectionnez votre **Langue** préférée
3. L'interface s'affiche dans cette langue

### Mot de passe

1. Allez dans votre **Profil**
2. Cliquez sur **Changer le mot de passe**
3. Entrez l'ancien et le nouveau mot de passe

---

## Sécurité

### Bonnes pratiques

| Recommandation | Pourquoi |
|----------------|----------|
| Mots de passe uniques | Évite les compromissions en cascade |
| Email professionnel | Meilleure traçabilité |
| Désactiver les anciens employés | Sécurité des données |

### Que faire si un employé part

1. **Désactivez** immédiatement son compte
2. Vérifiez qu'il n'a pas de sessions actives
3. Changez les mots de passe partagés (si applicable)

---

## Questions fréquentes

<details>
<summary><strong>Puis-je avoir plusieurs propriétaires ?</strong></summary>

Non, il n'y a qu'un seul propriétaire par compte. Vous pouvez donner des accès étendus aux employés mais ils n'auront pas accès à la facturation.

</details>

<details>
<summary><strong>Un employé peut-il voir les revenus/statistiques ?</strong></summary>

Oui, le dashboard avec les KPIs est visible par les employés. Seule la facturation (abonnement, paiements) est masquée.

</details>

<details>
<summary><strong>Comment transférer la propriété du compte ?</strong></summary>

Le transfert de propriété nécessite de contacter le support à support@pitstoply.ch.

</details>

<details>
<summary><strong>Les utilisateurs peuvent-ils avoir des accès différents par succursale ?</strong></summary>

Actuellement, tous les utilisateurs ont accès à toutes les succursales. Une gestion fine des permissions par succursale est prévue.

</details>
