# antonathley-v41-examination

Instruktioner för hur man öppnar och navigerar på webbplatsen:

- Clona repot, https://github.com/AntonAthley/antonathley-v41-examination.git , öppna i valfri kod-editerare eller i webbläsare. Alternativt kan du zippa filen direkt från github.

Kortfattad teknisk beskrivning av hur jag uppfyllde kraven:

- HTML-struktur: Försökte från början att vara så tydlig som möjligt när jag namngav grejer, så att det skulle vara så lättläst som möjligt. Använde header, nav, main, section och footer, utöver alla divs och la till alt texter på samtliga bilder.

- CSS - Flexbox, grid och clamp: Använde framförallt grid på hemsidan för att placera bilderna i ett bildgalleri efter mina önskemål, sen uteslutande flexbox på triviasidan för att hålla det enkelt och responsivt. Clamp användes för samtliga texter i navbar, samt i majoriteten av footern.

- Responsivitet: Använde mycket %, grid fractions och flexbox för att från början ha det så responsivt som möjligt. Utöver det använde jag media queries för liten mobil, stor mobil och padda.

- Tillgänglighet, alt, aria etc: Det användes där jag upplevde att det behövdes, tex alt på bilder och aria labels på ikonerna i footern.

- Webbläsarverktyg: Jag använde det under hela processen för att kolla responsivitet mellan skärmstorlekarna. Testade även med lighthouse ett flertal gånger under processen för att säkerställa att allt var tillgängligt och bra.

- Git: Commitade så fort jag blev klar med en feature, just nu är det på 8 commits över två branches. Använde en andra branch när jag jobbade med trivia-sidan.
