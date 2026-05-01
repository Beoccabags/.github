# Contributing

Bedankt voor je interesse in bijdragen aan een Beocca repo. Dit document beschrijft hoe we werken zodat je zonder ruis kunt beginnen.

Lees ook de [engineering conventions](./README.md) voor branch- en commit-afspraken.

## Voor je begint

1. Check of er al een issue bestaat voor wat je wilt doen. Zo niet, open er een, ook voor jezelf, het helpt scope vast te leggen.
2. Voor grotere wijzigingen: stem eerst de aanpak af in het issue voordat je code schrijft. Voorkomt dat een PR wordt afgewezen om een richting die in een paar minuten gesprek opgelost was.
3. Trivia (typo's, kleine docs-fixes) mag direct als PR.

## Workflow

1. Fork of branch (afhankelijk van toegangsrechten).
2. Maak een branch volgens de [naming conventions](./README.md#branch-naming).
3. Commit in logische stappen, met conventional commit messages.
4. Open een PR — `Draft` als hij nog niet klaar is.
5. Vink de checklist in het PR template af.
6. Vraag review aan zodra CI groen is.

## Lokale setup

Per repo verschillend. Check de `README.md` van de repo zelf voor:

- Vereiste runtime-versies (Node, Python, etc.)
- Environment variables (`.env.example`)
- Hoe je dev-server / tests draait

Als die info ontbreekt, dat is een issue waard — open er een.

## Code stijl

- Volg de bestaande stijl van de repo. Geen drive-by reformatting in feature-PRs.
- Linter/formatter draait in CI. Lokaal aanzetten scheelt heen-en-weer.
- TypeScript/SwiftUI/Python: types zijn niet optioneel.
- Comments leggen *waarom* uit, niet *wat*. De code zegt al wat.

## Tests

- Nieuwe functionaliteit: voeg tests toe waar dat zinnig is.
- Bugfixes: voeg een test toe die de bug reproduceert, zodat hij niet terugkomt.
- "Het is te klein om te testen" is meestal een prima reden om het toch even te doen.

## Reviews

- Reageer binnen redelijke tijd op review comments — een paar dagen is prima, twee weken niet.
- Comments zijn over de code, niet over de persoon. Geldt beide kanten op.
- Een approve betekent: "ik zou dit zelf zo gemerged hebben." Niet: "ziet er ongeveer goed uit."

## Security

Vond je een security issue? Open er **geen** publiek issue voor. Zie [SECURITY.md](./SECURITY.md) voor het juiste kanaal.

## Licentie

Door een PR in te dienen ga je akkoord dat je bijdrage onder dezelfde licentie valt als het project zelf.
