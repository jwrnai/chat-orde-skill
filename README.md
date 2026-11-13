# chat-orde

Een skill voor Claude die je chatlijst opruimt.

## Wat het doet
Na een paar weken staat je zijbalk vol met "Naamloze chat", drie keer "Mail opstellen" en "Maak het korter". Je vindt niets meer terug. Plak je chatlijst in Claude en deze skill:

1. zet elke chat in één van hooguit 7 mappen, geordend op klant, project of vast werk (op claude.ai worden dat Projects);
2. geeft elke chat een titel die je terugvindt: eerst het onderwerp, dan wat het oplevert;
3. haalt je vaste vragen eruit en maakt er een promptbibliotheek van, met je wensen er al in;
4. maakt van één lange chat een inhoudsopgave met per blok een zoekwoord, zodat je met Ctrl+F meteen bij het goede stuk bent.

Hij gooit niets weg en verzint niets: wat onduidelijk is, gaat naar "Nakijken".

## Installeren in 3 stappen
1. Download of clone deze map.
2. Zet de map `chat-orde` in `~/.claude/skills/` (of plak in Claude Code: "Maak hier de skill chat-orde van.").
3. Typ in Claude Code `/chat-orde` en plak daarna je chatlijst (de titels uit je zijbalk, of je export uit de instellingen van Claude), eventueel met één lange chat erbij.

## Wat erin zit
- `chat-orde/SKILL.md`: de skill zelf.
  - Drie soorten rommel: leeg, dubbel, taak zonder onderwerp.
  - Mappen: hooguit 7, elke chat precies één plek.
  - Titels: onderwerp eerst, max 6 woorden.
  - Promptbibliotheek: hooguit 4 vaste prompts.
  - Inhoudsopgave van een lange chat, met zoekwoorden.
  - Regels: Nederlands, kort, niets verzinnen, niets weggooien.

## Waar het op leunt
- David Allen, *Getting Things Done*: alles een vaste plek, één systeem dat je vertrouwt.
- Tiago Forte, *Building a Second Brain*: PARA, orden op waar je aan werkt in plaats van op onderwerp, en bewaar wat je opnieuw gebruikt.
- Johnny Noble, *Johnny.Decimal*: een klein, vast aantal vakken.
- Onze eigen regels: kort, Nederlands, alleen wat er echt staat.

Licentie: MIT.
