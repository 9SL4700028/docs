---
layout: base
title:  'Statistics of Degree in UD_Swedish-PUD'
udver: '2'
---

## Treebank Statistics: UD_Swedish-PUD: Features: `Degree`

This feature is universal.
It occurs with 3 different values: `Cmp`, `Pos`, `Sup`.

1519 tokens (8%) have a non-empty value of `Degree`.
825 types (13%) occur at least once with a non-empty value of `Degree`.
627 lemmas (13%) occur at least once with a non-empty value of `Degree`.
The feature is used with 2 part-of-speech tags: <tt><a href="sv_pud-pos-ADJ.html">ADJ</a></tt> (1245; 7% instances), <tt><a href="sv_pud-pos-ADV.html">ADV</a></tt> (274; 1% instances).

### `ADJ`

1245 <tt><a href="sv_pud-pos-ADJ.html">ADJ</a></tt> tokens (79% of all `ADJ` tokens) have a non-empty value of `Degree`.

The most frequent other feature values with which `ADJ` and `Degree` co-occurred: <tt><a href="sv_pud-feat-Tense.html">Tense</a></tt><tt>=EMPTY</tt> (1245; 100%), <tt><a href="sv_pud-feat-VerbForm.html">VerbForm</a></tt><tt>=EMPTY</tt> (1245; 100%), <tt><a href="sv_pud-feat-Case.html">Case</a></tt><tt>=Nom</tt> (1242; 100%), <tt><a href="sv_pud-feat-Gender.html">Gender</a></tt><tt>=EMPTY</tt> (830; 67%), <tt><a href="sv_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt> (692; 56%).

`ADJ` tokens may have the following values of `Degree`:

* `Cmp` (44; 4% of non-empty `Degree`): <em>större, högre, mer, tidigare, senare, färre, mindre, ytterligare, yttre, äldre</em>
* `Pos` (1126; 90% of non-empty `Degree`): <em>nya, andra, många, flera, stora, stor, hela, brittiska, olika, fler</em>
* `Sup` (75; 6% of non-empty `Degree`): <em>senaste, sista, högsta, största, bästa, främsta, bäst, flesta, mesta, värsta</em>
* `EMPTY` (324): <em>första, andra, betydande, sett, följande, kända, tredje, allierade, känd, levande</em>

<table>
  <tr><th>Paradigm <i>stor</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt></tt></td><td></td><td><em>större</em></td><td></td></tr>
  <tr><td><tt><tt><a href="sv_pud-feat-Definite.html">Definite</a></tt><tt>=Def</tt></tt></td><td></td><td></td><td><em>största</em></td></tr>
  <tr><td><tt><tt><a href="sv_pud-feat-Definite.html">Definite</a></tt><tt>=Def</tt>|<tt><a href="sv_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt></tt></td><td><em>stora</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="sv_pud-feat-Definite.html">Definite</a></tt><tt>=Ind</tt>|<tt><a href="sv_pud-feat-Gender.html">Gender</a></tt><tt>=Com</tt>|<tt><a href="sv_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt></tt></td><td><em>stor</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="sv_pud-feat-Definite.html">Definite</a></tt><tt>=Ind</tt>|<tt><a href="sv_pud-feat-Gender.html">Gender</a></tt><tt>=Neut</tt>|<tt><a href="sv_pud-feat-Number.html">Number</a></tt><tt>=Sing</tt></tt></td><td><em>stort</em></td><td></td><td></td></tr>
  <tr><td><tt><tt><a href="sv_pud-feat-Number.html">Number</a></tt><tt>=Plur</tt></tt></td><td><em>stora</em></td><td></td><td></td></tr>
</table>

`Degree` seems to be **lexical feature** of `ADJ`. 96% lemmas (521) occur only with one value of `Degree`.

### `ADV`

274 <tt><a href="sv_pud-pos-ADV.html">ADV</a></tt> tokens (27% of all `ADV` tokens) have a non-empty value of `Degree`.

`ADV` tokens may have the following values of `Degree`:

* `Cmp` (73; 27% of non-empty `Degree`): <em>mer, senare, tidigare, längre, bättre, mindre, hellre, snarare, närmare, vidare</em>
* `Pos` (172; 63% of non-empty `Degree`): <em>helt, mycket, ofta, väldigt, djupt, långt, direkt, lite, väl, faktiskt</em>
* `Sup` (29; 11% of non-empty `Degree`): <em>mest, sist, främst, värst, Minst, helst, ytterst, knappast</em>
* `EMPTY` (747): <em>så, in, ut, där, också, upp, bara, fram, här, även</em>

<table>
  <tr><th>Paradigm <i>mycket</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt></tt></td><td><em>mycket</em></td><td><em>mer</em></td><td><em>mest</em></td></tr>
</table>

`Degree` seems to be **lexical feature** of `ADV`. 92% lemmas (87) occur only with one value of `Degree`.

## Relations with Agreement in `Degree`

The 10 most frequent relations where parent and child node agree in `Degree`:
<tt>ADJ --[<tt><a href="sv_pud-dep-conj.html">conj</a></tt>]--> ADJ</tt> (20; 67%),
<tt>ADV --[<tt><a href="sv_pud-dep-conj.html">conj</a></tt>]--> ADV</tt> (2; 100%),
<tt>ADJ --[<tt><a href="sv_pud-dep-conj.html">conj</a></tt>]--> ADV</tt> (1; 100%),
<tt>ADJ --[<tt><a href="sv_pud-dep-nsubj.html">nsubj</a></tt>]--> ADJ</tt> (1; 100%),
<tt>ADV --[<tt><a href="sv_pud-dep-advcl.html">advcl</a></tt>]--> ADJ</tt> (1; 100%),
<tt>ADV --[<tt><a href="sv_pud-dep-parataxis.html">parataxis</a></tt>]--> ADV</tt> (1; 100%).

