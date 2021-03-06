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
Editor: Styrelsen for It og L??ring
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

# M??lgruppe og l??sevejledning

M??lgruppen for vejledningen er it-projektledere, -jurister og -arkitekter, indk??bere og contract managers samt it-chefer og andre strategiske beslutningstagere hos offentlige myndigheder, der skal tage stilling til anskaffelse af software, og som ??nsker mere viden, konkrete eksempler og praktisk vejledning til brug af open source.

Open source-software er software udgivet under en licens, der giver enhver ret til at bruge, unders??ge, ??ndre og dele softwaren og dens kildekode frit og til ethvert form??l.

Open source handler ikke om it-afdelingens teknologiske pr??ferencer, men er en strategisk forretningsmodel og nogle udviklingsmetoder, der fremmer offentlige myndigheders medejerskab til deres l??sninger og skaber bedre muligheder for at dele, videreudvikle og genbruge digitale l??sninger.

# Indledning

Danske myndigheder investerer massivt i digitalisering, og der er et stort behov for, at digitale l??sninger er fleksible, sammenh??ngende og bygget til genbrug og forandring.

Offentlige myndigheder undg??r s?? vidt muligt l??sninger, der skaber afh??ngighed af specifikke leverand??rer og teknologier, og [hvor det er relevant, kan de anvende b??redygtige open source-komponenter](https://arkitektur.digst.dk/principper-og-regler/princip-2-arkitektur-fremmer-sammenhaeng-innovation-og-effektivitet-4).

I valget mellem open source-software og propriet??re l??sninger er det ikke et sp??rgsm??l om enten-eller, men om at v??lge den l??sning, der skaber v??rdi p?? baggrund af de udfordringer og behov, der er relevante for den enkelte myndighed. 

> Figur: Open source og propriet??r software (DIGST)

Der er et stort potentiale i ??bne og cirkul??re forretningsmodeller og open source-software, der brugt p?? de rigtige omr??der kan bidrage til at underst??tte b??redygtig udvikling, innovation og kvalitet, styrke danske virksomheders omstillingsparathed og konkurrenceevne og ??ge v??kst og eksport af digitale l??sninger. 

> Figur: ??bne standarder mellem open source og propriet??r software (DIGST)

??bne standarder fremmer konkurrence p?? markedet for software og medvirker til, at offentlige it-systemer uanset valg af software kan udveksle informationer p?? tv??rs. De er det f??lles sprog, systemerne bruger til at tale med og forst?? hinanden.

Der findes mange kendte og udbredte open source-softwareprodukter. Distributioner af Linux-styresystemet underst??tter omkring 70 % af internettets 10 mio. mest bes??gte hjemmesider, der ofte hostes p?? webservere som Nginx (33 %) eller Apache HTTP Server (24 %). 42 % af hjemmesiderne er udviklet med Wordpress, men ogs?? Drupal og Umbraco er open source. Omkring 65 % browser internettet med Google Chrome, og 84 % k??rer det Linux-baserede styresystem Android p?? deres smartphone. 

> Figur: Open source findes p?? alle hylderne i softwarestakken (DIGST)

Danske offentlige myndigheder bruger LibreOffice til teksbehandling og QGIS til geodatabehandling, og 82 kommuner bruger OS2kitos - ofte sammen med et af de andre 21 OS2-produkter - til at holde styr p?? deres systemportef??lje.

Form??let med denne vejledning er ikke at ops??tte et mods??tningsforhold mellem brug af open source-software og propriet??re l??sninger. Derfor beskriver vejledningen en r??kke af de vigtigste overvejelser ved anskaffelse, herunder **strategier og markedsafd??kning**, **licenser og implementering** og **udvikling og vedligeholdelse**.

> Figur: Proces for it-anskaffelser (DIGST)

**Strategier og markedsafd??kning** beskriver myndighedernes overvejelser om strategier for anskaffelse af open source-software og afd??kning af markedet for b??de eksisterende open source-komponenter og propriet??re l??sninger.

**Licenser og implementering** beskriver myndighedernes overvejelser om brug af open source-licenser og implementering af open source, uanset om det eksisterende komponenter, der er genbrugt fra hylderne, eller software udviklet selv eller i f??llesskab med andre.

**Udvikling og vedligeholdelse** beskriver overvejelser om udvikling og vedligeholdelse, herunder drift, af open source-software, der best??r af l??bende opgaver, der alle stiller krav til kompetencer, hvorfor myndigheder med fordel kan deltage i open source-f??llesskaber.

# Strategier og markedsafd??kning

Form??let med dette afsnit er at beskrive offentlige myndigheders overvejelser om strategier for anskaffelse af open source-software. Det er ikke et sp??rgsm??l om enten-eller, men derimod om at v??lge den strategi, der passer bedst til den konkrete situation.

Open source-software og propriet??re l??sninger kan sagtens sameksistere, hvis man v??lger forskellige strategier fra gang til gang, og processen for anskaffelse er stort set den samme. De kr??ver dog hver is??r forskellige kompetencer og krav til samarbejde.

## Strategier

Overordnet findes der tre strategier for anskaffelse af open source, som offentlige myndigheder har i v??rkt??jskassen og kan anvende i forbindelse med it-anskaffelser:

> Figur: Open source-anskaffelsesstrategier (DIGST)

  * **Myndigheden genbruger fra hylderne**<br>
    Offentlige myndigheder, der anvender denne strategi, genbruger eksisterende open source-software, hvor det er relevant. Det kan v??re komponenter eller enkeltst??ende applikationer, der er gode eller billige alternativer til propriet??re l??sninger. Denne strategi omfatter ogs?? myndigheder, der er mindre bevidste om, at de anvender open source.
  * **Myndigheden udvikler selv**<br>
    Offentlige myndigheder, der anvender denne strategi, udvikler selv l??sninger, der foruden at anvende eksisterende open source-komponenter udgives under en open source-licens. Det kan v??re for at stille software til r??dighed for andre myndigheder eller virksomheder for at ??ge anvendelsen eller f?? andre til at bidrage til vedligeholdelsen.
  * **Myndigheden udvikler i f??llesskab**<br>
    Offentlige myndigheder, der anvender denne strategi, udvikler i f??llesskab med andre l??sninger, der lever op til ovenst??ende. Det kan v??re for at dele risici og omkostninger med andre myndigheder eller virksomheder og skabe et f??llesskab omkring vedligeholdelse af l??sningen eller en r??kke l??sninger i et ??kosystem.

Med andre ord er der forskellige strategiske ??rsager til at genbruge eksisterende open source-software og udvikle open source-software selv eller i f??llesskab med andre. De forskellige strategier har hver deres fordele, men kr??ver ogs?? noget af myndigherne i form af kompetencer.

At kildekoden er ??ben og frit kan genbruges, betyder ikke kun, at en myndighed kan dele sin open source-software med en anden myndighed. Det betyder ogs??, at den anden myndighed kan forbedre softwaren og derefter dele den forbedrede l??sning med den f??rste myndighed og med andre. P?? den m??de kan der v??re flere om at forbedre softwaren og finansiere fremtidige ??nsker til videreudvikling.

## Tjekliste til strategier

1. Er fordele og ulemper ved anvendelse af open source unders??gt?

   Offentlige myndigheder kan have en overordnet strategi for brug af open source, eller kan fra anskaffelse til anskaffelse overveje fordele og ulemper og den konkrete v??rdiskabelse ved anvendelse af open source.
   
2. Er risici, behov for tekniske kompetencer og andre ressourcer og omkostninger ved udvikling af open source unders??gt?

   Offentlige myndigheder, der ??nsker at udvikle open source-software, kan forholde sig til risici, behov for tekniske kompetencer og andre ressourcer og omkostninger ved udvikling selv i forhold til udvikling i f??llesskab med andre.
   
3. Er de rette kompetencer til at arbejde med open source sikret?

   Offentlige myndigheder b??r sikre sig de rette kompetencer til at arbejde med open source, uanset om de genbruger eksisterende open source-komponenter, udvikler selv eller udvikler i f??llesskab med andre.
   
4. Er de forskellige niveauer i softwarestakken identificeret med henblik p?? hvor open source giver mest v??rdi?
   
   Offentlige myndigheder kan danne sig et overblik over brug af open source-software p?? forskellige niveauer i softwarestakken og anvende en helhedsorienteret tilgang til   anskaffelser, der udnytter synergier mellem software som f.eks. de popul??re open source-softwarestakke LAMP og MEAN.
   
5. Er der valgt medie til offentligg??relse af kildekode? 
   
   Offentlige myndigheder kan ved ny- eller videreudvikling overveje, om kildekoden kan offentligg??res p?? f.eks. [GitHub](https://github.com/).

## Markedsafd??kning

Det fremg??r af den F??llesoffentlige Digitale Arkitektur, at den offentlige sektor kan bruge software, der underst??tter sammenh??ngende digitalisering uden bindinger til leverand??rer og propriet??re teknologier og udvikler et marked, hvor flere leverand??rer kan konkurrere om at levere systemer og services innovativt, billigt og fleksibelt, og der er plads til b??de standardl??sninger og moduler fra flere leverand??rer baseret p?? ??bne snitflader.

P?? markedet for open source-software har mange leverand??rer, herunder en r??kke st??rre leverand??rer med lange erfaringer som leverand??rer til offentlige myndigheder, taget bestik af udviklingen og etableret enheder, der udvikler open source-software for offentlige myndigheder og byder ind p?? ydelser omkring vedligeholdelse og videreudvikling.

F.eks. har OS2-f??llesskabet omkring 70 leverand??rpartnere, der producerer og overleverer produkter til f??llesskabet, leverer udviklingskraft og teknologividen, implementering, drift og support og er i aktiv dialog med f??llesskabet om nye forretningsmuligheder.

Dette er med til at validere open source som en udbredt og rentabel forretningsmodel p?? det danske leverand??rmarked og viser med al tydelighed, at open source-software ikke er gratis, eller at en open source-strategi river t??ppet v??k under leverand??rerne. Det er derimod en udviklingsmetode til at im??dekomme udfordringer med at genbruge og videreudvikle digitale l??sninger, der kommer af leverand??ruafh??ngighed, teknisk g??ld, kompetencetab og manglende ejerskab til kildekoden.

> Figur: Overordnede strategiske valg (DIGST)

Som tidligere beskrevet er open source ikke gratis, n??r man beregner en *Total Cost of Ownership* (TCO). Ligesom ved anvendelse af closed source-software er der omkostninger til implementering, videreudvikling og l??bende drift, support og vedligeholdelse. Det kr??ver samtidig ogs??, at myndigheden har og kan allokere de n??dvendige ressourcer til at st?? for opgaverne. Dermed er der ikke blot tale om omkostninger til de faktiske opgaver, men ogs?? til at sikre, at organisationen har de rette kompetencer over tid.

## Tjekliste til markedsafd??kning

1. Er mulighederne for genbrug af eksisterende open source-komponenter unders??gt?
   
   Offentlige myndigheder kan unders??ge, om der findes eksisterende open source-komponenter, de kan genbruge. De kan f.eks. orientere sig p?? [SourceForge](https://sourceforge.net/), [GitHub](https://github.com/), [OS2 Produkter](https://os2.eu/produkter) eller [OSS Repositories](https://joinup.ec.europa.eu/collection/open-source-observatory-osor/oss-repositories), der udstiller open source-software p?? tv??rs af europ??iske myndigheder. Danske myndigheder kan anvende [it-l??sningerne i den f??lles digitale infrastruktur](https://digst.dk/it-loesninger/), og statslige myndigheder kan orientere sig i [servicespecifikationen for GovCloud](https://govcloud.dk/media/11706/servicespecifikation-govclouddk.pdf), der beskriver de kundevendte komponenter hos Statens It. Kommunale myndigheder kan orientere sig i [Digitaliseringskataloget](https://digitaliseringskataloget.dk/) for anvendelse af f??lleskommunal infrastruktur.
   
2. Er *Total Cost of Ownership* for genbrug af eksisterende open source-komponenter og tilsvarende propriet??re l??sninger unders??gt?
   
   Offentlige myndigheder, der identificerer eksisterende open source-software, kan beregne *Total Cost of Ownership* for denne og tilsvarende propriet??re l??sninger med henblik p?? at v??lge den l??sning, der skaber v??rdi i den specifikke situation.
   
3. Er mulighederne for at f?? vejledning i genbrug af eksisterende open source-komponenter unders??gt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan unders??ge, om der er tilstr??kkelige vejledning og dokumentation til det p??g??ldende projekt. Myndigheden kan kunne forst?? og anvende kildekoden til at bygge og videreudvikle en digital l??sning, der l??ser deres behov.

4. Er aktivitetsniveauet i det tilh??rende community for en given eksisterende open source-komponent, som skal genbruges, unders??gt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan unders??ge aktivitetsniveauet i det p??g??ldende projekt, f.eks. seneste commit eller release, med henblik p?? at sikre sig, at projektet ikke er stagnerende eller inaktivt.

5. Er kadencen for fejlretning og udvikling for en given eksisterende open source-komponent, som skal genbruges, unders??gt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan unders??ge, om issues er offentligt tilg??ngelige, l??ses inden for en rimelig tidsperiode og prim??rt er fejl eller ??ndrings??nsker.

6. Er mulighederne for at bidrage til det tilh??rende community for en given eksisterende open source-komponent, som skal genbruges, unders??gt?

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan investere tid og ressourcer i at bidrage til vejledning og dokumentation, kildekode og issues med henblik p?? at holde projektet aktivt og opdateret.

# Licenser og implementering

Form??let med dette afsnit er at beskrive offentlige myndigheders overvejelser om brug af open source-licenser, der giver frihed til at bruge, unders??ge, ??ndre og dele kildekoden, og implementering af open source, myndigheden har genbrugt fra hylderne, udviklet selv eller i f??llesskab med andre.

Der er ikke noget mods??tningsforhold mellem at anskaffe open source-software og betale (en eller flere) leverand??rer for eksempelvis udvikling, vedligeholdelse eller drift af l??sningen. Det kr??ver ikke desto mindre, at man aftaler at bruge de rigtige licenser, s?? det f.eks. er muligt at skifte leverand??r, og s?? andre man forbedre kildekoden.

## Licenser

Open source-licenser er softwarelicenser, der tillader, at software frit kan bruges, unders??ges, ??ndres og deles. [Open Source Initiative](https://opensource.org/) har godkendt en lang r??kke licenser som v??rende open source, men anbefaler, at anvendere som udgangspunkt benytter de licenser, der er "popul??re og bredt anvendte eller med st??rke f??llesskaber". Det g??lder f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License og Mozilla Public License (MPL) 2.0.

EU-Kommissionen har sin egen open source-licens, [European Union Public License](https://ec.europa.eu/info/european-union-public-licence_en) (EUPL), der er den f??rste europ??iske open source-licens. Den findes p?? 22 sprog og kan anvendes af enhver til at distribuere software. Form??let er at opfordre europ??iske myndigheder til at anvende open source-modellen og de tilh??rende udviklingsmetoder til at styrke deres software og strategiske kapabiliteter.

Licenser kan indeholde forskellige vilk??r, f.eks. at publicerede videreudviklinger skal videregives under samme vilk??r (s??kaldte *copyleft*-vilk??r). S??danne vilk??r kan repr??sentere behov for at sikre, at kildekoden ikke bliver genbrugt i propriet??re l??sninger.

> Figur: Valg af licenstyper (DIGST)

Der er mange forskellige licenser, og det er vigtigt at v??re bevidst om, at omst??ndighederne for at anvende open source-software kan ??ndre sig som f??lge af licensen. Forskellige licenstyper g??r det f.eks. henholdsvis nemmere og sv??rere at vedligeholde eller overdrage softwaren, hvis man f.eks. indg??r i samarbeder med andre myndigheder eller indg??r aftale om videreudvikling med en leverand??r.

Offentlige myndigheder kan med fordel udarbejde egne, og gerne f??lles, strategier for brug af licenser og anbefalinger om, hvilke open source-licenser, man ??nsker at anvende, og hvilke man kan acceptere i open source-komponenter, man genbruger.

## Tjekliste til licenser

1. Er mulighederne for at anvende popul??re og bredt anvendte licenser i egen udvikling af open source unders??gt?

   Offentlige myndigheder, der udvikler selv eller i f??llesskab med andre, kan anvende en af de [godkendte open source-licenser](https://opensource.org/licenses), der er popul??r og bredt anvendt eller med st??rke f??llesskaber, f.eks. Apache License 2.0, GNU General Public License (GPL), MIT License og Mozilla Public License (MPL) 2.0.
    
2. Er risici for licenser med *copyleft* unders??gt?

   Offentlige myndigheder, der udvikler selv eller i f??llesskab med andre, kan forholde sig til s??rligt *copyleft*, hvis de ikke ??nsker, at kildekoden kan genbruges i propriet??re l??sninger.
    
3. Er mulighederne for at vejlede andre myndigheder om licenser for open source unders??gt? 

   Offentlige myndigheder kan udarbejde egne, og gerne f??lles, strategier for brug af licenser og anbefalinger om, hvilke open source-licenser, man ??nsker at anvende, og hvilke man kan acceptere i open source-komponenter, man genbruger.
    
4. Er licensen for en given eksisterende open source-komponent, som skal genbruges, unders??gt? 

   Offentlige myndigheder, der genbruger eksisterende open source-komponenter, kan v??re opm??rksomme p??, hvilken open source-licens, softwaren er offentliggjort under med henblik p?? mulighederne for at vedligeholde og dele eller overdrage kildekoden til andre.
    
5. Er mulighederne for at bruge EU-kommissionens v??rkt??j til at sammenligne softwarelicenser unders??gt?

   Offentlige myndigheder kan bruge EU-kommissionens [v??rkt??j til at finde og sammenligne softwarelicenser](https://joinup.ec.europa.eu/collection/eupl/solution/joinup-licensing-assistant/jla-find-and-compare-software-licenses) med henblik p?? at v??lge en open source-licens, der passer til den konkrete situation.

6. Er retlige forpligtelser og omst??ndigheder for brug af open source-licenser unders??gt? 

   Offentlige myndigheder, der er i tvivl om mulighederne for at kr??ve eller prioritere brug af (bestemte) open source-licenser ved udbud og anskaffelse af digitale l??sninger, kan orientere sig i OS2-f??llesskabet og Kammeradvokatens [notat vedr??rende OS2-f??llesskabet og open source](https://os2.eu/sites/default/files/blog-files/notat_os2_open_source.pdf), der beskriver retlige forpligtelser og omst??ndigheder for brug af open source-licenser.

7. Er mulighederne for at frigive evt. leverand??rers skriftlige dokumentation som open source unders??gt? 

   Offentlige myndigheder kan s??rge for, at skriftligt materiale, der udarbejdes af tilbudsgiver, herunder dokumentation, licenseres under en passende open source-licens, f.eks. en Creative Commons-licens. 

## Implementering

Implementering handler om samarbejdet mellem den offentlige myndighed som ordregiver og tilbudsgiver og senere leverand??r af en digital l??sning. Ved anskaffelse af open source-software afh??nger kravene til implementering en del af den valgte strategi for anskaffelsen.

> Figur: Kompetencer og opgaver (DIGST)

Hvis myndigheden genbruger open source-komponenter fra hylderne, er det ofte sv??rt, men heller ikke n??dvendigt, at stille krav til leverand??ren om f.eks. licensform eller dokumentation. Det kan imidlertid - over tid - v??re en mulighed, at myndigheden engagerer sig i et f??llesskab omkring komponenten og derigennem p??virker l??sningen.

Hvis myndigheden derimod udvikler selv eller i f??llesskab med andre, er det relevant at stille en r??kke krav til implementeringen af l??sningen. Open source-software er foruden anvendelse af en godkendt open source-licens som beskrevet ovenfor, kendetegnet ved, at l??sningen er veldokumenteret, s?? andre nemt og uden begr??nsninger kan genbruge og dele den.

Der er ved implementering ogs?? en lang r??kke overvejelser, der knytter sig til den efterf??lgende videreudvikling og vedligeholdelse af l??sningen, ejerskab til data og dokumentation, brug af ??bne standarder og snitflader, der sikrer sammenh??ngende digitalisering og s?? videre.

## Tjekliste til implementering

1. Er der udarbejdet vejledning og dokumentation som kan vedl??gges egen udvikling af open source-komponenter?

   Offentlige myndigheder kan ved offentligg??relse af kildekoden vedl??gge vejledning og dokumentation, der forklarer, hvad l??sningen kan bruges til, og hvordan man kan anvende kildekoden til at bygge og videreudvikle l??sningen.

2. Er mulighederne for at anvende standarder for indeksering af egen udvikling af open source-komponenter unders??gt? 

   Offentlige myndigheder kan ved offentligg??relse af kildekoden anvende standarder som f.eks. beskriver kildekoden med henblik p?? automatisk indeksering af open source-software. Dette giver s??gemuligheder p?? tv??rs af offentlige myndigheder, sektorer og landegr??nser.

3. Er mulighederne for at f?? lavet kodereview af egen udvikling af open source-komponenter unders??gt? 

   Offentlige myndigheder kan s??rge for, at der foretages kodereview af kildekoden. Kodereview kan med fordel foretages af en anden leverand??r.

4. Er mulighederne for at anvende ??bne standarder og snitflader unders??gt? 

   Offentlige myndigheder kan stille krav om, at l??sningen underst??tter ??bne (og obligatoriske) standarder og anvender ??bne, standardiserede snitflader, herunder at implementering af standarden ikke kr??ver nogen anden teknologi, der ikke opfylder kriterierne i dette krav, og tilbudsgiver kan redeg??re for, hvordan systemet lever op til kravene i aftale om anvendelse af ??bne standarder for software i det offentlige og de syv ??bne, obligatoriske standarder.

5. Er mulighederne for at anvende ??bne frameworks og kodebiblioteker unders??gt?

   Offentlige myndigheder kan stille krav om, at l??sningens komponenter, herunder tekniske standarder, frameworks og kodebiblioteker, er ??bne og kan anvendes uden ??konomiske eller juridiske begr??nsninger b??de nu og i fremtiden.

6. Er mulighederne for at anvende en ??ben datamodel og omkostningsfri adgang til data unders??gt? 

   Offentlige myndigheder kan stille krav om, at l??sningen leveres med en ??ben og fleksibel datamodel og med omkostningsfri adgang til samtlige data i l??sningen. Dette betyder, at data g??res tilg??ngelige for ordregiver p?? en m??de, som ikke foruds??tter manuelle processer ud over ops??tning og programmering. Desuden g??res  data tilg??ngelig i et standardiseret og maskinl??sbart databaseformat. Tilg??ngeligheden skal helst ikke, i m??rkbar grad, p??virke den normale driftssituation p?? den tilbudte l??sning. Herudover g??res data tilg??ngelige efter en aftalt frekvens, som fuld indl??sning eller deltaindl??sning og med metadata om status, tilf??jelser og rettelser bestemt af myndighedens behov og informationernes karakter, ligesom at data er kontrolleret for overholdelse af konsistenskrav og valideret med hensyn til type og feltindhold.

7. Er mulighederne for at sikre myndighedens ejerskab for data unders??gt?

   Offentlige myndigheder kan stille krav om at leverand??ren alene er berettiget til at anvende myndighedens data til brug for udf??relse af de af kontrakten omfattede leverancer og ydelser. Leverand??ren erhverver s??ledes hverken ejendomsret, ophavsret eller nogen anden rettighed til myndighedens data, uanset om disse data optr??der elektronisk i systemet, i uddatamateriale eller som print. Desuden kan offentlige myndigheder  stille krav om, at ejerskab til alle data tilfalder myndigheden, hvis kontrakten ??ndres, udl??ber eller p?? anden m??de bortfalder.

8. Er mulighederne for at f?? l??bende vedligeholdt datamodel unders??gt? 

   Offentlige myndigheder kan stille krav om, at dokumentation af datamodel (f.eks. E/R-diagram), n??gler, fortolkninger, opdateringsmetoder og tabelstrukturer kan v??re tilg??ngelige for ordregiver, og kan vedligeholdes af tilbudsgiver, s?? oplysninger til enhver tid er ajour.

9. Er mulighederne for at benytte data til ledelsesdata unders??gt? 

   Offentlige myndigheder kan aftale strukturering af indholdet i snitfladen med ordregivers datavarehusteam, herunder, at enhver ??ndring af datasnitfladen kan meddeles til ordregivers datavarehusteam i rimelig tid inden ??ndringen gennemf??res, s??ledes ordregiver har mulighed for at tilrette de bagvedliggende processer.

# Udvikling og vedligeholdelse

Form??let med dette afsnit er at beskrive offentlige myndigheders overvejelser om udvikling og vedligeholdelse, herunder drift, af open source-software, der best??r af l??bende opgaver og kr??ver ??benhed og agilitet, hvis skal realisere besparelserne ved omkostningseffektive udbud og sikre robuste digitale l??sninger for fremtiden.

Det stiller en r??kke krav til kompetencer, og - s??rligt hvis myndigheden udvikler i f??lleskab med andre - opbygning af et open source-f??llesskab internt eller p?? tv??rs af myndigheder, der kan fastholde den relevante viden og gode erfaringer med open source som udviklingsetode.

Til forskel fra propriet??re l??sninger er open source-software ofte drevet af et f??llesskab (af frivillige). Det en stor betydning for placering af ansvar for l??sningen. For nogle open source-l??sninger bliver der lagt mange frivillige kr??fter i projektet. 

Disse forskellige f??llesskaber sikrer, at der er mange, der har en dybdeg??ende viden om de forskellige open source-l??sninger, og denne viden ligger ofte tilg??ngelig for den nysgerrige p?? de respektive l??sningers websites. F??llesskaber kan b??de bruges i selve afs??gningen af markedet og som referencef??lleskab og videnbank ved valg af en specifik open source-l??sning. 

Forskellige typer it-anskaffelser kr??ver forskellige kompetencer i den enkelte myndighed. Ved indk??b af propriet??r software har man ofte ikke brug for at have alle kompetencerne internt, da det er leverand??ren, der servicerer, implementerer og opdaterer produktet.

N??r man udvikler open source, stiller det ofte flere krav til kompetencer, om end der er masser eksempler p?? leverand??rer, der tilbyder open source-software p?? samme vilk??r som propriet??re l??sninger. Hvis man imidlertid indg??r i et samarbejde, der kr??ver flere kompetencer, end organisationen r??der over, kan man med fordel opbygge et f??llesskab og leverand??raftaler, der sikrer, at man ikke skal besidde alle kompetencerne selv.

Friheden til at ??ndre softwaren og til at g??re dette i strategiske samarbejder underst??tter innovation, dels fordi det er muligt at tilpasse eksisterende software, dels fordi den voksende m??ngde open source-software, man kan tage ned fra hylden og i brug, g??r det muligt hurtigt at sammens??tte nye produkter og services.
 
De enkelte myndigheder kan opleve en h??ste-s??-problematik, som g??r det sv??rt at etablere nye open source-projekter. Med h??ste-s??-problematik menes, at det ikke altid er den myndighed, der l??gger alle ressourcerne i et projekt, som h??ster gevinsterne. Af den grund kan det v??re s??rligt relevant i nogle projekter at der mellem flere myndigheder indg??s et samarbejde om at (videre)udvikle en l??sning, som flere myndigheder kan f?? gl??de af. P?? den m??de deler man ressourcer og risici ved projektet.

## Tjekliste til udvikling og vedligeholdelse

1. Er mulighederne for at leverand??rer af vedligehold og videreudvikling nemt kan udskiftes unders??gt? 

   Offentlige myndigheder kan sikre, at tilbudsgiver leverer en veldokumenteret digital l??sning, s??ledes at eventuel videreudvikling kan foretages af andre leverand??rer. Dette omfatter teknisk dokumentation, herunder systembeskrivelser og arkitekturtegninger. Dermed sikrer man ogs??, at l??sningen kan drives videre efter kontraktudl??b. Offentlige myndigheder kan kr??ve, at den tekniske dokumentation og kildekoden overholder krav og standarder tilh??rende den valgte open source-licens, samt forholde sig til planer for videreudvikling, opgradering og udfasning af l??sningen fra begyndelsen og udarbejde passende strategier.
   
2. Er mulighederne for at varetage egen drift af implementeret open source unders??gt? 

   Offentlige myndigheder kan overveje, om de selv kan og vil l??fte opgaven, eller om de har brug for at indg?? kontrakt med en drifts- og supportleverand??r.

3. Er muligheden for at have f??lles krav til vedligeholdelse, governance, koordinationsorganer, videndeling i det tilh??rende community for en given nyudviklet open source-komponent unders??gt? 

   Offentlige myndigheder, der udvikler i f??llesskab med andre, kan forholde sig til krav til vedligeholdelse af den f??lles kodebase, efterlevelse af f??llesskabets governancekrav, etablering af koordinationsorganer, videndeling mv. mellem brugere af l??sningen, dialog med leverand??rer og promovering af l??sningen. Offentlige myndigheder, der udvikler selv eller i f??llesskab med andre, kan stille krav om koordinering og prioritering af videreudviklings??nsker, bestilling og styring af udviklingsopgaver og arkitekturstyring og governance for kodebasen. Ved udlicitering af driften til en ekstern leverand??r, kan der stilles krav om en drifts- og serviceaftale, der indeholder oppetider, supportniveauer og sanktioneringsmuligheder, beskrivelse af releases og deployment og leverand??rstyring.

4. Er muligheden for at l??bende evaluere modenheden af open source-komponenter, som er implementeret, unders??gt?

   Offentlige myndigheder kan l??bende evaluere modenheden af open source-komponenter, de anvender, og software, som de udvikler selv eller i f??llesskab med andre med henblik p?? at tr??ffe beslutning om at tilf??re flere ressourcer, opgive brug af l??sningen eller udbredelse af l??sningen til andre myndigheder.

# Baggrund for vejledningen

Open source er ikke noget nyt i den offentlige sektor. Det har v??ret og er fortsat interessant, fordi det underst??tter mere modul??re digitale l??sninger og samarbejdsorienterede metoder til at udvikle, vedligeholde og genbruge komponenter. Open source kan derfor underst??tte sammenh??ngende digitalisering og leverand??ruafh??ngighed i den offentlige sektor.

Open source er en del af arkitekturregel 2.3 om at [undg?? afh??ngighed af leverand??rer og propriet??re teknologier](https://arkitektur.digst.dk/principper-og-regler/princip-2-arkitektur-fremmer-sammenhaeng-innovation-og-effektivitet-4), der operationaliseres ved at "anvende b??redygtige open source-komponenter, hvor det er relevant".

[Statens it-projektmodel](https://digst.dk/styring/projektstyring/statens-it-projektmodel/) indeholder desuden et princip om, at allerede indk??bte eller udviklede l??sninger skal genbruges i videst mulige omfang. Hvis eksisterende l??sninger ikke kan bruges direkte, skal det overvejes, om det bedre kan betale sig at videreudvikle en allerede eksisterende funktionalitet fra en anden styrelse end at foretage nyudvikling af en tilsvarende l??sning fra bunden.

## Principper

[Open source-software i det offentlige](https://www.digitaliser.dk/resource/2212763) beskriver en r??kke **principper for anvendelse af open source i det offentlige**. Principperne sikrer offentlige myndigheder mange valgmuligheder og underst??tter, at it-anskaffelser samlet set bliver billigere og mere fleksible. Samtidig er principperne med til at sikre et innovativt og konkurrencepr??get marked.

 * **Konkurrence**<br>
 Velfungerende konkurrence er en foruds??tning for et effektivt og varieret softwaremarked. Open source underst??tter, at softwaren kan vedligeholdes og videreudvikles af flere leverand??rer. Softwareleverand??rer skal p?? lige vilk??r kunne tilbyde deres it-ydelser til det offentlige.
 * **Kontrol og selvbestemmelse**<br>
 Anvendelse af open source-software sikrer kontrollen over softwaren. Dermed kan den enkelte myndighed bestemme, hvorn??r og hvordan softwaren skal opdateres, udvikles og  eventuelt deles med andre myndigheder.
 * **Udvikling og innovation**<br>
 Myndigheder skal ved udvikling af software overveje, hvilken software-udviklingsmodel, herunder open source-udviklings- og forretningsmodellen, som bedst underst??tter innovation og hurtig udvikling af nye produkter og services. Egenudviklet software b??r som udgangspunkt stilles til r??dighed med en open source-licens. Det betyder ikke, at gamle metoder skal opgives, men at flere metoder kan leve side om side, og nye kan afpr??ves, s?? fordele og ulemper kan afklares i forhold til den danske forvaltnings virkelighed.
 * **Bedst og billigst uanset softwaretype**<br>
 Den enkelte myndighed skal have mulighed for at erhverve den bedste og billigste software ud fra lokale forvaltningsm??ssige behov, uanset om der er tale om closed source- eller open source-software. Software skal v??lges p?? baggrund af en vurdering af en samlet business case.
 * **Sammenh??ng og fleksibilitet**<br>
 Myndigheder skal satse p?? software, der opbygges i mindre dele, og som ved hj??lp af ??bne standarder er i stand til at kommunikere med andre typer software. Derved sikres det, at enkelte dele af systemet uafh??ngigt kan udskiftes til gavn for fleksibilitet, genbrug og konkurrence p?? omr??det.
 * **Genbrug af software**<br>
 Anvendelse af open source-software kan sikre, at skatteborgerne undg??r at betale for udvikling af den samme software flere gange.

## Europ??iske str??mninger

Open source st??r ogs?? h??jt p?? dagsordenen i EU, der peger p?? brug af open source i den offentlige sektor som en vej til tillid mellem borgere og myndigheder, gennemsigtighed, interoperabilitet og leverand??ruafh??ngighed.

Under overskriften *Think Open* har EU-kommissionen i deres [open source-softwarestrategi](https://ec.europa.eu/info/departments/informatics/open-source-software-strategy_en) pr??senteret en vision for digital transformation, innovation og samarbejde med open source som l??ftestang. Open source skal sikre nye, effektiver l??sninger, der virker og kan deles og udvikles p?? tv??rs af landegr??nser.

* **T??nk ??bent**<br>
  Open source-l??sninger er at foretr??kke, n??r de er tilsvarende i funktionalitet, total omkostninger og cybersikkerhed.
* **Transform??r**<br>
  Vi udnytter principperne for open source: vi innoverer, vi samskaber, deler og genbruger, og bygger sammen brugercentrerede, datadrevne offentlige tjenester.
* **Del**<br>
  Vi deler vores kode and muligg??r bidrag til relaterede open source-projekter.
* **Bidrag**<br>
  Vi str??ber efter at v??re et aktivt medlem af det mangfoldige open source-??kosystem.
* **G??r sikker**<br>
  Vi s??rger for, at den kode, vi bruger, og den kode, vi deler, er fri for s??rbarheder ved at teste sikkerheden l??bende.
* **Bevar kontrol**<br>
  Vi fremmer ??bne standarder og specifikationer, der er implementeret og distribueret i open source.

I en [unders??gelse om effekten af open source](https://digital-strategy.ec.europa.eu/en/library/study-about-impact-open-source-software-and-hardware-technological-independence-competitiveness-and) p?? teknologisk uafh??ngighed, konkurrenceevne og innovation i den europ??iske ??konomi fremh??ver tre overordnede anbefalinger, hvor brug af open source kan bidrage til:

 * En digitalt uafh??ngig offentlig sektor
 * ??ben forskning og udvikling som fundament for v??kst
 * Et digitaliseret og internationalt konkurrencedygtigt erhvervsliv

# Bilag

## Tjekliste til brug af open source

**Strategier**

1.	Er fordele og ulemper ved anvendelse af open source unders??gt?
2.	Er risici, behov for tekniske kompetencer og andre ressourcer og omkostninger ved udvikling af open source unders??gt?
3.	Er de rette kompetencer til at arbejde med open source sikret? 
4.	Er de forskellige niveauer i softwarestakken identificeret med henblik p?? hvor open source giver mest v??rdi?
5.	Er der valgt medie til offentligg??relse af kildekode? 

**Markedsafd??kning**

1.	Er mulighederne for genbrug af eksisterende open source-komponenter unders??gt?
2.	Er *Total Cost of Ownership* for genbrug af eksisterende open source-komponenter og tilsvarende propriet??re l??sninger unders??gt?
3.	Er mulighederne for at f?? vejledning i genbrug af eksisterende open source-komponenter unders??gt?
4.	Er aktivitetsniveauet i det tilh??rende community for en given eksisterende open source-komponent, som skal genbruges, unders??gt?
5.	Er kadancen for fejlretning og udvikling for en given eksisterende open source-komponent, som skal genbruges, unders??gt?
6.	Er mulighederne for at bidrage til det tilh??rende community for en given eksisterende open source-komponent, som skal genbruges, unders??gt?

**Licenser**

1.	Er mulighederne for at anvende popul??re og bredt anvendte licenser i egen udvikling af open source unders??gt? 
2.	Er risici for licenser med *copyleft* unders??gt?.
3.	Er mulighederne for at vejlede andre myndigheder om licenser for open source unders??gt? 
4.	Er licensen for en given eksisterende open source-komponent, som skal genbruges, unders??gt? 
5.	Er mulighederne for at bruge EU-kommissionens v??rkt??j til at sammenligne softwarelicenser unders??gt?
6.	Er retlige forpligtelser og omst??ndigheder for brug af open source-licenser unders??gt? 
7.	Er mulighederne for at frigive evt. leverand??rers skriftlige dokumentation som open source unders??gt? 

**Implementering**

1.	Er der udarbejdet vejledning og dokumentation som kan vedl??gges egen udvikling af open source-komponenter? 
2.	Er mulighederne for at anvende standarder for indeksering af egen udvikling af open source-komponenter unders??gt? 
3.	Er mulighederne for at f?? lavet kodereview af egen udvikling af open source-komponenter unders??gt? 
4.	Er mulighederne for at anvende ??bne standarder og snitflader unders??gt? 
5.	Er mulighederne for at anvende ??bne frameworks og kodebiblioteker unders??gt? 
6.	Er mulighederne for at anvende ??ben datamodel og omkostningsfri adgang og ejerskab for data unders??gt?
7.	Er mulighederne for at sikre myndighedens ejerskab for data unders??gt?
8.	Er mulighederne for at f?? l??bende vedligeholdt datamodel unders??gt?
9.	Er mulighederne for at benytte data til ledelsesdata unders??gt? 

**Udvikling og vedligeholdelse**

1.	Er mulighederne for at leverand??rer af vedligehold og videreudvikling nemt kan udskiftes unders??gt? 
2.	Er mulighederne for at varetage egen drift af implementeret open source unders??gt? 
3.	Er muligheden for at have f??lles krav til vedligeholdelse, governance, koordinationsorganer, videndeling i det tilh??rende community for en given nyudviklet open source-komponent unders??gt? 
4.	Er muligheden for at l??bende evaluere modenheden af open source-komponenter, som er implementeret, unders??gt?

## Cases om brug af open source

EU-Kommissionens [Open Source Observatory](https://joinup.ec.europa.eu/collection/open-source-observatory-osor) (OSOR) fungerer som et samlingssted, hvor open source-f??llesskaber kan dele viden og erfaringer og finde og genbruge open source-software.

I Danmark har OS2-f??llesskabet, med udgangspunkt i materiale overdraget fra Aarhus Kommune, udarbejdet tre vejledninger, som indeholder relevant og vigtig viden omkring open source og anskaffelsen af open source software.

Form??let med vejledningerne er at afmystificere og hj??lpe myndigheder med at indk??be og bruge af open source. Det er at hj??lpe til at benytte open source strategisk og hj??lpe med at g??re kravspecificering, valg og indk??b af l??sning s?? nemt som muligt. L??s vejledninger om [licenser, jura, udbud og kontrakter](https://faq.os2.eu/open-source-anskaffelse-licenser-jura-udbud-og-kontrakter?collection=59).

Der findes ogs?? andre vejledninger i genbrug af open source-software i den offentlige sektor. F.eks. har det italienske ministerium for teknologisk innovation og digital omstilling beskrevet [retningslinjer for anskaffelse og genbrug af software for offentlige myndigheder](https://docs.italia.it/italia/developers-italia/gl-acquisition-and-reuse-software-for-pa-docs/en/stabile/index.html) og open source-organisation Foundation for Public Code har etableret en s??kaldt [Standard for Public Code](https://standard.publiccode.net/), der skal hj??lpe organisationer med at udvikle og genbruge open source-software.

I forbindelse med udarbejdelsen af n??rv??rende vejledning har projektet tilvejebragt en r??kke open source-casebeskrivelser, der deler gode r??d til og opm??rksomhedspunkter ved brug af open source.

Casebeskrivelserne bliver l??bende publiceret p?? [KL og KOMBITs videncenter for digitalisering og teknologi](https://videncenter.kl.dk/viden-og-vaerktoejer/innovation), der ogs?? fremover vil fungere som en f??lles platform for deling af viden, v??rkt??jer og cases om brug af open source i den offentlige sektor.

================

[arkitektur.digst.dk](arkitektur.digst.dk)
