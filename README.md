# The Othniel Etienne Bipartite-Arc Method

**A visual way to count pairs (handshakes, matches, connections) by splitting people into two rows, joined by straight lines and arcs.**

Designed and developed by **Othniel Etienne** for **Fondasyon Ann Inove**, as an open educational initiative made in Haiti.

- **Live app:** https://mxothniel.github.io/bipartite-arc-method/
- **DOI:** [10.5281/zenodo.XXXXXXX](https://doi.org/10.5281/zenodo.XXXXXXX) *(replace after your first Zenodo release)*
- **Languages:** English, Français, Kreyòl ayisyen, Español

## The originality

Complete graphs (like the handshake problem) are usually drawn as a circle of dots joined by a web of straight lines. By combining a **bipartite layout** (two parallel rows) with an **arc diagram**, this method separates the counting into clear stages:

1. straight lines between the two rows,
2. arcs along the top row,
3. arcs along the bottom row.

For n people, the total is n(n−1)/2. The diagram shows *why*, instead of asking students to memorize the formula.

## What the app does

- **Solve from a total:** enter the number of handshakes *or* the number of people; the diagram is built for you.
- **Build node by node:** add one person at a time and watch the new connections appear. Each newcomer adds exactly (n−1) handshakes.
- **Two groups:** choose the size of group A (top row) and group B (bottom row), for example 12 and 8. The tool counts in stages (straight lines, then arcs of A, then arcs of B) and shows the identity C(a+b, 2) = C(a, 2) + C(b, 2) + a × b live.
- **Step through:** reveal one connection per click.
- Show or hide **letters** and **numbers**.
- **Export as SVG and PNG**, signed with the method's credit line.
- **Art mode:** turns large diagrams into colorful artwork (six palettes, four backgrounds, adjustable line weight), exportable as SVG or PNG. Free for commercial use with credit (CC BY 4.0).
- Four interface languages; adding another takes one block in the `translations` object in `index.html`.

## Use it

Open `index.html` in any browser. No installation, no server, no account.

## Beyond handshakes

The method fits problems where pairs fall into two categories: pairs inside one group (arcs) and pairs between two groups (straight lines). The "Two groups" mode lets you choose the size of each group. Examples:

- **The basic identity** C(a+b, 2) = C(a, 2) + C(b, 2) + a × b (5 + 5 people: 10 + 10 + 25 = 45).
- **Tournaments with pools or conferences** (12 teams in two pools of 6: 30 games inside the pools + 36 between them = 66).
- **Networks on two sites** (6 + 4 computers: 21 internal links + 24 links between sites = 45).
- **Meetings between two delegations** (9 teachers and 6 inspectors: 51 + 54 = 105 meetings).
- **Simple probabilities** (12 girls and 8 boys: 96 mixed pairs out of 190).
- **The number of links of a point** (handshake lemma): everyone has n − 1 links, and the sum of all links is twice the number of pairs.

## Cite this work

> Etienne, O. (2026). *The Othniel Etienne Bipartite-Arc Method* (Version 1.0.0) [Software]. Fondasyon Ann Inove. https://doi.org/10.5281/zenodo.XXXXXXX

GitHub's "Cite this repository" button uses `CITATION.cff`.

## License

- **Code** (`index.html`): [MIT License](LICENSE).
- **The method, its name, text and diagrams:** [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt them, including commercially, **if you credit**:
  *"The Othniel Etienne Bipartite-Arc Method, Othniel Etienne, Fondasyon Ann Inove"*, link to the license, and indicate any changes.

## En français

La **méthode Bipartite-Arc d'Othniel Etienne** répartit les personnes sur deux rangées reliées par des lignes droites et des arcs, pour compter visuellement les poignées de main et autres paires. Conçue et développée par Othniel Etienne pour la Fondasyon Ann Inove (initiative éducative ouverte). Code sous licence MIT ; méthode, textes et schémas sous licence CC BY 4.0 (mention des auteurs obligatoire).

## Nan Kreyòl

**Metòd Bipatit-Ark Othniel Etienne** mete moun yo sou de ranje ki konekte ak liy dwat ak ark, pou konte bay lamen (ak lòt pè) ak je ou. Othniel Etienne konsevwa epi devlope li pou Fondasyon Ann Inove (inisyativ edikatif ouvè). Kòd la sou lisans MIT; metòd la, tèks yo ak dyagram yo sou lisans CC BY 4.0 (dwe site otè yo).

## En español

El **método Bipartito-Arco de Othniel Etienne** reparte a las personas en dos filas unidas por líneas rectas y arcos, para contar visualmente los apretones de manos y otros pares. Diseñado y desarrollado por Othniel Etienne para la Fondasyon Ann Inove (iniciativa educativa abierta). Código bajo licencia MIT; método, textos y esquemas bajo licencia CC BY 4.0 (atribución obligatoria).

## Credits

Othniel Etienne, Fondasyon Ann Inove, https://anninove.org
