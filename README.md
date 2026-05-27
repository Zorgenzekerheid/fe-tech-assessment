# Technische Opdracht: Meerstaps Formulier

## Overzicht

Bouw een meerstaps formulier (3 stappen) voor een verzekerings-aanmeldflow.

- Geschatte tijd: max. 4 uur, mocht je niet alles af kunnen ronden is dat geen probleem, wij letten vooral op je onderbouwing.
- Tech stack: React, TypeScript

## Functionele vereisten

### Stap 1: Persoonlijke gegevens

Verzamel de volgende (verplichte) velden:

- Voornaam
- Achternaam
- Geboortedatum
- E-mailadres
- Adres

### Stap 2: Basisverzekering

Fetch de data uit `data.json` om de basisverzekeringen te renderen:

- Naam, prijs & omschrijving.
- Eén optie moet geselecteerd zijn voor je verder kunt.
- Maximaal 1 optie mag geselecteerd zijn.

### Stap 3: Aanvullende verzekeringen

Toon optionele aanvullende verzekeringen.

- Meerdere keuzes zijn mogelijk.
- Toon een overzicht met de totale maandelijkse premie.

### Verzenden

De knop op de laatste stap roept een `handleSubmit`-functie aan met de volledige payload:

```ts
{
	personal: PersonalInfo;
	basicInsurance: Plan;
	additionalInsurance: Addon[];
}
```

## Bonuspunten

- State persistentie, gekozen velden blijven bekend na refresh.
- Een gebruiksvriendelijke en toegankelijke UI.
- Minimaal één unit test.

## Inlevering

Lever een GitHub-repository op met een README waarin minimaal staat:

- Installatie-instructies
- Architectuurkeuzes en eventuele afwegingen
- Wat je anders zou doen met meer tijd
