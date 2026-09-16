# Kanji — version vérifiée (170 kanji)

## Ce qui a été refait

**Tout le contenu a été repris depuis zéro**, fiche par fiche, kanji par kanji,
à partir des PDF de cours. L'ancienne version contenait des dizaines d'erreurs.

### Les erreurs corrigées

**1. Lectures inventées.** J'avais ajouté des lectures ON qui ne figurent PAS sur
tes fiches. Exemples : 好(+コウ), 良(+リョウ), 飲(+イン), 着(+チャク), 次(+ジ),
走(+ソウ), 春夏秋冬(+シュン/カ/シュウ/トウ), 悪(+アク), 少(+ショウ), 山川田
(+サン/セン/デン), 私(+シ), 書(+ショ), 読(+ドク), 糸紙(+シ)… Toutes supprimées.

**2. 生 — le cas que tu as signalé.** Ta fiche (leçon 28) donne :
う(まれる) — セイ、ジョウ — « naissance, vie ».
J'avais mis « い(きる) » avec le sens « vivre » : un kun inventé ET un sens faux.
Corrigé.

**3. Lectures tronquées.** Tes fiches donnent souvent plusieurs lectures que
j'avais réduites à une : 本(ホン/ボン/ポン), 文(ブン、モ、モン), 歩(ホ、ポ),
図(ト、ズ), 分(フン/ブン/プン), 漢(カン、ハン), 父(ちち／とう), 母(はは／かあ),
姉(あね／ねえ), 明(あか(るい)／あか(り))… Toutes rétablies.

**4. Sens appauvris.** Rétablis à l'identique des fiches, y compris les mentions
transitif/intransitif de la leçon 25 (出る/出す, 入る/入れる, 止まる/止める) et
les doubles formes de 赤/青/白 (あか／あか(い)).

### Contrôles automatiques passés

- **Syllabaires** : 170/170 — chaque kun en hiragana, chaque on en katakana,
  vérifié par expression régulière. Zéro erreur.
- **Nombre de traits** : comparé entre tes fiches et KanjiVG. Un seul écart,
  良 (ta fiche indique 6 traits, le vrai compte est 7 — coquille de la fiche ;
  j'ai gardé 7 pour que l'animation du tracé soit juste).
- **Doublons** : 水, 入, 出 sont enseignés deux fois (leçons 21/24 et 23/25).
  Fusionnés en une carte chacun, en gardant TOUTES les lectures et sens des
  deux fiches.

## Le bouton « Revoir la liste du jour » — bug corrigé

Tu avais raison : le bouton existait dans le code mais **ne s'affichait jamais**.
Cause : la liste du jour était effacée dès qu'on rouvrait l'appli après avoir
terminé sa session (la file recalculée était vide et écrasait la mémoire).
Corrigé : la liste n'est plus écrasée par une file vide, et elle se réinitialise
proprement au changement de jour.

Le bouton apparaît maintenant sur l'écran de fin (済) et permet de rejouer les
mêmes cartes autant de fois que tu veux dans la journée, sans toucher à la
progression (un bandeau le rappelle, avec un bouton « Terminer » pour sortir).

## Contenu

- **170 kanji** : 105 acquis (ancien classeur leçons 21-31 + Niveau 1) en
  rotation de révision, et 65 nouveaux (leçons 32-40) qui sortent dans l'ordre
  strict du classeur.
- **2 nouveaux par jour** — écoulement des 65 en environ 33 jours.

## Installation

Remplace les fichiers sur ton dépôt GitHub. Le cache est en `kanji-verifie-v1`.
Sur le téléphone, ferme complètement l'appli avant de la rouvrir.

⚠️ La progression repart de zéro (nouvelle base de données, contenu différent).

## Crédits

Tracés : KanjiVG (Ulrich Apel), CC BY-SA 3.0.
