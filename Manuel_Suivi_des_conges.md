# REGISTRE PERSONNEL — Suivi des congés

## Manuel d'utilisation

Un guide pas à pas pour suivre vos CP, CAS, RTT1 et RTT2 : cocher vos jours dans le calendrier, lire vos soldes, ajuster vos paramètres et synchroniser vos données entre appareils.

**Catégories :** CP — congés payés · CAS — congés ancienneté · RTT1 · RTT2 · Arrêt maladie · Récupération

Application locale, gratuite, sans installation — fonctionne dans tout navigateur (ordinateur, iPhone, Android).

---

## Sommaire

01. Vue d'ensemble de l'application — p. 3
02. Le tableau des soldes — p. 4
03. Le calendrier — p. 5
04. Modifier un jour — p. 6
05. Sélectionner plusieurs jours — p. 7
06. Paramètres et corrections manuelles — p. 8
07. Thème clair / sombre — p. 9
08. Synchroniser vos appareils avec Supabase — p. 10
09. Sauvegarde locale (fichier JSON) — p. 11
10. Sur iPhone et mobile — p. 12
11. Questions fréquentes — p. 13

> **À savoir avant de commencer**
> L'application ne nécessite ni compte ni installation : c'est un simple fichier `suivi_conges.html` à ouvrir dans votre navigateur. Vos données sont enregistrées automatiquement dans ce navigateur (aucune saisie n'est jamais perdue en fermant la page).

---

## 01 — Prise en main

### 01 Vue d'ensemble

L'écran principal réunit tout ce dont vous avez besoin : le sélecteur d'année, le tableau de vos soldes, et le calendrier de l'année complète.

**Les trois zones de l'écran**

- **En haut** — le titre, le sélecteur d'année (‹ / ›) et la barre d'outils (thème, paramètres, Supabase).
- **Au milieu** — le tableau « Attribution & solde », qui résume vos droits à congés pour l'année affichée.
- **En bas** — le calendrier des 12 mois de l'année, où vous cochez vos jours d'absence.

> **Astuce**
> Changez d'année avec les flèches ‹ › à tout moment : le tableau des soldes et le calendrier se mettent à jour ensemble.

---

## 02 — Vos droits à congés

### 02 Le tableau des soldes

Ce tableau répond à la question « combien de jours me reste-t-il ? » pour chacune de vos quatre catégories de congés.

**Les quatre catégories**

- **CP** — Congés payés. Période du 1ᵉʳ juin au 31 mai. Ne se reporte pas d'une année sur l'autre.
- **CAS** — Congés d'ancienneté. Même période que le CP, mais le solde se reporte chaque année.
- **RTT1** — Année civile (1ᵉʳ janv. – 31 déc.), non reportable.
- **RTT2** — Année civile (1ᵉʳ janv. – 31 déc.), non reportable.

**Lire les colonnes**

- **Attribution** — le nombre de jours accordés pour la période.
- **Reporté N-1** — le solde ramené de la période précédente (uniquement pour le CAS).
- **Pris** — le nombre de jours déjà cochés dans le calendrier pour cette période.
- **Solde** — ce qu'il vous reste : Attribution + Reporté − Pris.

En dessous du tableau, deux compteurs informatifs affichent vos **arrêts maladie** et vos **jours de récupération** de l'année (ils n'affectent aucun solde). Le badge en haut à droite indique le **total de jours de congés pris** tous types confondus.

> **Point important**
> Un jour de CP coché en janvier compte sur la période qui se termine cette année-là (1ᵉʳ juin de l'année précédente → 31 mai de l'année en cours) — la période exacte est toujours rappelée sous chaque poste.

---

## 03 — Saisie des congés

### 03 Le calendrier

Les 12 mois de l'année sont toujours affichés. Chaque case représente un jour, divisée en deux moitiés : le matin et l'après-midi.

**Comment lire une case**

- Le **numéro du jour** apparaît en haut à gauche.
- Un **liseret fin gris** délimite les jours ouvrés cliquables ; week-ends et jours fériés sont grisés et non modifiables.
- Le **jour en cours** est entouré d'un contour ambré épais.
- Un **liseret orange continu** (week-ends compris) signale les **vacances scolaires zone B** — Toussaint, Noël, Hiver, Printemps, Été, académie d'Orléans-Tours, dates officielles 2020-2027.
- Quand un jour est coché, la catégorie s'affiche **en toutes lettres** (CP, RTT1…) dans une pastille colorée — jamais juste une couleur, pour rester lisible.

> **Astuce**
> Le vendredi de l'Ascension est traité comme un jour férié. Le liseret orange s'arrête en mai 2027, faute de calendrier scolaire 2027-2028 publié par le ministère.

---

## 04 — Saisie d'un jour

### 04 Modifier un jour

Un clic sur un jour ouvré ouvre une fenêtre pour choisir séparément la catégorie du matin et de l'après-midi.

**Marche à suivre**

1. Cliquez sur le jour à modifier dans le calendrier.
2. Choisissez la catégorie du **matin** (CP, CAS, RTT1, RTT2, Maladie, Récup, ou « — » pour vide).
3. Choisissez la catégorie de l'**après-midi** de la même façon.
4. Cliquez sur **Fermer** — l'enregistrement est automatique, aucune validation supplémentaire n'est nécessaire.

Pour une journée complète dans la même catégorie, sélectionnez simplement la même option pour le matin et l'après-midi.

---

## 05 — Gain de temps

### 05 Sélectionner plusieurs jours

Pour poser une semaine de congés d'un coup, inutile de cliquer jour par jour : sélectionnez une plage ou plusieurs jours séparés.

**Deux façons de sélectionner**

- **Maj + clic** — sélectionne toute la période entre le dernier jour cliqué et celui-ci (idéal pour une semaine de vacances).
- **Ctrl (ou Cmd sur Mac) + clic** — ajoute ou retire des jours isolés à la sélection, un par un.

**Appliquer une catégorie à la sélection**

1. Choisissez la portée : **Journée entière**, **Matin** seul, ou **Après-midi** seul.
2. Cliquez sur la catégorie à appliquer (CP, RTT1…) — elle s'applique instantanément à tous les jours sélectionnés.
3. Cliquez sur **✕ Fermer**, ou cliquez n'importe où en dehors du calendrier, pour annuler une sélection en cours.

---

## 06 — Personnalisation

### 06 Paramètres et corrections manuelles

Le bouton **⚙ Paramètres** permet de choisir les catégories que vous utilisez réellement, d'ajuster vos droits, et de corriger un solde si besoin.

**Adapter l'app à votre situation**

Toutes les entreprises n'ont pas de CAS ni deux types de RTT. En haut du panneau, décochez ce que vous n'utilisez pas : CP (toujours actif), CAS, RTT1, RTT2.

Une catégorie décochée disparaît du tableau des soldes, de la légende, du calendrier de saisie et des colonnes d'attribution — **sans jamais supprimer** les jours déjà enregistrés dans cette catégorie. Vous pouvez la réactiver à tout moment pour la retrouver.

**Ce que vous pouvez régler**

- **Attribution** — le nombre de jours accordés pour chaque catégorie active, si votre situation diffère des valeurs par défaut (25 / 8 / 7 / 8 jours).
- **Solde reporté CAS** — normalement calculé automatiquement (étiquette « AUTO »). Vous pouvez le corriger à la main — par exemple après un ajustement de votre service RH — l'étiquette passe alors à « corrigé manuellement ». Le bouton **↺ Auto** annule la correction.

> **Astuce**
> Une correction du solde reporté ne s'applique qu'à l'année affichée : les années suivantes recalculent automatiquement à partir de cette correction.

Le bouton **↺ Recharger les données d'origine** réinitialise le calendrier et les paramètres à leur état initial. À utiliser avec précaution : toutes vos modifications manuelles seront perdues.

---

## 07 — Confort visuel

### 07 Thème clair / sombre

Le bouton 🌙 / ☀️ dans la barre d'outils bascule l'application entre thème clair et thème sombre, à tout moment.

Votre préférence est mémorisée dans le navigateur : elle sera conservée à la prochaine ouverture de l'application, même après avoir fermé l'onglet.

---

## 08 — Multi-appareils

### 08 Synchroniser vos appareils avec Supabase

Par défaut, vos données restent dans le navigateur où vous les avez saisies. Pour les retrouver sur plusieurs appareils (ordinateur ET iPhone, par exemple), connectez un projet Supabase gratuit.

**Configuration, étape par étape**

1. Créez un compte gratuit sur **supabase.com** et un nouveau projet.
2. Dans l'app, ouvrez **☁ Supabase**, dépliez « Configuration requise côté Supabase », et exécutez une fois le SQL ci-dessous dans l'éditeur SQL de votre projet (menu *SQL Editor*) — un bouton **📋 Copier le SQL** le copie automatiquement.
3. Dans Supabase, allez dans *Project Settings → API* : copiez l'**URL du projet** et la clé **anon public**.
4. Collez ces deux valeurs dans l'app, choisissez un **identifiant de synchro** (Sync ID) — ou cliquez sur **🎲 Générer** — puis **Enregistrer & connecter**.
5. Sur votre second appareil (iPhone…), ouvrez l'app et répétez l'étape 4 avec **exactement les mêmes** URL, clé et Sync ID.

```sql
create table if not exists conges_sync (
  sync_id text primary key,
  days jsonb not null default '{}'::jsonb,
  config jsonb not null default '{}'::jsonb,
  updated_at timestamptz not null default now()
);
alter table conges_sync enable row level security;
create policy "acces via sync_id" on conges_sync
  for all using (true) with check (true);
```

> **Sécurité**
> Le **Sync ID** fait office de mot de passe (pas de compte utilisateur) : choisissez-en un long et ne le communiquez à personne.

---

## 09 — Sécurité des données

### 09 Sauvegarde locale (fichier JSON)

Que vous utilisiez Supabase ou non, vous pouvez à tout moment sauvegarder vos données dans un fichier, ou restaurer une sauvegarde.

Ces options se trouvent dans le panneau **☁ Supabase**, sous « Sauvegarde locale (fichier JSON) » :

- **⬇ Exporter un fichier de sauvegarde** — télécharge un fichier `.json` contenant tout votre calendrier et vos paramètres.
- **⬆ Importer un fichier de sauvegarde** — recharge un fichier exporté précédemment, en remplaçant les données actuelles.

> **Bon réflexe**
> Exportez une sauvegarde de temps en temps, surtout avant une manipulation importante (comme « Recharger les données d'origine »). C'est aussi le moyen le plus simple de transférer vos données vers un nouvel appareil sans passer par Supabase.

---

## 10 — Nomade

### 10 Sur iPhone et mobile

L'application s'adapte à l'écran de votre téléphone : le tableau des soldes et le calendrier passent automatiquement en une seule colonne, avec des boutons agrandis pour un usage tactile confortable.

**Ajouter l'app à l'écran d'accueil (optionnel)**

1. Ouvrez le fichier dans **Safari** sur votre iPhone.
2. Appuyez sur le bouton de partage ⬆.
3. Choisissez **« Sur l'écran d'accueil »**.

Vous obtenez ainsi une icône dédiée, qui ouvre l'application en plein écran, sans barre d'adresse — pratique au quotidien, même s'il ne s'agit pas techniquement d'une app installée depuis l'App Store.

---

## 11 — Pour aller plus loin

### 11 Questions fréquentes

**Mes données sont-elles envoyées quelque part ?**
Non, par défaut tout reste dans votre navigateur (stockage local). Rien n'est envoyé sur internet, sauf si vous configurez volontairement la synchronisation Supabase (section 08).

**Si j'ouvre l'app sur mon ordinateur ET mon iPhone, mes données sont-elles les mêmes ?**
Pas automatiquement : chaque navigateur/appareil garde sa propre copie locale. Utilisez la synchronisation Supabase (section 08) ou l'export/import JSON (section 09) pour les faire correspondre.

**Pourquoi un jour de CP coché en mars ne change pas le solde affiché sur la page de cette même année ?**
Le CP et le CAS suivent la période légale du 1ᵉʳ juin au 31 mai, indiquée sous chaque poste dans le tableau. Un jour de mars appartient à la période qui a commencé en juin de l'année précédente — c'est donc bien pris en compte, simplement dans la bonne période.

**Puis-je modifier les jours fériés ou en ajouter ?**
Les jours fériés français (dont le vendredi de l'Ascension) sont calculés automatiquement chaque année et ne sont pas modifiables dans l'interface actuelle.

**J'ai fait une erreur de manipulation, comment revenir en arrière ?**
Il n'y a pas de fonction « annuler ». Recliquez sur le jour concerné pour corriger la catégorie, ou restaurez une sauvegarde JSON exportée précédemment (section 09).

**Mon entreprise n'a pas de CAS ou de RTT2, puis-je les faire disparaître ?**
Oui : décochez la catégorie correspondante dans ⚙ Paramètres (section 06). Elle disparaît de l'affichage sans effacer vos données ; vous pouvez la réactiver à tout moment.

**Le liseret orange des vacances scolaires correspond-il à ma zone ?**
Il est calé sur la zone B (académie d'Orléans-Tours). Si vous dépendez d'une autre zone, ignorez simplement ce repère visuel — il n'a aucun effet sur vos soldes de congés.

> **Besoin d'aide**
> Ce manuel couvre l'usage courant de l'application. Pour toute question sur un cas particulier (jours fériés locaux, règles d'entreprise spécifiques…), les paramètres d'attribution et de solde reporté (section 06) permettent d'adapter le calcul à votre situation réelle.
