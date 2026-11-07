# Inlämningsuppgift
Här är repot för din inlämningsuppgift.

Om filerna:
- `.gitignore` - Denna fil används för att ignorera/exkludera vissa systemfiler som inte behöver komma med i versionshanteringen. En sådan bör man alltid ha i sitt repo.
- `index.html` - För att sidan ska kunna publiceras automatiskt på GitHub Pages är det viktigt att filen heter `index.html` med ett litet `i` i början.
- I mappen `.github` finns ett script som automatiskt publicerar sidan till GitHub Pages.
- I mappen `.github` finns även instruktioner för hur CoPilot ska ge feedback på koden.
- Det går bra att redigera denna README-fil.

Din uppgift är att ta fram en (fiktiv) konferens-sida. Konferens-sidan ska innehålla följande information:

Schema/program med tid, programpunktens "titel", talarens namn och en kort beskrivning av innehållet på "föreläsningen". Du ska ha med minst 5 programpunkter.
Ett "galleri" över talarna på konferensen. Du ska ha med minst 5 talare.
Biljettnivåer, här får du hitta på egna. T.ex. "Student", "After Work", "Utställare", osv. Du ska ha minst 3 biljettnivåer.
Det ska finnas praktisk information, t.ex. adress, karta (en statisk bild, ska ej vara en interaktiv karta), osv.
Du får välja tema själv på konferensen, det kan handla om blockchain, crypto, katter, astrologi…
Det går jättebra att använda AI för att slutföra uppgiften. Lägg fokus på att lära dig förstå begrepp och koncept inom CSS under tiden som du jobbar med uppgiften, så att du blir effektiv i din promptning.

Tips/övning! Sätt en "budget" för dig själv, t.ex. att du har max 10 promptar på dig för att slutföra uppgiften. Därefter måste du "koda allt själv". Fundera på hur långt du har kommit efter t.ex. 3 promptar, och om du behöver läsa på om något/förstå något, för att kunna slutföra uppgiften på resterande 7 promptar.

Det räcker med en s.k. "one-pager" för uppgiften, du behöver inte skapa separata sidor.

Kravlista
Du ska använda ett "ramverk" eller en pre-processor för att ta fram sidans CSS, t.ex. Sass eller Tailwind.
Även om du använder Tailwind eller motsvarande, ska du skriva minst 5 selektorer själv.
Du ska använda minst 3 "avancerade" CSS-selektorer, t.ex.:
barn- eller syskonselektorer (child & sibling combinators)
pseudo-klasser (pseudo classes, structural pseudo classes)
pseudo-element (pseudo elements)
attribut-selektorer
Du ska ha med minst en CSS-animation
Det ska finnas stöd för ljust/mörkt tema i grundläggande form, dvs. du demonstrerar att du vet hur du anpassar sidan till ljust/mörkt läge. Det behöver inte vara perfekt och allt behöver inte vara på plats. Det räcker med prefers-color-scheme, ingen JavaScript/toggle-knapp krävs. Du kan testa tema via DevTools så behöver du inte ändra i ditt operativsystem.
Det ska finnas med minst 1 hover-effekt, t.ex. om man för musen över ett talarkort så ska det visas någon extra information. Det kan t.ex. vara en annan bild, kontaktuppgifter, att bilden blir svartvit, eller något annat. Effekten ska även fungera vid tangentbordsnavigering.
Sidan ska vara responsiv på mobil, tablet och desktop.
Det ska finnas en navigation/meny som hoppar till rätt sektion på sidan, t.ex. om jag klickar på "Talare" i menyn så ska jag scrollas ner till sektionen som visar alla talare.