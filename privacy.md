# Politique de confidentialité

**Application Fabuline**

**Version 1.0.0 — date de prise d'effet : à la date de mise en ligne sur l'App Store et Google Play**

---

## 1. Préambule

La présente politique de confidentialité décrit la manière dont **La Fabrique du Numérique** (ci-après « **Fabuline** » ou l'« **Éditeur** ») collecte, utilise, conserve et protège vos données personnelles dans le cadre de l'utilisation de l'application mobile **Fabuline** (ci-après l'« **Application** »).

Elle est rédigée en application du Règlement (UE) 2016/679 du 27 avril 2016 dit « **RGPD** » et de la loi n° 78-17 du 6 janvier 1978 modifiée dite « Informatique et Libertés ».

> **Important — voix biométrique** : la voix que vous enregistrez dans l'Application constitue une **donnée biométrique** au sens de l'article 9 du RGPD (dite « catégorie particulière »). Elle ne peut être traitée qu'avec votre **consentement explicite**, recueilli au moment de chaque enregistrement.

## 2. Responsable de traitement

**La Fabrique du Numérique**, société par actions simplifiée unipersonnelle, RCS **Paris 105 777 544**, siège social **61 rue de Lyon, 75012 Paris, France**, représentée par son Président **Julien Tran**.

**Contact RGPD** : **contact@fabuline.fr** (un délégué à la protection des données pourra être désigné dès que les seuils légaux ou stratégiques le justifieront).

## 3. Données collectées et finalités

| Catégorie | Données concernées | Finalité | Base légale | Durée de conservation |
|---|---|---|---|---|
| Compte | email, mot de passe haché (ou identifiant Apple/Google si OAuth) | Authentification, gestion du Compte | Exécution du contrat (CGU) | Durée du Compte + 30 jours après suppression |
| Profil enfant | prénom, tranche d'âge | Personnalisation du prénom dans l'histoire, adaptation du contenu | Exécution du contrat | Durée du Compte + 30 jours |
| **Voix de référence (biométrique Art. 9)** | enregistrement audio (WAV) | Clonage vocal pour la génération d'histoires personnalisées | **Consentement explicite** (Art. 9 §2 a) RGPD) | Durée du Compte + 30 jours, ou jusqu'au retrait du consentement |
| Texte de consentement biométrique | version + horodatage du consentement | Preuve du consentement explicite | Obligation légale (RGPD Art. 7 §1) | 5 ans après suppression du Compte |
| Histoires générées | fichiers audio résultants, métadonnées (œuvre, voix, enfant, date) | Mise à disposition des histoires personnalisées dans la bibliothèque | Exécution du contrat | Durée du Compte + 30 jours |
| Solde et historique des crédits | nombre de crédits, transactions de débit/crédit | Suivi de la consommation, support, comptabilité | Exécution du contrat / Obligations comptables | 10 ans (durée légale comptable) |
| Données techniques | logs d'erreurs, métriques anonymisées (temps de réponse) | Amélioration et sécurité du service | Intérêt légitime | 13 mois maximum |
| Achats intégrés | identifiant de transaction Apple/Google | Validation des achats, lutte contre la fraude | Exécution du contrat / Obligations comptables | 10 ans |

> **Aucune donnée d'identification précise de l'enfant** (nom de famille, date de naissance, photo, géolocalisation) n'est collectée. L'Application est conçue selon le principe de **minimisation** : seules les données strictement nécessaires sont traitées.

## 4. Sous-traitants et destinataires des données

L'Éditeur fait appel à des prestataires techniques agissant en qualité de sous-traitants au sens de l'article 28 du RGPD :

| Sous-traitant | Service rendu | Localisation | Catégories de données |
|---|---|---|---|
| **Supabase Inc.** | Authentification, base de données Postgres, fonctions serverless | Région UE (Frankfurt) | Compte, profils enfants, métadonnées voix, histoires générées, crédits |
| **Cloudflare R2** | Stockage des fichiers audio (voix de référence + histoires générées) | Juridiction UE (Frankfurt) | Enregistrements audio biométriques, audio générés |
| **Mistral AI** (société française) | Modèle de clonage vocal et génération de la parole | UE (France) | Voix de référence (transit uniquement, non stockée durablement chez Mistral — décision Sprint 1.5) |
| **RevenueCat Inc.** *(à activer en Sprint 3)* | Gestion des abonnements et achats intégrés | États-Unis | Identifiants d'achat, état d'abonnement |
| **Apple Inc. / Google LLC** | Magasins d'applications, paiements intégrés, services d'authentification (Sign in with Apple / Sign in with Google) | États-Unis | Identifiant de compte plateforme, transactions |

L'Éditeur communique cette répartition en toute transparence : si l'**hébergement principal des données est en Union européenne** (Supabase EU, Cloudflare EU, Mistral France), les services de paiement et de plateforme (Apple, Google, RevenueCat) impliquent par nature un traitement aux États-Unis. À ce titre, l'Éditeur s'appuie sur les **clauses contractuelles types (CCT)** approuvées par la Commission européenne et sur l'éventuelle adhésion de ces sous-traitants au cadre de protection des données UE-États-Unis (« EU-U.S. Data Privacy Framework »).

L'Éditeur ne vend ni ne loue aucune donnée personnelle à des tiers à des fins commerciales.

## 5. Localisation des données

Les données vivent par défaut **en Union européenne** :

- Authentification + base de données : Supabase, région Frankfurt (Allemagne)
- Fichiers audio : Cloudflare R2, juridiction EU (Frankfurt)
- Inférence IA vocale : Mistral AI, France

Les transferts hors UE sont limités aux fonctions de paiement et de plateforme (Apple, Google, RevenueCat — États-Unis), encadrés par les CCT et/ou le DPF.

## 6. Durées de conservation

Les durées détaillées par catégorie figurent au tableau de l'article 3.

À la **suppression du Compte** :

- toutes les données personnelles courantes (email, profils enfants, voix de référence, histoires générées) sont supprimées dans un délai maximum de **30 jours** ;
- la trace du **consentement biométrique** (texte + horodatage, sans la voix elle-même) est conservée 5 ans à des fins probatoires (RGPD Art. 7 §1) ;
- les **données comptables** (transactions, factures) sont conservées 10 ans (Code de commerce Art. L.123-22).

Le délai de 30 jours permet à l'Utilisateur de revenir sur sa décision et de récupérer ses données par contact email.

## 7. Sécurité

L'Éditeur met en œuvre des mesures techniques et organisationnelles appropriées :

- **Chiffrement en transit** : HTTPS/TLS 1.2+ pour tous les échanges client-serveur, signatures AWS V4 pour le stockage R2.
- **Chiffrement au repos** : disques chiffrés côté Supabase (AES-256) et Cloudflare R2.
- **Cloisonnement par utilisateur** : Row Level Security (RLS) côté Postgres + préfixes utilisateur côté stockage (`voices/<user_id>/...`, `generated/<user_id>/...`) — un Utilisateur A ne peut techniquement pas lire les données de l'Utilisateur B.
- **Authentification** : mots de passe hachés (bcrypt/argon), JWT à durée limitée, support de Sign in with Apple et Sign in with Google.
- **Accès interne restreint** : seuls les membres autorisés de l'équipe peuvent accéder à l'infrastructure de production, sous obligation de confidentialité contractuelle. Les accès aux données biométriques sont tracés.
- **Audit** : enregistrement des accès sensibles (table `audit_log`).
- **Secrets** : aucune clé API (Mistral, Cloudflare, Supabase service role) n'est intégrée au code de l'Application. Les opérations sensibles passent par des fonctions serveur authentifiées (Supabase Edge Functions) avec vérification d'identité de l'Utilisateur.

En cas de **violation de données** susceptible d'engendrer un risque pour les droits et libertés des personnes, l'Éditeur notifiera la **CNIL dans un délai de 72 heures** (Art. 33 RGPD) et informera les Utilisateurs concernés sans délai indu (Art. 34 RGPD).

## 8. Droits des Utilisateurs

Conformément au RGPD, vous disposez à tout moment des droits suivants :

- **Droit d'accès** (Art. 15) : obtenir la confirmation que des données vous concernant sont traitées et obtenir une copie de ces données.
- **Droit de rectification** (Art. 16) : demander la correction de données inexactes.
- **Droit à l'effacement / « droit à l'oubli »** (Art. 17) : demander la suppression de vos données. Cette demande est satisfaite via la fonction « Supprimer mon compte » de l'Application, ou par email.
- **Droit à la limitation du traitement** (Art. 18).
- **Droit d'opposition** (Art. 21) : pour les traitements fondés sur l'intérêt légitime.
- **Droit à la portabilité** (Art. 20) : recevoir vos données dans un format structuré et lisible par machine. L'Application propose un export ZIP de l'ensemble de vos voix de référence, histoires générées et métadonnées de Compte, accessible depuis la rubrique « Profil → Exporter mes données ».
- **Droit de retrait du consentement** (Art. 7 §3) à tout moment, sans affecter la licéité des traitements antérieurs. Le retrait du consentement biométrique entraîne la suppression de la Voix de référence concernée et l'impossibilité de générer de nouvelles histoires avec cette voix.
- **Droit de définir des directives sur le sort de vos données après votre décès** (Loi Informatique et Libertés, Art. 85).

### Modalités d'exercice

Pour exercer vos droits, contactez :

- Email : **contact@fabuline.fr**
- Courrier : **La Fabrique du Numérique, 61 rue de Lyon, 75012 Paris, France**

L'Éditeur répondra dans un délai d'**un mois** maximum, prolongeable de deux mois en cas de demande complexe.

### Réclamation auprès de la CNIL

En cas de désaccord avec les réponses apportées, vous pouvez introduire une réclamation auprès de la Commission nationale de l'informatique et des libertés (CNIL) — 3 place de Fontenoy, TSA 80715, 75334 Paris CEDEX 07 — <https://www.cnil.fr/fr/plaintes>.

## 9. Cookies, traceurs et SDK

L'Application est une application mobile native qui n'utilise **pas de cookies** au sens de la directive ePrivacy.

Les **SDK tiers** intégrés se limitent aux strict minimum nécessaires au fonctionnement (Supabase pour l'authentification, RevenueCat pour les achats à partir du Sprint 3, Apple/Google pour les magasins). Aucun SDK publicitaire ni de mesure d'audience tierce (Google Analytics, Facebook SDK, etc.) n'est intégré.

## 10. Profilage et décisions automatisées

L'Éditeur ne procède à **aucune décision automatisée** au sens de l'article 22 du RGPD ayant un effet juridique ou affectant de manière significative l'Utilisateur. Le clonage vocal et la génération d'histoire constituent un traitement automatisé au sens technique mais ne produisent aucune décision sur la personne.

## 11. Mineurs

L'Application est destinée à un usage **par des adultes**, avec des contenus à destination de leurs enfants. Le Compte est obligatoirement détenu par un majeur (cf. CGU Art. 3). Les profils enfants associés ne contiennent que le prénom et la tranche d'âge, sans aucune autre donnée d'identification.

L'usage par un mineur de l'Application sans autorisation parentale est interdit. Si l'Éditeur a connaissance qu'un Compte a été créé par un mineur sans cette autorisation, il procédera à la suppression du Compte concerné.

## 12. Modifications de la présente politique

La présente politique peut être amenée à évoluer (nouvelles fonctionnalités, évolution réglementaire, ajout/retrait de sous-traitants). Toute modification substantielle fait l'objet d'une notification dans l'Application et/ou par email, avec un préavis de 15 jours minimum lorsque cela est légalement requis.

L'historique des versions est conservé et consultable sur demande.

## 13. Contact

Pour toute question relative à la présente politique :

- Email : **contact@fabuline.fr**
- Courrier : **La Fabrique du Numérique, 61 rue de Lyon, 75012 Paris, France**
