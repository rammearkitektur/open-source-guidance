# Licenser og implementering

Formålet med dette afsnit er at beskriver de godkendte open source-licenser, der muliggør frihed til at bruge, undersøge, ændre og dele kildekoden.

Der er ikke noget modsætningsforhold mellem open source-software og betaling af en eller flere leverandører for udvikling, vedligeholdelse og drift af de digitale løsninger. Det kræver ikke desto mindre, at man aftale at bruge de rette licenser, så det er muligt at skifte leverandør, og mange aktører man bidrage til løbende at forbedre kildekoden.

## Open source-licenser

Open source-licenser er softwarelicenser, der tillader, at software frit kan bruges, undersøges, ændres og deles. [Open Source Initiative](https://opensource.org/) har godkendt en lang række licenser som værende open source, men anbefaler, at anvendere som udgangspunkt benytter de licenser, der er "populære og bredt anvendte eller med stærke fællesskaber". Det gælder f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License og Mozilla Public License (MPL) 2.0.

EU-Kommissionen har sin egen open source-licens, [European Union Public License](https://ec.europa.eu/info/european-union-public-licence_en) (EUPL), der er den første europæiske open source-licens. Den findes på 22 sprog og kan anvendes af enhver til at distribuere software. Formålet er at opfordre europæiske myndigheder til at anvende open source-modellen og de tilhørende udviklingsmetoder til at styrke deres software og strategiske kapabiliteter.

Læs mere om og find alle de [godkendte open source-licenser](https://opensource.org/licenses).

Licenser kan indeholde forskellige vilkår, f.eks. at publicerede videreudviklinger skal videregives under samme vilkår (såkaldte *copyleft*-vilkår). Sådanne vilkår kan repræsentere behov for at sikre, at kildekoden ikke bliver genbrugt i proprietære løsninger.

Der er mange forskellige licenser, og det er vigtigt at være bevidst om, at omstændighederne for at anvende open source-software kan ændre sig som følge af licensen. Forskellige licenstyper gør det f.eks. henholdsvis nemmere og sværere at vedligeholde eller overdrage softwaren, hvis man f.eks. indgår i samarbeder med andre myndigheder eller indgår aftale om videreudvikling med en leverandør.

Offentlige myndigheder kan med fordel udarbejde egne, og gerne fælles, strategier for brug af licenser og anbefalinger om, hvilke open source-licenser, man ønsker at anvende, og hvilke man kan acceptere i open source-komponenter, man genbruger.

> **OS2-fællesskabets brug af licenser**
>
> OS2-fællesskabet benytter open source-licenserne [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/) til kildekode og [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) til dokumentation og andet materiale, der ikke er kildekode. MPL 2.0 er en *file scope*-licens, hvilket vil sige, at filerne og deres indhold er omfattet af licensen. I praksis betyder det, at hvis nogen ændrer filerne, skal ændringerne gives tilbage til OS2.

Offentlige myndigheder kan med fordel anvende EU-Kommissionens [værktøj til at finde og sammenligne softwarelicenser](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses).

Der opstår fra tid til anden spørgsmål om lovligheden af at stille krav om open source-licenser i offentlige it-anskaffelser. Derfor har OS2-fællesskabet sammen med Kammeradvokaten udarbejdet et [open source-notat](https://os2.eu/blog/nu-faar-vi-et-open-source-notat), der beskriver myndighedernes retlige forpligtelser og slår fast, at open source er lovligt for offentlige myndigheder, så længe det varetager egne og borgernes interesser. Udbudsreglerne skal stadig overholdes, og offentlige myndigheder skal handle økonomisk forsvarligt, også når der udvikles under en open source-licens.

Når offentlige myndigheder stiller krav om open source, er det derfor vigtigt at specificere de konkrete krav, der stilles, og listen over godkendte open source-licenser fra Open Source Initiative er derfor et godt udgangspunkt.

### Tjekliste til licenser

1. Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, bør anvende en af de [godkendte open source-licenser](https://opensource.org/licenses), der er populær og bredt anvendt eller med stærke fællesskaber, f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License og Mozilla Public License (MPL) 2.0.
2. Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, bør forholde sig til særligt *copyleft*, hvis de ikke ønsker, at kildekoden kan genbruges i proprietære løsninger.
3. Offentlige myndigheder bør udarbejde egne, og gerne fælles, strategier for brug af licenser og anbefalinger om, hvilke open source-licenser, man ønsker at anvende, og hvilke man kan acceptere i open source-komponenter, man genbruger.
4. Offentlige myndigheder, der genbruger eksisterende open source-komponenter, skal være opmærksomme på, hvilken open source-licens, softwaren er offentliggjort under med henblik på mulighederne for at vedligeholde og dele eller overdrage kildekoden til andre.
6. Offentlige myndigheder kan bruge EU-kommissionens [værktøj til at finde og sammenligne softwarelicenser](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses) med henblik på at vælge en open source-licens, der passer til den konkrete situation.
7. Offentlige myndigheder, der er i tvivl om mulighederne for at kræve eller prioritere brug af (bestemte) open source-licenser ved udbud og anskaffelse af digitale løsninger, kan orientere sig i OS2-fællesskabet og Kammeradvokatens [notat vedrørende OS2-fællesskabet og open source](https://os2.eu/sites/default/files/blog-files/notat_os2_open_source.pdf), der beskriver retlige forpligtelser og omstændigheder for brug af open source-licenser.

## Implementering

## Tjekliste til implementering

8. Offentlige myndigheder bør ved offentliggørelse af kildekoden vedlægge vejledning og dokumentation, der forklarer, hvad løsningen kan bruges til, og hvordan man kan anvende kildekoden til at bygge og videreudvikle løsningen.
9. Offentlige myndigheder bør ved offentliggørelse af kildekoden anvende standarder som f.eks. [publiccode.yml](https://docs.italia.it/italia/developers-italia/publiccodeyml-en/en/master/index.html.), der beskriver kildekoden med henblik på automatisk indeksering af open source-software, der giver søgemuligheder på tværs af offentlige myndigheder, sektorer og landegrænser.

  5. Tilbudsgiver skal levere en veldokumenteret open source-løsning, således at eventuel videreudvikling kan foretages af andre leverandører. Dette inkluderer teknisk dokumentation, herunder systembeskrivelser og arkitekturtegninger. Dermed sikrer man også, at løsninger kan drives videre efter kontraktudløb
  6. Den tekniske dokumentation og koden skal overholde krav og standarder tilhørende den valgte open source-licens. 
  7. Sørg for, at der foretages kodereview af kildekoden
  8. Det er vigtigt at forholde sig til en ”upgrade-strategi”, altså hvordan løsningen kan udvikles og vedligeholdes 
  9. Skal der indgås kontrakt med en drifts- og supportleverandør? 
  10. Al skriftligt materiale jf. ovenstående, som produceres af tilbudsgiver, herunder dokumentation, licenseres under en Creative Commons licens, og det er god skik at nævne de personer der har ydet bidrag til projektet. 
  11. Al software skal leveres til kunden med åbne standarder. Tilbudsgiveren skal sørge for at løsningen har åbne snitflader. 
  12. Løsningen skal bygge på åbne standarder, hvor standarden er veldokumenteret med den fuldstændige specifikation og er offentligt tilgængelig. 
  13. Det er et krav, at udveksling af data mellem løsningen og andre systemer skal ske via åbne standardiserede snitflader, så nuværende og fremtidige behov for systemintegration kan dækkes.
  14. Standarden skal være frit implementérbar uden økonomiske, politiske eller juridiske begrænsninger på implementering og anvendelse hverken nu eller i fremtiden. 
  15. Standarden skal være godkendt og vedligeholdt i et åbent forum (standardiseringsorganisation) via en åben proces. 
  16. Implementering af standarden må ikke kræve nogen anden teknologi, der ikke opfylder kriterierne i dette krav. Tilbudsgiveren skal redegøre for, hvordan systemet lever op til kravene i aftale om anvendelse af åbne standarder for software i det offentlige (B103) og de syv åbne standarder, der trådte i kraft pr. 01.01.2008. 
  17. Det tilbudte system skal leveres med en åben og fleksibel datastruktur og med omkostningsfri adgang til samtlige data i det tilbudte system. 
  18. Alle data der ligger i det tilbudte system skal stilles tilgængelig for ordregiver i overskuelig datamodel. Metadata betragtes som en del af data. Dokumentation af datamodel (f.eks. E/R-diagram), nøgler, fortolkninger, opdateringsmetoder og tabelstrukturer skal være tilgængelig for ordregiver, og skal vedligeholdes af tilbudsgiver, så oplysninger til enhver tid er ajour.
  19. Data skal gøres tilgængelig for ordregiver på en måde, som ikke forudsætter manuelle processer ud over opsætning og programmering. Desuden skal data gøres tilgængelig i et læsbart standarddatabaseformat. Tilgængeligheden må ikke i mærkbar grad påvirke den normale driftssituation på den tilbudte løsning. 
  20. Strukturering af indholdet i snitfladen aftales nærmere med ordregivers datavarehusteam. 
  21. Data skal gøres tilgængelig med aftalt frekvens bestemt af behovet og informationernes karakter. Som udgangspunkt forventes data ’leveret’ om aftenen/natten på daglig/ugentlig basis – i et aftalt miks mellem fuld load og delta load. Ved levering, skal gårsdagens status/tilføjelser/rettelser være tilgængelig i ordregivers datavarehus næste dags morgen. 
  22. Data skal være kontrolleret for overholdelse af konsistenskrav og valideret mht. type og feltindhold. 
  23. Enhver ændring af datasnitfladen skal meddeles til ordregivers datavarehusteam i rimelig tid inden ændringen gennemføres, således ordregiver har mulighed for at tilrette de bagvedliggende processer. 
  24. Leverandøren er alene berettiget til at anvende kundens data til brug for udførelse af de af kontrakten omfattede leverancer og ydelser. 
  25. Leverandøren erhverver hverken ejendomsret, ophavsret eller nogen anden rettighed til kundens data, uanset om disse data optræder elektronisk i systemet eller som print. 
  26. Leverandøren skal behandle kundens data fortroligt i overensstemmelse med persondataloven, aftalte sikkerhedsprocedurer og god IT-skik. 
  27. Det skal fremgå, at hvis kontrakten opsiges eller på anden måde ændres, så skal ejerskab over alle data tilfalde ordregiver
