# Anskaffelse

Ved it-anskaffelser bør der først og fremmest udarbejdes en business case, der klargør de mulige gevinster, omkostninger og risici, der er forbundet med valg af forskellige produkter, uanset om det software baseret på open eller closed source. 

Open source og closed source-løsninger kan godt sameksistere og det behøver ikke at være et spørgsmål om enten-eller, og processen vedrørende indkøb behøver heller ikke at være særligt forskellige.

## Forskellige scenarier

Overordnet er der tre forskellige scenarier, når det vedrører anvendelse af open source:

  * Myndigheden udvikler selv open source-software 
  * Myndigheden stiller krav til leverandører om anvendelse af open source-software, når disse leverer produkter og projekter til den offentlige sektor?
  * Myndigheden ønsker genbrug af software og komponenter, som den offentlige sektor har investeret i på tværs af kommuner/regioner/staten

Med andre ord er det vigtigt at holde sig for øje, at der er forskel på køb af en open source-løsning der allerede eksisterer og en anskaffelse, der handler om udvikling af open source-software, mere eller mindre fra bunden. Myndigheder kan således både være brugere af eksisterende open source-software eller være licensgivere, som kan stille software til rådighed for andre myndigheder eller andre aktører.
Det handler om hvad der skaber mest værdi og bedste business case i de enkelte situationer, men det er vigtigt at have de strategiske overvejer tidligt og allerede i idéfasen af projektet og måske allerede inden, der overhovedet er en projektleder. 

Derudover behøver indkøb af open source ikke at være ret meget anderledes end closed source. Det kan dog kræve, at man husker at lave gode drifts – og support aftaler med en leverandør i forbindelse med indkøb. At stille krav om open source, hvis det er relevant ift. markedet i et udbud, der vedrører it-anskaffelser, fremmer den åbne konkurrence, der er det grundlæggende formål med udbudsreglerne. 

> Evt. boks med tegning her: Løsning fra bund til top: abstrakt tegning af, hvor der kan være open source i porteføljen 

Der principielt ikke noget til hinder for, at ordregiver køber eller på anden vis betinger, at programmet kan benyttes, ændres og stilles til rådighed for almenheden under en open source-licens. 

At kildekoden er åben og frit kan genbruges, betyder ikke blot at én myndighed kan videredistribuere sin open source-software til en anden myndighed. Det betyder også, at den anden myndighed kan forbedre softwaren og derefter igen dele det forbedrede produkt med den første myndighed eller med andre. På den måde kan der være flere om at forbedre softwaren og om at finansiere fremtidig udvikling.

Med alle typer af it-anskaffelser kan der være mange elementer man skal huske i løbet af processen. Nedenfor er derfor opstillet en tjekliste til brug ved anskaffelse af open source. Herunder til afklaring i forhold til licenser.  

Licenser kan indeholde forskellige vilkår om f.eks. at publicerede videreudviklinger skal videregives under samme vilkår (såkaldte copyleft-vilkår). Dette element kan være vigtigt i henhold til at sikre, at produktet ikke senere hen overgår fra open til closed source.

Under hensyn til gennemsigtigheden må det derfor i alle tilfælde kræves, at ordregiver specificerer, hvilke open source-(mindste)krav, der stilles til det programmel, som skal (videre)udvikles.

> Faktaboks: Eksempel på open Source på de ”store tunge løsninger”? Fx eksempel på at der er en juridisk løsning på vendor lockin og ejerskab til IT; case kunne evt. være Digital Post vs. eboks.

## Licenser

Open source-licenser er softwarelicenser, der tillader, at software frit kan bruges, forbedres og deles. Open Source Initiative har godkendt en række licenser, men anbefaler, at man som udgangspunkt benytter de licenser, der er "populære og bredt anvendte eller med stærke fællesskaber", f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License eller Mozilla Public License (MPL) 2.0.[^1]

> **OS2-fællesskabets brug af licenser**
>
> OS2-fællesskabet benytter open source-licenserne [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/) til kildekode og [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) til dokumentation og andet materiale, der ikke er kildekode. MPL 2.0 er en "file scope"-licens, hvilket vil sige, at filerne og deres indhold er omfattet. I praksis betyder det, at hvis nogen ændrer i filerne, skal ændringerne gives tilbage til OS2.

Læs mere om og find alle de godkendte open source-licenser på https://opensource.org/licenses.

Det er også muligt at anvende EU-Kommissionens værktøj til at finde og sammenligne softwarelicenser på https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses.

[^1]: [Open Source Licenses by Category - Open Source Initiative](https://opensource.org/licenses/category)

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
