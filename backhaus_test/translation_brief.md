# Translation brief: Backhaus, "Zur logischen Misere der Nationalökonomie"

Source: `backhaus_misere_de.md` (712 lines). Target: `backhaus_misere_en.md`.
Reference: `glossaries/glossary.md`; textual decisions in `backhaus_misere_de_notes.md`.

## 1. Form

- Translate line for line. English line *n* renders German line *n*. Do not merge or split lines; keep every blank
  line where it is. The finished file must have exactly 712 lines, so that `table.py` can pair them.
- Within a line, English word order may shift clauses about. Nothing may move to another line.
- Keep all Markdown: `#` heading, `*italics*` (including partial-word italics such as Wert*form*, rendered as
  value-*form*), footnote references `[^n]` in the same places, and definitions `[^n]: ` at the start of their lines.
- Quotation marks: » « become “ ”; nested > < become ‘ ’. Keep Backhaus's insertions (!), (!!), (?!), (...) and (!?)
  exactly as they stand.
- Editorial brackets: `[im Druck: …]` becomes `[printed: …]`, with the printed word given in German *and* English,
  e.g. “absolute” [printed: “objective” (*objektive*)].
- Leave Marx citations in the form (23/85), (II.5/47), (26.3/491) unchanged (MEW volume/page; MEGA in Roman numerals).
- Footnote apparatus: Ebd. → Ibid.; ebd. → ibid.; Bd. → vol.; Fn. → n.; zit. n. → quoted in; Hg. → ed.; Vgl. → Cf.;
  u. → and; f./ff. unchanged; Sp. → col.; m. W. → to my knowledge. In Hegel references, keep "§ 231 A" and "§ 82 Z"
  as printed (A = Remark, Z = Addition).
- Footnote titles stay in German, because the page numbers refer to those editions. Do not add English titles there.
  In the running text, use the established English title where one exists (*Capital*, *Grundrisse*, *The Philosophy of
  Money*, *History and Class Consciousness*, *Negative Dialectics*); otherwise give the German title in italics.

## 2. The governing principle: three registers

The essay is about economists, so most of its vocabulary belongs to them, not to Marx. This is the decisive point.
The Moore–Aveling *Capital* is the model: they left the philosophical terms largely as they were, but recognised
exactly where Marx was coding an expression from Smith, Ricardo et al., and then used the classical economists'
own English. Do the same here. Before translating a term, decide which register it belongs to.

**(a) Marx/Hegel register: use the glossary.** This applies where Backhaus quotes Marx or Hegel, or argues in their
categories: Darstellung, Vorstellung, Verstand/Vernunft, Erscheinung/Schein, Gegenständlichkeit,
Wertgegenständlichkeit, Vergegenständlichung, sinnlich übersinnlich, Wertform, gesellschaftliche Natureigenschaft,
Realabstraktion, Formwechsel, Metamorphose, gelten, setzen, allgemein/besonder/einzeln. Follow
`glossary.md` strictly, including its forcing choices (presentation, semblance, actual, figure as, unity).

**(b) Economics register: use the standard English term of economics.** This applies wherever the German encodes a
term of the discipline, as it does in Menger, Wieser, Böhm-Bawerk, Schumpeter, Amonn, Gottl, Cassel, Wicksell, Knapp,
Walras, Robinson, the Neo-Ricardians and modern monetary theory, and in Backhaus's own discussion of them. Use the term an English-speaking
economist would recognise, and where an English edition of the author exists, use that edition's term. Here the
glossary yields:
- Gleichung → *equation*, not "equality", when an economist means an equation (Verkehrsgleichung, Quantitätsgleichung,
  Tauschgleichungen, Gleichungen zwischen monetären und realen Größen). Keep *equality* only for Marx's value-form
  and for Gleichheit/Gleichsetzbarkeit.
- Einheit → *unit* in monetary contexts (Recheneinheit, Werteinheit, Geldeinheit, Mengeneinheit). Keep *unity* where the
  sense is logical or totalising ("die große Einheit", "Einheit von Sein und Gelten").
- Größe → *magnitude* in Marx; with the economists, *quantity*, *variable* or *aggregate* as the context requires
  (makroökonomische Größen = macroeconomic aggregates; Gesamtgrößen = aggregates).
- Umlauf → *circulation* with the economists (Geldumlauf, Umlaufsgeschwindigkeit = velocity of circulation).

**(c) Methodology and philosophy register: use the established English of each school.**
- Neo-Kantians (Rickert, Weber, Amonn): Erfahrungsobjekt / Erkenntnisobjekt = object of experience / object of
  knowledge; heterogenes Kontinuum = heterogeneous continuum; Gesichtspunkt = point of view; Wertbeziehung = value relevance.
- Frankfurt School: traditionelle/kritische Theorie = traditional/critical theory; Positivismusstreit = positivist dispute;
  erste/zweite Natur = first/second nature.
- Heidegger: follow Macquarrie/Robinson (Wertbehaftetheit = being-burdened-with-value; Behaftetsein = being-burdened).

## 3. Quotations

- Authors who wrote in English must be quoted in their own words, not translated back from German. This applies to
  Schumpeter's *History of Economic Analysis* (the German *Geschichte der ökonomischen Analyse* is a translation of it),
  Joan Robinson, Robbins, Bailey, Keynes, Daniel Bell and Hahn where they wrote in English, and Marx's English sentence
  "at applying the dialectic method to Political Economy". Keep Backhaus's ellipses and (!) marks inside the original wording.
- For German authors with a standard English translation, use its wording if it can be found, and adapt it to Backhaus's
  cuts and emphases: Menger (*Principles of Economics*, Dingwall/Hoselitz; *Problems of Economics and Sociology*),
  Böhm-Bawerk (*Capital and Interest*), Wieser (*Natural Value*; *Social Economics*), Simmel (*The Philosophy of Money*,
  Bottomore/Frisby), Knapp (*The State Theory of Money*), Wicksell (*Lectures on Political Economy*), Weber
  ("'Objectivity' in Social Science"), Lukács (*History and Class Consciousness*, Livingstone), Horkheimer, Adorno,
  Heidegger (*Being and Time*), Hegel (*Encyclopaedia*, *Philosophy of Right*), Marx (MECW; *Capital*, Fowkes or
  Moore–Aveling; *Grundrisse*, Nicolaus).
- Where the English source wording cannot be checked, translate from Backhaus's German and record it in a separate list.
  Do not put markers in the text line.

## 4. Core economics vocabulary (register b)

| German | English |
|---|---|
| Nationalökonomie, Volkswirtschaftslehre, Wirtschaftswissenschaft | economics (political economy only in Marx quotations) |
| Nationalökonom, Ökonom | economist |
| Sozialökonomie / Sozialökonomik | social economics |
| Volkswirtschaft | national economy, economy |
| Wertlehre, Werttheorie | theory of value |
| subjektive / objektive Wertlehre | subjective / objective theory of value |
| Arbeitswerttheorie | labour theory of value |
| Grenznutzen, Grenznutzenschule | marginal utility, marginal utility school |
| objektiver Tauschwert (Böhm-Bawerk, Wieser) | objective exchange value |
| volkswirtschaftlicher Tauschwert | exchange value in the national-economic sense (Wieser) |
| Tauschkraft | power in exchange |
| Kaufkraft | purchasing power |
| Preistheorie, Preissystem | price theory, price system |
| relative / absolute Preise | relative / absolute prices |
| Gleichgewichtstheorie | (general) equilibrium theory |
| Verkehrsgleichung | equation of exchange |
| Quantitätstheorie / -gleichung | quantity theory / quantity equation |
| Recheneinheit, Rechnungseinheit | unit of account |
| Werteinheit / Geldeinheit | unit of value / monetary unit |
| Geldschleier | veil of money |
| Geldvolumen / Handelsvolumen | quantity (stock) of money / volume of trade |
| Warenströme / Geldströme | flows of goods / money flows |
| Kapitalgüter, Kapitalwert | capital goods, capital value |
| Kapitalzins, Kapitalzinstheorien | interest (on capital), theories of interest |
| Zins, Rente, Lohn | interest, rent, wages |
| Verteilungstheorie | theory of distribution |
| Produktionsfaktoren, Faktorleistungen | factors of production, factor services |
| Gesamtnachfrage / Gesamtangebot | aggregate demand / aggregate supply |
| Volkseinkommen / Volksvermögen | national income / national wealth |
| Sozialprodukt | social product (national product where the context is accounting) |
| Verfügungsmacht, Verfügungsgewalt | power of disposal |
| Anweisung (Schumpeter) | claim |
| Rechenpfennige (Schumpeter) | counters |
| Datenanalyse, Daten | analysis of data, data (Walrasian "data") |
| Wahlakte, Wahlhandlungen | acts of choice |
| Modell, Modellplatonismus | model, model-Platonism |
| Neoricardianismus, Walrasianer | neo-Ricardianism, Walrasians |
| Methodenstreit | Methodenstreit (italicised, as in English usage) |

## 5. Points the translator must not smooth over

- *Verstand* / *Vernunft* (understanding / reason) and *verständig* / *vernünftig* carry the opening argument. Never
  render both as "reasonable".
- *rationell / irrationell*, wherever they come from Marx (the quotation at line 9; "irrationelle Preise", "irrationelle
  Form" at lines 11 and 23): render them "rational (*rationell*)" and "irrational (*irrationell*)", with the German at every occurrence.
  The words were uncommon even then. Marx uses them with a geometric or arithmetical analogy: what does not fit, what has
  no common measure, like an irrational number. Hegel's § 231, quoted at line 13, makes this explicit: "Inkommensurabilitäten
  und Irrationalitäten" arise in the progress of geometry. So the sense is not today's "irrational" as in an irrational policy.
  German would say *unvernünftig* or *vernunftlos* for that.
- Keep these apart from the *Vernunft* family. *Vernunft* = reason; *vernünftig* = rational in the sense of reason, or
  "of reason", as in `glossary.md`; *Vernünftigkeit* = rationality (the quality of reason); *unvernünftig* / *vernunftlos* = irrational
  or unreasonable in the ordinary sense. Because "rational" now serves both *vernünftig* and the marked *rationell*, the
  German tag on *rationell* is what keeps the two words distinct for the reader.
- Backhaus's own nouns *Rationalität* / *Irrationalität* (from line 13 on) are his generalisation of Marx's usage. Render them
  "rationality" / "irrationality" without a tag, but do not paraphrase them as "unreasonableness". Hegel's "rational /
  irrational" at line 13 (*rational* genannt wird, das *Verständige*) are also left untagged, because Hegel himself is
  glossing the words there.
  They must stay literally "rational / irrational" in their arithmetical sense, so that the inversion survives in
  English: what is *called* rational is the work of the understanding, while what is called irrational is "rather a
  beginning and trace of rationality (*Vernünftigkeit*)". Reason shows itself in geometry only at the incommensurables;
  before that it is all *Verstand*. Tag *Vernünftigkeit* here, because "rationality" would otherwise read as the
  *rational* that has just been called *das Verständige*.
- The metaphors of adhesion are the theme of the middle of the essay: haften, anhaften, anheften, kleben, beklebt,
  Behaftetsein, verkörpern, Verkörperung, Inkarnation, Verknüpfung, Kettung, Bindung. Give each German verb one English
  rendering and use it throughout (e.g. adhere / adhere to / be affixed / stick / be stuck with / being-burdened;
  embody / embodiment / incarnation; connection / chaining / binding).
- *Sache / Ding / Gegenstand* follow the glossary: thing (*Sache*) / thing / object.
- *gegenständlicher Schein*: objective semblance (*gegenständlicher Schein*), with the German at first occurrence.
- *Dritte(s)* (Amonn's "sehr reales Drittes"): "a very real third".
- *Erfahrungs-* / *Erkenntnisobjekt* are technical terms. Do not vary them.
