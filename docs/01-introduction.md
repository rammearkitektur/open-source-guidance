# Indledning

Danske myndigheder investerer massivt i digitalisering, og der er et stort behov for, at digitale løsninger er fleksible, sammenhængende og bygget til genbrug og forandring, hvis [Danmark skal fastholde sin position som et digitalt foregangsland](https://fm.dk/udgivelser/2021/oktober/visioner-og-anbefalinger-til-danmark-som-et-digitalt-foregangsland) og skabe et robust og bæredygtigt grundlag for fortsat vækst, velstand, grøn omstilling og effektiv offentlig service.

Den digitale udvikling går hurtigere og hurtigere, og offentlige myndigheder skal derfor blive endnu bedre til løbende at udvikle den digitale service til gavn for borgere og virksomheder. Verdens bedste offentlige sektor understøtter en bæredygtig udvikling og kræver myndigheder, der er i stand til at udnytte nye teknologier og digitale muligheder, samarbejde med mange leverandører på et åbent marked og levere nye løsninger hurtigt og effektivt.

Visionen for den fællesoffentlige digitale arkitektur er en [digitalt sammenhængende offentlig sektor](https://arkitektur.digst.dk/mandat-og-styring/hvidbog-om-faellesoffentlig-digital-arkitektur), der understøtter innovation, vækst og udvikling i samfundet. Offentlige myndigheder skal så vidt muligt undgå løsninger, der skaber afhængighed af specifikke leverandører og proprietære teknologier. Dermed udvikles et marked, hvor flere leverandører kan konkurrere om at levere systemer og services innovativt, billigt og fleksibelt, og der er plads til både standardløsninger og moduler fra flere leverandører baseret på åbne snitflader. [Hvor det er relevant, anvendes bæredygtige open source-komponenter](https://arkitektur.digst.dk/principper-og-regler/princip-2-arkitektur-fremmer-sammenhaeng-innovation-og-effektivitet-4).

Både offentlige myndigheder og private virksomheder har en interesse i [bæredygtig digitalisering](https://www.digitalsme.eu/sustainable-digitalisation/). Nye samarbejdsmodeller og åbne, digitale økosystemer skaber agilitet og  digital selvbestemmelse. Grønne it-udbud og cirkulære forretningsmodeller, der sikrer genbrug og vedligeholdelse, sparer ressourcer og forlænger løsningernes levetid. Juridiske, administrative og tekniske rammer for åbenhed og interoperabilitet, så myndigheder og leverandører frit kan dele, genbruge, undersøge og forbedre data og løsninger, er en forudsætning for innovation. [Bæredygtighed er blevet en konkurrenceparameter for danske virksomheder](https://www.danskindustri.dk/arkiv/analyser/2021/8/baredygtighed--en-vigtig-konkurrenceparameter/).

Der er et stort potentiale i åbne og cirkulære forretningsmodeller og open source-software, der brugt på de rigtige områder kan bidrage til at understøtte bæredygtig udvikling, innovation og kvalitet, styrke danske virksomheders omstillingsparathed og konkurrenceevne og øge vækst og eksport af digitale løsninger. Derfor beskriver vejledningen en række **principper for anvendelse af open source** samt de tre overordnede **strategier for brug af open source**, deres forskellige bevæggrunde og værdiskabelser.

Formålet med denne vejledning er ikke at opsætte et modsætningsforhold mellem brug af open source-software og proprietære løsninger. Det er ikke et spørgsmål om enten-eller, men om at vælge den løsning, der skaber værdi på baggrund af de udfordringer og behov, der er relevante for den enkelte myndighed. Derfor beskriver vejledningen en række af de vigtigste overvejelser ved anskaffelse, herunder **strategi og markedsafdækning**, **anskaffelse og implementering** og **vedligeholdelse og videreudvikling**.

## Hvad er open source?

Open source-software er software udgivet under en licens, der giver enhver ret til at bruge, undersøge, ændre og dele softwaren og dens kildekode frit og til ethvert formål.

Modsætningen til open source er proprietære løsninger, såkaldt closed source. Med proprietære løsninger har man i modsætning til open source ikke mulighed for at ”kigge under kølerhjelmen” og dermed læse og forstå, hvordan softwaren er bygget. Ved anvendelse af proprietære løsninger er det dermed leverandøren, der har den eksklusive ophavsret til softwaren. Man anvender derfor proprietære løsninger under nogle fastlagte betingelser, og kan ikke selv forbedre løsningen eller dele den med andre.

Open source bliver af og til forvekslet med åbne standarder, der ofte er en forudsætning for open source, men de to er ikke det samme.

> **Åbne standarder**
> 
> Offentlige myndigheder skal så vidt muligt anvende åbne og internationale standarder. Åbne standarder fremmer konkurrence på markedet for software og medvirker til, at offentlige it-systemer uanset valg af software kan udveksle informationer på tværs. De er det fælles sprog, systemerne bruger til at tale med og forstå hinanden.
> 
> Læs mere i [Vejledning om anvendelse af obligatoriske, åbne standarder for software i det offentlige](https://www.digitaliser.dk/resource/3778907/artefact/Vejledning_om_abne_standarder.pdf?artefact=true&PID=3778930).

Open source handler ikke om teknik, men kan snarere ses som en udviklingsmetode og forretningsmodel, der fremmer offentlige myndigheders medejerskab til deres løsninger og skaber flere og bedre muligheder for at dele dem med andre, fordi de er offentliggjort under en open source-licens.

> **Eksempler på udbredelsen af open source**
> 
> Der findes mange kendte og udbredte open source-softwareprodukter. Distributioner af Linux-styresystemet understøtter omkring 70 % af internettets 10 mio. mest besøgte hjemmesider, der f.eks. hostes af webserversoftwaren Nginx (33 %) eller Apache HTTP Server (24 %). 42 % af internettet kører Wordpress, og de 6,5 mio. artikler på den engelsksprogede Wikipedia, kører MediaWiki. Omkring 65 % besøger internettet vha. Google Chrome, der også findes til smartphones, hvoraf 84 % kører det Linux-baserede styresystem Android. Danske offentlige myndigheder bruger f.eks. LibreOffice til teksbehandling og QGIS til geodatabehandling, og 82 kommuner bruger OS2kitos til at holde styr på deres it-portefølje.

## Internationale tendenser

Open source står også højt på dagsordenen i EU og i mange andre lande. EU har peget på øget brug af open source, som en oplagt vej til øget tillid og transparens mellem myndigheder og borgerne. 

Der er i løbet af det sidste års tid kommet fokus på øgede samfundsgevinster i form af blandt andet sikkerhed, gennemsigtighed, leverandøruafhængighed og interoperabilitet ved anvendelse af open source i offentlige myndigheder.

Under overskriften *Think Open* har EU-kommissionen i deres [open source-softwarestrategi](https://ec.europa.eu/info/departments/informatics/open-source-software-strategy_en) præsenteret en vision for digital transformation, innovation og samarbejde med open source som løftestang for offentlige digitale løsninger. Open source skal sikre løsninger, der virker og kan deles på tværs af grænser og fremtidssikrer Europas og medlemslandenes teknologiske selvbestemmelse i kraft af øget leverandøruafhængighed.

> **Principper for strategiens implementering**
>
> * **Tænk åbent**<br>
>   Open source-løsninger er at foretrække, når de er tilsvarende i funktionalitet, total omkostninger og cybersikkerhed.
> * **Transformér**<br>
>   Vi udnytter principperne for open source: vi innoverer, vi samskaber, deler og genbruger, og bygger sammen brugercentrerede, datadrevne offentlige tjenester.
> * **Del**<br>
>   Vi deler vores kode and muliggør bidrag til relaterede open source-projekter.
> * **Bidrag**<br>
>   Vi stræber efter at være et aktivt medlem af det mangfoldige open source-økosystem.
> * **Gør sikker**<br>
>   Vi sørger for, at den kode, vi bruger, og den kode, vi deler, er fri for sårbarheder ved at teste sikkerheden løbende.
> * **Bevar kontrol**<br>
>   Vi fremmer åbne standarder og specifikationer, der er implementeret og distribueret i open source.

En [undersøgelse om effekten af open source](https://digital-strategy.ec.europa.eu/en/library/study-about-impact-open-source-software-and-hardware-technological-independence-competitiveness-and) på teknologisk uafhængighed, konkurrenceevne og innovation i den europæiske økonomi fremhæver tre overordnede anbefalinger, hvor brug af open source kan bidrage til:

 * En digitalt uafhængig offentlig sektor
 * Åben forskning og udvikling som fundament for vækst
 * Et digitaliseret og internationalt konkurrencedygtigt erhvervsliv

I et europæisk perspektiv kan open source dermed være en nøgle til digital og teknologisk selvbestemmelse i EU og uafhængighed af de globale techgiganter. Det er en stor del af forklaringen på, at der fra EU-Kommissionens side tilskyndes anvendelse af open source, og at der er udarbejdet standarder for, hvordan software deles og genbruges.

> **Italiensk for open source-begyndere**
> 
> I Italien er det indført ved lov, at open source-software gives fortrinsret i offentlige udbud, og myndighederne forpligter sig til at offentliggøre koden til software, der er udviklet under en open source-licens, for at gøre den genanvendelig.
> 
> Læs mere om italienske myndigheders [genbrug af åbne løsninger og standarder](https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/v2017-12-13/_rst/capo6_art69.html). 

Undersøgelsen fremhæver nogle anbefalinger, der skal skabe et mere uafhængigt og konkurrencedygtigt Europa. Herunder at betragte open source som en grundlæggende komponent i den offentlige forvaltnings digitale transformation samt direkte finansiere udviklingen af open source-software og dens sikkerhed.

## Baggrund for vejledningen

Open source er ikke noget nyt - hverken som forretningsmodel eller udviklingsmetode. Open source er interessant, fordi det understøtter mere modulære og samarbejdsorienterede måder at udvikle, dele, og genbruge komponenter. Open source kan derfor understøtte sammenhængende digitalisering og leverandøruafhængighed i den offetnlige sektor.. 

Anvendelse af open source er i overensstemmelse med principperne i den fællesoffentlige digitale arkitektur og EU-Kommissionens vision for øget brug af open source. Herunder en dagsorden om mere tillid mellem myndigheder og borgere samt styrkelse af EU’s digitale selvbestemmelse og interoperabilitet mellem medlemslandene digitale service.

Den fællesoffentlige digitale arkitektur sætter de overordnede rammer for udviklingen af den digitalt sammenhængende offentlige sektor. Den skal understøtte digital sammenhæng i den offentlige sektor på flere niveauer: mellem stat, kommuner og regioner. På tværs af fagområder som f.eks. sundheds-, social, uddannelses- og arbejdsmarkedsområderne. Mellem den offentlige sektor og den private sektor. Og på tværs af landegrænser, ikke mindst i forhold til EU og det digitale indre marked.

> **Den fælles digitale arkitektur** omfatter fælles rammer for projekternes arkitekturarbejde, herunder governance med fora, mandater og processer for det fælles arkitekturarbejde, fælles arkitekturregler samt rammer for projekters dokumentation af arkitektur og kvalitetssikring gennem review. Den fælles digitale arkitektur indeholder desuden en rammearkitektur, der består af et antal referencearkitekturer, der beskriver genbrugelige arkitekturbyggeblokke, som projekterne skal tage bestik af i deres arbejde. 

At basere digitale løsninger på open source er i overenstemmelse med arkitekturregel 2.3 om at undgå afhængighed af leverandører og proprietære teknologier og anvende bæredygtige open source-komponenter, hvor det er relevant. Denne vejledning vil blandt andet bidrage med overvejelser til, hvor det kan blive relevant.

[Statens it-projektmodel](https://digst.dk/styring/projektstyring/statens-it-projektmodel/), der skal bidrage til at sikre, at staten ikke igangsætter unødvendigt risikofyldte it-projekter, indeholder desuden et princip om, at allerede indkøbte eller udviklede løsninger skal genbruges i videst muligt omfang.

## Målgruppe

Målgruppen for vejledningen er især projektledere/it-indkøbere, it-arkitekter og beslutningstagere i offentlige myndigheder der skal tage stilling til eventuel anskaffelse af software, og som ønsker viden, praktisk vejledning og anbefalinger og konkrete eksempler i forhold til open source, som er relevante i alle dele af anskaffelsesprocessen og ved efterfølgende drift og vedligeholdelse.

Der er tidligere lavet vejledninger om open source til offentlige myndigheder, som er mere overordnede, men ikke har et praksisnært fokus. Vejledningen tilstræber at hjælpe alle, der overvejer eller ønsker at indkøbe software, og som ikke har et forhåndskendskab. 

Samtidig ønskes med vejledningen at bringe projektledere og it-arkitekter i stand til at have en kvalificeret dialog med jurister samt beslutningstagerne i ledelseslaget, i forbindelse med beslutning om evt. anvendelse af open source.
