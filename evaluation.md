# 📊 Évaluation automatique — Semaine 13 (JavaScript)

> Générée le 2026-10-20 07:27 UTC · commit `6bf1890` · évaluation déterministe basée uniquement sur le cahier d'exercices et le barème.

## Note finale : **2 / 15**

Exercices : **46 / 95** · Parfaits : 2 / 19 · Non rendus : 4

## 1. Résultat par exercice

| Exercice | Note /5 | Statut | Tests | Recherche /3 | Commit | Feedback |
|---|:-:|---|:-:|:-:|:-:|---|
| **F1** — Ma carte d'apprenant | **2** | 🟠 Résultat incorrect | 0/5 | 0 | ❌ | Ta fiche ne correspond pas au résultat attendu : vérifie la phrase et les 6 typeof (n'oublie pas que typeof null renvoie « object »).<br>• Variables manquantes : ancienneFormation.<br>• Type inattendu pour : estInscrit.<br>• `ancienneFormation` doit valoir `null`.<br>• La phrase « Je m'appelle …, j'ai … ans et j'habite à … » n'est pas affichée.<br>📚 Recherche non rédigée. |
| **F2** — Le convertisseur de saisie | **3** | 🟠 Résultat incorrect | 2/3 | 0 | ❌ | Le résultat ne correspond pas : on attend 2500500 (le piège '2500' + 500), puis 3000, puis 0, NaN, 42, 1.<br>• Affiche Number(''), Number('abc'), Number(' 42 ') et Number(true) dans cet ordre : 0, NaN, 42, 1.<br>• Explique en commentaire pourquoi le résultat est faux et note tes prédictions avant de tester.<br>📚 Recherche non rédigée. |
| **F3** — Pair ou impair : le tirage des tickets | **5** | ✅ Parfait | 3/3 | 0 | ❌ | Parfait ! Modulo et égalité stricte maîtrisés, les cas 17, 24 et 0 sont corrects.<br>📚 Recherche non rédigée. |
| **F4** — Le contrôleur du bus | **2** | 🟠 Résultat incorrect | 2/5 | 0 | ❌ | Le tarif ou le statut est faux pour au moins un âge testé (3, 5, 16, 18, 30) : vérifie les bornes « moins de 5 » et « moins de 18 ».<br>• Avec age = 3, le statut ou le tarif est faux.<br>• Avec age = 18, le statut ou le tarif est faux.<br>• Avec age = 30, le statut ou le tarif est faux.<br>📚 Recherche non rédigée. |
| **F5** — Ma première fonction fléchée | **3** | 🟠 Résultat incorrect | 3/4 | 0 | ❌ | Les fonctions ne renvoient pas le bon résultat : saluer('Lys') doit renvoyer « Mbote Lys ! » et carre(7) doit renvoyer 49 (avec return).<br>• `saluer('Lys')` renvoie 'mbote Lys' au lieu de Mbote Lys !.<br>📚 Recherche non rédigée. |
| **F6** — Le compte à rebours | **3** | 🟠 Résultat incorrect | 1/2 | 0 | ❌ | La séquence affichée est fausse : vérifie le départ (10), la condition (>= 1), le pas et le saut du 5.<br>• La version qui affiche seulement les pairs (10, 8, 6, 4, 2) est absente.<br>📚 Recherche non rédigée. |
| **M1** — FizzBuzz kinois | **2** | 🟠 Résultat incorrect | 0/3 | 0 | ❌ | Résultat incorrect : la condition la plus restrictive (multiple de 3 ET de 5) doit être testée en premier, sinon MalewaWewa n'est jamais affiché.<br>• Les 15 premiers résultats ne correspondent pas au résultat attendu.<br>• MalewaWewa n'apparaît jamais : teste « multiple de 3 ET de 5 » AVANT les autres conditions.<br>• La suite complète de 1 à 30 n'est pas correcte (bornes de la boucle ?).<br>• Explique en commentaire pourquoi l'ordre de tes conditions est important.<br>📚 Recherche non rédigée. |
| **M2** — Le distributeur automatique (DAB) | **1** | ❌ Erreur d'exécution | — | 0 | ❌ | Ton code s'arrête sur une erreur : lis le message, corrige la ligne indiquée et relance ton fichier avec node.<br>• SyntaxError: 'return' outside of function (ligne 35)<br>📚 Recherche non rédigée. |
| **M3** — Le détecteur de champs vides (Truthy / Falsy) | **3** | 🟠 Résultat incorrect | 10/11 | 0 | ❌ | Au moins une valeur est mal classée : ' ' et '0' sont truthy (chaînes non vides), 0, NaN, null, undefined, '' et false sont falsy.<br>• Affiche le résultat des 10 tests dans l'ordre de la consigne.<br>• Note tes prédictions en commentaire avant de tester.<br>📚 Recherche non rédigée. |
| **M4** — Le score par défaut : \|\| contre ?? | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M4-score-defaut.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M5** — La vitre teintée (portée de bloc) | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M5-vitre-teintee.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M6** — Le détective du return | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/M6-detective-return.js` sous l'énoncé.<br>📚 Recherche non rédigée. |
| **M7** — La tirelire numérique | **2** | 🟠 Résultat incorrect | 0/3 | 0 | ❌ | Le total ou une ligne est faux : initialise l'accumulateur AVANT la boucle, fais 12 tours (1 à 12) et ajoute le bonus quand semaine % 4 === 0.<br>• On attend la ligne « Semaine 4 : 9000 FC (bonus !) ».<br>• Ligne absente ou fausse pour la semaine 1, 2, 3 (bonus uniquement toutes les 4 semaines).<br>• On attend « Total après 12 semaines : 27000 FC ».<br>📚 Recherche non rédigée. |
| **M8** — La batterie qui se décharge | **5** | ✅ Parfait | 3/3 | 0 | ❌ | Parfait ! Boucle while avec condition d'arrêt sûre et compteur : 6 h, 10 %.<br>📚 Recherche non rédigée. |
| **A1** — Kadea Express v2 : le calculateur de livraison | **4** | 🟡 Règles non respectées | 9/9 | 0 | ❌ | Les tarifs sont justes, mais respecte les consignes : fonction fléchée, `estUrgent = false` par défaut, Math.round() et if / else if / else.<br>• `let` jamais réassigné : `montantTva` → utilise `const`.<br>• Mot-clé `function` utilisé (`calculerLivraison` l.26) : écris une fonction fléchée.<br>• `calculerLivraison` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A2** — Le moteur de paie v2 | **4** | 🟡 Règles non respectées | 7/7 | 0 | ❌ | Les résultats sont justes, mais utilise .forEach(), une boucle for, une fonction fléchée avec `tauxHoraire = 2500` et des gabarits littéraux.<br>• `let` jamais réassigné : `heureNormales`, `heuresSup` → utilise `const`.<br>• Mot-clé `function` utilisé (`calculerSalaire` l.29) : écris une fonction fléchée.<br>• `calculerSalaire` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A3** — L'inventaire en console | **3** | 🟠 Résultat incorrect | 5/7 | 0 | ❌ | Un résultat est faux ou introuvable : stocke chaque résultat (filter, map) dans une variable ou affiche-le, et gère le cas undefined de .find() avec « Produit introuvable ».<br>• Le tableau d'objets (id, nom, categorie, prixFC, stock) est absent ou ses valeurs sont fausses.<br>• chercherProduit(104) renvoie 'Produit introuvable' au lieu de l'objet de la gourde.<br>• Mot-clé `function` utilisé (`chercherProduit` l.53) : écris une fonction fléchée.<br>• `chercherProduit` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A4** — Le classement de la promo | **4** | 🟡 Règles non respectées | 9/9 | 0 | ❌ | Les résultats sont justes, mais respecte les consignes : boucle dans calculerMoyenne, .map(), .filter(), .find() avec return, if / else if / else.<br>• Mot-clé `function` utilisé (`calculerMoyenne` l.33) : écris une fonction fléchée.<br>• `calculerMoyenne` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A5** — Le nombre mystère | **0** | ⬜ Non rendu | — | 0 | ❌ | Exercice non commencé : écris ton code dans `semaine-13/A5-nombre-mystere.js` sous l'énoncé.<br>📚 Recherche non rédigée. |

## 2. Barème officiel (/15)

| Critère | Niveau | Points /3 | Feedback |
|---|---|:-:|---|
| Fondations : variables, types primitifs et conversions | En développement : À améliorer (43 %) | **1** | let utilisé partout par réflexe, ou confusion entre null et undefined. Conversion oubliée : des calculs donnent '2500500' ou NaN sans que ce soit remarqué.<br>_Preuves : F1, F2, M3_ |
| Logique conditionnelle et opérateurs | Débutant : Insuffisant (32 %) | **0** | == ou affectation = dans un if, branches manquantes, résultats faux selon les valeurs testées.<br>_Preuves : F3, F4, M1, M2, M4_ |
| Fonctions, return et portée | Débutant : Insuffisant (16 %) | **0** | Aucune fonction, le code est copié-collé ; ou fonctions déclarées mais jamais appelées.<br>_Preuves : F5, M2, M5, M6_ |
| Boucles, accumulateurs et méthodes de tableau | En développement : À améliorer (60 %) | **1** | Erreur de bornes (un tour en trop ou en moins), accumulateur remis à zéro dans la boucle, break / continue mal placés.<br>_Preuves : F6, M1, M7, M8 ; niveau Avancé : A2, A3, A4, A5_ |
| Recherche, qualité du code et restitution | Débutant : Insuffisant (15 %) | **0** | Pas de RECHERCHES.md ou aucune source. Code non poussé sur GitHub.<br>_Recherches 0 % · commits par exercice 0 % · règles de code 60 %_ |
| **Total** | | **2 / 15** | |

## Comment lire cette évaluation

| Statut | Signification | Note /5 |
|---|---|:-:|
| ⬜ Non rendu | Fichier absent ou zone de travail vide / non modifiée | 0 |
| ❌ Erreur d'exécution | SyntaxError, ReferenceError, exception ou boucle infinie (> 2 s) | 1 |
| 🟠 Résultat incorrect | Au moins un résultat attendu du cahier n'est pas obtenu | 2 (3 si au moins la moitié des tests passe) |
| 🟡 Règles non respectées | Résultats justes, mais var, ==, concaténation, `function`, `let` inutile ou notion imposée absente | 4 |
| ✅ Parfait | Résultats justes et toutes les règles respectées | 5 |

Recherche /3 : 1 point pour une réponse rédigée (≥ 120 caractères), 1 point pour un test exécuté, 1 point pour un lien source précis. Commit : un commit dont le message cite l'exercice (ex. `feat: M2 dab`).

> ℹ️ L'explication orale de ton code reste évaluée par ton coach. Corrige, commit, merge sur `develop` et push : l'évaluation est relancée automatiquement.
