# Dokumentation — Tag 05 Praxis

<!--
  Vorlage. Ersetze jeden <Platzhalter> durch deine eigene Analyse.
  Welche Angaben pro Abschnitt zwingend sind, steht im README unter
  "Format der Abgabe-Dateien". Diese Kommentarzeilen darfst du loeschen.
-->

**Gruppe:** <Milos Radovanovic>

## Auftrag 1 — Broken Pipeline

| Workflow | Symptom (wo bricht der Lauf ab?) | Ursache | Fix |
| --- | --- | --- | --- |
| a1-hello.yml | runs-on ist falsch eingerückt | <...> | runs-pn richtig einrücken |
| a2-actions.yml | actions/setup-pyton falsch geschrieben | schreibfehler python | pyton auf --> python korrigiert |
| a3-deps.yml | Beim ausführen von Requirements.txt | Pytest ist nicht in Requirements.txt aufgelistet | pytest in Requirements aufgenommen |
| a4-tests.yml | Ausführen von working-directory: src | Falscher Testpfad angegeben weil src nicht existiert | working-directory: src rauslöschen |

## Auftrag 2 — PR-Gate

### Regeln auf `main`

<Wie heisst das Regelwerk, mit dem GitHub einen Branch absichert, und welche
Regeln wuerdet ihr setzen?>

### Pull Request mit rotem Check

- Pull Request: <Nummer oder Link>
- Welcher Check war rot und warum: <...>
- Wie repariert: <...>

## Auftrag 3 — Laufzeit

| Messung | Dauer von `ci.yml` |
| --- | --- |
| <Messpunkt 1> | <...> |
| <Messpunkt 2> | <...> |

**Trade-off der Parallelisierung:** <...>
