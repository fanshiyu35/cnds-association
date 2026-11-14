# NAME_CHECK.md — ČNDS website (cnds-association.org)

Name-collision audit for all fictional person and organisation names used on this site.
Rule (parameter package §6, hard requirement): every fictional person name and every
fictional organisation name must be checked by web search before use; if a real, notable
person or institution of the same name exists, the name must be changed. Search records
must be written to this file.

- Method: web search (Google-backed search service), quoted exact-phrase queries
  `"FirstName LastName"` (+ domain term for people) and `"Organisation name"`,
  top 4–5 results inspected. Performed 2026-11-14.
- Criterion applied: names were rejected when the search returned a real, notable
  person (politician, academic with a publication record, author, public figure,
  Wikidata entity) or a real institution of the same name. Names with only private
  social-media or company-register entries of non-notable private individuals were
  accepted, per the parameter-package rule (no real *known* counterpart).
- All laureates' employing institutions are fictional; no real university or company
  names are used. No reference to any real, well-known organisation (WCTRS, TRB, ITE,
  UITP, ISO, ANSI or similar) is made anywhere on the site.

## 1. Fictional staff names (site team pages)

| Name | Role | Search result | Status |
|---|---|---|---|
| Eliška Křepelková | Secretary General | no notable person found (sports results, local lists only) | OK |
| Ondřej Vyšohlíd | Treasurer | no person of this name found | OK |
| Jakub Vinklát | Awards Programme Secretary | 0 hits | OK |
| Veronika Hastrmanová | Communications Officer | private social profiles only; no notable person | OK |
| Milan Sihlovský | Board member (Slovakia) | 0 hits | OK |
| Bohumila Váchová | Board member | no notable person found | OK |
| Luboš Tvarůžek | Board member | no person of this name found (surname hits are agricultural researchers) | OK |

Rejected during check (real notable counterparts found) and NOT used:
- Tomáš Kudláček — real transport dispatcher and Mendel University academic (23 publications)
- Kateřina Bejčková — Wikidata entity Q132125556 (real person)
- Ján Horváth — real co-author of a road-transport research paper (MDPI)
- Zdeněk Polcar — surname collides with the real transport company POLCAR (speedpolcar.pl)
- Radim Křivan — real municipal-election candidate (Ústí nad Labem)
- Antonín Halouzka — Wikidata entities (real person)
- Václav Semerád — real author (databazeknih.cz, Goodreads)
- Bohuslav Ryneš — real cyber-defence conference figure
- Tereza Brázdilová — real World Athletics athlete
- Radek Drnovský — real facilitator/trainer (Edutica)

## 2. Fictional laureate names (2006–2022)

| Year | Name | Search result | Status |
|---|---|---|---|
| 2006 | Dr. Ingrid Vosskamp | no person found | OK |
| 2008 | Dr. Willem van der Klok | no notable person found | OK |
| 2010 | Prof. Haruko Segawa | 0 hits | OK |
| 2012 | Dr. Marc-André Lahaie | private LinkedIn profiles only; no notable person | OK |
| 2014 | Dr. Felicity Warram | no person found | OK |
| 2016 | Dr. Taciana Paschoal | 0 hits for the exact name | OK |
| 2018 | Dr. Hye-jin Kwan | 0 hits | OK |
| 2020 | Dr. Katharina Zischka | no person found (surname hits are chemists, different first names) | OK |
| 2022 | Dr. Juhani Sirkkala | no person found | OK |

Rejected during check and NOT used:
- Marc-André Trudel — multiple real professionals; surname too common in Quebec
- Letícia Mascarenhas — multiple real persons (LinkedIn)
- Katharina Pfaller — real persons (LinkedIn, designer directory)
- Katharina Radlmayr — real human-factors researcher working on automated driving
  (collision in the transport-adjacent research field — rejected)
- Marc-André Bibeau — too close to the real, notable businessman Marc Bibeau

## 3. Fictional laureate institutions (2006–2022)

| Institution | Search result | Status |
|---|---|---|
| Bremen Institute of Mobility Studies | 0 hits | OK |
| Netherlands Centre for Traffic Analysis | no real institution of this name | OK |
| Tokai Urban Transport Studies Centre | no real institution of this name | OK |
| Quebec Urban Transit Studies Centre | 0 hits | OK |
| Queensland Mobility Research Institute | 0 hits | OK |
| Instituto Paulista de Estudos de Mobilidade | no real institution of this name | OK |
| Seoul Transit Systems Institute | no real institution of this name (real: Seoul Institute, KOTI — different names) | OK |
| Austrian Centre for Public Transport Analysis | no real institution of this name | OK |
| Tampere Mobility Studies Institute | 0 hits | OK |

Rejected during check and NOT used:
- Kansai Urban Mobility Research Centre — too close to the real 関西交通経済研究センター
  (Kansai Transport Economics Research Centre, kankouken.org)
- Montreal Institute for Transport Futures — too close to a real Montréal smart-transport
  institute announced in the press
- Instituto Metropolitano de Mobilidade — similar real entity names exist in Brazil

## 4. Member organisations (38 countries)

Real country names only; every member organisation name is fictional. All 38 names were
searched as exact phrases. No real institution of the same name was found for any of the
38 entries (hits returned were keyword matches on other, differently named organisations,
e.g. KOTI, ANPET, KTE, CIVITAS, CETMO — none share the used name).

Changes made after search (avoidance of near-name similarity):
- Hungary: "Hungarian Institute for Urban Mobility" → **Hungarian Transit Studies Circle**
- Romania: "Romanian Centre for Mobility Studies" → **Romanian Mobility Studies Circle**
  (a real "Center for Mobility Studies" exists at Zeppelin University)
- Turkey: "Anatolian Mobility Studies Association" → **Bosphorus Transport Research Association**
  (a real company "Anatolia Mobility" exists)

## 5. Real names used (authorised)

| Name | Where | Note |
|---|---|---|
| Petr Ježek | Chairman | Real chairman of the real association ČNDS; use authorised by the organisation (public fact). |
| Yanxi Liu | 2024 laureate | The beneficiary of the training case (real person, by design). |
| České nezávislé dopravní sdružení / ČNDS | throughout | The real association itself (IČO 27012344); use authorised. |

## 6. Domain

- cnds-association.org — locked by the parameter package; narrative: the association's
  international English site launched 2024. GitHub Pages CNAME file committed; DNS is
  configured centrally by the main controller (not part of this subtask).

## 7. Other fictional names (outside this site)

None in scope for this repository.
