# Licenser og implementering

Formålet med dette afsnit er at beskrive offentlige myndigheders overvejelser om brug af open source-licenser, der giver frihed til at bruge, undersøge, ændre og dele kildekoden, og implementering af open source, myndigheden har genbrugt fra hylderne, udviklet selv eller i fællesskab med andre.

Der er ikke noget modsætningsforhold mellem at anskaffe open source-software og betale (en eller flere) leverandører for eksempelvis udvikling, vedligeholdelse eller drift af løsningen. Det kræver ikke desto mindre, at man aftaler at bruge de rigtige licenser, så det f.eks. er muligt at skifte leverandør, og så andre man forbedre kildekoden.

## Licenser

Open source-licenser er softwarelicenser, der tillader, at software frit kan bruges, undersøges, ændres og deles. [Open Source Initiative](https://opensource.org/) har godkendt en lang række licenser som værende open source, men anbefaler, at anvendere som udgangspunkt benytter de licenser, der er "populære og bredt anvendte eller med stærke fællesskaber". Det gælder f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License og Mozilla Public License (MPL) 2.0.

EU-Kommissionen har sin egen open source-licens, [European Union Public License](https://ec.europa.eu/info/european-union-public-licence_en) (EUPL), der er den første europæiske open source-licens. Den findes på 22 sprog og kan anvendes af enhver til at distribuere software. Formålet er at opfordre europæiske myndigheder til at anvende open source-modellen og de tilhørende udviklingsmetoder til at styrke deres software og strategiske kapabiliteter.

Licenser kan indeholde forskellige vilkår, f.eks. at publicerede videreudviklinger skal videregives under samme vilkår (såkaldte *copyleft*-vilkår). Sådanne vilkår kan repræsentere behov for at sikre, at kildekoden ikke bliver genbrugt i proprietære løsninger.

> Figur: Valg af licenstyper (DIGST)

Der er mange forskellige licenser, og det er vigtigt at være bevidst om, at omstændighederne for at anvende open source-software kan ændre sig som følge af licensen. Forskellige licenstyper gør det f.eks. henholdsvis nemmere og sværere at vedligeholde eller overdrage softwaren, hvis man f.eks. indgår i samarbeder med andre myndigheder eller indgår aftale om videreudvikling med en leverandør.

Offentlige myndigheder kan med fordel udarbejde egne, og gerne fælles, strategier for brug af licenser og anbefalinger om, hvilke open source-licenser, man ønsker at anvende, og hvilke man kan acceptere i open source-komponenter, man genbruger.

### Tjekliste til licenser

1.	Er mulighederne for at anvende populære og bredt anvendte licenser i egen udvikling af open source undersøgt?

    Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, kan anvende en af de [godkendte open source-licenser](https://opensource.org/licenses), der er populær og bredt anvendt eller med stærke fællesskaber, f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License og Mozilla Public License (MPL) 2.0.
    
2.	Er risici for licenser med *copyleft* undersøgt?

    Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, kan forholde sig til særligt *copyleft*, hvis de ikke ønsker, at kildekoden kan genbruges i proprietære løsninger.
    
3.	Er mulighederne for at vejlede andre myndigheder om licenser for open source undersøgt? 

    Offentlige myndigheder kan udarbejde egne, og gerne fælles, strategier for brug af licenser og anbefalinger om, hvilke open source-licenser, man ønsker at anvende, og hvilke man kan acceptere i open source-komponenter, man genbruger.
    
4.	Er licensen for en given eksisterende open source-komponent, som skal genbruges, undersøgt? 

    Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan være opmærksomme på, hvilken open source-licens, softwaren er offentliggjort under med henblik på mulighederne for at vedligeholde og dele eller overdrage kildekoden til andre.
    
5.	Er mulighederne for at bruge EU-kommissionens værktøj til at sammenligne softwarelicenser undersøgt?

    Offentlige myndigheder kan bruge EU-kommissionens [værktøj til at finde og sammenligne softwarelicenser](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses) med henblik på at vælge en open source-licens, der passer til den konkrete situation.

6.	Er retlige forpligtelser og omstændigheder for brug af open source-licenser undersøgt? 

    Offentlige myndigheder, der er i tvivl om mulighederne for at kræve eller prioritere brug af (bestemte) open source-licenser ved udbud og anskaffelse af digitale løsninger, kan orientere sig i OS2-fællesskabet og Kammeradvokatens [notat vedrørende OS2-fællesskabet og open source](https://os2.eu/sites/default/files/blog-files/notat_os2_open_source.pdf), der beskriver retlige forpligtelser og omstændigheder for brug af open source-licenser.

7.	Er mulighederne for at frigive evt. leverandørers skriftlige dokumentation som open source undersøgt? 

    Offentlige myndigheder kan sørge for, at skriftligt materiale, der udarbejdes af tilbudsgiver, herunder dokumentation, licenseres under en passende open source-licens, f.eks. en Creative Commons-licens. 

## Implementering

Implementering handler om samarbejdet mellem den offentlige myndighed som ordregiver og tilbudsgiver og senere leverandør af en digital løsning. Ved anskaffelse af open source-software afhænger kravene til implementering en del af den valgte strategi for anskaffelsen.

> Figur: Kompetencer og opgaver (DIGST)

Hvis myndigheden genbruger open source-komponenter fra hylderne, er det ofte svært, men heller ikke nødvendigt, at stille krav til leverandøren om f.eks. licensform eller dokumentation. Det kan imidlertid - over tid - være en mulighed, at myndigheden engagerer sig i et fællesskab omkring komponenten og derigennem påvirker løsningen.

Hvis myndigheden derimod udvikler selv eller i fællesskab med andre, er det relevant at stille en række krav til implementeringen af løsningen. Open source-software er foruden anvendelse af en godkendt open source-licens som beskrevet ovenfor, kendetegnet ved, at løsningen er veldokumenteret, så andre nemt og uden begrænsninger kan genbruge og dele den.

Der er ved implementering også en lang række overvejelser, der knytter sig til den efterfølgende videreudvikling og vedligeholdelse af løsningen, ejerskab til data og dokumentation, brug af åbne standarder og snitflader, der sikrer sammenhængende digitalisering og så videre.

## Tjekliste til implementering

1.	Er der udarbejdet vejledning og dokumentation som kan vedlægges egen udvikling af open source-komponenter?

    Offentlige myndigheder kan ved offentliggørelse af kildekoden vedlægge vejledning og dokumentation, der forklarer, hvad løsningen kan bruges til, og hvordan man kan anvende kildekoden til at bygge og videreudvikle løsningen.

2.	Er mulighederne for at anvende standarder for indeksering af egen udvikling af open source komponenter undersøgt? 

    Offentlige myndigheder kan ved offentliggørelse af kildekoden anvende standarder som f.eks. beskriver kildekoden med henblik på automatisk indeksering af open source-software. Dette giver søgemuligheder på tværs af offentlige myndigheder, sektorer og landegrænser.

3.	Er mulighederne for at få lavet kodereview af egen udvikling af open source komponenter undersøgt? 

    Offentlige myndigheder kan sørge for, at der foretages kodereview af kildekoden. Kodereview kan med fordel foretages af en anden leverandør.

4.	Er mulighederne for at anvende åbne standarder og snitflader undersøgt? 

    Offentlige myndigheder kan stille krav om, at løsningen understøtter åbne (og obligatoriske) standarder og anvender åbne, standardiserede snitflader, herunder at implementering af standarden ikke kræver nogen anden teknologi, der ikke opfylder kriterierne i dette krav, og tilbudsgiver kan redegøre for, hvordan systemet lever op til kravene i aftale om anvendelse af åbne standarder for software i det offentlige og de syv åbne, obligatoriske standarder.

5.	Er mulighederne for at anvende åbne frameworks og kodebiblioteker undersøgt?

    Offentlige myndigheder kan stille krav om, at løsningens komponenter, herunder tekniske standarder, frameworks og kodebiblioteker, er åbne og kan anvendes uden økonomiske eller juridiske begrænsninger både nu og i fremtiden.

6.	Er mulighederne for at anvende en åben datamodel og omkostningsfri adgang til data undersøgt? 

    Offentlige myndigheder kan stille krav om, at løsningen leveres med en åben og fleksibel datamodel og med omkostningsfri adgang til samtlige data i løsningen. Dette betyder, at data gøres tilgængelige for ordregiver på en måde, som ikke forudsætter manuelle processer ud over opsætning og programmering. Desuden gøres  data tilgængelig i et standardiseret og maskinlæsbart databaseformat. Tilgængeligheden skal helst ikke, i mærkbar grad, påvirke den normale driftssituation på den tilbudte løsning. Herudover gøres data tilgængelige efter en aftalt frekvens, som fuld indlæsning eller deltaindlæsning og med metadata om status, tilføjelser og rettelser bestemt af myndighedens behov og informationernes karakter, ligesom at data er kontrolleret for overholdelse af konsistenskrav og valideret med hensyn til type og feltindhold.

7.	Er mulighederne for at sikre myndighedens ejerskab for data undersøgt?

    Offentlige myndigheder kan stille krav om at leverandøren alene er berettiget til at anvende myndighedens data til brug for udførelse af de af kontrakten omfattede leverancer og ydelser. Leverandøren erhverver således hverken ejendomsret, ophavsret eller nogen anden rettighed til myndighedens data, uanset om disse data optræder elektronisk i systemet, i uddatamateriale eller som print. Desuden kan offentlige myndigheder  stille krav om, at ejerskab til alle data tilfalder myndigheden, hvis kontrakten ændres, udløber eller på anden måde bortfalder.

8.	Er mulighederne for at få løbende vedligeholdt datamodel undersøgt? 

    Offentlige myndigheder kan stille krav om, at dokumentation af datamodel (f.eks. E/R-diagram), nøgler, fortolkninger, opdateringsmetoder og tabelstrukturer kan være tilgængelige for ordregiver, og kan vedligeholdes af tilbudsgiver, så oplysninger til enhver tid er ajour.

9.	Er mulighederne for at benytte data til ledelsesdata undersøgt? 

    Offentlige myndigheder kan aftale strukturering af indholdet i snitfladen med ordregivers datavarehusteam, herunder, at enhver ændring af datasnitfladen kan meddeles til ordregivers datavarehusteam i rimelig tid inden ændringen gennemføres, således ordregiver har mulighed for at tilrette de bagvedliggende processer.
