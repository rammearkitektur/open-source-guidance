# Anskaffelse

Formålet med dette afsnit er at skitsere de forskellige strategier for anskaffelse af software hos offentlige myndigheder. Det er ikke et spørgsmål om enten-eller, men derimod om at vælge den anskaffelsesstrategi, der passer bedst til den konkrete situation. 

Processen for anskaffelse er inddelt i tre faser, der omfatter henholdsvis strategi og markedsafdækning, anskaffelse og implementering og vedligeholdelse og videreudvikling.

> Figur: Proces for it-anskaffelser (DIGST)

Open source-software og proprietære løsninger kan sagtens sameksistere, hvis man vælger forskellige strategier fra gang til gang, og processen for anskaffelse er stort set den samme. Det kræver dog forskellige kompetencer, og valg af licenser er en af dem.

## Strategier for brug af open source

Overordnet er der tre strategier for anskaffelse af open source, som offentlige myndigheder kan anvende:

  * **Myndigheden genbruger fra hylderne**<br>
    Offentlige myndigheder, der anvender denne strategi, genbruger eksisterende open source-software, hvor det er relevant. Det kan være komponenter eller enkeltstående applikationer, der er gode eller billige alternativer til proprietære løsninger. Denne strategi omfatter også myndigheder, der er mindre bevidste om, at de anvender open source.
  * **Myndigheden udvikler selv**<br>
    Offentlige myndigheder, der anvender denne strategi, udvikler selv løsninger, der foruden at anvende eksisterende open source-komponenter udgives under en open source-licens. Det kan være for at stille software til rådighed for andre myndigheder eller virksomheder for at øge anvendelsen eller få andre til at bidrage til vedligeholdelsen.
  * **Myndigheden udvikler i fællesskab**<br>
    Offentlige myndigheder, der anvender denne strategi, udvikler i fællesskab med andre løsninger, der lever op til ovenstående. Det kan være for at dele risici og omkostninger med andre myndigheder eller virksomheder og skabe et fællesskab omkring vedligeholdelse af løsningen eller en række løsninger i et økosystem.

> Figur: Open source-anskaffelsesstrategier (DIGST)

Med andre ord er der forskellige strategiske årsager til at genbruge eksisterende open source-software og udvikle open source-software selv eller i fællesskab med andre. De forskellige strategier har hver deres fordele, men kræver også noget af myndigherne i form af kompetencer.

Det er også vigtigt at påpege, at open source-software findes på alle hylder i softwarestakken. Det kan være basisteknologi som styresystemer, hvor Linux er meget udbredt på servere, eller databasesoftware som MySQL. En af de mest populære softwarestakke til webapplikationer består af de fire komponenter Linux, Apache, MySQL og PHP, Perl og Python (LAMP).

> Figur: Open source findes på alle hylder i softwarestakken (DIGST)

At kildekoden er åben og frit kan genbruges, betyder ikke kun, at en myndighed kan dele sin open source-software med en anden myndighed. Det betyder også, at den anden myndighed kan forbedre softwaren og derefter dele den forbedrede løsning med den første myndighed og med andre. På den måde kan der være flere om at forbedre softwaren og finansiere fremtidige ønsker til videreudvikling.

### Tjekliste til anskaffelsesstrategier

1. Offentlige myndigheder kan have en overordnet strategi for brug af open source, men bør fra anskaffelse til anskaffelse overveje fordele og ulemper og den konkrete værdiskabelse ved anvendelse af open source.
2. Offentlige myndigheder, der ønsker at udvikle og tilbyde open source-software til andre, bør forholde sig til risici, behov for tekniske kompetencer og omkostninger ved egenudvikling kontra udvikling sammen med andre.
3. Offentlige myndigheder bør sikre sig de rette kompetencer til at arbejde med open source, uanset om det er genbrug af open source-komponenter, egenudvikling eller udvikling i fællesskab.
4. Offentlige myndigheder bør danne sig et overblik over brug af open source-software på forskellige niveauer i softwarestakken og anvende en helhedsorienteret tilgang til anskaffelser, der udnytter synergier mellem software som f.eks. de populære open source-softwarestakke LAMP og MEAN.

## Licenser

Open source-licenser er softwarelicenser, der tillader, at software frit kan bruges, forbedres og deles. [Open Source Initiative](https://opensource.org/) har godkendt en række licenser, men anbefaler, at man som udgangspunkt benytter de licenser, der er "populære og bredt anvendte eller med stærke fællesskaber", f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License eller Mozilla Public License (MPL) 2.0.

Læs mere om og find alle de godkendte open source-licenser under [Licenses & Standards](https://opensource.org/licenses).

Licenser kan indeholde forskellige vilkår, f.eks. at publicerede videreudviklinger skal videregives under samme vilkår (såkaldte *copyleft*-vilkår). Dette element kan være vigtigt i henhold til at sikre, at kildekoden ikke bliver genbrugt i proprietære løsninger.

Der er forskellige licenser, og det er vigtigt at være bevidst om, at betingelserne for at anvende open source-software kan ændre sig. Forskellige licenstyper gør det hhv. nemmere og sværere at vedligeholde og overdrage softwaren. Offentlige myndigheder kan med fordel udarbejde egne eller fælles strategier og anbefalinger om, hvilke open source-licenser, man ønsker at anvende, hivlke man kan acceptere og i hvilke situationer eller anvendelsesscenarier.

> **OS2-fællesskabets brug af licenser**
>
> OS2-fællesskabet benytter open source-licenserne [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/) til kildekode og [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) til dokumentation og andet materiale, der ikke er kildekode. MPL 2.0 er en "file scope"-licens, hvilket vil sige, at filerne og deres indhold er omfattet. I praksis betyder det, at hvis nogen ændrer i filerne, skal ændringerne gives tilbage til OS2.

Det er også muligt at anvende EU-Kommissionens [værktøj til at finde og sammenligne softwarelicenser](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses).

Der opstår fra tid til anden spørgsmål om lovligheden af at bruge open source-licenser i offentlige it-anskaffelser. Derfor har OS2-fællesskabet sammen med Kammeradvokaten udarbejdet et [open source-notat](https://os2.eu/blog/nu-faar-vi-et-open-source-notat), der beskriver de retlige forpligtelser for deltagelse i fællesskabet og slår fast, at open source er lovligt for offentlige myndigheder, så længe det varetager egen opgaveløsning og borgernes interesser. Udbudsreglerne skal stadig overholdes, og myndigheder skal handle økonomisk forsvarligt. Det gælder også, når der udvikles under en open source-licens.

Når offentlige myndigheder stiller krav om open source, er det desuden vigtigt at specificere de konkrete krav, der stilles, og dertil kan listen over anerkendte licenser fra Open Source Initiative være en støtte.

### Tjekliste til open source-licenser

1. Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, bør anvende en open source-licens, der er populær og bredt anvendt eller med stærke fællesskaber.
2. Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, bør forholde sig til særligt *copyleft*, hvis de ikke ønsker, at kildekoden kan genbruges i proprietære løsninger.
3. Offentlige myndigheder bør som kunder have egne eller fælles strategier og anbefalinger om, hvilke open source-licenser, man ønsker at anvende, hivlke man kan acceptere og i hvilke situationer.
4. Offentlige myndigheder, der genbruger open source-komponenter fra hylderne, skal være opmærksomme på, hvilken open source-licens, softwaren er offentliggjort under med henblik på governance og muligheder for at vedligeholde og overdrage softwaren.
6. Offentlige myndigheder kan bruge EU-kommissionens [værktøj til at finde og sammenligne softwarelicenser](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses) med henblik på at vælge en open source-licens, der bedst imødekommer deres behov.
7. Offentlige myndigheder, der er i tvivl om mulighederne for at kræve eller prioritere brug af (bestemte) open source-licenser ved udbud og anskaffelse af digitale løsninger, kan orientere sig i OS2-fællesskabet og Kammeradvokatens [notat vedrørende OS2-fællesskabet og open source](https://os2.eu/sites/default/files/blog-files/notat_os2_open_source.pdf), der beskriver de retlige forpligtelser og omstændigheder for brug af open source-licenser.

## Tjekliste til anskaffelse

  1. Al software skal leveres til kunden under en Open Source-softwarelicens godkendt af Open Software Initiative. Det kan fx væ-re Mozilla Public Licensen 2.0 https://www.mozilla.org/MPL/2.0/.  
  2. Er produktet tilgængeligt på Github? Github er et godt sted at starte sin søgning efter Open Source-projekter/løsninger
  3. Ved ny – og videreudvikling skal kildekoden publiceres på et offentligt tilgængeligt repository, fx GitHub. 
  4. Sammen med kildekoden skal det være muligt at hente vejledninger og dokumentation, der forklarer, hvordan man anvender kildekoden til at bygge og implementere løsningen. Hermed opnår kunden ejerskab og rettigheder til materialet. I forbindelse med at åbne op for kildekoden er et vigtigt skridt dokumentationen. 
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

## Eksisterende løsning

 1. Findes der god og dokumentation: "Sådan kommer du i gang", "Sådan kommer du videre", "Sådan bidrager du"? dækkende information om anvendelse, setup og bidrag
 2. Ser det ud til at være under aktiv udvikling, hvornår var seneste commit til source koden, hvornår var seneste release, hvornår var seneste kommentar eller statusskift på et rapporteret issue?
 3. Er der mange issues med softwaren, hvilke typer af issues er det, er det ændringsforslag og forslag til ny funktionalitet, ellerer det bug-rapporter? danne sig et indtryk af, om issues bliver løst og om der arbejdes aktivt på projekterne. Det betyder fx, at der bør være adgang til/links til Issue lister
 4. Er der et åbent community forum, med folk der bidrager til at løse issues, og hvor brugerne udveksler erfaringer og hjælper hinanden? 
