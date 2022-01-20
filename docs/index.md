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
Title: open-source-guidance 1.0.0-rc: Vejledning om brug af open source i den offentlige sektor
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
Revision: 1.0.0-rc
Date: 2022-01-20
Max ToC Depth: 3
Markup Shorthands: markdown yes
Repository: rammearkitektur/open-source-guidance
Translation: en https://rammearkitektur.github.io/open-source-guidance/docs/index-en.html
Inline Github Issues: full
Logo: rammearkitektur
</pre>

<h1>open-source-guidance 1.0.0-rc: Vejledning om brug af open source i den offentlige sektor</h1>

# Målgruppe og læsevejledning

Målgruppen for vejledningen er it-projektledere, -jurister og -arkitekter, indkøbere og contract managers samt it-chefer og andre strategiske beslutningstagere hos offentlige myndigheder, der skal tage stilling til anskaffelse af software, og som ønsker mere viden, konkrete eksempler og praktisk vejledning til brug af open source.

Open source-software er software udgivet under en licens, der giver enhver ret til at bruge, undersøge, ændre og dele softwaren og dens kildekode frit og til ethvert formål.

Open source handler ikke om it-afdelingens teknologiske præferencer, men er en strategisk forretningsmodel og nogle udviklingsmetoder, der fremmer offentlige myndigheders medejerskab til deres løsninger og skaber bedre muligheder for at dele, videreudvikle og genbruge digitale løsninger.

# Indledning

Danske myndigheder investerer massivt i digitalisering, og der er et stort behov for, at digitale løsninger er fleksible, sammenhængende og bygget til genbrug og forandring.

Offentlige myndigheder undgår så vidt muligt løsninger, der skaber afhængighed af specifikke leverandører og teknologier, og [hvor det er relevant, kan de anvende bæredygtige open source-komponenter](https://arkitektur.digst.dk/principper-og-regler/princip-2-arkitektur-fremmer-sammenhaeng-innovation-og-effektivitet-4).

I valget mellem open source-software og proprietære løsninger er det ikke et spørgsmål om enten-eller, men om at vælge den løsning, der skaber værdi på baggrund af de udfordringer og behov, der er relevante for den enkelte myndighed. 

> Figur: Open source og proprietær software (DIGST)

Der er et stort potentiale i åbne og cirkulære forretningsmodeller og open source-software, der brugt på de rigtige områder kan bidrage til at understøtte bæredygtig udvikling, innovation og kvalitet, styrke danske virksomheders omstillingsparathed og konkurrenceevne og øge vækst og eksport af digitale løsninger. 

> Figur: Åbne standarder mellem open source og proprietær software (DIGST)

Åbne standarder fremmer konkurrence på markedet for software og medvirker til, at offentlige it-systemer uanset valg af software kan udveksle informationer på tværs. De er det fælles sprog, systemerne bruger til at tale med og forstå hinanden.

Der findes mange kendte og udbredte open source-softwareprodukter. Distributioner af Linux-styresystemet understøtter omkring 70 % af internettets 10 mio. mest besøgte hjemmesider, der ofte hostes på webservere som Nginx (33 %) eller Apache HTTP Server (24 %). 42 % af hjemmesiderne er udviklet med Wordpress, men også Drupal og Umbraco er open source. Omkring 65 % browser internettet med Google Chrome, og 84 % kører det Linux-baserede styresystem Android på deres smartphone. 

> Figur: Open source findes på alle hylderne i softwarestakken (DIGST)

Danske offentlige myndigheder bruger LibreOffice til teksbehandling og QGIS til geodatabehandling, og 82 kommuner bruger OS2kitos - ofte sammen med et af de andre 21 OS2-produkter - til at holde styr på deres systemportefølje.

Formålet med denne vejledning er ikke at opsætte et modsætningsforhold mellem brug af open source-software og proprietære løsninger. Derfor beskriver vejledningen en række af de vigtigste overvejelser ved anskaffelse, herunder **strategier og markedsafdækning**, **licenser og implementering** og **udvikling og vedligeholdelse**.

> Figur: Proces for it-anskaffelser (DIGST)

**Strategier og markedsafdækning** beskriver myndighedernes overvejelser om strategier for anskaffelse af open source-software og afdækning af markedet for både eksisterende open source-komponenter og proprietære løsninger.

**Licenser og implementering** beskriver myndighedernes overvejelser om brug af open source-licenser og implementering af open source, uanset om det eksisterende komponenter, der er genbrugt fra hylderne, eller software udviklet selv eller i fællesskab med andre.

**Udvikling og vedligeholdelse** beskriver overvejelser om udvikling og vedligeholdelse, herunder drift, af open source-software, der består af løbende opgaver, der alle stiller krav til kompetencer, hvorfor myndigheder med fordel kan deltage i open source-fællesskaber.

# Strategier og markedsafdækning

Formålet med dette afsnit er at beskrive offentlige myndigheders overvejelser om strategier for anskaffelse af open source-software. Det er ikke et spørgsmål om enten-eller, men derimod om at vælge den strategi, der passer bedst til den konkrete situation.

Open source-software og proprietære løsninger kan sagtens sameksistere, hvis man vælger forskellige strategier fra gang til gang, og processen for anskaffelse er stort set den samme. De kræver dog hver især forskellige kompetencer og krav til samarbejde.

## Strategier

Overordnet findes der tre strategier for anskaffelse af open source, som offentlige myndigheder har i værktøjskassen og kan anvende i forbindelse med it-anskaffelser:

> Figur: Open source-anskaffelsesstrategier (DIGST)

  * **Myndigheden genbruger fra hylderne**<br>
    Offentlige myndigheder, der anvender denne strategi, genbruger eksisterende open source-software, hvor det er relevant. Det kan være komponenter eller enkeltstående applikationer, der er gode eller billige alternativer til proprietære løsninger. Denne strategi omfatter også myndigheder, der er mindre bevidste om, at de anvender open source.
  * **Myndigheden udvikler selv**<br>
    Offentlige myndigheder, der anvender denne strategi, udvikler selv løsninger, der foruden at anvende eksisterende open source-komponenter udgives under en open source-licens. Det kan være for at stille software til rådighed for andre myndigheder eller virksomheder for at øge anvendelsen eller få andre til at bidrage til vedligeholdelsen.
  * **Myndigheden udvikler i fællesskab**<br>
    Offentlige myndigheder, der anvender denne strategi, udvikler i fællesskab med andre løsninger, der lever op til ovenstående. Det kan være for at dele risici og omkostninger med andre myndigheder eller virksomheder og skabe et fællesskab omkring vedligeholdelse af løsningen eller en række løsninger i et økosystem.

Med andre ord er der forskellige strategiske årsager til at genbruge eksisterende open source-software og udvikle open source-software selv eller i fællesskab med andre. De forskellige strategier har hver deres fordele, men kræver også noget af myndigherne i form af kompetencer.

At kildekoden er åben og frit kan genbruges, betyder ikke kun, at en myndighed kan dele sin open source-software med en anden myndighed. Det betyder også, at den anden myndighed kan forbedre softwaren og derefter dele den forbedrede løsning med den første myndighed og med andre. På den måde kan der være flere om at forbedre softwaren og finansiere fremtidige ønsker til videreudvikling.

## Tjekliste til strategier

1. Er fordele og ulemper ved anvendelse af open source undersøgt?

   Offentlige myndigheder kan have en overordnet strategi for brug af open source, eller kan fra anskaffelse til anskaffelse overveje fordele og ulemper og den konkrete værdiskabelse ved anvendelse af open source.
   
2. Er risici, behov for tekniske kompetencer og andre ressourcer og omkostninger ved udvikling af open source undersøgt?

   Offentlige myndigheder, der ønsker at udvikle open source-software, kan forholde sig til risici, behov for tekniske kompetencer og andre ressourcer og omkostninger ved udvikling selv i forhold til udvikling i fællesskab med andre.
   
3. Er de rette kompetencer til at arbejde med open source sikret?

   Offentlige myndigheder bør sikre sig de rette kompetencer til at arbejde med open source, uanset om de genbruger eksisterende open source-komponenter, udvikler selv eller udvikler i fællesskab med andre.
   
4. Er de forskellige niveauer i softwarestakken identificeret med henblik på hvor open source giver mest værdi?
   
   Offentlige myndigheder kan danne sig et overblik over brug af open source-software på forskellige niveauer i softwarestakken og anvende en helhedsorienteret tilgang til   anskaffelser, der udnytter synergier mellem software som f.eks. de populære open source-softwarestakke LAMP og MEAN.
   
5. Er der valgt medie til offentliggørelse af kildekode? 
   
   Offentlige myndigheder kan ved ny- eller videreudvikling overveje, om kildekoden kan offentliggøres på f.eks. [GitHub](https://github.com/).

## Markedsafdækning

Det fremgår af den Fællesoffentlige Digitale Arkitektur, at den offentlige sektor kan bruge software, der understøtter sammenhængende digitalisering uden bindinger til leverandører og proprietære teknologier og udvikler et marked, hvor flere leverandører kan konkurrere om at levere systemer og services innovativt, billigt og fleksibelt, og der er plads til både standardløsninger og moduler fra flere leverandører baseret på åbne snitflader.

På markedet for open source-software har mange leverandører, herunder en række større leverandører med lange erfaringer som leverandører til offentlige myndigheder, taget bestik af udviklingen og etableret enheder, der udvikler open source-software for offentlige myndigheder og byder ind på ydelser omkring vedligeholdelse og videreudvikling.

F.eks. har OS2-fællesskabet omkring 70 leverandørpartnere, der producerer og overleverer produkter til fællesskabet, leverer udviklingskraft og teknologividen, implementering, drift og support og er i aktiv dialog med fællesskabet om nye forretningsmuligheder.

Dette er med til at validere open source som en udbredt og rentabel forretningsmodel på det danske leverandørmarked og viser med al tydelighed, at open source-software ikke er gratis, eller at en open source-strategi river tæppet væk under leverandørerne. Det er derimod en udviklingsmetode til at imødekomme udfordringer med at genbruge og videreudvikle digitale løsninger, der kommer af leverandøruafhængighed, teknisk gæld, kompetencetab og manglende ejerskab til kildekoden.

> Figur: Overordnede strategiske valg (DIGST)

Som tidligere beskrevet er open source ikke gratis, når man beregner en *Total Cost of Ownership* (TCO). Ligesom ved anvendelse af closed source-software er der omkostninger til implementering, videreudvikling og løbende drift, support og vedligeholdelse. Det kræver samtidig også, at myndigheden har og kan allokere de nødvendige ressourcer til at stå for opgaverne. Dermed er der ikke blot tale om omkostninger til de faktiske opgaver, men også til at sikre, at organisationen har de rette kompetencer over tid.

## Tjekliste til markedsafdækning

1. Er mulighederne for genbrug af eksisterende open source-komponenter undersøgt?
   
   Offentlige myndigheder kan undersøge, om der findes eksisterende open source-komponenter, de kan genbruge. De kan f.eks. orientere sig på [SourceForge](https://sourceforge.net/), [GitHub](https://github.com/), [OS2 Produkter](https://os2.eu/produkter) eller [OSS Repositories](https://joinup.ec.europa.eu/collection/open-source-observatory-osor/oss-repositories), der udstiller open source-software på tværs af europæiske myndigheder. Danske myndigheder kan anvende [it-løsningerne i den fælles digitale infrastruktur](https://digst.dk/it-loesninger/), og statslige myndigheder kan orientere sig i [servicespecifikationen for GovCloud](https://govcloud.dk/media/11706/servicespecifikation-govclouddk.pdf), der beskriver de kundevendte komponenter hos Statens It. Kommunale myndigheder kan orientere sig i [Digitaliseringskataloget](https://digitaliseringskataloget.dk/) for anvendelse af fælleskommunal infrastruktur.
   
2. Er *Total Cost of Ownership* for genbrug af eksisterende open source-komponenter og tilsvarende proprietære løsninger undersøgt?
   
   Offentlige myndigheder, der identificerer eksisterende open source-software, kan beregne *Total Cost of Ownership* for denne og tilsvarende proprietære løsninger med henblik på at vælge den løsning, der skaber værdi i den specifikke situation.
   
3. Er mulighederne for at få vejledning i genbrug af eksisterende open source-komponenter undersøgt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan undersøge, om der er tilstrækkelige vejledning og dokumentation til det pågældende projekt. Myndigheden kan kunne forstå og anvende kildekoden til at bygge og videreudvikle en digital løsning, der løser deres behov.

4. Er aktivitetsniveauet i det tilhørende community for en given eksisterende open source-komponent, som skal genbruges, undersøgt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan undersøge aktivitetsniveauet i det pågældende projekt, f.eks. seneste commit eller release, med henblik på at sikre sig, at projektet ikke er stagnerende eller inaktivt.

5. Er kadencen for fejlretning og udvikling for en given eksisterende open source-komponent, som skal genbruges, undersøgt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan undersøge, om issues er offentligt tilgængelige, løses inden for en rimelig tidsperiode og primært er fejl eller ændringsønsker.

6. Er mulighederne for at bidrage til det tilhørende community for en given eksisterende open source-komponent, som skal genbruges, undersøgt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan investere tid og ressourcer i at bidrage til vejledning og dokumentation, kildekode og issues med henblik på at holde projektet aktivt og opdateret.

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

## Tjekliste til licenser

1. Er mulighederne for at anvende populære og bredt anvendte licenser i egen udvikling af open source undersøgt?

   Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, kan anvende en af de [godkendte open source-licenser](https://opensource.org/licenses), der er populær og bredt anvendt eller med stærke fællesskaber, f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License og Mozilla Public License (MPL) 2.0.
    
2. Er risici for licenser med *copyleft* undersøgt?

   Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, kan forholde sig til særligt *copyleft*, hvis de ikke ønsker, at kildekoden kan genbruges i proprietære løsninger.
    
3. Er mulighederne for at vejlede andre myndigheder om licenser for open source undersøgt? 

   Offentlige myndigheder kan udarbejde egne, og gerne fælles, strategier for brug af licenser og anbefalinger om, hvilke open source-licenser, man ønsker at anvende, og hvilke man kan acceptere i open source-komponenter, man genbruger.
    
4. Er licensen for en given eksisterende open source-komponent, som skal genbruges, undersøgt? 

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan være opmærksomme på, hvilken open source-licens, softwaren er offentliggjort under med henblik på mulighederne for at vedligeholde og dele eller overdrage kildekoden til andre.
    
5. Er mulighederne for at bruge EU-kommissionens værktøj til at sammenligne softwarelicenser undersøgt?

   Offentlige myndigheder kan bruge EU-kommissionens [værktøj til at finde og sammenligne softwarelicenser](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses) med henblik på at vælge en open source-licens, der passer til den konkrete situation.

6. Er retlige forpligtelser og omstændigheder for brug af open source-licenser undersøgt? 

   Offentlige myndigheder, der er i tvivl om mulighederne for at kræve eller prioritere brug af (bestemte) open source-licenser ved udbud og anskaffelse af digitale løsninger, kan orientere sig i OS2-fællesskabet og Kammeradvokatens [notat vedrørende OS2-fællesskabet og open source](https://os2.eu/sites/default/files/blog-files/notat_os2_open_source.pdf), der beskriver retlige forpligtelser og omstændigheder for brug af open source-licenser.

7. Er mulighederne for at frigive evt. leverandørers skriftlige dokumentation som open source undersøgt? 

   Offentlige myndigheder kan sørge for, at skriftligt materiale, der udarbejdes af tilbudsgiver, herunder dokumentation, licenseres under en passende open source-licens, f.eks. en Creative Commons-licens. 

## Implementering

Implementering handler om samarbejdet mellem den offentlige myndighed som ordregiver og tilbudsgiver og senere leverandør af en digital løsning. Ved anskaffelse af open source-software afhænger kravene til implementering en del af den valgte strategi for anskaffelsen.

> Figur: Kompetencer og opgaver (DIGST)

Hvis myndigheden genbruger open source-komponenter fra hylderne, er det ofte svært, men heller ikke nødvendigt, at stille krav til leverandøren om f.eks. licensform eller dokumentation. Det kan imidlertid - over tid - være en mulighed, at myndigheden engagerer sig i et fællesskab omkring komponenten og derigennem påvirker løsningen.

Hvis myndigheden derimod udvikler selv eller i fællesskab med andre, er det relevant at stille en række krav til implementeringen af løsningen. Open source-software er foruden anvendelse af en godkendt open source-licens som beskrevet ovenfor, kendetegnet ved, at løsningen er veldokumenteret, så andre nemt og uden begrænsninger kan genbruge og dele den.

Der er ved implementering også en lang række overvejelser, der knytter sig til den efterfølgende videreudvikling og vedligeholdelse af løsningen, ejerskab til data og dokumentation, brug af åbne standarder og snitflader, der sikrer sammenhængende digitalisering og så videre.

## Tjekliste til implementering

1. Er der udarbejdet vejledning og dokumentation som kan vedlægges egen udvikling af open source-komponenter?

   Offentlige myndigheder kan ved offentliggørelse af kildekoden vedlægge vejledning og dokumentation, der forklarer, hvad løsningen kan bruges til, og hvordan man kan anvende kildekoden til at bygge og videreudvikle løsningen.

2. Er mulighederne for at anvende standarder for indeksering af egen udvikling af open source-komponenter undersøgt? 

   Offentlige myndigheder kan ved offentliggørelse af kildekoden anvende standarder som f.eks. beskriver kildekoden med henblik på automatisk indeksering af open source-software. Dette giver søgemuligheder på tværs af offentlige myndigheder, sektorer og landegrænser.

3. Er mulighederne for at få lavet kodereview af egen udvikling af open source-komponenter undersøgt? 

   Offentlige myndigheder kan sørge for, at der foretages kodereview af kildekoden. Kodereview kan med fordel foretages af en anden leverandør.

4. Er mulighederne for at anvende åbne standarder og snitflader undersøgt? 

   Offentlige myndigheder kan stille krav om, at løsningen understøtter åbne (og obligatoriske) standarder og anvender åbne, standardiserede snitflader, herunder at implementering af standarden ikke kræver nogen anden teknologi, der ikke opfylder kriterierne i dette krav, og tilbudsgiver kan redegøre for, hvordan systemet lever op til kravene i aftale om anvendelse af åbne standarder for software i det offentlige og de syv åbne, obligatoriske standarder.

5. Er mulighederne for at anvende åbne frameworks og kodebiblioteker undersøgt?

   Offentlige myndigheder kan stille krav om, at løsningens komponenter, herunder tekniske standarder, frameworks og kodebiblioteker, er åbne og kan anvendes uden økonomiske eller juridiske begrænsninger både nu og i fremtiden.

6. Er mulighederne for at anvende en åben datamodel og omkostningsfri adgang til data undersøgt? 

   Offentlige myndigheder kan stille krav om, at løsningen leveres med en åben og fleksibel datamodel og med omkostningsfri adgang til samtlige data i løsningen. Dette betyder, at data gøres tilgængelige for ordregiver på en måde, som ikke forudsætter manuelle processer ud over opsætning og programmering. Desuden gøres  data tilgængelig i et standardiseret og maskinlæsbart databaseformat. Tilgængeligheden skal helst ikke, i mærkbar grad, påvirke den normale driftssituation på den tilbudte løsning. Herudover gøres data tilgængelige efter en aftalt frekvens, som fuld indlæsning eller deltaindlæsning og med metadata om status, tilføjelser og rettelser bestemt af myndighedens behov og informationernes karakter, ligesom at data er kontrolleret for overholdelse af konsistenskrav og valideret med hensyn til type og feltindhold.

7. Er mulighederne for at sikre myndighedens ejerskab for data undersøgt?

   Offentlige myndigheder kan stille krav om at leverandøren alene er berettiget til at anvende myndighedens data til brug for udførelse af de af kontrakten omfattede leverancer og ydelser. Leverandøren erhverver således hverken ejendomsret, ophavsret eller nogen anden rettighed til myndighedens data, uanset om disse data optræder elektronisk i systemet, i uddatamateriale eller som print. Desuden kan offentlige myndigheder  stille krav om, at ejerskab til alle data tilfalder myndigheden, hvis kontrakten ændres, udløber eller på anden måde bortfalder.

8. Er mulighederne for at få løbende vedligeholdt datamodel undersøgt? 

   Offentlige myndigheder kan stille krav om, at dokumentation af datamodel (f.eks. E/R-diagram), nøgler, fortolkninger, opdateringsmetoder og tabelstrukturer kan være tilgængelige for ordregiver, og kan vedligeholdes af tilbudsgiver, så oplysninger til enhver tid er ajour.

9. Er mulighederne for at benytte data til ledelsesdata undersøgt? 

   Offentlige myndigheder kan aftale strukturering af indholdet i snitfladen med ordregivers datavarehusteam, herunder, at enhver ændring af datasnitfladen kan meddeles til ordregivers datavarehusteam i rimelig tid inden ændringen gennemføres, således ordregiver har mulighed for at tilrette de bagvedliggende processer.

# Udvikling og vedligeholdelse

Formålet med dette afsnit er at beskrive offentlige myndigheders overvejelser om udvikling og vedligeholdelse, herunder drift, af open source-software, der består af løbende opgaver og kræver åbenhed og agilitet, hvis skal realisere besparelserne ved omkostningseffektive udbud og sikre robuste digitale løsninger for fremtiden.

Det stiller en række krav til kompetencer, og - særligt hvis myndigheden udvikler i fælleskab med andre - opbygning af et open source-fællesskab internt eller på tværs af myndigheder, der kan fastholde den relevante viden og gode erfaringer med open source som udviklingsetode.

Til forskel fra proprietære løsninger er open source-software ofte drevet af et fællesskab (af frivillige). Det en stor betydning for placering af ansvar for løsningen. For nogle open source-løsninger bliver der lagt mange frivillige kræfter i projektet. 

Disse forskellige fællesskaber sikrer, at der er mange, der har en dybdegående viden om de forskellige open source-løsninger, og denne viden ligger ofte tilgængelig for den nysgerrige på de respektive løsningers websites. Fællesskaber kan både bruges i selve afsøgningen af markedet og som referencefælleskab og videnbank ved valg af en specifik open source-løsning. 

Forskellige typer it-anskaffelser kræver forskellige kompetencer i den enkelte myndighed. Ved indkøb af proprietær software har man ofte ikke brug for at have alle kompetencerne internt, da det er leverandøren, der servicerer, implementerer og opdaterer produktet.

Når man udvikler open source, stiller det ofte flere krav til kompetencer, om end der er masser eksempler på leverandører, der tilbyder open source-software på samme vilkår som proprietære løsninger. Hvis man imidlertid indgår i et samarbejde, der kræver flere kompetencer, end organisationen råder over, kan man med fordel opbygge et fællesskab og leverandøraftaler, der sikrer, at man ikke skal besidde alle kompetencerne selv.

Friheden til at ændre softwaren og til at gøre dette i strategiske samarbejder understøtter innovation, dels fordi det er muligt at tilpasse eksisterende software, dels fordi den voksende mængde open source-software, man kan tage ned fra hylden og i brug, gør det muligt hurtigt at sammensætte nye produkter og services.
 
De enkelte myndigheder kan opleve en høste-så-problematik, som gør det svært at etablere nye open source-projekter. Med høste-så-problematik menes, at det ikke altid er den myndighed, der lægger alle ressourcerne i et projekt, som høster gevinsterne. Af den grund kan det være særligt relevant i nogle projekter at der mellem flere myndigheder indgås et samarbejde om at (videre)udvikle en løsning, som flere myndigheder kan få glæde af. På den måde deler man ressourcer og risici ved projektet.

## Tjekliste til udvikling og vedligeholdelse

1. Er mulighederne for at leverandører af vedligehold og videreudvikling nemt kan udskiftes undersøgt? 

   Offentlige myndigheder kan sikre, at tilbudsgiver leverer en veldokumenteret digital løsning, således at eventuel videreudvikling kan foretages af andre leverandører. Dette omfatter teknisk dokumentation, herunder systembeskrivelser og arkitekturtegninger. Dermed sikrer man også, at løsningen kan drives videre efter kontraktudløb. Offentlige myndigheder kan kræve, at den tekniske dokumentation og kildekoden overholder krav og standarder tilhørende den valgte open source-licens, samt forholde sig til planer for videreudvikling, opgradering og udfasning af løsningen fra begyndelsen og udarbejde passende strategier.
   
2. Er mulighederne for at varetage egen drift af implementeret open source undersøgt? 

   Offentlige myndigheder kan overveje, om de selv kan og vil løfte opgaven, eller om de har brug for at indgå kontrakt med en drifts- og supportleverandør.

3. Er muligheden for at have fælles krav til vedligeholdelse, governance, koordinationsorganer, videndeling i det tilhørende community for en given nyudviklet open source-komponent undersøgt? 

   Offentlige myndigheder, der udvikler i fællesskab med andre, kan forholde sig til krav til vedligeholdelse af den fælles kodebase, efterlevelse af fællesskabets governancekrav, etablering af koordinationsorganer, videndeling mv. mellem brugere af løsningen, dialog med leverandører og promovering af løsningen. Offentlige myndigheder, der udvikler selv eller i fællesskab med andre, kan stille krav om koordinering og prioritering af videreudviklingsønsker, bestilling og styring af udviklingsopgaver og arkitekturstyring og governance for kodebasen. Ved udlicitering af driften til en ekstern leverandør, kan der stilles krav om en drifts- og serviceaftale, der indeholder oppetider, supportniveauer og sanktioneringsmuligheder, beskrivelse af releases og deployment og leverandørstyring.

4. Er muligheden for at løbende evaluere modenheden af open source-komponenter, som er implementeret, undersøgt?

   Offentlige myndigheder kan løbende evaluere modenheden af open source-komponenter, de anvender, og software, som de udvikler selv eller i fællesskab med andre med henblik på at træffe beslutning om at tilføre flere ressourcer, opgive brug af løsningen eller udbredelse af løsningen til andre myndigheder.

# Baggrund for vejledningen

Open source er ikke noget nyt i den offentlige sektor. Det har været og er fortsat interessant, fordi det understøtter mere modulære digitale løsninger og samarbejdsorienterede metoder til at udvikle, vedligeholde og genbruge komponenter. Open source kan derfor understøtte sammenhængende digitalisering og leverandøruafhængighed i den offentlige sektor.

Open source er en del af arkitekturregel 2.3 om at [undgå afhængighed af leverandører og proprietære teknologier](https://arkitektur.digst.dk/principper-og-regler/princip-2-arkitektur-fremmer-sammenhaeng-innovation-og-effektivitet-4), der operationaliseres ved at "anvende bæredygtige open source-komponenter, hvor det er relevant".

[Statens it-projektmodel](https://digst.dk/styring/projektstyring/statens-it-projektmodel/) indeholder desuden et princip om, at allerede indkøbte eller udviklede løsninger skal genbruges i videst mulige omfang. Hvis eksisterende løsninger ikke kan bruges direkte, skal det overvejes, om det bedre kan betale sig at videreudvikle en allerede eksisterende funktionalitet fra en anden styrelse end at foretage nyudvikling af en tilsvarende løsning fra bunden.

## Principper

[Open source-software i det offentlige](https://www.digitaliser.dk/resource/2212763) beskriver en række **principper for anvendelse af open source i det offentlige**. Principperne sikrer offentlige myndigheder mange valgmuligheder og understøtter, at it-anskaffelser samlet set bliver billigere og mere fleksible. Samtidig er principperne med til at sikre et innovativt og konkurrencepræget marked.

 * **Konkurrence**<br>
 Velfungerende konkurrence er en forudsætning for et effektivt og varieret softwaremarked. Open source understøtter, at softwaren kan vedligeholdes og videreudvikles af flere leverandører. Softwareleverandører skal på lige vilkår kunne tilbyde deres it-ydelser til det offentlige.
 * **Kontrol og selvbestemmelse**<br>
 Anvendelse af open source-software sikrer kontrollen over softwaren. Dermed kan den enkelte myndighed bestemme, hvornår og hvordan softwaren skal opdateres, udvikles og  eventuelt deles med andre myndigheder.
 * **Udvikling og innovation**<br>
 Myndigheder skal ved udvikling af software overveje, hvilken software-udviklingsmodel, herunder open source-udviklings- og forretningsmodellen, som bedst understøtter innovation og hurtig udvikling af nye produkter og services. Egenudviklet software bør som udgangspunkt stilles til rådighed med en open source-licens. Det betyder ikke, at gamle metoder skal opgives, men at flere metoder kan leve side om side, og nye kan afprøves, så fordele og ulemper kan afklares i forhold til den danske forvaltnings virkelighed.
 * **Bedst og billigst uanset softwaretype**<br>
 Den enkelte myndighed skal have mulighed for at erhverve den bedste og billigste software ud fra lokale forvaltningsmæssige behov, uanset om der er tale om closed source- eller open source-software. Software skal vælges på baggrund af en vurdering af en samlet business case.
 * **Sammenhæng og fleksibilitet**<br>
 Myndigheder skal satse på software, der opbygges i mindre dele, og som ved hjælp af åbne standarder er i stand til at kommunikere med andre typer software. Derved sikres det, at enkelte dele af systemet uafhængigt kan udskiftes til gavn for fleksibilitet, genbrug og konkurrence på området.
 * **Genbrug af software**<br>
 Anvendelse af open source-software kan sikre, at skatteborgerne undgår at betale for udvikling af den samme software flere gange.

## Europæiske strømninger

Open source står også højt på dagsordenen i EU, der peger på brug af open source i den offentlige sektor som en vej til tillid mellem borgere og myndigheder, gennemsigtighed, interoperabilitet og leverandøruafhængighed.

Under overskriften *Think Open* har EU-kommissionen i deres [open source-softwarestrategi](https://ec.europa.eu/info/departments/informatics/open-source-software-strategy_en) præsenteret en vision for digital transformation, innovation og samarbejde med open source som løftestang. Open source skal sikre nye, effektiver løsninger, der virker og kan deles og udvikles på tværs af landegrænser.

* **Tænk åbent**<br>
  Open source-løsninger er at foretrække, når de er tilsvarende i funktionalitet, total omkostninger og cybersikkerhed.
* **Transformér**<br>
  Vi udnytter principperne for open source: vi innoverer, vi samskaber, deler og genbruger, og bygger sammen brugercentrerede, datadrevne offentlige tjenester.
* **Del**<br>
  Vi deler vores kode and muliggør bidrag til relaterede open source-projekter.
* **Bidrag**<br>
  Vi stræber efter at være et aktivt medlem af det mangfoldige open source-økosystem.
* **Gør sikker**<br>
  Vi sørger for, at den kode, vi bruger, og den kode, vi deler, er fri for sårbarheder ved at teste sikkerheden løbende.
* **Bevar kontrol**<br>
  Vi fremmer åbne standarder og specifikationer, der er implementeret og distribueret i open source.

I en [undersøgelse om effekten af open source](https://digital-strategy.ec.europa.eu/en/library/study-about-impact-open-source-software-and-hardware-technological-independence-competitiveness-and) på teknologisk uafhængighed, konkurrenceevne og innovation i den europæiske økonomi fremhæver tre overordnede anbefalinger, hvor brug af open source kan bidrage til:

 * En digitalt uafhængig offentlig sektor
 * Åben forskning og udvikling som fundament for vækst
 * Et digitaliseret og internationalt konkurrencedygtigt erhvervsliv

# Bilag

## Tjekliste til brug af open source

**Strategier**

1.	Er fordele og ulemper ved anvendelse af open source undersøgt?
2.	Er risici, behov for tekniske kompetencer og andre ressourcer og omkostninger ved udvikling af open source undersøgt?
3.	Er de rette kompetencer til at arbejde med open source sikret? 
4.	Er de forskellige niveauer i softwarestakken identificeret med henblik på hvor open source giver mest værdi?
5.	Er der valgt medie til offentliggørelse af kildekode? 

**Markedsafdækning**

1.	Er mulighederne for genbrug af eksisterende open source-komponenter undersøgt?
2.	Er *Total Cost of Ownership* for genbrug af eksisterende open source-komponenter og tilsvarende proprietære løsninger undersøgt?
3.	Er mulighederne for at få vejledning i genbrug af eksisterende open source-komponenter undersøgt?
4.	Er aktivitetsniveauet i det tilhørende community for en given eksisterende open source-komponent, som skal genbruges, undersøgt?
5.	Er kadancen for fejlretning og udvikling for en given eksisterende open source-komponent, som skal genbruges, undersøgt?
6.	Er mulighederne for at bidrage til det tilhørende community for en given eksisterende open source-komponent, som skal genbruges, undersøgt?

**Licenser**

1.	Er mulighederne for at anvende populære og bredt anvendte licenser i egen udvikling af open source undersøgt? 
2.	Er risici for licenser med *copyleft* undersøgt?.
3.	Er mulighederne for at vejlede andre myndigheder om licenser for open source undersøgt? 
4.	Er licensen for en given eksisterende open source-komponent, som skal genbruges, undersøgt? 
5.	Er mulighederne for at bruge EU-kommissionens værktøj til at sammenligne softwarelicenser undersøgt?
6.	Er retlige forpligtelser og omstændigheder for brug af open source-licenser undersøgt? 
7.	Er mulighederne for at frigive evt. leverandørers skriftlige dokumentation som open source undersøgt? 

**Implementering**

1.	Er der udarbejdet vejledning og dokumentation som kan vedlægges egen udvikling af open source-komponenter? 
2.	Er mulighederne for at anvende standarder for indeksering af egen udvikling af open source-komponenter undersøgt? 
3.	Er mulighederne for at få lavet kodereview af egen udvikling af open source-komponenter undersøgt? 
4.	Er mulighederne for at anvende åbne standarder og snitflader undersøgt? 
5.	Er mulighederne for at anvende åbne frameworks og kodebiblioteker undersøgt? 
6.	Er mulighederne for at anvende åben datamodel og omkostningsfri adgang og ejerskab for data undersøgt?
7.	Er mulighederne for at sikre myndighedens ejerskab for data undersøgt?
8.	Er mulighederne for at få løbende vedligeholdt datamodel undersøgt?
9.	Er mulighederne for at benytte data til ledelsesdata undersøgt? 

**Udvikling og vedligeholdelse**

1.	Er mulighederne for at leverandører af vedligehold og videreudvikling nemt kan udskiftes undersøgt? 
2.	Er mulighederne for at varetage egen drift af implementeret open source undersøgt? 
3.	Er muligheden for at have fælles krav til vedligeholdelse, governance, koordinationsorganer, videndeling i det tilhørende community for en given nyudviklet open source-komponent undersøgt? 
4.	Er muligheden for at løbende evaluere modenheden af open source-komponenter, som er implementeret, undersøgt?

## Cases om brug af open source

EU-Kommissionens [Open Source Observatory](https://joinup.ec.europa.eu/collection/open-source-observatory-osor) (OSOR) fungerer som et samlingssted, hvor open source-fællesskaber kan dele viden og erfaringer og finde og genbruge open source-software.

I Danmark har OS2-fællesskabet, med udgangspunkt i materiale overdraget fra Aarhus Kommune, udarbejdet tre vejledninger, som indeholder relevant og vigtig viden omkring open source og anskaffelsen af open source software.

Formålet med vejledningerne er at afmystificere og hjælpe myndigheder med at indkøbe og bruge af open source. Det er at hjælpe til at benytte open source strategisk og hjælpe med at gøre kravspecificering, valg og indkøb af løsning så nemt som muligt. Læs vejledninger om [licenser, jura, udbud og kontrakter](https://faq.os2.eu/open-source-anskaffelse-licenser-jura-udbud-og-kontrakter?collection=59).

Der findes også andre vejledninger i genbrug af open source-software i den offentlige sektor. F.eks. har det italienske ministerium for teknologisk innovation og digital omstilling beskrevet [retningslinjer for anskaffelse og genbrug af software for offentlige myndigheder](https://docs.italia.it/italia/developers-italia/gl-acquisition-and-reuse-software-for-pa-docs/en/stabile/index.html) og open source-organisation Foundation for Public Code har etableret en såkaldt [Standard for Public Code](https://standard.publiccode.net/), der skal hjælpe organisationer med at udvikle og genbruge open source-software.

I forbindelse med udarbejdelsen af nærværende vejledning har projektet tilvejebragt en række open source-casebeskrivelser, der deler gode råd til og opmærksomhedspunkter ved brug af open source.

Casebeskrivelserne bliver løbende publiceret på [KL og KOMBITs videncenter for digitalisering og teknologi](https://videncenter.kl.dk/viden-og-vaerktoejer/innovation), der også fremover vil fungere som en fælles platform for deling af viden, værktøjer og cases om brug af open source i den offentlige sektor.

================

[arkitektur.digst.dk](arkitektur.digst.dk)
