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
Title: open-source-guidance 1.0.0-alpha: Fællesoffentlig vejledning om brug af open source
Status: LD
URL: https://github.com/rammearkitektur/open-source-guidance/tree/main/
Editor Term: Udgiver, Udgivere 
Editor: KL, rammearkitektur@kl.dk
Abstract: 'open-source-guidance 1.0.0' .
Boilerplate: copyright no, conformance no, abstract no
Shortname: open-source-guidance
Revision: 1.0.0-alpha
Date: 2021-10-06
Max ToC Depth: 3
Markup Shorthands: markdown yes
Repository: rammearkitektur/open-source-guidance
Translation: en https://rammearkitektur.github.io/open-source-guidance/docs/index-en.html
Inline Github Issues: full
Logo: rammearkitektur
</pre>

<h1>open-source-guidance 1.0.0-alpha: Vejledning om brug af open source</h1>

# Indledning

(indledningen specifikt rettet mod (top)ledelse som målgruppe)

EU har peget på øget brug af Open Source, som en oplagt vej til øget tillid og transparens mellem myndigheder og borgerne . Højt på dagsordenen i det fællesoffentlige digitaliseringssamarbejde er også et ønske om at styr-ke tillid og trygheden ved borgernes og virksomhedernes brug af de offent-lige digitale tjenester:

”Danskernes høje tryghed og tillid til hinanden og til den offentlige sektor er fundamentet for vores velfærd” 

Der er i løbet af det sidste års tid kommet fokus på øgede samfundsgevin-ster i form af blandt andet sikkerhed, transparens og interoperabilitet ved anvendelse af Open Source i offentlige myndigheder. Under overskriften ”Think Open” har EU-kommissionen præsenteret en vision for digital trans-formation, innovation og samarbejde med open source som løftestang for offentlige digitale løsninger, der virker på tværs af grænser og fremtidssik-rer Europas og medlemslandenes teknologiske selvbestemmelse.

## Hvad er open source?

Open Source betyder ”åben kildekode” og der er dermed tale om software, der er distribueret og udviklet i overensstemmelse med princippet om, at et computerprograms kildekode skal være åben og tilgængelig. 

Med open source-software er der dermed frihed til at anvende, undersøge, ændre, forbedre og dele kildekode og dokumentation. Open source vedrø-rer altså selve den kode, som softwaren består af.

Begrebet om open source (åben kildekode) bliver af og til forvekslet med begrebet ’åbne standarder’. Åbne standarder betyder, at koden til den måde softwaren kommunikerer med andre systemer på, er åben og med frit til-gængelige tekniske specifikationer. I modsætning til open source vedrører åbne standarder derfor det ‘sprog’, softwaren kan tale. Sagt på en anden måde, så kan du, når du fremsender en fil, som er baseret på en åben standard være sikker på, at din modtager har mulighed for at åbne filen. 

Et godt eksempel er, at offentlige myndigheder primært udsender filer i pdf-formatet, for at være sikre på, at borgeren i den anden ende kan åbne filen uanset hvilket operativsystem eller software, som borgeren i øvrigt anven-der.

Open Source handler i virkeligheden ikke om teknik, men kan snarere ses som en udviklingsmetode eller en forretningsmodel, der essentielt fremmer offentlige myndigheders medejerskab til deres egne løsninger samt giver mulighed for deling med andre, da løsningen/softwaren ikke er underlagt copyright. 

Modsætningen til open source er proprietære løsninger eller closed source. I proprietære løsninger har vi i modsætning til open source ikke mulighed for at ”kigge under kølerhjelmen” og se hvordan løsningen eller softwaren er bygget. Ved anvendelse af proprietære løsninger er det dermed leveran-døren, der har ansvar for - og den eksklusive copyright til softwaren. Man anvender derfor proprietære løsninger under nogle fastlagte betingelser, og kan ikke selv modificere eller dele løsningen/softwaren med andre.

## Hvorfor en fællesoffentlig vejledning om anvendelse af open source?

Open source er ikke noget nyt begreb, eller ny metode/forretningsmodel. Det nye er, at der, udover et øget fokus i EU, sker en generel samfundsudvikling i andre EU-lande i retning af øgede krav om anvendelse af Open Source. I Italien er der indført et følg-eller-forklar princip for offentlige myndigheder i forhold til anvendelse af Open Source. Frankrig har det største marked for open source i Europa og høj efterspørgsel efter open source i deres myndighe-der. Ud over en egentlig EU open source-strategi gives der i EU-regi støtte til initiativer som Foundation for Public Code. I mange EU-projekter er open source obligatorisk.

Formålet med denne vejledning er ikke at opsætte et modsætningsforhold mellem brug af open source og closed source. Der er ikke tale om et enten-eller, men vejledningen har til derimod hensigt at belyse hvor open source kan give værdi samt skabe grundlaget for en strategisk beslutning for den enkelte myndighed. 

I Danmark kan overvejelser om gevinster ved udbredelse af Open Source-løsninger i offentlige myndigheder i Danmark blandt andet spores tilbage til vejledninger fra det forhenværende It-og Telestyrelsen i årene 2007 og 2008 samt Videncenter for Åbne Standarder og Open Source under Digitali-seringsstyrelsen, som blev etableret med finansiering fra Finansloven i 2014. 

Det tidligere store fokus på anvendelse af open source i offentlige myndigheder er siden hen gledet i baggrunden. Én forklaring kan være, at der var opstået en antagelse om, at anvendelse af open source var blevet en selv-følgelighed, fordi det lå implicit i ”bedst og billigst” .  

Uanset årsagen til, at open source gled lidt i baggrunden, er open Source særligt aktuelt nu, da metoden eller forretningsmodellen understøtter mere modulbaserede og agile måder at udvikle, dele, og genbruge komponenter. Open Source kan være ét element i den aktuelle udvikling med krav om indbygget uafhængighed fremfor opbygning af siloløsninger. 

Anvendelse af open source er samtidig i overensstemmelse med principperne i den fællesoffentlige Digitale Arkitektur og EU's vision for øget brug af Open Source, som nævnt i indledningen. Herunder en dagsorden om mere tillid mellem myndigheder og borgere samt styrkelse af EU’s digitale suverænitet og interoperabilitet mellem medlemslandene. 

At basere software-løsninger på Open source flugter specifikt med arkitek-turregel 2.3 i den fællesoffentlige Digitale Arkitektur om at undgå af-hængighed af leverandører og proprietære teknologier, og hvor det i forkla-ringen til reglen understreges, at ”hvor det er relevant anvendes bæredyg-tige open source-komponenter.”  Denne vejledning vil blandt andet belyse ”hvor det er relevant”. 

Statens it-projektmodel skal bidrage til at sikre, at staten ikke igangsætter unødigt risikofyldte it-projekter. Som princip 2 i modellen hedder det, at: ”Allerede indkøbte eller udviklede løsninger skal genbruges i videst muligt omfang.” 

**Udviklingen i de andre EU-lande aktualiserer behovet for at analysere mulige barrierer for offentlige myndigheders anvendelse af open source i Danmark samt tilvejebringe overblik over centrale overvejelser, gode råd og helt praksisnær vejledning. Det er derfor formålet med denne fællesoffentlige vejledning om anskaffelse og anvendelse af open source.**

Formålet er også at synliggøre hvordan og hvornår, det er relevant at anvende open source samt opstille anbefalinger, som offentlige myndigheder i Danmark kan læne sig op ad, når det gælder anvendelse af Open Source. Vejledningen skal desuden tilvejebringe et overblik over krav og eksisterende open source-software samt vejlede i, hvordan man gennemfører et udbud og indkøber på en open source-licens. 

Vejledningen her vil forsøge at gøre op med nogle myter om open source samt bygge ovenpå tidligere vejledninger ved i højere grad at belyse hvad open source betyder i praksis og hvilke nuancer, og barrierer, man som offentlig myndighed skal holde sig for øje i anskaffelse og anvendelse af open source, samt bidrage med egentlige tjeklister som fx projektledere og it-arkitekter kan benytte sig af.   

### Målgruppe

Målgruppen for vejledningen er især projektledere/it-indkøbere, it-arkitekter i offentlige myndigheder, der i dialog med deres ledelse skal tage stilling til eventuel anskaffelse af software baseret på open source, og som ønsker viden, praktisk vejledning og anbefalinger og konkrete eksempler, som er relevante i alle dele af anskaffelsesprocessen og ved efterfølgende drift og vedligeholdelse.

Der er tidligere lavet vejledninger til offentlige myndigheder, der i højere grad henvender sig til jurister samt vejledninger, som er mere overordnede, men ikke har et praksisnært fokus. Vejledningen tilstræber at hjælpe alle, der overvejer eller ønsker at indkøbe open source, og som ikke har et for-håndskendskab. 

Samtidig ønskes med vejledningen at bringe projektledere og it-arkitekter i stand til at have en kvalificeret dialog med jurister samt beslutningstagerne i ledelseslaget, i forbindelse med beslutning om evt. anvendelse af open source.  

# Anbefalinger om og potentielle gevinster ved brug af open source

Anvendelse af open source-software kan bidrage til at understøtte yderlige-re innovation og konkurrence på softwaremarkedet, fordi softwaren kan genbruges, og videredistribueres med henblik på at andre kan få glæde af den. Dermed undgår skatteborgerne at skulle betale for udviklingen af den samme software flere gange.

Open source-software kan bidrage til sammenhæng og fortsat digital udvik-ling på tværs af den offentlige sektor. Som nævnt i indledningen har der tidligere været fokus på et ønske om at anvende open source i offentlige myndigheder der, hvor det er relevant. I den forbindelse blev der opstillet en række principper for anvendelse af open source i det offentlige, som skulle sikre de offentlige institutioner store valgmuligheder og innovation samt understøtte, at softwareanskaffelser samlet set gøres billigere og mere fleksible. Principperne for anvendelse af open source blev oplistet i ” Open source-software i det offentlige” af Ministeriet for Videnskab, Teknologi og Udvikling, december 2008 , og de er kun blevet endnu mere relevante siden 2008: 

  * Konkurrence
    Velfungerende konkurrence er en forudsætning for et effektivt og varieret softwaremarked. Open source understøtter, at softwaren kan vedligeholdes og videreudvikles af flere leverandører. Soft-wareleverandører skal på lige vilkår kunne tilbyde deres it-ydelser til det offentlige
  * Kontrol og selvbestemmelse
    Anvendelse af open source-software sikrer kontrollen over soft-waren. Dermed kan den enkelte myndighed bestemme, hvornår og hvordan softwaren skal opdateres, udvikles og eventuelt deles med andre myndigheder.
  * Udvikling og innovation
    Myndigheder skal ved udvikling af software overveje, hvilken soft-ware-udviklingsmodel, herunder open source-udviklings- og forret-ningsmodellen, som bedst understøtter innovation og hurtig udvik-ling af nye produkter og services. Egenudviklet software bør som udgangspunkt stilles til rådighed med en open source-licens. Det betyder ikke, at gamle metoder skal opgives, men at flere metoder kan leve side om side, og nye kan afprøves, så fordele og ulemper kan afklares i forhold til den danske forvaltnings virkelighed.
  * Bedst og billigst uanset softwaretype
    Den enkelte myndighed skal have mulighed for at erhverve den bedste og billigste software ud fra lokale forvaltningsmæssige be-hov, uanset om der er tale om closed source- eller open source-software. Software skal vælges på baggrund af en vurdering af en samlet business case.
  * Sammenhæng og fleksibilitet
    Myndigheder skal satse på software, der opbygges i mindre dele, og som ved hjælp af åbne standarder er i stand til at kommunikere med andre typer software. Derved sikres det, at enkelte dele af software-systemet uafhængigt kan udskiftes til gavn for fleksibilitet, genbrug og konkurrence på området.
  * Genbrug af software
    Anvendelse af open source-software kan sikre, at skatteborgerne undgår at betale for udvikling af den samme software flere gange

Som antydet i indledningen er der på den anden side dels en række myter forbundet med open source, og dels er der noget, der tyder på, at nogle offentlige myndigheder oplever en række barrierer, som gør det vanskeligt at vælge open source, selvom det havde været relevant for den pågælden-de it-løsning, der skulle anskaffes. Nedenfor analyseres mulige barrierer for anvendelse af open source, som man med fordel kan holde sig for øje.

## Barrierer for offentlige myndigheders anvendelse af open source 

Der er en række barrierer og misforståelser knyttet til begrebet open sour-ce. I det følgende identificeres og besvares en række centrale spørgsmål og bekymringer vedr. open source. Fx hvordan open source påvirker sik-kerheden i løsningen og omkostninger forbundet med indkøb og drift.  

Myte nr. 1: Open source er en niche for primært computerkyndige, eller meget små løsninger, og ikke særlig udbredt

Myte nr. 2: Man skal selv kunne kode for at anvende Open source-løsninger, (og derfor er det svært at anvende for ikke-computer kyndige). 

Myte nr. 3: Open source er gratis, og derfor dårligere kvalitet end proprie-tær software/closed source. At der som oftest ikke er licensomkostninger ved brug af open source-software, betyder, at der kan hentes nogle direkte besparelser. Men det er ikke gratis at anvende open source-software. De samlede omkostninger vil oftest være de samme, selvom der ikke er li-censomkostninger.

Myte nr. 4: open source-løsninger er usikre/sårbare i forhold til proprietære løsninger, fordi der med open source, er fuld transparens om, hvordan løs-ningen fungerer.  

Myte nr. 5: Det er sværere at vedligeholde- og få support, hvis man har problemer med sin open source-software. 

I forhold til myte nr. 5. Nogle af verdens største firmaer, fx Google og Fa-cebook, er afhængige af Open Source-Linux-servere for at opretholde de-res platforme. Det vil derfor altid være kritisk for virksomhederne at opret-holde den software på hvilken de baserer deres platforme og dermed deres virksomhed. Når der er tale om åben source-software vil det desuden altid være muligt for en virksomhed at bringe en uafhængig tredjepart ind for at varetage support og rådgivning fremfor at afvente, at den proprietære ud-byder har tid og mulighed for at adressere det problem man måtte have.

Myte 6: Open source er uholdbart, fordi man kan ikke som virksomhed tjene penge på open source.

# Anskaffelse af open source - herunder afklaring ift. licenser

Ved it-anskaffelser bør der først og fremmest udarbejdes en business ca-se, der klargør de mulige gevinster, omkostninger og risici, der er forbun-det med valg af forskellige produkter, uanset om det software baseret på open eller closed source. 

Open source og closed source-løsninger kan godt sameksistere og det behøver ikke at være et spørgsmål om enten-eller, og processen vedrø-rende indkøb behøver heller ikke at være særligt forskellige.

## Forskellige scenarier

Overordnet er der tre forskellige scenarier, når det vedrører anvendelse af open source:

  * Myndigheden udvikler selv open source-software 
  * Myndigheden stiller krav til leverandører om anvendelse af open source-software, når disse leverer produkter og projekter til den of-fentlige sektor?
  * Myndigheden ønsker genbrug af software og komponenter, som den offentlige sektor har investeret i på tværs af kommu-ner/regioner/staten

Med andre ord er det vigtigt at holde sig for øje, at der er forskel på køb af en open source-løsning der allerede eksisterer og en anskaffelse, der handler om udvikling af open source-software, mere eller mindre fra bun-den. Myndigheder kan således både være brugere af eksisterende open source-software eller være licensgivere, som kan stille software til rådig-hed for andre myndigheder eller andre aktører.
Det handler om hvad der skaber mest værdi og bedste business case i de enkelte situationer, men det er vigtigt at have de strategiske overvejer tid-ligt og allerede i idéfasen af projektet og måske allerede inden, der overho-vedet er en projektleder. 

Derudover behøver indkøb af open source ikke at være ret meget anderle-des end closed source. Det kræver blot, at man husker at lave gode drifts – og support aftaler med en leverandør i forbindelse med indkøb. At stille krav om open source, hvis det er relevant i et udbud, der vedrører it-anskaffelser, fremmer den åbne konkurrence, der er det grundlæggende formål med udbudsreglerne. 

Der således ikke noget til hinder for, at ordregiver køber eller på anden vis betinger, at programmet kan benyttes, ændres og stilles til rådighed for almenheden under en open source-licens. 

At kildekoden er åben og frit kan genbruges, betyder ikke blot at én myn-dighed kan videredistribuere sin open source-software til en anden myndig-hed. Det betyder også, at den anden myndighed kan forbedre softwaren og derefter igen dele det forbedrede produkt med den første myndighed eller med andre. På den måde kan der være flere om at forbedre softwaren og om at finansiere fremtidig udvikling.

Med alle typer af it-anskaffelser kan der være mange elementer man skal huske i løbet af processen. Nedenfor er derfor opstillet en tjekliste til brug ved anskaffelse af open source. Herunder til afklaring i forhold til licenser.  

Licenser kan indeholde forskellige vilkår om f.eks. at publicerede videreudviklinger skal videregives under samme vilkår (såkaldte copyleft-vilkår). Dette element kan være vigtigt i henhold til at sikre, at produktet ikke senere hen overgår fra open til closed source.

Under hensyn til gennemsigtigheden må det derfor i alle tilfælde kræves, at ordregiver specificerer, hvilke open source-(mindste)krav, der stilles til det programmel, som skal (videre)udvikles.

Specifikationen kan evt. ske ved blot at anføre, at programmellet skal være licenseret via en licens, der er optaget på Open Source Initiative's liste over anerkendte open source-licenser .

## Tjekliste til brug i forhold til anskaffelse af open source 

(vil blive inddelt på faser jf. ’den gode it-anskaffelse’)

  1. Al software skal leveres til kunden under en Open Source-softwarelicens godkendt af Open Software Initiative. Det kan fx væ-re Mozilla Public Licensen 2.0 https://www.mozilla.org/MPL/2.0/.  
  2. Er produktet tilgængeligt på Github? Github er et godt sted at starte sin søgning efter Open Source-projekter/løsninger
  3. Ved ny – og videreudvikling skal kildekoden publiceres på et offent-ligt tilgængeligt repository, fx GitHub. 
  4. Sammen med kildekoden skal det være muligt at hente vejlednin-ger og dokumentation, der forklarer, hvordan man anvender kilde-koden til at bygge og implementere løsningen. Hermed opnår kun-den ejerskab og rettigheder til materialet. I forbindelse med at åbne op for kildekoden er et vigtigt skridt dokumentationen. 
  5. Tilbudsgiver skal levere en veldokumenteret Open Source-løsning, således at eventuel videreudvikling kan foretages af andre leveran-dører. Dette inkluderer teknisk dokumentation, herunder systembe-skrivelser og arkitekturtegninger. Dermed sikrer man også, at løs-ninger kan drives videre efter kontraktudløb
  6. Den tekniske dokumentation og koden skal overholde krav og standarder tilhørende den valgte Open Source-licens. 
  7. Sørg for, at der foretages kodereview af kildekoden
  8. Det er vigtigt at forholde sig til en ”upgrade-strategi”, altså hvordan løsningen kan udvikles og vedligeholdes 
  9. Skal der indgås kontrakt med en drifts- og support-leverandør? 
  10. Al skriftligt materiale jf. ovenstående, som produceres af tilbudsgi-ver, herunder dokumentation, licenseres under en Creative Com-mons licens, og det er god skik at nævne de personer der har ydet bidrag til projektet. 
  11. Al software skal leveres til kunden med åbne standarder. Tilbuds-giveren skal sørge for at løsningen har åbne snitflader. 
  12. Løsningen skal bygge på åbne standarder, hvor standarden er vel-dokumenteret med den fuldstændige specifikation og er offentligt tilgængelig. 
  13. Det er et krav, at udveksling af data mellem løsningen og andre systemer skal ske via åbne standardiserede snitflader, så nuvæ-rende og fremtidige behov for systemintegration kan dækkes.
  14. Standarden skal være frit implementérbar uden økonomiske, politi-ske eller juridiske begrænsninger på implementering og anvendel-se hverken nu eller i fremtiden. 
  15. Standarden skal være godkendt og vedligeholdt i et åbent forum (standardiseringsorganisation) via en åben proces. 
  16. Implementering af standarden må ikke kræve nogen anden tekno-logi, der ikke opfylder kriterierne i dette krav. Tilbudsgiveren skal redegøre for, hvordan systemet lever op til kravene i aftale om an-vendelse af åbne standarder for software i det offentlige (B103) og de syv åbne standarder, der trådte i kraft pr. 01.01.2008. 
  17. Det tilbudte system skal leveres med en åben og fleksibel data-struktur og med omkostningsfri adgang til samtlige data i det til-budte system. 
  18. Alle data der ligger i det tilbudte system skal stilles tilgængelig for ordregiver i overskuelig datamodel. Metadata betragtes som en del af data. Dokumentation af datamodel (f.eks. E/R-diagram), nøgler, fortolkninger, opdateringsmetoder og tabelstrukturer skal være til-gængelig for ordregiver, og skal vedligeholdes af tilbudsgiver, så oplysninger til enhver tid er ajour.
  19. Data skal gøres tilgængelig for ordregiver på en måde, som ikke forudsætter manuelle processer ud over opsætning og programme-ring. Desuden skal data gøres tilgængelig i et læsbart standardda-tabaseformat. Tilgængeligheden må ikke i mærkbar grad påvirke den normale driftssituation på den tilbudte løsning. 
  20. Strukturering af indholdet i snitfladen aftales nærmere med ordregi-vers datavarehusteam. 
  21. Data skal gøres tilgængelig med aftalt frekvens bestemt af behovet og informationernes karakter. Som udgangspunkt forventes data ’leveret’ om aftenen/natten på daglig/ugentlig basis – i et aftalt miks mellem fuld load og delta load. Ved levering, skal gårsdagens sta-tus/tilføjelser/rettelser være tilgængelig i ordregivers datavarehus næste dags morgen. 
  22. Data skal være kontrolleret for overholdelse af konsistenskrav og valideret mht. type og feltindhold. 
  23. Enhver ændring af datasnitfladen skal meddeles til ordregivers da-tavarehusteam i rimelig tid inden ændringen gennemføres, således ordregiver har mulighed for at tilrette de bagvedliggende processer. 
  24. Leverandøren er alene berettiget til at anvende kundens data til brug for udførelse af de af kontrakten omfattede leverancer og ydelser. 
  25. Leverandøren erhverver hverken ejendomsret, ophavsret eller no-gen anden rettighed til kundens data, uanset om disse data optræ-der elektronisk i systemet eller som print. 
  26. Leverandøren skal behandle kundens data fortroligt i overens-stemmelse med persondataloven, aftalte sikkerhedsprocedurer og god IT-skik. 
  27. Det skal fremgå, at hvis kontrakten opsiges eller på anden måde ændres, så skal ejerskab over alle data tilfalde ordregiver

### Hvis det er en eksisterende løsning

 1. Findes der god og dokumentation: "Sådan kommer du i gang", "Så-dan kommer du videre", "Sådan bidrager du"? dækkende informati-on om anvendelse, set-up og bidrag
 2. Ser det ud til at være under aktiv udvikling, hvornår var seneste commit til source koden, hvornår var seneste release, hvornår var seneste kommentar eller status-skift på et rapporteret issue?
 3. Er der mange issues med softwaren, hvilke typer af issues er det, er det ændringsforslag og forslag til ny funktionalitet, ellerer det bug-rapporter? danne sig et indtryk af, om issues bliver løst og om der arbejdes aktivt på projekterne. Det betyder fx, at der bør være adgang til/links til Issue lister
 4. Er der et åbent community forum, med folk der bidrager til at løse issues, og hvor brugerne udveksler erfaringer og hjælper hinan-den? 

# Markedet

Når man i en offentlig myndighed tager de første tilløb i forhold til et pro-jekt, der har til formål at anskaffe et nyt it-system skal man blandt andet udarbejde en business case og afsøge markedet. Dette er en stor del af den afdækning, der skal kvalificere beslutningen, om hvorvidt det er rele-vant at vælge et system på en open source-licens eller ej.
 
Det fremgår af den fællesoffentlige digitale arkitektur, at den offentlige sek-tor skal bruge software, der både understøtter sammenhænge på tværs af institutioner og understøtter et softwaremarked, hvor leverandører uanset softwaretype kan tilbyde deres produkter til den offentlige sektor. 

I forhold til markedet for open source-løsninger har en del leverandører, heriblandt større leverandører med stor erfaring som leverandør af løsnin-ger til offentlige myndigheder, taget bestik af udviklingen og etableret en-heder, der skal udbrede anvendelsen af open source i deres forretning. Der er samtidig også flere myndigheder, der har tilsluttet sig OS2-fællesskabet. Det er med til at validere open source-modellen som en gangbar og profita-bel forretningsmodel, der er i stand til at tiltrække etablerede leverandører af digitale løsninger til den offentlige sektor. 

Det handler i sidste ende om, hvilken type software, der passer bedst i en given situation. Det er ikke et spørgsmål om enten open source-software eller closed source-software og softwareleverandører skal på lige vilkår kunne tilbyde deres it-ydelser til det offentlige.

Open source-licens- og forretningsmodellen er modnet, og der er i dag et kommercielt og konkurrencepræget marked, der understøtter en lang ræk-ke open source-produkter, der bør vurderes på vilkår med proprietære løs-ninger, så man opnår et kvalificeret beslutningsgrundlag. Open source bør kun anvendes dér, hvor det giver værdi, og software skal derfor vælges på baggrund af en vurdering af en samlet business case og herunder mar-kedsafdækning. 

Som tidligere beskrevet er open source ikke gratis, når man beregner et ”total cost of ownership”. Ligesom ved anvendelse af closed source-software er der omkostninger til implementering, tilpasninger samt løbende drift, support og vedligehold. Nogle myndigheder har kompetencer til selv at foretage tilpasninger eller vedligehold af et stykke software, eller en løs-ning. Da man med open source har uhindret adgang til koden vil det derfor ikke være nødvendigt at købe ydelsen hos en leverandør. Det er dog langt fra alle myndigheder, der har kompetencerne indenfor egen personalegrup-pe. 

Open source kan bidrage til øget kontrol og en fleksibilitet i to henseender:

  1. Fri tilrettelæggelse af softwaren til de præcise behov
  2. Den frie adgang til kildekoden sikrer, at langt flere it-leverandører har mulighed for at tilbyde ydelser til softwaren, og det øger kon-kurrencen på markedet og mindsker risikoen for at blive ”låst” til én leverandør.

Uanset hvilken licensform og forretningsmodel der anvendes, er det vigtigt,
at myndighederne i videst muligt omfang sikrer sig selvbestemmelse og
kontrol over den anskaffede software. Hermed er de selv med til at fast-lægge vilkår for anvendelse og videreudvikling. Dette vil være med til at sikre
kvalitet og mindske risikoen for bindinger til bestemte leverandører.

Open source-software tillader udveksling og videreudvikling af software på frie vilkår. Det gør det muligt for mange forskellige it-virksomheder at tilby-de ydelser i forbindelse med softwaren, og at udvikle nye it-produkter. Samtidig kan offentlige myndigheder nemmere samarbejde om at lave sammenhængende it-systemer. Open source kan på den måde skabe dy-namik og fremme innovation og konkurrence på markedet.

## Tjekliste til brug for afsøgning af markedet

  1. Afsøg markedet – er der flere leverandører at vælge mellem? Hvis man vælger at benytte software, som ikke er så hyppigt anvendt, kan antallet af leverandører, som uden videre kan yde service, væ-re begrænset.
  2. Beregn ”total cost of ownership” i forhold til den ønskede løsning. Herunder implementering, tilpasninger samt løbende drift, support og vedligehold
  3. Open source bør kun anvendes dér, hvor det giver værdi, og soft-ware skal derfor vælges på baggrund af en vurdering af en samlet business case.

# Kompetencer og community-opbygning

Udvikling, drift og vedligeholdelse af digitale løsninger er en konstant pro-ces, der kræver åbenhed og agilitet, hvis den offentlige sektor skal realise-re besparelserne ved omkostningseffektive udbud og sikre robuste digitale tjenester i mange år fremover. 

At arbejde med open source stiller samtidig nogle krav til bestillerne af it-løsninger. Ikke mindst, når det gælder kompetencer hos myndighederne og leverandørerne afhængigt af den valgte anskaffelsesmetode. 

Det følgende skal blandt andet understøtte offentlige myndigheder i forhold til overblik over og håndtering af krav og kompetencer og komme med an-befalinger til opbygning af et open source-community, fastholdelsen af den relevante viden og gode erfaringer med open source som metode og forret-ningsmodel.

EU's Open Source Observatory (OSOR) fungerer som samlingssted, hvor open source-communities kan mødes og offentliggøre nyheder, få viden om begivenheder, finde relevant open source-programmel, og indhente viden om brug af gratis open source-programmel til brug i den offentlige admini-stration på tværs af Europa.

Til forskel fra proprietære/kommercielle løsninger er open source-løsninger ofte drevet af et fællesskab (community). Det kan det i hvert fald være, og det har en stor betydning ift. placering af ansvar for løsningen. For nogle open source-løsninger bliver der lagt mange frivillige kræfter i projektet. 

Disse forskellige fællesskaber sikrer, at der er mange, der har en dybde-gående viden om de forskellige Open Source-løsninger, og denne viden ligger ofte tilgængelig for den nysgerrige på de respektive løsningers web-sites. Fællesskaber kan både bruges i selve afsøgningen af markedet og som referencefælleskab og videnbank ved valg af en specifik Open Sour-ce-løsning. 

Udfordringen er, at det kan være svært at gennemskue hvem der i et open source-community har ansvaret. Som nævnt i afsnittet med vejledning til den konkrete anskaffelse kan det det derfor være særlig vigtigt at indgå en kontrakt om drift, vedligehold, og support af løsningen. I mange offentlige myndigheder vil det være naturligt at forvente, at der ved fejl i en løsning er et telefonnummer til en leverandør, man kan ringe til. 

Forskellige typer it-anskaffelser kræver forskellige kompetencer i den en-kelte myndighed. Ved indkøb af kommerciel software har man ikke brug for at have alle kompetencerne internt, da det er leverandøren, der servicerer, implementerer og opdaterer produktet. 

Ved egen anskaffelse – enten nyudvikling eller anskaffelse af allerede ek-sisterende løsning er det nødvendigt enten allerede at have kompetencerne   eller anskaffe sig disse ved indkøb af en serviceydelse eller uddannelse af ansatte. I lige så høj grad som sidstnævnte type fordrer et større arbejde med af afklare interne kompetencer, handler den om at evne at afsøge markedet for erfaringer med det respektive produkt samt at vurdere egen-skaberne og styrken i det fællesskab, der er tilknyttet Open Source-løsningen. 

Friheden til at ændre softwaren og til at gøre dette i strategiske samarbej-der understøtter innovation, dels fordi det er muligt at tilpasse eksisterende software, dels fordi den voksende mængde open source-”hyldevarer” gør det muligt hurtigt at sammensætte nye produkter og services.

Kompetencer/community: Ny incitament-struktur der skal bygges op. Stor investering, hvis man skal opbygge kompetencer til ny – eller videreudvik-ling af software indenfor egen myndighed. Det vil ofte også kræve et læn-gere perspektiv, hvor ledelsen på forhånd kan se et potentiale i at drive flere open source-projekter, hvis investeringen skal give mening. 
 
De enkelte myndigheder kan opleve en høste-så-problematik, som gør det svært at etablere nye open source-projekter. Med høste-så-problematik menes, at det ikke altid er den myndighed, der lægger alle ressourcerne i et projekt, som høster gevinsterne. Af den grund kan det være særligt re-levant i nogle projekter at der mellem flere myndigheder indgås et samar-bejde om at (videre)udvikle en løsning, som flere myndigheder kan få glæ-de af. På den måde deler man ressourcer og risici ved projektet.     

Kapabiliteter, enterprisearkitektur – analyse af landskab.

Community: Give tilbage – hindringer til donationer. Daglig support. 

Kompetencer: Der dukker nye opgaver/roller op; kodereview, gode driftsle-verandører (5 på OS2iot) – det kommer ikke af sig selv, vi skal være ek-splicitte om det.

Ressourcer i OS2 og OSOR. OS2-samarbejdets organisation - ressourcer råd  og vejledning. 

## Tjekliste til kompetencer/community-opbygning

  * Foretag en kompetenceafklaring – allerede inden projektet går i gang
  * Er der behov for egentlige software-udviklingskompetencer i egen myndighed?
  * Er der behov for nye strategiske partnerskaber omkring open-source med andre myndigheder?
  * Er der styr på hvem har ansvaret i et OS-community?
  * Er der i fællesskabet udstukket retningslinjer for source-kodens placering, readme-filer, og issue lister? Eller er der oprettet en funktion, der kan hjælpe de forskellige projekter med at få disse ting på plads?

# Internationale strømninger

I 2017 har ministrene, som er ansvarlige for eGovernment politik i EU’s medlemslande, underskrevet den såkaldte Tallin deklaration. Under punkt 5, Interoperability by default, er der anført følgende:

Under 1. har Kommissionen udarbejdet vejledningen ”The Sharing and Reu-se Framework for IT Solutions”. I punkt 4, Promote legal certainty, i denne vejledning anbefales det, at offentlige myndigheder anvender software li-censer med færrest mulige legale barrierer, så der etableres mindst mulige begrænsninger i at dele og genbruge software. Dette oplyses at blive gjort bedst ved at anvende open source-licenser så som EUPL. I punkt 5 anbefa-les det, at myndighederne som led i deres kontrakter og standard klausuler lægger vægt på, at deling og genbrug bliver en del heraf. ISA programmet har udarbejdet en række standardklausuler, som det anføres, at offentlige myndigheder kan anvende .

ISA programmet understøtter 54 initiativer, som er fokuseret på udvikling af digitale løsninger indenfor området for interoperabilitet. 

Et af disse initiativer er:

* Promoting sharing and reuse of IT solutions

Under dette initiativ understøtter EU offentlige administrationer i at dele og genbruge IT løsninger. Dette gøres ved tilvejebringelse af 

  1. Et Framework for Sharing and Reuse of IT Solutions
  2. Årlige prisuddelinger til offentlige myndigheder, som har delt og genbrugt IT løsninger og iii) årlige konferencer, hvor best prac-tice og erfaringer med deling og genbrug af IT løsninger ud-veksles.

Under dette initiativ har EU etableret en platform, hvorpå deling og genbrug af IT-løsninger og best practice kan ske mellem professionelle aktører på tværs af EU og udover Europa. Joinup fungerer som et katalog, hvor bru-gerne gratis og let kan finde og downloade allerede udviklede IT-løsninger. Dags dato er der 2.820 IT-løsninger, som deles på platformen.

En undersøgelse  er blevet offentliggjort i september 2021 af det der hed-der GD CONNECT- enheden i Europa -Kommissionen. Enheden har til op-gave at fremhæve virkningen af open source - software og hardware på EU's økonomi. Dette med hensyn til innovation, konkurrenceevne, teknolo-gisk uafhængighed og jobskabelse.

Ifølge undersøgelsen investerede virksomheder i EU omkring 1 milliard euro i open source - software (OSS) i 2018 med en anslået indvirkning på eurozonens økonomi på mellem 65 og 95 milliarder euro. Også ifølge un-dersøgelsen kan en stigning på 10% i investeringer i OSS bidrage til føds-len af over 600 nye opstartsvirksomheder i EU og generere en stigning i BNP på 100 milliarder euro.

Derudover fremhæver undersøgelsen, hvordan brug af udelukkende open source-software i stedet for proprietær software kan: 

  * Fremme den offentlige sektors uafhængighed i Unionen
  * Reducere omkostninger 
  * Begrænse fænomenet lock-in (afhængighed af leverandører). 

Set fra EU's perspektiv kan open source dermed være en nøgle til et mere autonomt og teknologisk suverænt EU løsrevet fra techgiganter. Det er en stor del af forklaringen på, at der fra EU's side tilskyndes til anvendelse af open source samt, at der er udarbejdet anerkendte standarder for, hvorle-des programmel deles og genanvendes, ud fra et ønske om anvendelse af færrest mulige ressourcer.

Undersøgelsen fremhæver nogle anbefalinger, der skal skabe et mere uaf-hængigt og konkurrencedygtigt Europa. Herunder bl.a. at betragte open source som en grundlæggende komponent i den offentlige forvaltnings digitale transformation samt direkte finansiere udviklingen af open source -software og dens sikkerhed. 

Som nævnt i indledningen er Italien et af de lande blandt vores europæiske partnere, hvor open source -politikker en del af landets bredere digitale transformationsarbejde. I Italien har man lovgivningsmæssigt lagt op til, at det er nødvendigt at prioritere open source - løsninger i valget af software til den offentlige administration. Den italienske forfatningsdomstol har i 2010 fastslået, at en lov, hvorefter open source-programmer gives fortrins-ret i offentlige udbud, er lovlig. Myndighederne forpligter sig til at offentlig-gøre koden til en software, der er udviklet under en open source-licens, for at gøre den genanvendelig.

# Overblik over hvor man kan finde åben kildekode og open source-software

(bliver svært at gøre udtømmende og kan hurtigt blive uaktuelt - taler for et levende dokument)

Følgende vil bidrage til at skabe et overblik over open source-produkter. Der er en række websites, der har relevans for danske myndigheder, der leverer oversigter over gode Open Source-alternativer og – løsninger. 

www.github.com
www.alternativeto.net
www.linuxalt.com
www.osalt.com
www.sourceforge.net
www.tuleap.org
https://joinup.ec.europa.eu/collection/open-source-observatory-osor/oss-repositories
www.opensource.com

Ovenstående er nogle af de mest bruge Open Source-biblioteker, der har samlet alt fra simple til meget komplekse systemer baseret på Open Sour-ce og giver direkte adgang til download.

# Bilag: Casebeskrivelser til inspiration

Vejledningen vil inddrage konkrete cases til at belyse fx argumenter for valg eller fravalg af open source i forbindelse med en anskaffelse, erfarin-ger med drift, vedligeholdelse og genudbud af open source-løsninger og viden og erfaringer om etablering og drift af blivende, åbne partnerskaber.

(måske henvise til cases, som lægges på en open source-temaside på KL/KOMBITS videnscenter? Fx Tage udgangspunkt i fx 5 arketypiske pro-jekter (forståelse af forskellige behov))

5 mønstre/modenhedsniveauer: hvem er du som myndighed – koble til ca-se?

Hos STIL ville man undgå vendor-lock-in (mulig case – rammeaftale om service og rejse imod fuld ejerskab af kode). 

================

[rammearkitektur.kl.dk](rammearkitektur.kl.dk)
