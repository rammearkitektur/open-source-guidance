# Licenser og implementering

Formålet med dette afsnit er at beskrive offentlige myndigheders overvejelser om brug af open source-licenser, der giver frihed til at bruge, undersøge, ændre og dele kildekoden, og implementering af open source, myndigheden har genbrugt fra hylderne, udviklet selv eller i fællesskab med andre.

Der er ikke noget modsætningsforhold mellem at anskaffe open source-software og betale (en eller flere) leverandører for eksempelvis udvikling, vedligeholdelse eller drift af løsningen. Det kræver ikke desto mindre, at man aftaler at bruge de rigtige licenser, så det f.eks. er muligt at skifte leverandør, og så andre man forbedre kildekoden.

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
8. Offentlige myndigheder bør sørge for, at skriftligt materiale, der udarbejdes af tilbudsgiver, herunder dokumentation, licenseres under en passende open source-licens, f.eks. en Creative Commons-licens. 

## Implementering af open source

Implementering handler om samarbejdet mellem den offentlige myndighed som ordregiver og tilbudgiver og senere leverandør af en digital løsning. Ved anskaffelse af open source-software afhænger kravene til implementering en del af den valgte strategi for anskaffelsen.

Hvis myndigheden genbruger open source-komponenter fra hylderne, er det ofte svært, men heller ikke nødvendigt, at stille krav til leverandøren om f.eks. licensform eller dokumentation. Det kan imidlertid - over tid - være en mulighed, at myndigheden engagerer sig i et fællesskab omkring komponenten og derigennem påvirker løsningen.

Hvis myndigheden derimod udvikler selv eller i fællesskab med andre, er det relevant at stille en række krav til implementeringen af løsningen. Open source-software er foruden anvendelse af en godkendt open source-licens som beskrevet ovenfor, kendetegnet ved, at løsningen er veldokumenteret, så andre nemt og uden begrænsninger kan genbruge og dele den.

Der er ved implementering også en lang række overvejelser, der knytter sig til den efterfølgende videreudvikling og vedligeholdelse af løsningen, ejerskab til data og dokumentation, brug af åbne standarder og snitflader, der sikrer sammenhængende digitalisering og så videre.

## Tjekliste til implementering

1. Offentlige myndigheder bør ved offentliggørelse af kildekoden vedlægge vejledning og dokumentation, der forklarer, hvad løsningen kan bruges til, og hvordan man kan anvende kildekoden til at bygge og videreudvikle løsningen.
2. Offentlige myndigheder bør ved offentliggørelse af kildekoden anvende standarder som f.eks. [publiccode.yml](https://docs.italia.it/italia/developers-italia/publiccodeyml-en/en/master/index.html.), der beskriver kildekoden med henblik på automatisk indeksering af open source-software, der giver søgemuligheder på tværs af offentlige myndigheder, sektorer og landegrænser.
3. Offentlige myndigheder bør sørge for, at der foretages kodereview af kildekoden. Kodereview kan med fordel foretages af en anden leverandør.
4. Offentlige myndigheder bør stille krav om, at løsningen understøtter åbne (og obligatoriske) standarder og anvender åbne, standardiserede snitflader. 
5. Offentlige myndigheder bør stille krav om, at løsningens komponenter, herunder tekniske standarder, frameworks og kodebiblioteker, er åbne og kan anvendes uden økonomiske eller juridiske begrænsninger både nu og i fremtiden. 
6. Offentlige myndigheder bør så vidt muligt kun anvende standarder, der er godkendt og vedligeholdt i et åbent forum (standardiseringsorganisation) ved hjælp af en åben proces. 
7. Offentlige myndigheder skal sørge for, at implementering af standarden ikke kræver nogen anden teknologi, der ikke opfylder kriterierne i dette krav, og tilbudsgiver skal redegøre for, hvordan systemet lever op til kravene i [aftale om anvendelse af åbne standarder for software i det offentlige](https://www.digitaliser.dk/resource/3778907/) og de syv åbne, obligatoriske standarder.
8. Offentlige myndigheder bør stille krav om, at løsningen leveres med en åben og fleksibel datamodel og med omkostningsfri adgang og ejerskab til samtlige data i løsningen.
9. Offentlige myndigheder bør stille krav om, at dokumentation af datamodel (f.eks. E/R-diagram), nøgler, fortolkninger, opdateringsmetoder og tabelstrukturer skal være tilgængelige for ordregiver, og skal vedligeholdes af tilbudsgiver, så oplysninger til enhver tid er ajour.
10. Offentlige myndigheder bør stille krav om, at data gøres tilgængelige for ordregiver på en måde, som ikke forudsætter manuelle processer ud over opsætning og programmering. Desuden skal data gøres tilgængelig i et standardiseret og maskinlæsbaart databaseformat. Tilgængeligheden må ikke i mærkbar grad påvirke den normale driftssituation på den tilbudte løsning. 
11. Offentlige myndigheder bør aftale strukturering af indholdet i snitfladen med ordregivers datavarehusteam. 
12. Offentlige myndigheder bør stille krav om, at data gøres tilgængelige efter en aftalt frekvens, som fuld indlæsning eller deltaindlæsning og med metadata om status, tilføjelser og rettelser bestemt af myndighedens behov og informationernes karakter.
13. Offentlige myndigheder bør stille krav om, at data skal være kontrolleret for overholdelse af konsistenskrav og valideret med hensyn til type og feltindhold. 
14. Offentlige myndigheder bør stille krav om, at enhver ændring af datasnitfladen skal meddeles til ordregivers datavarehusteam i rimelig tid inden ændringen gennemføres, således ordregiver har mulighed for at tilrette de bagvedliggende processer. 
15. Leverandøren er alene berettiget til at anvende myndighedens data til brug for udførelse af de af kontrakten omfattede leverancer og ydelser. 
16. Leverandøren erhverver hverken ejendomsret, ophavsret eller nogen anden rettighed til myndighedens data, uanset om disse data optræder elektronisk i systemet, i uddatamateriale eller som print.
17. Leverandøren skal behandle myndighedens data med henblik på fortrolighed, integritet og tilgængelighed i overensstemmelse med databeskyttelseslovgivning, aftalte sikkerhedsprocedurer og god it-skik. 
