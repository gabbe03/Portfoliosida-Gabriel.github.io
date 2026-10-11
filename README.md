# Portfoliosida

Från skiss till kod började jag med skissens ramar 1600px för desktop och 600 för mobil, jag byggde mobil versionen först och la till desktop med en brytpunkt. Jag satte font-size på alla htmlar till 62.5% så att 1 rem = 10 px sedan kopierade jag måtten från figmas skiss. Jag kopierade färgerna också från figma och la till dem som variablar i css så jag lätt kan använda dom till alla sidor. Det svåra var mest att göra gradient färgerna exakt som hans eftersom det står inte hur mycket av en färg han använder, och mobil läge var svårt att göra eftersom jag inte kan se måtten.

Jag använde header, main och footer till alla sidor, två nav i header en för huvudmenyn och andra för ikonerna. En h1 i varje sida och h2 för sektioner. ul och li för tech stack-ikoner, projektkort och menyer, eftersom det är listor. firgure för profilbilden i home. Jag har några divar i about och project för jag hitta inga bättre element.

Jag använde Grid där det är två dimensioner så som headern på mobil och rutnäten, med techstack ikoner och projektkort. Flex använde jag där det är en dimension som typ desktopmenyn, ikonraden, rader med ikon och text, och kort-innehåll. Body är också flex, så att footern hamnar längst ner. Jag gjorde den responsiv med mobil först 800px då vissa element gick utanför skärmen. Jag använde clamp och rem så text skalar mellan brytpunker.

Jag har semantiska element och logisk rubrikordning, aria-label på båda nav i headern, alt texter för alla bilder. Jag har en hamburgar meny för mobil läget och menyn fungerar med tangentbord, eftersom details har det inbyggt. Sist gjorde jag mörkt läge också för alla sidor. Jag testade det i chrome dev tools med 600px läge och 1600px samt ändrade jag imellan dom, jag tabbade igenom alla sidor och det funkade bra.

Jag känner igen dens tydliga visuella hierarki, stora rubriker med gradient, fet navigation och mycket luft. Samma header och footer på alla sidor, projektkort och ikonrutnät är lätta att ta in snabbt och hamburgermeny på mobil, horisontell meny på desktop. Jag hade lagt till så att den aktuella sida i menyn markeras tydligare.

Det som blev bra är att sajten följer skissen nära, CSS:en är strukturerad i filer så som variables.css, base.css, en fil per sida och dark.css. Alla färger ligger som variabler och allt fungerar utan JavaScript. Det jag skulle ändra är hur header och footer upprepas i varje HTML-fil. Med mer tid och kunskap hade de legat på ett ställe.

Jag använde mest calude för att snabbt göra layouten till sidorna sen la jag till måtten själv för alla element i css.

http://127.0.0.1:5500/pages/project.html
