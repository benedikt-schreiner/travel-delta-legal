---
layout: default
title: Politique de confidentialité — Travel Delta
lang: fr
---

[Deutsch](de.html) · [English](en.html) · [Français](fr.html) · [Español](es.html) · [Italiano](it.html) · [Português](pt.html)

# Politique de confidentialité

## 1. Responsable du traitement

Benedikt Schreiner
Industriestraße 65
46414 Rhede, Allemagne
E-mail : support@schreiner-apps.de

## 2. Principe : traitement minimal des données

Travel Delta ne nécessite pas de compte utilisateur et ne traite aucune donnée personnelle telle que le nom, l'adresse e-mail ou la localisation. L'application est conçue pour fonctionner avec une collecte de données minimale.

## 3. Données stockées localement

Les données suivantes sont stockées exclusivement sur votre appareil (SharedPreferences) et ne sont pas transmises à des tiers :

- Pays sélectionnés (pays d'origine et destination)
- Itinéraires enregistrés
- Préférences (langue, apparence)
- Données de voyage en cache (taux de change, conditions d'entrée, numéros d'urgence)

Ces données restent entièrement sur votre appareil et peuvent être supprimées à tout moment en désinstallant l'application.

## 4. Services externes et requêtes réseau

Les services externes suivants sont utilisés pour faire fonctionner l'application :

**Supabase** (Supabase Inc., San Francisco, États-Unis)
Charge les données de voyage telles que les conditions d'entrée, les numéros d'urgence et les informations d'itinérance. Seuls des codes pays sont transmis (ex. : « DE », « US »). Aucune donnée personnelle n'est transférée. Les données sont mises en cache localement pendant 24 heures maximum. Plus d'infos : [supabase.com/privacy](https://supabase.com/privacy)

**Supabase – Fonction de parrainage (« inviter un ami »)**
Pour attribuer les codes de parrainage, un identifiant d'appareil anonyme généré aléatoirement est envoyé à Supabase. Cet identifiant n'est lié ni à votre nom, ni à votre adresse e-mail, ni à aucune autre donnée personnelle. Vous pouvez le supprimer vous-même à tout moment (voir section 8) ; il est de toute façon supprimé automatiquement au plus tard après 180 jours.

**Supabase – Creator Partner Program (attribution)**
Si vous installez Travel Delta via un lien de suivi partagé par un créateur de contenu, l'application signale l'installation — puis, plus tard, un achat premium finalisé — à un second projet Supabase distinct que nous exploitons, afin de pouvoir créditer ce créateur d'une commission. Cela utilise : un hachage cryptographique à sens unique de l'identifiant d'appareil décrit ci-dessus (il ne peut pas être retracé jusqu'à cet identifiant) ; sur Android, la chaîne d'origine d'installation fournie par Google Play ; sur iOS, un code de courte durée que le lien de suivi place brièvement dans votre presse-papiers avant l'installation et que l'application lit une seule fois après celle-ci (cela peut déclencher la notification système iOS « Collé depuis Safari » — c'est un comportement attendu, pas une erreur). Pour un achat finalisé, nous envoyons également le produit, le prix, la devise et l'identifiant de transaction du magasin. Ni votre nom, ni votre adresse e-mail, ni votre localisation précise ne sont transmis. Si vous n'avez pas installé l'application via un lien de créateur, cette vérification a tout de même lieu, sans qu'aucune attribution ne soit faite.

**frankfurter.app** (API publique de taux de change)
Récupère les taux de change. Seuls des codes de devise sont transmis (ex. : « EUR », « USD »). Aucune donnée personnelle. Les taux sont mis en cache localement pendant 4 heures maximum.

**Apple App Store / Google Play Store**
Pour les achats Premium, Apple ou Google gèrent le traitement des paiements selon leurs propres politiques de confidentialité. Travel Delta reçoit uniquement une confirmation anonymisée du statut d'achat.

## 5. Base juridique

Le traitement est fondé sur l'art. 6(1)(b) RGPD (exécution du contrat, lorsqu'une fonctionnalité Premium est utilisée), l'art. 6(1)(f) RGPD (intérêt légitime à exploiter l'application) et l'art. 6(1)(a) RGPD (consentement, si requis).

## 6. Traçage limité pour l'attribution aux créateurs

Travel Delta n'utilise aucun SDK d'analyse, de traçage ou de publicité tiers, et ne constitue aucun profil publicitaire. Le seul mécanisme apparenté au traçage est l'attribution interne du Creator Partner Program décrite à la section 4, dont le seul but est de créditer les créateurs pour les installations et achats provenant de leurs propres liens de suivi.

## 7. Transferts internationaux de données

Supabase peut traiter des données sur des serveurs aux États-Unis — cela vaut aussi bien pour notre projet principal que pour le projet distinct du Creator Partner Program décrit à la section 4. Supabase Inc. est certifiée dans le cadre du Data Privacy Framework UE–États-Unis. Seuls des codes pays non personnels et les données d'attribution décrites à la section 4 sont transmis.

## 8. Vos droits (Art. 15–22 RGPD)

Vous avez le droit :

- D'accéder à vos données stockées (Art. 15)
- De rectifier des données inexactes (Art. 16)
- D'obtenir l'effacement de vos données (Art. 17)
- De limiter le traitement (Art. 18)
- À la portabilité des données (Art. 20)
- De vous opposer au traitement (Art. 21)

Vous pouvez supprimer vos données de parrainage (voir section 4) directement dans l'application : Réglages → À propos → « Supprimer mes données ». Les données de parrainage que vous ne supprimez pas vous-même sont automatiquement supprimées au plus tard après 180 jours.

Les données d'attribution du Creator Partner Program (section 4) ne sont pas couvertes par l'outil de suppression ci-dessus ; contactez support@schreiner-apps.de pour en demander l'effacement.

Pour exercer vos autres droits, contactez : support@schreiner-apps.de

Vous avez également le droit d'introduire une réclamation auprès d'une autorité de contrôle de la protection des données.

---

Mise à jour : septembre 2026
