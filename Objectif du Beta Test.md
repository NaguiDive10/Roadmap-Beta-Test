---

# Beta Test – Stratégie complète et outils

## Objectif du Beta Test

Collecter des retours qualitatifs et quantitatifs de vrais utilisateurs afin d’améliorer l’outil :

* Identifier les bugs
* Évaluer l’UX/UI (intuitivité, design, clarté)
* Mesurer la prise en main (fluidité, compréhension)
* Analyser le ressenti général
* Identifier les points forts
* Détecter les irritants ou blocages

---

## 1. Plateformes de feedback anonyme recommandées

| Plateforme     | Gratuité          | Anonyme | Mobile friendly | Compte requis | Avantages clés                                   |
| -------------- | ----------------- | ------- | --------------- | ------------- | ------------------------------------------------ |
| Tally.so       | Oui               | Oui     | Oui             | Non           | Interface moderne, rapide, sans pub              |
| Google Forms   | Oui               | Oui     | Oui             | Non           | Simple, connu, rapide à mettre en place          |
| Framaforms.org | Oui (open source) | Oui     | Oui             | Non           | Éthique, hébergé en France, conforme RGPD        |
| Typeform       | Oui (limité)      | Oui     | Oui             | Non           | Très bonne expérience utilisateur, design soigné |

**Recommandation** : utiliser **Tally.so** ou **Typeform**, avec **Zapier + Google Sheets** pour centraliser automatiquement les réponses.

---

## 2. Roadmap du Beta Test

| Phase        | Durée          | Objectif principal                                   |
| ------------ | -------------- | ---------------------------------------------------- |
| Préparation  | 1 semaine      | Sélection des testeurs et mise en place              |
| Test         | 2 à 3 semaines | Collecte de feedbacks à chaud (via formulaire court) |
| Analyse      | 1 semaine      | Synthèse et priorisation des retours                 |
| Amélioration | 2 à 4 semaines | Corrections et itérations                            |

---

## 3. Formulaires à mettre en place

### A. Formulaire principal (évaluation complète)

**À diffuser au début ou à la fin de la période de test.**
**Objectif** : récolter une évaluation complète et qualitative.

#### Titre

**Donne ton avis sur notre outil – en toute liberté**

#### Description

Merci de tester notre application en avant-première.
Nous souhaitons recueillir ton avis sincère et anonyme.
Aucune question n’est obligatoire. Réponds librement.

#### Questions

1. **Globalement, comment as-tu trouvé l’outil ?**
   Type : choix multiple

* Très intuitif
* Plutôt simple à prendre en main
* Un peu complexe
* Incompréhensible
* Je ne sais pas / pas testé assez

2. **Qu’as-tu particulièrement apprécié ?**
   Type : réponse longue

3. **As-tu rencontré un bug ?**
   Type : réponse longue

4. **Qu’est-ce qui t’a frustré ou gêné ?**
   Type : réponse longue

5. **Qu’est-ce qui, selon toi, devrait être amélioré en priorité ?**
   Type : réponse longue

6. **Note globale de satisfaction (de 0 à 10)**
   Type : curseur

7. **Une suggestion, idée ou remarque libre ?**
   Type : réponse longue

8. **Une dernière chose à dire ?**
   Type : réponse longue libre (non orientée)

#### Message de fin

Merci pour ta participation. Tes réponses sont bien enregistrées, de manière totalement anonyme.
Elles nous aideront à faire progresser l’outil.
Reste connecté sur nos réseaux pour suivre l’évolution.

---

### B. Formulaire quotidien (rapport rapide)

**À diffuser quotidiennement ou tous les deux jours pendant la phase de test.**
**Objectif** : suivre à chaud l’utilisation et les ressentis sans surcharger.

#### Titre

**Ton ressenti aujourd’hui – 30 secondes suffisent**

#### Questions

1. **As-tu utilisé l’outil aujourd’hui ?**
   Type : Oui / Non

2. **Combien de temps environ ?**
   Type : choix multiple

* Moins de 5 minutes
* 5 à 15 minutes
* Plus de 15 minutes

3. **Ton ressenti aujourd’hui ?**
   Type : curseur (0 = mauvais, 10 = excellent)

4. **Un bug ou souci rencontré ?**
   Type : réponse courte (facultatif)

5. **Un mot ou une phrase pour résumer ta journée avec l’outil ?**
   Type : réponse courte

---

## 4. Bonnes pratiques

* Ne jamais demander d’informations personnelles
* Ne pas afficher les réponses d’autres testeurs
* Rassurer sur l’anonymat et la confidentialité
* Fournir une version stable et fonctionnelle
* Clarifier ce qui est attendu (éviter les termes techniques)
* Récompenser les testeurs (ex : tirage au sort, accès premium, code promo)

---

## 5. Hébergement de l’application à tester

| Format               | Plateformes recommandées                |
| -------------------- | --------------------------------------- |
| Web app              | Vercel, Netlify, Firebase               |
| App mobile (iOS)     | TestFlight (via compte Apple Developer) |
| App mobile (Android) | Google Play Console (bêta fermée)       |

---

## 6. Exemple de diffusion auprès des testeurs

* **Jour 0** : sélection des testeurs + envoi du formulaire principal (optionnel)
* **Jour 1 à 10** : envoi du formulaire quotidien chaque jour (via e-mail, lien en story Instagram, etc.)
* **Jour final** : envoi ou relance du formulaire principal pour une synthèse complète
* **Analyse** : centralisation dans Google Sheets, Notion ou Airtable

---

## 7. Configuration recommandée sur Tally.so

1. Se rendre sur [https://tally.so](https://tally.so)
2. Cliquer sur **"Create new form"**
3. Copier-coller les contenus ci-dessus
4. Paramétrer :

* **Collect email addresses** : désactivé
* **Show a ‘Powered by Tally’ message** : facultatif
* **Require login** : désactivé
* **Allow multiple submissions** : activé

---

