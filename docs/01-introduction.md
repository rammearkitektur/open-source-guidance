# Indledning

Danske myndigheder investerer mange penge i it og der er i stigende grad krav til at it-løsninger er fleksible, og kan arbejde sammen. Samtidig er der stadig stærkere krav til sikkerhed, privatlivsbeskyttelse og transparens. 

Højt på dagsordenen i det fællesoffentlige digitaliseringssamarbejde er også et ønske om at styrke tillid og trygheden ved borgernes og virksomhedernes brug af de offentlige digitale tjenester:

”Danskernes høje tryghed og tillid til hinanden og til den offentlige sektor er fundamentet for vores velfærd” 

Den fællesoffentlige Digitale Arkitektur (FDA) peger også på brug af open source, som en vigtig tilgang til at undgå afhængighed af leverandører og proprietære teknologier, hvor det er relevant. 

Denne vejledning vil blandt andet belyse, hvor det er relevant at vælge en open source baseret løsning, og fokusere på at give konkret vejledning til nogle af de vigtigste overvejelser, som man skal gennem, når man står i en anskaffelsessituation. Desuden giver vejledningen et overblik over de forhold, som er vigtige, når man først har anskaffet sig en eller flere open source-løsninger, og fx står over for opgaver som vedligehold, videreudvikling og genudbud. 

Open source står også højt på dagsordenen i EU og i mange andre lande. EU har peget på øget brug af open source, som en oplagt vej til øget tillid og transparens mellem myndigheder og borgerne. 

Der er i løbet af det sidste års tid kommet fokus på øgede samfundsgevinster i form af blandt andet sikkerhed, transparens, leverandøruafhængighed og interoperabilitet ved anvendelse af open source i offentlige myndigheder. Under overskriften ”Think Open” har EU-kommissionen præsenteret en vision for digital trans-formation, innovation og samarbejde med open source som løftestang for offentlige digitale løsninger.[^1] Open source skal sikre løsninger, der virker og kan deles på tværs af grænser og fremtidssikrer Europas og medlemslandenes teknologiske selvbestemmelse i kraft af øget leverandøruafhængighed.

Formålet med denne vejledning er ikke at opsætte et modsætningsforhold mellem brug af open source og closed source. Der er ikke tale om et enten-eller, men vejledningen har til derimod hensigt at belyse hvor open source kan give værdi samt skabe grundlaget for en strategisk beslutning på baggrund af hvilke muligheder og overvejelser, der kan være relevant for den enkelte myndighed. 

[^1]: [Open source software strategy (oktober 2021)](https://ec.europa.eu/info/departments/informatics/open-source-software-strategy_en)

## Hvad er open source?

Open source-software er software udgivet under en licens, der giver enhver ret til at bruge, undersøge, ændre og dele softwaren og dens kildekode frit og til ethvert formål.

Modsætningen til open source er proprietære løsninger, såkaldt closed source. Med proprietære løsninger har man i modsætning til open source ikke mulighed for at ”kigge under kølerhjelmen” og dermed læse og forstå, hvordan softwaren er bygget. Ved anvendelse af proprietære løsninger er det dermed leverandøren, der har den eksklusive ophavsret til softwaren. Man anvender derfor proprietære løsninger under nogle fastlagte betingelser, og kan ikke selv forbedre løsningen eller dele den med andre.

Open source bliver af og til forvekslet med åbne standarder, der ofte er en forudsætning for open source, men de to er ikke det samme.

> **Åbne standarder**
> 
> Offentlige myndigheder skal så vidt muligt anvende åbne og internationale standarder. Åbne standarder fremmer konkurrence på markedet for software og medvirker til, at offentlige it-systemer uanset valg af software kan udveksle informationer på tværs. De er det fælles sprog, systemerne bruger til at tale med og forstå hinanden.
> 
> Læs mere i [Vejledning om anvendelse af obligatoriske, åbne standarder for software i det offentlige](https://www.digitaliser.dk/resource/3778907/artefact/Vejledning_om_abne_standarder.pdf?artefact=true&PID=3778930).

Open source handler i virkeligheden ikke om teknik, men kan snarere ses som en forretningsmodel eller udviklingsmodel, der fremmer offentlige myndigheders medejerskab til deres løsninger og giver bedre muligheder for at dele dem med andre, fordi de er offentliggjort på en open source-licens.

> **Eksempler på udbredelsen af open source**
> Der findes mange kendte og udbredte open source-softwareprodukter. Distributioner af Linux-styresystemet understøtter omkring 70 % af internettets 10 mio. mest besøgte hjemmesider, der f.eks. hostes af webserversoftwaren Nginx (33 %) eller Apache HTTP Server (24 %). 42 % af internettet kører Wordpress, og de 6,5 mio. artikler på den engelsksprogede Wikipedia, kører MediaWiki. Omkring 65 % besøger internettet vha. Google Chrome, der også findes til smartphones, hvoraf 84 % kører det Linux-baserede styresystem Android. Danske offentlige myndigheder bruger f.eks. LibreOffice til teksbehandling og QGIS til geodatabehandling, og 82 kommuner bruger OS2kitos til at holde styr på deres it-portefølje.

## Internationale strømninger

En undersøgelse  er blevet offentliggjort i september 2021 fra EU-Kommissionen vedr. virkningen af open source-software og hardware på EU's økonomi. Dette med hensyn til innovation, konkurrenceevne, teknologisk uafhængighed og jobskabelse.[^2]

[^2]: [Study about the impact of open source software and hardware on technological independence, competitiveness and innovation in the EU economy (september 2021)](https://digital-strategy.ec.europa.eu/en/library/study-about-impact-open-source-software-and-hardware-technological-independence-competitiveness-and)

Undersøgelsen fremhæver, hvordan brug af open source-software kan: 

  * Fremme den offentlige sektors uafhængighed i Unionen
  * Reducere omkostninger 
  * Begrænse fænomenet vendor lock-in (afhængighed af leverandører). 

Set fra EU's perspektiv kan open source dermed være en nøgle til et mere autonomt og teknologisk suverænt EU løsrevet fra techgiganter. Det er en stor del af forklaringen på, at der fra EU's side tilskyndes til anvendelse af open source samt, at der er udarbejdet anerkendte standarder for, hvorledes programmel deles og genanvendes, ud fra et ønske om anvendelse af færrest mulige ressourcer.

> I Italien er det indført ved lov, at open source-software gives fortrinsret i offentlige udbud, og myndighederne forpligter sig til at offentliggøre koden til software, der er udviklet under en open source-licens, for at gøre den genanvendelig.

Undersøgelsen fremhæver nogle anbefalinger, der skal skabe et mere uafhængigt og konkurrencedygtigt Europa. Herunder bl.a. at betragte open source som en grundlæggende komponent i den offentlige forvaltnings digitale transformation samt direkte finansiere udviklingen af open source -software og dens sikkerhed.

## Hvorfor open source?

Open source er ikke noget nyt begreb, eller ny metode/forretningsmodel. Open source særligt aktuelt nu, da metoden eller forretningsmodellen understøtter mere modulbaserede og agile måder at udvikle, dele, og genbruge komponenter. Open Source kan være ét element i den aktuelle udvikling med krav om indbygget uafhængighed fremfor opbygning af siloløsninger. 

Anvendelse af open source er som nævnt ovenfor i overensstemmelse med principperne i den fællesoffentlige Digitale Arkitektur og EU's vision for øget brug af open source, som nævnt i indledningen. Herunder en dagsorden om mere tillid mellem myndigheder og borgere samt styrkelse af EU’s digitale suverænitet og interoperabilitet mellem medlemslandene. 

Den fællesoffentlige digitale arkitektur sætter de overordnede rammer for udviklingen af den digitalt sammenhængende offentlige sektor. Den skal understøtte digital sammenhæng i den offentlige sektor på flere niveauer: mellem stat, kommuner og regioner. På tværs af fagområder som fx sundhed, socialområdet, uddannelse og arbejdsmarked. Mellem den offentlige sektor og den private sektor. Og på tværs af landegrænser, ikke mindst i forhold til EU og det digitale indre marked. 

> Den fælles digitale arkitektur omfatter fælles rammer for projekternes arkitekturarbejde, herunder governance med fora, mandater og processer for det fælles arkitekturarbejde, fælles arkitekturregler samt rammer for projekters dokumentation af arkitektur og kvalitetssikring gennem review. Den fælles digitale arkitektur indeholder desuden en rammearkitektur, der består af et antal referencearkitekturer, der definerer genbrugelige arkitekturbyggeblokke som projekterne skal tage bestik af i deres arbejde. 

At basere software-løsninger på open source flugter specifikt med arkitekturregel 2.3 i den fællesoffentlige digitale arkitektur om at undgå afhængighed af leverandører og proprietære teknologier, og hvor det i forklaringen til reglen understreges, at ”hvor det er relevant anvendes bæredygtige open source-komponenter.”  Denne vejledning vil blandt andet belyse ”hvor det er relevant”. 

Statens it-projektmodel skal bidrage til at sikre, at staten ikke igangsætter unødigt risikofyldte it-projekter. Som princip 2 i modellen hedder det, at: ”Allerede indkøbte eller udviklede løsninger skal genbruges i videst muligt omfang.”[^3]

[^3]: [Statens it-projektmodel](https://digst.dk/styring/projektstyring/statens-it-projektmodel/)

Formålet er at analysere mulige barrierer for offentlige myndigheders anvendelse af open source i Danmark og at synliggøre hvordan og hvornår, det er relevant at anvende open source samt opstille anbefalinger, som offentlige myndigheder i Danmark kan læne sig op ad, når det gælder anvendelse af open source. Vejledningen skal tilvejebringe overblik over centrale overvejelser, gode råd og bidrage med helt praksisnær vejledning samt vejlede i, hvordan man gennemfører et udbud og indkøber på en open source-licens. 

Denne vejledning vil forsøge at gøre op med nogle myter om open source samt bygge ovenpå tidligere vejledninger ved i højere grad at belyse hvad open source betyder i praksis og hvilke nuancer, og barrierer, man som offentlig myndighed skal holde sig for øje i anskaffelse og anvendelse af open source, samt bidrage med egentlige tjeklister som fx projektledere og it-arkitekter kan benytte sig af.   

## Målgruppe

Målgruppen for vejledningen er især projektledere/it-indkøbere, it-arkitekter og beslutningstagere i offentlige myndigheder der skal tage stilling til eventuel anskaffelse af software, og som ønsker viden, praktisk vejledning og anbefalinger og konkrete eksempler i forhold til open source, som er relevante i alle dele af anskaffelsesprocessen og ved efterfølgende drift og vedligeholdelse.

Der er tidligere lavet vejledninger om open source til offentlige myndigheder, som er mere overordnede, men ikke har et praksisnært fokus. Vejledningen tilstræber at hjælpe alle, der overvejer eller ønsker at indkøbe software, og som ikke har et forhåndskendskab. 

Samtidig ønskes med vejledningen at bringe projektledere og it-arkitekter i stand til at have en kvalificeret dialog med jurister samt beslutningstagerne i ledelseslaget, i forbindelse med beslutning om evt. anvendelse af open source. 
