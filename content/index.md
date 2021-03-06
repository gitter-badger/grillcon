---
views:

    flash:
        region: flash
        template: default/content
        data:
            meta:
                type: content
                route: grillcon-2018-var/block/flash

    article-toc:
        region: sidebar-right
        template: default/article-toc
        sort: 1
        data:
            meta:
                type: article-toc

    share-this:
        region: main
        template: default/share
        sort: 2

    sidebar-anmal:
        region: sidebar-right
        template: default/block
        sort: 1
        data:
            meta:
                type: content
                route: grillcon-2018-var/block/sidebar-anmalan

author:
    - mos
revision:
    "2018-03-29": (A, mos) Inför GrillCon 2018 vår.
...
GrillCon 2018 Vår - Hackathon och Konferens
===============================

Vårens GrillCon går av stapel torsdag till lördag den 17-19 maj, 2018.

Det blir Hackathon följt av barhäng, Konferens med seminarier, Grill med aktiviteter samt Utflykt.

[ANMÄL DIG NU!](https://goo.gl/f7SQdv)



Övergripande planering {#plan}
--------------------------------

Det övergripande schemat ser ut så här.

| Dag          | Tid   | Vad händer?                        |
|--------------|:-----:|------------------------------------|
| Torsdag      | 09-10 | Samling inför Hackathon            |
|              | 10-17 | Hackathon                          |
|              | 18-   | The Fox & Anchor, med eller utan karaoke |
| Fredag       | 09-10 | Hackathon frukost                  |
|              | 10-15 | Konferens med seminarier och presentationer |
|              | 15-17 | Samtal, fika, hacka (track 1) och öppen kårpub (track 2) |
|              | 17-   | Traditionell Grill med aktiviteter |
|              | 17-23 | Kårpuben håller extra öppet för GrillCon gäster |
| Lördag       | 09-14 | Utflykt i Foto- och Fritidsklubbens regi |



Hackathon {#hackathon}
--------------------------------

Plats H429 och H430 klockan 9-17.

Under dagen förekommer presentationer, planerade och spontana. Det finns team som har annonserat sitt fokus för dagen och man kan anmäla sig till teamledaren för att delta i teamet.



### Presentationer {#pres}

Följande presentationern är grovt inplanerade. Eventuellt tillkommer spontana tillägg efter hand som inspirationen blomstrar.

| Tid (ish)  | Fokus                        |
|:----------:|------------------------------|
|  11        | Assembler i webbläsaren, webassembly (Andreas) |
|  14        | Mikrooptimeringar för vardagen i terminalen I (Mikael) |
|  15        | Mikrooptimeringar för vardagen i terminalen II (Daniel) |

Presentationerna är korta, 10 minuter.



### Team {#team}

Följande team kommer att verksamhet under dagen.

| Team titel | Teamledare |
|------------|------------|
| BITS webbsida | Martin "ocpu" Hövre |
| CSS usability hack contest | Vidar "Lenore" Tedenbrant |
| Programmera spel i JavaScript/Canvas i webbläsaren | Mikael "mos" Roos |

Tanken är att varje team har ett fokus att leverera innan dagen är slut. Eventuellt blir det spontana presentationer av dagens resultat, innan vi går hem.


<!--
* terminilogy du måste veta om för att inte bli mobbad på arbetsplatsnme
-->


<!--
Möte den 18/4 för att bestämma fokus på hackathonet.
-->

<!--
Tanken är att det blir vissa team-aktiviteter där en teamledare bestämmer fokus och de som hänger på jobbar på samma typ av aktivitet under dagen. Tanken är att alla team lyckas komma till ett avslut innan dagen är slut.

Ett exempel kan vara ett team som sysslar med att programmera spel för webbläsaren med JavaScript och grafik i canvas.

Under dagen finns det korta 10-15 minuters presentationer som hålls klockan 11, 14 och 15 i en av salarna.

Ta möjligheten att dedikera dagen för att koda loss på ett av dina egna personliga projekt. Hojta gärna till om du kan tänka dig att leda ett team med specifikt fokus. Du bestämmer själv fokuset.
-->

<!--
Agenda.

1. Den stora planen (hur GrillCon nu skall växa)
    * Hur höst och våreventet skall fungera framöver.
    * Planering med 2-3 events rullande cykel (aktiv backlogg, levande grupper).
1. Vårens GrillCon och schemat (informera, saker att planera)
    * Hackathonet
    * KOnferensen
    * grillen
    * Utflykten
2. Organisation
    * (Daniels lista)
3. Manifest

-->


<!--

### Team XXX {#ht1}

Team med visst fokus under hackathonet, med mål att bli klar innan kvällen.



### Pres 11:00  {#h11}



### Pres 14:00  {#h14}



### Pres 15:00 Micro-optimeringar {#h15}


-->


<!--

Kort ord för presentationerna.

Coding kata

11
* foiki

14
* maria s

15
*

(petter, niclas, maria)
(msv)
larsson (daniel)


-->



Konferens och Seminarier {#konferens}
--------------------------------

Plats: Sal J1640.

Konferensdelen pågår 10-15 med paus för lunch klockan 12-13.Tid 10-12, 13-15.

<!--
 Det blir en blandning av presentationer och hör av dig till organisatörerna om du är sugen på att hålla en presentation.
-->


<!-- tuta o klocka -->

Följande är schemat för seminarierna.



### 10:00 Teknologi-snick-snack {#10}

Tanken är kort-korta presentationer som följer en gemensam form likt [Pecha kucha](https://sv.wikipedia.org/wiki/Pecha_kucha). Om vi efterliknar pecha kucha upplägget så gäller 20 slides á 20 sekunder (6 minuter och 40 sekunder) följt av frågor, efter 10 minuter är det nästa talare.

Gongongen ringer högt när tiden gått ut.

Presentatörer äro följande.

| Presentatör       | Typ             | Titel |
|-------------------|-----------------|-------|
| Marcus Gustafsson | Pecha kucha     | p5.js - libb för att koda grafik på canvas. |
| Peder Tornberg    | Pecha kucha     | Distribuerade små team i global software engineering. |
| Andreas o Kenneth | Pecha kucha     | Comparison and Prediction of Temporal Hotspots |

<!-- pansar om arkadbygge -->



### 11:00 Eiffel - CI/CDD på stor skala {#11}

[FIGURE src=image/personer/magnus-aronsson.jpg?w=240&h=240&cf&a=0,20,0,0 caption="Magnus" class="right"]

Magnus Aronsson jobbar som systemutvecklare på Tieto i Umeå och har ett stort intresse för CI/CDD och distribuerade system.

Magnus berättar så här om sitt seminarie.

> Eiffel är en standard för maskin-till-maskin kommunikation och ett antal implementationer av den standarden som tillsammans skapar ett meddelande-drivet Continuous Integration/Delivery/Deployment system. Detta ger team möjlighet att automatiskt sända meddelanden med information som andra team kan ha nytta av och en gemensam vokabulär att använda i denna kommunikation. Exempelvis kan team istället för vattenfall och överlämningar automatiskt uttala sig om kvalitén på varje commit och tillåta nedströms beroenden själva avgöra när de vill ta in en ny version.

> I denna presentation ges ett par exempel på användningsfall för Eiffel, samt en demonstration av en docker-baserad implementation av ett CI-system som använder Eiffel.

Magnus har gått ett av kurspaketet och har en examen från Umeå Universitet i systemvetenskap. Magnus är en hängiven dbwebbare och känd som ceruza i IRC:n. Läs mer om Magnus på [LinkedIn](https://www.linkedin.com/in/magnus-aronsson-26447812b/) eller läs Magnus' artikel på dbwebb som handlar om "[Flux med Redux och React](https://dbwebb.se/kunskap/flux-med-redux-och-react)".



### 13:00 `C#` {#13}

[FIGURE src=image/personer/filip-ekberg.jpg??w=240&h=240&cf&a=25,25,10,12 caption="Filip" class="right"]

Filip Ekberg är konsult på fekberg AB och författare till boken C# Smorgasbord.

Så här säger Filip om sitt seminarie.

> Mycket har hänt de senaste 18 åren sedan C# först visades upp, vad är det egentligen som gör att programmeringsspråket är ett av de mest använda och omtyckta på marknaden? Låt oss titta på nya, och några gamla, språk-features som gör en C#-utvecklares vardag enklare och roligare att jobba i. Jag är C# utvecklare i grund och botten, jobbar dagligen med språket -- men jag sitter inte i Windows-miljö! Hur funkar det? Låt oss prata om hur C# möjliggör utveckling på vilken platform som helst!

Filip gick ut SE-programmet vid BTH för 10 år sedan och har sedan dess gjort karriär som internationell programutvecklare, skribent och talare på konferenser. Läs mer om Filip på [LinkedIn](https://www.linkedin.com/in/filipekberg/) eller i dbwebb-artikeln "[Fråga Filip Ekberg om livet som egenkonsult](https://dbwebb.se/blogg/fraga-filip-ekberg-om-livet-som-egenkonsult)".



### 14:00 Flexa CSS med Bäck {#1400}

[FIGURE src=image/personer/oscar-back.jpg??w=240&h=240&cf&a=0,0,0,0 caption="Oscar" class="right"]

Oscar Bäck brinner för frontend-utveckling och kommer att hålla en presentation för att ge oss insikter i design, layout och positionering med Flexbox i CSS3.

Så här säger Oscar om sitt seminarie.

> Innan flexbox kom med CSS3 har vi fått nöja oss med bland annat position och float. Även om dessa (i alla fall position) fortfarande fyller sina funktioner, så är flex ett nytt sätt att hantera objekt mer flexibelt (no pun intended) på sidan. 

> Tanken med detta seminarie är att introducera tänket med Flex och visa vissa finesser som du enkelt kan applicera i dina egna projekt. 

> Kanske även rekrytera en och annan backendare till frontend? 

Läs mer om [Oscar på LinkedIn](https://www.linkedin.com/in/oscar-b%C3%A4ck-453aa0151/).



### 14:30 Problemet är lösningen {#1430}

[FIGURE src=image/grill-album/skalle.jpg?w=240&h=240&cf&a=0,15,30,33 caption="Charlie" class="right"]

Charlie Svahnberg besöker oss och delar med sig av sina erfarenheter från en lång karriär som programvarutekniker. Charlie är en av de första programvarutekniker som examinerades från BTH, hans studentakronym är pt91cs.

Charlie är konsult på firman [HLL](http://www.hll.se/) och jobbar främst med IT (nätverk, switchar, routrar och annat som gör att nätet fungerar).

Så här säger Charlie om sitt seminarie.

> Smaka på titeln, "Problemet är lösningen", "en filosofisk betraktelse kring hur duktiga tekniker får lov att förbli duktiga tekniker", typ. Kräver nog lite mer tanke, men.

Charlie är hemlighetsfull, men vi kan räkna med att han levererar. Charlie har som tekniker en lång och gedigen erfarenhet av att hantera chefer och management ur olika aspekter så att de gör ett gott jobb. Vi ser fram emot hans besök och att få dela hans erfarenheter.



Klassisk Grill {#grill}
--------------------------------

<!--
[FIGURE src=image/grillcon-2016-var/vi-fixar-grillen.jpg?w=720&h=240&cf&a=20,15,30,13&f0=colorize,40,0,0,0 caption="Grill med grillspett och annat."]
-->

[FIGURE src=image/grill-album/mos_grill.jpg?w=730&h=240&cf&a=16,0,0,0&f0=colorize,40,0,0,0 caption="Grillspett i sann spiritualistisk anda."]

Traditionell grill med förrätt, varmrätt, efterrätt och snacks.

Kårpuben har extra öppet 15-17 inför grillen. Externa gäster måste finnas anmälda på en gästlista.

Förhoppningsvis har någon hackat och preppat inför grillspetten. Har vi ännu mer tur har någon handlat och det finns en grill som vi kan låna och någon som bär den till grillplatsen.

Under kvällen sker bland annat följande:

* Riktigt svår tipspromenad.
* Statusuppdatering för WM i Arkadbyggeri 2018.
* Resultat och priser för WM i Uptime 2017/2018.
* Notis om startskott för WM i Uptime 2018/2019.

Kåren har extra öppet i puben till klockan 23 i anslutning till grillen. 

<!--
* Statusuppdatering för [WM i Arkadbyggeri 2018](blogg/wm-i-arkadbyggeri-2018).
* Startskott för [WM i Uptime 2017/2018](blogg/wm-i-uptime-2018).
-->


Utflykt med Foto- och Fritidsklubben {#utflykt}
--------------------------------

<!--
[FIGURE src=image/fotoklubben/aspo-2017-var_1600.jpg?w=720&h=240&cf&a=30,0,0,0,0&f0=colorize,40,0,0,0 caption="Vårutflykten gick till Aspö."]
-->

[FIGURE src=image/fotoklubben/tjurko-2017-nossenur_1600.jpg?w=730&h=240&cf&a=0,0,0,0,0&f0=colorize,40,0,0,0 caption="Höstutflykten 2017 gick till Tjurkö."]

Utflykten pågår ungefär mellan 09-14. Plats för starten meddelas senare tillsammans med fler detaljer om dagen.

Utflykten arrangeras av dbwebb's Foto- och Fritidsklubb. Det blir ett hemligt resmål som innebär enklare vandring/promenad bland sevärdheter och natur. En halvdagsutflykt i (hav), skog och mark i all enkelhet. Ta med egen matsäck, kläder för väder och en kamera om andan faller på.

Ta gärna med en kompis.

Våren 2017 gick utflykten till Aspö och hösten 2017 var vi på Tjurkö.

Missa inte fotoklubbens permanenta utställning utanför (och i) labbsalarna H429/H430. Där visas bilder upp från tidigare utflykter och andra händelser. Premiär och vernissage är planerad till Hackathonet.



Hitta hit {#hitta}
--------------------------------

Här är vi.

<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1UNmeJUpCMmbFy7dAFLzOwzwfFps" width="640" height="480"></iframe>



<!--
Hackathon {#hackathon}
--------------------------------

Tänk om alla krav och måsten försvann och du kunde ägna dig åt att programmera ditt eget hobby-projekt tillsammans med andra likasinnade under en och en halv dag? Låter det lockande?

Vi sitter i labbsalen och delar in oss i grupper efter intresseområden som vi själva bestämmer. Sedan gör vi en plan för kod som vi vill hinna med och sen kör vi och hjälps åt att komma i mål. Vi ägnar dagen åt kodning och kodverktyg.

Troligen blir det en del öppen källkod men alla variationer är välkomna.

För min egen del så funderar jag om det blir ramverket Anax som får en insats, eller blir det en start av programvara för ett diskussionsforum, eller satsar jag allt på att utveckla mitt Asteroids i JavaScript? Svåra val som ni alla förstår.

Hackathon i vår mening är att samlas och dedikera tiden till kodning. Vilken härlig frihetskänsla, inga måsten, bara kodande.

Vill du delta i hackathonet men hacka på dina skoluppgifter och kmom så går det strålande bra.

Årets sponsor till Hackathonet är Lars Ollén, aka Laeffe, som bidrar med kolsyrat vatten, färsk och torkad frukt samt osaltade/osötade nötter. Allt för att hålla produktiviteten på en hälsosamt hög nivå. Laeffe är alumni BTH student från Civ PT, aktiv i studentföreningen SIS och numer företagare på konsultföretaget [Projektkoll Sverige AB](https://www.projektkoll.nu/). Lars tänker även delta i Hackathonet så vi ser honom där.



Prisjakt kommer på besök {#prisjakt}
--------------------------------

[FIGURE src=image/personer/maria-hall.jpg?w=120&h=120&cf&a=15,10,15,10 caption="Maria" class="right"]

Maria Hall, CTO (Chief Technology Officer), teknikchef på ren svenska, kommer med några av sina pålitliga medarbetare och gästar oss under fredagseftermiddagen och korvgrillningen.

Maria har utlovat seminarier om React och Redux samt om deras projekt inom Machine Learning.

Tanken är att vi avslutar sessionen med en frågestund/panel där vi kan ställa frågor till gänget från Prisjakt för att höra vilka krav som ställs på webbprogrammerare utanför skolvärlden.

Vad kan jag säga, vilket erbjudande!



Prisjakt-Mattias: React och Redux {#mattias}
--------------------------------

[FIGURE src=image/personer/mattias-lyckne.jpg?w=120&h=120&cf&a=15,10,15,10 caption="Mattias" class="right"]

Först ut är Mattias Lyckne med en presentation i det heta området React och Redux.

Mattias gick ut Web, Internet och Programvaruteknik vid BTH 2013 (_numer heter programmet Webbprogrammering_). Efter det gick flytlasset till Skellefteå för att jobba på en liten byrå med webb- och iOS-utveckling. 2015 blev det Prisjakt där han nu jobbar som utvecklare med både backend och frontend.

Mattias kommer tillbaka till BTH för att prata främst om React och Redux men även lite andra verktyg som kan tänkas behövas. Grunderna presenteras och sen studeras en liten applikation som bryts ned till mindre delar och görs små förbättringar i. Mattias går igenom allt från hur en React-komponent ser ut och vad Redux hjälper oss med till hur vi testar vår kod. Förhoppningsvis går vi alla därifrån sugna på att börja bygga saker i React.



Prisjakt-Emanuel & Henrik: Machine Learning {#emanuelhenrik}
--------------------------------

Emanuel och Henrik håller presentationen om Machine Learning och delar med sig om erfarenheter från ett nystartat Prisjakt-projekt.

<div style="overflow: auto;">
[FIGURE src=image/personer/emanuel-johansson.jpg?w=120&h=120&cf&a=15,10,15,10 caption="Emanuel" class="right"]

Emanuel gick ut från Teknisk Fysik på KTH 2006 och började karriären inom embedded-mjukvara. Därifrån blev det mer och mer machine learning och bildbehandling. Han har bland annat jobbat med bildbehandling och bildigenkänning på värmekameror för övervakning, samt machine learning och statistik för automatiska väderprognoser i Nya Zeeland.

</div>

[FIGURE src=image/personer/henrik-ohman.jpg?w=120&h=120&cf&a=15,10,15,10 caption="Henrik" class="right"]

Henrik gick tre år på Fysikerprogrammet på Uppsala universitet men pausade studierna för att arbeta som mjukvaruutvecklare. Tio år senare återvände han till fysiken och disputerade i elementarpartikelfysik vid ATLAS-experimentet på CERN och Uppsala universitet 2016. Hans intresse för machine learning väcktes genom forskningen, där tekniken används för att urskilja små signaler bland en stor mängd bakgrund.

Nu på Prisjakt har Emanuel och Henrik tillsammans fått möjligheten att starta upp en helt ny machine learning-grupp som än så länge har fokuserat på textanalys i samband med sortering av Prisjakts alla inkommande produkter vilket kommer att vara en stor del av ämnet för presentationen.



Tomten: Webbsäkerhet - en kraschkurs {#tomten}
--------------------------------

[FIGURE src=image/personer/tomten.jpg?w=120&h=120&cf&a=15,10,15,10 caption="Thomas" class="right"]

Vi får ytterligare finbesök då [Thomas Marcks Von Würtemberg, aka tomten](https://www.linkedin.com/in/thomas-marcks-von-w%C3%BCrtemberg-968392132/), kommer och gästar oss och håller ett seminarie om hans specialitet inom säkerhet.

Thomas gick ut programmet IT-säkerhet 2009 och har sedan dess jobbat med säkerhetsfrågor, både professionellt och som sitt fritidsintresse. Thomas har tagit ledigt från sitt jobb som säkerhetskonsult på NCC Group i Leatherhead, England och kommer hit till oss för att grilla korv och hålla ett seminarie med titeln "Webbsäkerhet - En krashkurs".

Vilka skrämmande saker kan han tänkas berätta för oss?

För övrigt är Thomas en stabil dbwebb-innebandyspelare som sponsrat innebandy-gänget med en sjukvårdslåda, det tackar vi för. Thomas är också admin på irc-servern sedan många år tillbaka i tiden. Bra saker att ha i ett CV.



Klassisk Grill {#grill}
--------------------------------

[FIGURE src=image/grillcon-2016-var/vi-fixar-grillen.jpg?w=720&h=240&cf&a=20,15,30,13&f0=colorize,40,0,0,0 caption="Grill med grillspett och annat."]

Traditionell grill med förrätt, varmrätt, efterrätt och snacks.

Förhoppningsvis har någon hackat och preppat inför grillspetten. Har vi ännu mer tur har någon handlat och det finns en grill som vi kan låna och någon som bär den till grillplatsen.

Under kvällen sker bland annat följande:

* Riktigt svår tipspromenad.
* Statusuppdatering för WM i Arkadbyggeri 2018.
* Startskott för WM i Uptime 2017/2018.


-->

<!--
* Statusuppdatering för [WM i Arkadbyggeri 2018](blogg/wm-i-arkadbyggeri-2018).
* Startskott för [WM i Uptime 2017/2018](blogg/wm-i-uptime-2018).
-->


<!--

Utflykt med Foto- och Fritidsklubben {#utflykt}
--------------------------------

[FIGURE src=image/fotoklubben/aspo-2017-var_1600.jpg?w=720&h=240&cf&a=30,0,0,0,0&f0=colorize,40,0,0,0 caption="Vårutflykten gick till Aspö."]

Utflykten pågår ungefär mellan 09-14. Plats för starten meddelas senare tillsammans med fler detaljer om dagen.

Utflykten arrangeras av dbwebb's Foto- och Fritidsklubb. Det blir ett hemligt resmål som innebär enklare vandring/promenad bland sevärdheter och natur. En halvdagsutflykt i (hav), skog och mark i all enkelhet. Ta med egen matsäck, kläder för väder och en kamera om andan faller på.

Ta gärna med en kompis.

I våras gick utflykten till Aspö.


-->
