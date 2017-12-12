# HTMLochCSS_individuell
Individuell uppgift i kursen HTML och CSS.

Uppgift:

"Startup-företaget Arboreal behöver en ny hemsida för sin affärsidé. Ni har fått i uppdrag att skapa denna sida."

https://github.com/fend17/html-css/blob/master/examination/individuell_examination_1.md

Feedback från Fredrik Bruér 2017-12-11:
positivt:
- Bra struktur med korrekt indentering i HTMLen
- Supersnygg header och navigation som följer med när man scrollar sidan
- Sidan är i stort sett responsiv
- Fina och passande bilder som livar upp sidan
- Intressant och snyggt val av hur de olika prisalternativen presenteras i en mer unik stil
  istället för i ett vanligt table-format (lite mer padding i boxarna med punkterna skulle dock inte skada!!)
- Stilpoäng för lite javascript när man trycker på "send"-knappen
allmänt:
- När man trycker på länkarna i navigationen hamnar man inte alltid på en position där man kan
  se aktuell rubrik, vilket kan vara lite förvirrande för användaren.
- Mer padding på en del av sidans element skulle kunna behövas - t.ex. i övre delen av footern
- Större radavstånd i textstyckena skulle kunna göra sidan lite mer luftig och lättläst

html:
- Label-elemeten är inte kopplade till input-elementen i formuläret (genom id-attribut)
- Det finns inga kontroller att formuläret har blivit rätt ifyllt (se nedre punkt)
- Formuläret saknar ett input-element av typen "submit", vilket ett fungerande formulär måste
  ha (så vitt jag vet). Kanske inte är nödvändigt till den här uppgiften, men värt att notera.
- Slogan-texten i headern borde kanske inte vara inne i en h3-tagg då det inte är en rubrik
- Texten "Contact information" borde vara ett h3-element istället för h4, då rubriken över i
  DOM:en är ett h2-element.
- Article-elementen borde kankse vara av typen section istället? detta är nog en smaksak dock.

css:
Ser överlag bra ut tycker jag, hittar bara småbrister som några överflödiga deklarationer och upprepningar - t.ex.:
- Man kan ta bort "list-style: none" i "price ul"-selektorn
- Istället för att ange font-family på två ställen kan man använda * -selektorn för att välja
  samtliga element
- Att h3-elementen ska vara centrerade anges tre gånger
Det är typ dom bristerna jag kan se... jag suger på CSS och skriver antagligen mer överflödiga saker än vad jag kunde hitta i din kod :-).
