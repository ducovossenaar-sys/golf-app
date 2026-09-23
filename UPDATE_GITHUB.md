# Update naar v0.2

1. Pak de ZIP uit.
2. Kopieer alle bestanden uit deze map naar de hoofdmap van je bestaande `golf-app` repository.
3. Kies **Bestanden in de bestemming vervangen**.
4. Open GitHub Desktop.
5. Summary: `Golf app v0.2 GPS kaart`.
6. Klik **Commit to main**.
7. Klik **Push origin**.
8. Wacht 1-2 minuten en open de app opnieuw. Sluit de geïnstalleerde PWA eventueel volledig af en start hem opnieuw zodat de nieuwe service worker actief wordt.

## Nieuw in v0.2
- OpenStreetMap kaart in het ronde-scherm.
- Live GPS met nauwkeurigheidsindicatie.
- Centreren op je huidige positie.
- GPS-positie wordt bij een slag lokaal opgeslagen.
- Zodra je de volgende slag op een andere positie registreert, wordt de afstand van de vorige slag automatisch berekend.

De kaarttegels hebben internet nodig. GPS zelf gebruikt de locatievoorziening van de telefoon.
