<style>
@media print {
  html { margin: 0cm 2cm 2cm 0cm; font-size: 80%; }
  /* DIGST fonts */
  body { font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;}
  h2,h3,h4, h4 dfn { font-family: "Garamond", serif; color: black; margin-bottom: 0; font-style: normal; font-weight: normal;}
  h2:not(#subtitle) { page-break-before: always; font-size: 250%; border-bottom: solid 0.5px black; padding-top: 20px; margin-bottom: 6px;}
  h3 { font-size: 145%;}
  h4 { font-size: 125%;}
  #toc {page-break-before: always;}
  /* DIGST-like frontpage */
  .head { width: 50%; margin-left: 24px; padding: 0px; background-color: #031D5C;}
  .head div { background-color: white; padding: 24px; }
  .head hr { display: none;}
  .head h1 { background-color: #031D5C; color: white; margin: 0px; padding: 50px 0px 50px 24px; font-weight: normal; }
  #subtitle { padding-left: 24px; background-color: #031D5C; color: #031D5C; }
  .head time { display: block; font-family: "Helvetica Neue", Helvetica, Arial; margin: 0px; background-color: #031D5C; font-size: 80%; color: white;}
  .toc li { line-height: 70%; font-family: "Helvetica Neue", Helvetica, Arial;
    font-weight: 600; font-size: 90%; }
  h2.heading.settled > a.self-link, h3.heading.settled > a.self-link, h4.heading.settled > a.self-link, h4.heading.settled > a.self-link, h5.heading.settled > a.self-link, h6.heading.settled > a.self-link { display: none; }
  blockquote { font-size: 80%; font-style: italic; margin-left: 5%; width: 70%; border-left-width: 2px;}
	h2#abstract {display: none;}
	.p-summary {width: 50%; margin-left: 24px; padding: 0px;}
}
  
.new {
    border: solid 3px green;
    padding: 6px;
    margin: 18px 0px 18px 0px;
}

h2.heading.settled > a.self-link, h3.heading.settled > a.self-link, h4.heading.settled > a.self-link, h4.heading.settled > a.self-link, h5.heading.settled > a.self-link, h6.heading.settled > a.self-link { display: none; }

.term-table{
  font-size: 80%;
}

.term-table tr td:nth-of-type(3), .term-table tr td:nth-of-type(4), .term-table tr td:nth-of-type(5){
  word-wrap: anywhere;
  overflow-wrap: anywhere;
  hyphens: auto;
  word-break: break-all;
}

.term-table td{
  border-bottom: 1px solid #ccc;
  padding: 12px 8px;
}

.term-table tr td:first-child{
  font-weight: 600;
  word-wrap: break-word;
}

.term-table tr th:first-child{
  width: 20%;
}

.term-table tr th:nth-of-type(2){
  width: 22%;
}

.term-table tr th:nth-of-type(3){
  width: 15%;
}

.term-table tr th:nth-of-type(4){
  width: 15%;
}

.term-table tr th:nth-of-type(5){
  width: 15%;
}

.term-table tr th:nth-of-type(6){
  width: 13%;
}

.term-table tr td:nth-of-type(2){
  font-style: italic;
}

.term-table th{
  color: #fff;
  border: none;
  background-color: #940027;
  text-transform: capitalize;
  font-weight: 600;
  padding: 6px 8px;
}

.body{
  max-width: 100% !important;
}

.body.h-entry{
  max-width: 100%;
}

	@media screen and (min-width: 78em) {

		body.h-entry:not(.toc-inline) {
			padding-left: 25em;
		}
  
}

dl.def dt,dl.def dd {
    box-sizing: border-box;
}
  
dl.def dt {
    float: left;
    width: 25%;
    padding-bottom: 0;
}
  
dl.def dd {
    margin-left: 25%!important;
}
  
dl.def dd:after {
    content: "";
    display: block;
    clear: both;
} 

img{max-width:100%!important}
p.center{text-align:center!important}
p.left{text-align:left!important}
p.right{text-align:right!important}
p.italic{font-style: italic!important;}
#toc h2{color:#000!important}
#toc ol, #toc li, #toc a {
    display: block;
}
  
.toc .secno {
    margin-right: 1rem!important;
}
  
:not(li) > .toc {
    margin-left: 0rem!important;
}
  
	#toc > .toc > li > a > span {
    margin-top: 0rem;
}
	
</style>

<pre class="metadata">
Title: open-source-guidance 1.0.0-beta: Vejledning om brug af open source
Status: LD
URL: https://github.com/rammearkitektur/open-source-guidance/tree/main/
Editor Term: Bidragyder, Bidragydere
Editor: KL, rammearkitektur@kl.dk
Editor: Digitaliseringsstyrelsen
Editor: OS2
Editor: Aarhus Kommune
Editor: Odense Kommune
Editor: Favrskov Kommune
Editor: Brugerklubben SBSYS
Editor: Statens It
Editor: Styrelsen for It og Læring
Editor: Styrelsen for Dataforsyning og Effektivisering
Editor: KOMBIT
Editor: Kriminalforsorgen
Abstract: 'open-source-guidance 1.0.0' .
Boilerplate: copyright no, conformance no, abstract no
Shortname: open-source-guidance
Revision: 1.0.0-beta
Date: 2021-11-16
Max ToC Depth: 3
Markup Shorthands: markdown yes
Repository: rammearkitektur/open-source-guidance
Translation: en https://rammearkitektur.github.io/open-source-guidance/docs/index-en.html
Inline Github Issues: full
Logo: rammearkitektur
</pre>

<h1>open-source-guidance 1.0.0-beta: Vejledning om brug af open source</h1>

# Indledning

Danske myndigheder investerer mange penge i it og der er i stigende grad krav til at it-løsninger er fleksible, og kan arbejde sammen. Samtidig er der stadig stærkere krav til sikkerhed, privatlivsbeskyttelse og transparens. 

Højt på dagsordenen i det fællesoffentlige digitaliseringssamarbejde er også et ønske om at styrke tillid og trygheden ved borgernes og virksomhedernes brug af de offentlige digitale tjenester:

”Danskernes høje tryghed og tillid til hinanden og til den offentlige sektor er fundamentet for vores velfærd” 

Den fællesoffentlige Digitale Arkitektur (FDA) peger også på brug af open source, som en vigtig tilgang til at undgå afhængighed af leverandører og proprietære teknologier, hvor det er relevant. 

Denne vejledning vil blandt andet belyse, hvor det er relevant at vælge en open source baseret løsning, og fokusere på at give konkret vejledning til nogle af de vigtigste overvejelser, som man skal gennem, når man står i en anskaffelsessituation. Desuden giver vejledningen et overblik over de forhold, som er vigtige, når man først har anskaffet sig en eller flere open source-løsninger, og fx står over for opgaver som vedligehold, videreudvikling og genudbud. 

Open source står også højt på dagsordenen i EU og i mange andre lande. EU har peget på øget brug af open source, som en oplagt vej til øget tillid og transparens mellem myndigheder og borgerne. 

Der er i løbet af det sidste års tid kommet fokus på øgede samfundsgevinster i form af blandt andet sikkerhed, transparens, leverandøruafhængighed og interoperabilitet ved anvendelse af open source i offentlige myndigheder. Under overskriften ”Think Open” har EU-kommissionen præsenteret en vision for digital trans-formation, innovation og samarbejde med open source som løftestang for offentlige digitale løsninger.
^1] Open source skal sikre løsninger, der virker og kan deles på tværs af grænser og fremtidssikrer Europas og medlemslandenes teknologiske selvbestemmelse i kraft af øget leverandøruafhængighed.

Formålet med denne vejledning er ikke at opsætte et modsætningsforhold mellem brug af open source og closed source. Der er ikke tale om et enten-eller, men vejledningen har til derimod hensigt at belyse hvor open source kan give værdi samt skabe grundlaget for en strategisk beslutning på baggrund af hvilke muligheder og overvejelser, der kan være relevant for den enkelte myndighed. 

[^1]: https://ec.europa.eu/info/departments/informatics/open-source-software-strategy_en

## Hvad er open source?

Open source betyder ”åben kildekode” og der er dermed tale om software, der er distribueret og udviklet i overensstemmelse med et princip om, at et computerprograms kildekode skal være åben og tilgængelig. 

Modsætningen til open source er proprietære løsninger eller closed source. I proprietære løsninger har vi i modsætning til open source ikke mulighed for at ”kigge under kølerhjelmen” og se hvordan løsningen eller softwaren er bygget. Ved anvendelse af proprietære løsninger er det dermed leverandøren, der har den eksklusive copyright til softwaren. Man anvender derfor proprietære løsninger under nogle fastlagte betingelser, og kan ikke selv modificere eller dele løsningen/softwaren med andre.

Med open source-software er der dermed frihed til at anvende, undersøge, ændre, forbedre og dele kildekode og dokumentation. Open source vedrører altså selve den kode, som softwaren består af.

Begrebet om open source (åben kildekode) bliver af og til forvekslet med begrebet ’åbne standarder’. 

> Faktaboks: "hvad er åbne standarder? "En åben standard er en teknisk specifikation, som er offentligt tilgængeligt, der har til formål at nå et bestemt mål. Ved at tillade at alle kan bruge standarden, kan man øge kompatibiliteten mellem diverse hardware- og software-komponenter" (kilde: Wikipedia). I modsætning til open source vedrører åbne standarder derfor det ‘sprog’, softwaren anvender til at "tale med andre systemer". Sagt på en anden måde, så kan du, når du fremsender en fil, som er baseret på en åben standard være sikker på, at din modtager har mulighed for at åbne filen. Offentlige myndigheder sender eksempelvis primært filer i pdf-formatet, for at være sikre på, at borgeren i den anden ende kan åbne filen uanset hvilket operativsystem eller software, som borgeren i øvrigt anvender.

Open source handler i virkeligheden ikke om teknik, men kan snarere ses som en udviklingsmetode eller en forretningsmodel, der essentielt fremmer offentlige myndigheders medejerskab til deres egne løsninger samt giver mulighed for deling med andre, da løsningen/softwaren ikke er underlagt copyright. 

> Faktaboks: Her kunne indsættes eksempler på kendte applikationer/løsninger – gerne lidt større, som anvendes på en open source-licens – gerne nogle som anvendes bredt i kommunerne/staten og regionerne. Eksempelvis er open source på SKI 02.06 og 02.18/02.17.  Formålet er at vise, at open source ikke er niche/kun for mindre løsninger.

## Internationale strømninger

En undersøgelse  er blevet offentliggjort i september 2021 fra EU-Kommissionen vedr. virkningen af open source-software og hardware på EU's økonomi. Dette med hensyn til innovation, konkurrenceevne, teknologisk uafhængighed og jobskabelse.[^2]

Undersøgelsen fremhæver, hvordan brug af open source-software kan: 

•	Fremme den offentlige sektors uafhængighed i Unionen
•	Reducere omkostninger 
•	Begrænse fænomenet vendor lock-in (afhængighed af leverandører). 

Set fra EU's perspektiv kan open source dermed være en nøgle til et mere autonomt og teknologisk suverænt EU løsrevet fra techgiganter. Det er en stor del af forklaringen på, at der fra EU's side tilskyndes til anvendelse af open source samt, at der er udarbejdet anerkendte standarder for, hvorledes programmel deles og genanvendes, ud fra et ønske om anvendelse af færrest mulige ressourcer.

> Faktaboks: I Italien er det fx indført ved lov, at open source-programmer gives fortrinsret i offentlige udbud og myndighederne forpligter sig til at offetliggøre koden til software, der er udviklet under en open source-licens, for at gøre den genanvendelig.

Undersøgelsen fremhæver nogle anbefalinger, der skal skabe et mere uafhængigt og konkurrencedygtigt Europa. Herunder bl.a. at betragte open source som en grundlæggende komponent i den offentlige forvaltnings digitale transformation samt direkte finansiere udviklingen af open source -software og dens sikkerhed. 

[^2]: https://digital-strategy.ec.europa.eu/en/library/study-about-impact-open-source-software-and-hardware-technological-independence-competitiveness-and

## Hvorfor open source?

Open source er ikke noget nyt begreb, eller ny metode/forretningsmodel. Open source særligt aktuelt nu, da metoden eller forretningsmodellen understøtter mere modulbaserede og agile måder at udvikle, dele, og genbruge komponenter. Open Source kan være ét element i den aktuelle udvikling med krav om indbygget uafhængighed fremfor opbygning af siloløsninger. 

I Danmark har der tidligere været et stort fokus på anvendelse af open source i offentlige myndigheder. Det er siden hen gledet i baggrunden. Én forklaring kan være, at der var opstået en antagelse om, at anvendelse af open source var blevet en selvfølgelighed, fordi det lå implicit i princippet om ”bedst og billigst”.   

Anvendelse af open source er som nævnt ovenfor i overensstemmelse med principperne i den fællesoffentlige Digitale Arkitektur og EU's vision for øget brug af open source, som nævnt i indledningen. Herunder en dagsorden om mere tillid mellem myndigheder og borgere samt styrkelse af EU’s digitale suverænitet og interoperabilitet mellem medlemslandene. 

Den fællesoffentlige digitale arkitektur sætter de overordnede rammer for udviklingen af den digitalt sammenhængende offentlige sektor. Den skal understøtte digital sammenhæng i den offentlige sektor på flere niveauer: mellem stat, kommuner og regioner. På tværs af fagområder som fx sundhed, socialområdet, uddannelse og arbejdsmarked. Mellem den offentlige sektor og den private sektor. Og på tværs af landegrænser, ikke mindst i forhold til EU og det digitale indre marked. 

Den fælles digitale arkitektur omfatter fælles rammer for projekternes arkitekturarbejde, herunder governance med fora, mandater og processer for det fælles arkitekturarbejde, fælles arkitekturregler samt rammer for projekters dokumentation af arkitektur og kvalitetssikring gennem review. Den fælles digitale arkitektur indeholder desuden en rammearkitektur, der består af et antal referencearkitekturer, der definerer genbrugelige arkitekturbyggeblokke som projekterne skal tage bestik af i deres arbejde. 

At basere software-løsninger på open source flugter specifikt med arkitekturregel 2.3 i den fællesoffentlige Digitale Arkitektur om at undgå afhængighed af leverandører og proprietære teknologier, og hvor det i forklaringen til reglen understreges, at ”hvor det er relevant anvendes bæredygtige open source-komponenter.”  Denne vejledning vil blandt andet belyse ”hvor det er relevant”. 

Statens it-projektmodel skal bidrage til at sikre, at staten ikke igangsætter unødigt risikofyldte it-projekter. Som princip 2 i modellen hedder det, at: ”Allerede indkøbte eller udviklede løsninger skal genbruges i videst muligt omfang.”[^3]

Formålet er at analysere mulige barrierer for offentlige myndigheders anvendelse af open source i Danmark og at synliggøre hvordan og hvornår, det er relevant at anvende open source samt opstille anbefalinger, som offentlige myndigheder i Danmark kan læne sig op ad, når det gælder anvendelse af Open Source. Vejledningen skal tilvejebringe overblik over centrale overvejelser, gode råd og bidrage med helt praksisnær vejledning samt vejlede i, hvordan man gennemfører et udbud og indkøber på en open source-licens. 

Denne vejledning vil forsøge at gøre op med nogle myter om open source samt bygge ovenpå tidligere vejledninger ved i højere grad at belyse hvad open source betyder i praksis og hvilke nuancer, og barrierer, man som offentlig myndighed skal holde sig for øje i anskaffelse og anvendelse af open source, samt bidrage med egentlige tjeklister som fx projektledere og it-arkitekter kan benytte sig af.   

>Faktaboks: hvorfor ikke open source? Her måske et eksempel på barrierer fra analysen senere i vejledningen?

[^3]: https://digst.dk/styring/projektstyring/statens-it-projektmodel/

## Målgruppe

Målgruppen for vejledningen er især projektledere/it-indkøbere, it-arkitekter og beslutningstagere i offentlige myndigheder der skal tage stilling til eventuel anskaffelse af software, og som ønsker viden, praktisk vejledning og anbefalinger og konkrete eksempler i forhold til open source, som er relevante i alle dele af anskaffelsesprocessen og ved efterfølgende drift og vedligeholdelse.

> Faktaboks: Målgruppe: -Topledelsen: porteføljeansvarlige - projektlederen/it-indkøberen - it-arkitekten/udvikleren

Der er tidligere lavet vejledninger om open source til offentlige myndigheder, som er mere overordnede, men ikke har et praksisnært fokus. Vejledningen tilstræber at hjælpe alle, der overvejer eller ønsker at indkøbe software, og som ikke har et forhåndskendskab. 

Samtidig ønskes med vejledningen at bringe projektledere og it-arkitekter i stand til at have en kvalificeret dialog med jurister samt beslutningstagerne i ledelseslaget, i forbindelse med beslutning om evt. anvendelse af open source. 

# Anbefalinger

Anvendelse af open source-software kan bidrage til at understøtte yderligere innovation og konkurrence på softwaremarkedet, fordi softwaren kan genbruges, og videredistribueres med henblik på at andre kan få glæde af den. Dermed undgår fx en myndighed at skulle betale for udviklingen af den samme software flere gange.

Open source-software kan bidrage til sammenhæng og fortsat digital udvikling på tværs af den offentlige sektor. Som nævnt i indledningen har der tidligere været fokus på et ønske om at anvende open source i offentlige myndigheder der, hvor det er relevant. I den forbindelse blev der opstillet en række principper for anvendelse af open source i det offentlige, som skulle sikre de offentlige institutioner store valgmuligheder og innovation samt understøtte, at softwareanskaffelser samlet set gøres billigere og mere fleksible. Principperne for anvendelse af open source blev oplistet i ”Open source-software i det offentlige” af Ministeriet for Videnskab, Teknologi og Udvikling, december 2008 , og de er kun blevet endnu mere relevante siden 2008: 

  * **Konkurrence**<br>
    Velfungerende konkurrence er en forudsætning for et effektivt og varieret softwaremarked. Open source understøtter, at softwaren kan vedligeholdes og videreudvikles af flere leverandører. Softwareleverandører skal på lige vilkår kunne tilbyde deres it-ydelser til det offentlige
  * **Kontrol og selvbestemmelse**<br>
    Anvendelse af open source-software sikrer kontrollen over softwaren. Dermed kan den enkelte myndighed bestemme, hvornår og hvordan softwaren skal opdateres, udvikles og  eventuelt deles med andre myndigheder.
  * **Udvikling og innovation**<br>
    Myndigheder skal ved udvikling af software overveje, hvilken software-udviklingsmodel, herunder open source-udviklings- og forretningsmodellen, som bedst understøtter innovation og hurtig udvikling af nye produkter og services. Egenudviklet software bør som udgangspunkt stilles til rådighed med en open source-licens. Det betyder ikke, at gamle metoder skal opgives, men at flere metoder kan leve side om side, og nye kan afprøves, så fordele og ulemper kan afklares i forhold til den danske forvaltnings virkelighed.
  * **Bedst og billigst uanset softwaretype**<br>
    Den enkelte myndighed skal have mulighed for at erhverve den bedste og billigste software ud fra lokale forvaltningsmæssige behov, uanset om der er tale om closed source- eller open source-software. Software skal vælges på baggrund af en vurdering af en samlet business case.
  * **Sammenhæng og fleksibilitet**<br>
    Myndigheder skal satse på software, der opbygges i mindre dele, og som ved hjælp af åbne standarder er i stand til at kommunikere med andre typer software. Derved sikres det, at enkelte dele af systemet uafhængigt kan udskiftes til gavn for fleksibilitet, genbrug og konkurrence på området.
  * **Genbrug af software**<br>
    Anvendelse af open source-software kan sikre, at skatteborgerne undgår at betale for udvikling af den samme software flere gange

Som antydet i indledningen er der på den anden side dels en række myter forbundet med open source, og dels er der noget, der tyder på, at nogle offentlige myndigheder oplever en række barrierer, som gør det vanskeligt at vælge open source, selvom det havde været relevant for den pågældende it-løsning, der skulle anskaffes. Nedenfor analyseres mulige barrierer for anvendelse af open source, som man med fordel kan holde sig for øje.

## Barrierer

Der er en række barrierer og misforståelser knyttet til begrebet open source. I det følgende identificeres og besvares en række centrale spørgsmål og bekymringer vedr. open source. Fx hvordan open source påvirker sikkerheden i løsningen og omkostninger forbundet med indkøb og drift.  

Myte nr. 1: Open source er en niche for primært computerkyndige, eller meget små løsninger, og ikke særlig udbredt

Myte nr. 2: Man skal selv kunne kode for at anvende open source-løsninger, (og derfor er det svært at anvende for ikke-computerkyndige). 

Myte nr. 3: Open source er gratis, og derfor dårligere kvalitet end proprietær software/closed source. At der som oftest ikke er licensomkostninger ved brug af open source-software, betyder, at der kan hentes nogle direkte besparelser. Men det er ikke gratis at anvende open source-software. De samlede omkostninger kan være de samme, selvom der ikke er licensomkostninger.

Myte nr. 4: open source-løsninger er usikre/sårbare i forhold til proprietære løsninger, fordi der med open source, er fuld transparens om, hvordan løsningen fungerer.  

Myte nr. 5: Det er sværere at vedligeholde og få support, hvis man har problemer med sin open source-software. 

I forhold til myte nr. 5. Nogle af verdens største firmaer, fx Google og Facebook, er afhængige af open source-linuxservere for at opretholde deres platforme. Det vil derfor altid være kritisk for virksomhederne at opretholde den software på hvilken de baserer deres platforme og dermed deres virksomhed. Når der er tale om open source-software vil det desuden altid være muligt for en virksomhed at bringe en uafhængig tredjepart ind for at varetage support og rådgivning fremfor at afvente, at den proprietære udbyder har tid og mulighed for at adressere det problem man måtte have.

Myte 6: Open source er uholdbart, fordi man kan ikke som virksomhed tjene penge på open source.

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

Open source-licenser er softwarelicenser, der tillader, at software frit kan bruges, forbedres og deles. Open Source Initiative har godkendt en række licenser, men anbefaler, at man som udgangspunkt benytter de licenser, der er "populære og bredt anvendte eller med stærke fællesskaber", f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License eller Mozilla Public License (MPL) 2.0.[^4]

> **OS2-fællesskabets brug af licenser**
>
> OS2-fællesskabet benytter open source-licenserne [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/) til kildekode og [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) til dokumentation og andet materiale, der ikke er kildekode. MPL 2.0 er en "file scope"-licens, hvilket vil sige, at filerne og deres indhold er omfattet. I praksis betyder det, at hvis nogen ændrer i filerne, skal ændringerne gives tilbage til OS2.

Læs mere om og find alle de godkendte open source-licenser på https://opensource.org/licenses.

Det er også muligt at anvende EU-Kommissionens værktøj til at finde og sammenligne softwarelicenser på https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses.

[^4]: [Open Source Licenses by Category - Open Source Initiative](https://opensource.org/licenses/category)

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

# Markedet

Når man i en offentlig myndighed tager de første tilløb i forhold til et projekt, der har til formål at anskaffe et nyt it-system skal man blandt andet udarbejde en business case og afsøge markedet. Dette er en stor del af den afdækning, der skal kvalificere beslutningen, om hvorvidt det er relevant at vælge et system på en open source-licens eller ej.
 
Det fremgår af den fællesoffentlige digitale arkitektur, at den offentlige sektor skal bruge software, der både understøtter sammenhænge på tværs af institutioner og understøtter et softwaremarked, hvor leverandører uanset softwaretype kan tilbyde deres produkter til den offentlige sektor. 

I forhold til markedet for open source-løsninger har en del leverandører, heriblandt større leverandører med stor erfaring som leverandør af løsninger til offentlige myndigheder, taget bestik af udviklingen og etableret enheder, der skal udbrede anvendelsen af open source i deres forretning. Der er samtidig også flere myndigheder, der har tilsluttet sig OS2-fællesskabet. Det er med til at validere open source-modellen som en gangbar og profitabel forretningsmodel, der er i stand til at tiltrække etablerede leverandører af digitale løsninger til den offentlige sektor. 

Det handler i sidste ende om, hvilken type software, der passer bedst i en given situation. Det er ikke et spørgsmål om enten open source-software eller closed source-software og softwareleverandører skal på lige vilkår kunne tilbyde deres it-ydelser til det offentlige.

Open source-licens- og forretningsmodellen er modnet, og der er i dag et kommercielt og konkurrencepræget marked, der understøtter en lang række open source-produkter, der bør vurderes på vilkår med proprietære løsninger, så man opnår et kvalificeret beslutningsgrundlag. Open source bør anvendes på baggrund af en samlet vurdering af en business case og markedsafdækning. 

Som tidligere beskrevet er open source ikke gratis, når man beregner et ”total cost of ownership”. Ligesom ved anvendelse af closed source-software er der omkostninger til implementering, tilpasninger samt løbende drift, support og vedligehold. Nogle myndigheder har kompetencer til selv at foretage tilpasninger eller vedligehold af et stykke software, eller en løsning. I de tilfælde er det en billigere løsning, da man ikke har den mulighed med priprietære løsninger. Da man med open source har uhindret adgang til koden vil det derfor ikke være nødvendigt at købe ydelsen hos en leverandør. Det er dog langt fra alle myndigheder, der har kompetencerne indenfor egen personalegruppe. 

Open source kan bidrage til øget kontrol og en fleksibilitet i to henseender:

  1. Fri tilrettelæggelse af softwaren til de præcise behov
  2. Den frie adgang til kildekoden sikrer, at langt flere it-leverandører har mulighed for at tilbyde ydelser til softwaren, og det øger kon-kurrencen på markedet og mindsker risikoen for at blive ”låst” til én leverandør.

Uanset hvilken licensform og forretningsmodel der anvendes, er det vigtigt,
at myndighederne i videst muligt omfang sikrer sig selvbestemmelse og
kontrol over den anskaffede software. Hermed er de selv med til at fastlægge vilkår for anvendelse og videreudvikling. Dette vil være med til at sikre
kvalitet og mindske risikoen for bindinger til bestemte leverandører.

Open source-software tillader udveksling og videreudvikling af software på frie vilkår. Det gør det muligt for mange forskellige it-virksomheder at tilbyde ydelser i forbindelse med softwaren, og at udvikle nye it-produkter. Samtidig kan offentlige myndigheder nemmere samarbejde om at lave sammenhængende it-systemer. Open source kan på den måde skabe dynamik og fremme innovation og konkurrence på markedet.

## Tjekliste til markedsafdækning

  1. Afsøg markedet – er der flere leverandører at vælge mellem? Hvis man vælger at benytte software, som ikke er så hyppigt anvendt, kan antallet af leverandører, som uden videre kan yde service, være begrænset.
  2. Beregn ”total cost of ownership” i forhold til den ønskede løsning. Herunder implementering, tilpasninger samt løbende drift, support og vedligehold
  3. Open source bør kun anvendes dér, hvor det giver værdi, og software skal derfor vælges på baggrund af en vurdering af en samlet business case.

# Kompetencer og fællesskaber

Udvikling, drift og vedligeholdelse af digitale løsninger er en konstant proces, der kræver åbenhed og agilitet, hvis den offentlige sektor skal realisere besparelserne ved omkostningseffektive udbud og sikre robuste digitale tjenester i mange år fremover. 

At arbejde med open source stiller samtidig nogle krav til bestillerne af it-løsninger. Ikke mindst, når det gælder kompetencer hos myndighederne og leverandørerne afhængigt af den valgte anskaffelsesmetode. 

Det følgende skal blandt andet understøtte offentlige myndigheder i forhold til overblik over og håndtering af krav og kompetencer og komme med anbefalinger til opbygning af et open source-community, fastholdelsen af den relevante viden og gode erfaringer med open source som metode og forretningsmodel.

EU's Open Source Observatory (OSOR) fungerer som samlingssted, hvor open source-communities kan mødes og offentliggøre nyheder, få viden om begivenheder, finde relevant open source-programmel, og indhente viden om brug af gratis open source-programmel til brug i den offentlige admini-stration på tværs af Europa.

Til forskel fra proprietære/kommercielle løsninger er open source-løsninger ofte drevet af et fællesskab (community). Det kan det i hvert fald være, og det har en stor betydning ift. placering af ansvar for løsningen. For nogle open source-løsninger bliver der lagt mange frivillige kræfter i projektet. 

Disse forskellige fællesskaber sikrer, at der er mange, der har en dybdegående viden om de forskellige open source-løsninger, og denne viden ligger ofte tilgængelig for den nysgerrige på de respektive løsningers websites. Fællesskaber kan både bruges i selve afsøgningen af markedet og som referencefælleskab og videnbank ved valg af en specifik open source-løsning. 

Udfordringen er, at det kan være svært at gennemskue hvem der i et open source-fællesskab har ansvaret. Som nævnt i afsnittet med vejledning til den konkrete anskaffelse kan det det derfor være særlig vigtigt at indgå en kontrakt om drift, vedligehold, og support af løsningen. I mange offentlige myndigheder vil det være naturligt at forvente, at der ved fejl i en løsning er et telefonnummer til en leverandør, man kan ringe til. 

Forskellige typer it-anskaffelser kræver forskellige kompetencer i den enkelte myndighed. Ved indkøb af kommerciel software har man ikke brug for at have alle kompetencerne internt, da det er leverandøren, der servicerer, implementerer og opdaterer produktet. 

Ved egen anskaffelse – enten nyudvikling eller anskaffelse af allerede eksisterende løsning er det nødvendigt enten allerede at have kompetencerne   eller anskaffe sig disse ved indkøb af en serviceydelse eller uddannelse af ansatte. I lige så høj grad som sidstnævnte type fordrer et større arbejde med af afklare interne kompetencer, handler den om at evne at afsøge markedet for erfaringer med det respektive produkt samt at vurdere egenskaberne og styrken i det fællesskab, der er tilknyttet open source-løsningen. 

Friheden til at ændre softwaren og til at gøre dette i strategiske samarbejder understøtter innovation, dels fordi det er muligt at tilpasse eksisterende software, dels fordi den voksende mængde open source-”hyldevarer” gør det muligt hurtigt at sammensætte nye produkter og services.

Kompetencer/community: Ny incitament-struktur der skal bygges op. Stor investering, hvis man skal opbygge kompetencer til ny – eller videreudvikling af software indenfor egen myndighed. Det vil ofte også kræve et længere perspektiv, hvor ledelsen på forhånd kan se et potentiale i at drive flere open source-projekter, hvis investeringen skal give mening. 
 
De enkelte myndigheder kan opleve en høste-så-problematik, som gør det svært at etablere nye open source-projekter. Med høste-så-problematik menes, at det ikke altid er den myndighed, der lægger alle ressourcerne i et projekt, som høster gevinsterne. Af den grund kan det være særligt relevant i nogle projekter at der mellem flere myndigheder indgås et samarbejde om at (videre)udvikle en løsning, som flere myndigheder kan få glæde af. På den måde deler man ressourcer og risici ved projektet.     

> faktaboks: En god case ift. community her. OS2?

## Tjekliste til kompetencer og fællesskaber

  * Foretag en kompetenceafklaring – allerede inden projektet går i gang
  * Er der behov for egentlige software-udviklingskompetencer i egen myndighed?
  * Er der behov for nye strategiske partnerskaber omkring open-source med andre myndigheder?
  * Er der styr på hvem har ansvaret i et open source-fællesskab?
  * Er der i fællesskabet udstukket retningslinjer for source-kodens placering, readme-filer, og issue lister? Eller er der oprettet en funktion, der kan hjælpe de forskellige projekter med at få disse ting på plads?

# Bilag

## Tjekliste til brug af open source

Kommer snart.

## Katalog over open source-software

Det er en af vejledningens anbefalinger, at offentlige myndigheder så vidt muligt, og hvor det er relevant, genbruger eksisterende open source-software. Til det formål er der brug for et katalog, der gør det nemt at finde og genbruge open source-software.

Det [italienske ministerium for teknologisk innovation og digital omstilling](https://innovazione.gov.it/) har til formålet defineret en metadatastandard for beskrivelse af kildekode til software, der er udviklet eller anskaffet af offentlige myndigheder. Standarden er obligatorisk at anvende til beskrivelse af al offentlig software udviklet i Italien og gør det muligt at udstille løsningerne i et samlet [katalog over open source-software](https://developers.italia.it/en/software).

Ved at inkludere en metadatafil i roden af et offentligt *repository* (et sted til opbevaring af kildekode som f.eks. [Github](https://github.com/)) og udfylde den med oplysninger om softwaren, kan andre offentlige myndigheder og leverandører nemmere opdage, evaluere og eventuelt genbruge den eksisterende open source-software.

Standarden er udviklet til at være interoperabel på tværs af landegrænser, og hvert land kan tilføje nationale udvidelser til kernen.

Standarden hedder publiccode.yml og kan findes på https://docs.italia.it/italia/developers-italia/publiccodeyml-en/en/master/index.html.

## Cases om brug af open source

I forbindelse med udarbejdelsen af vejledning om brug af open source har projektet tilvejebragt en række open source-casebeskrivelser, der hver især belyser et konkret problem og en tilhørende business case for brug af open source til at løse problemet. Casebeskrivelserne har til formål at dele gode råd til og opmærksomhedspunkter ved brug af open source til realisering af en business case og har fokus på realiseringen af en række centrale værdiskabelser, f.eks. kompetencer, ejerskab, samarbejde, dokumentation, kvalitet og økonomi.

Vejledningen inddrager undervejs casebeskrivelserne som konkrete eksempler på problemer, som brug af open source har bidraget til at løse, eller værdiskabelser, som brug af open source har bidraget til at realisere.

Derudover bliver casebeskrivelserne løbende publiceret på [KL og KOMBITs videncenter for digitalisering og teknologi](https://videncenter.kl.dk/viden-og-vaerktoejer/innovation/open-source), der også fremover vil fungere som en fælles platform for deling af viden, værktøjer og cases om brug af open source i den offentlige sektor.

================

[arkitektur.digst.dk](arkitektur.digst.dk)
