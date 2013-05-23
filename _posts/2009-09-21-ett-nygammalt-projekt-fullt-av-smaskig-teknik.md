---
layout: post
title: Ett nygammalt projekt fullt av smaskig teknik
date: 2009-09-21 15:46
comments: true
categories: []
---
Så länge som man jobbar med tekniska nördigheter som webb- och systemutveckling så finns det ett ständigt behov att hålla sig uppdaterad och lära sig nya saker. Tyvärr/som tur är dyker det upp grejer precis hela tiden så man blir tvungen att välja/så man har mycket att välja mellan. Sedan gäller det förstås att ha tid och lust att faktiskt sätta sig in i det som är nytt, så att man är hyfsat bekväm med det när det är dags för den första skarpa tillämpningen. I mitt fall blev det lite tvärt om - jag hade ett vettigt projekt jag ville genomföra och jag såg att en rad relativt nya tekniker skulle passa perfekt i lösningen, men jag fick krypa till korset och erkänna för mig själv att jag inte tagit mig tid att lära mig tillräckligt för att kunna sätta igång. Dags att göra något åt det, alltså.

<!--more-->Som jag <a href="http://utmaningen.fjeldstad.se/2009/09/massor-av-tid-men-anda-stressad-dags-att-ta-ett-steg-tillbaka/">berättade i förra veckan</a> så lyckades jag ta mig ur en väldigt stressad och okonstruktiv sinnesstämning genom att inse att jag stångade min panna mot fel vägg, så att säga. Nu har jag bytt frustrationen över de tekniska trösklarna i mitt "skarpa" projekt mot gottningen i att testa nya saker i ett mer prestigebefriat hobbyprojekt.

Även om man har helt fria händer är det inte alltid så lätt att komma på vad för semi-vettigt man ska hitta på när man sitter och knackar kod (eller motsvarande) på kammaren (eller på ett café). Faktiskt kan det vara precis tvärt om - får man ett uppdrag av någon så är det ju "bara att göra", men om ingen har några som helst synpunkter eller önskemål så är man utelämnad åt sin egen fantasi, ve och fasa. Vän av struktur och ordning satte jag mig ner och skrev ner några krav och några önskemål, för att på det sättet kunna rama in vad det egentligen var jag ville göra. Så här såg det ut:

<a href="http://utmaningen.fjeldstad.se/wp-content/uploads/2009/09/hobbyprojekt.jpg"><img class="alignnone size-full wp-image-240" title="hobbyprojekt" src="http://utmaningen.fjeldstad.se/wp-content/uploads/2009/09/hobbyprojekt.jpg" alt="hobbyprojekt" width="500" height="375" /></a>

Okej, jag inser att min handstil troligen inte går att läsa. Jag översätter.

<strong>Teknik jag vill använda:</strong>
<ul>
	<li><a href="http://asp.net/mvc">ASP.NET MVC</a>, själva grundramverket för webbapplikationen (för en sådan ska det bli). Man kan säga att det är en variant av ASP.NET som fungerar som ett alternativ till "Web Forms" och som uppmuntrar en design som följer <a href="http://sv.wikipedia.org/wiki/Model-View-Controller">Model-View-Controller-mönstret</a>.</li>
	<li><a href="http://developer.yahoo.com/yui/">YUI Library</a>, ett Javascriptbibliotek utvecklat av Yahoo. Det heter egentligen "The Yahoo! User Interface Library" vilket väl säger det mesta. Innehåller färdiga komponenter som knappar och sliders men även nyttigheter som <a href="http://developer.yahoo.com/yui/fonts/">schyssta inställningar för teckensnitt</a> och <a href="http://developer.yahoo.com/yui/reset/">normalisering av standardutseende för HTML-element</a> mellan olika webbläsare.</li>
	<li><a href="http://jquery.com/">jQuery</a>, Javascriptbiblioteket alla talar om...eller började tala om för flera år sedan, kanske jag borde säga. Underlättar utveckling av en "rik" webbapplikation på många sätt.</li>
	<li><a href="http://msdn.microsoft.com/en-us/library/bb425822.aspx">LINQ to SQL</a>, ett slags ramverk som om inte suddar ut så åtminstone döljer gränsen mellan programkod och databas inom .NET - smidigt om man vill låta sin applikation lagra och hämta information i en databas. Vilket man vill. Hela tiden.</li>
	<li><a href="https://rpxnow.com/">RPX</a>, en onlinetjänst som låter en utnyttja en uppsjö av OpenID:aktiga autentiseringstjänster utan att behöva interagera med dem allihop själv. Gör att man enkelt kan låta besökare logga in på ens egen webbsajt med exempelvis sitt Google-, Facebook-, Twitter- eller MySpace-konto istället för att skapa ännu-ett-användarnamn-och-lösenord-att-komma-ihåg. Win-win.</li>
</ul>
<strong>Övriga önskemål / bonus:</strong>
<ul>
	<li>Flashigt/kul att visa upp.</li>
	<li>Användbart, gärna även för andra än mig själv.</li>
	<li>Publikt.</li>
	<li>Kan fungera som en referens eller ett exempelprojekt.</li>
	<li>"Lagom" komplext.</li>
	<li>Överblickbart.</li>
</ul>
Det är udda att utgå från tekniska förutsättningar och bygga hela projektet på dem - oftast är ju situationen den omvända... Hursomhelst, några möjliga projekt jag kom att tänka på var i alla fall:
<ul>
	<li><strong>Utmaningen</strong>, alltså den här bloggen. Det vore kul att göra en egen, särskilt eftersom den ändå har en del trogna/tappra läsare jag kunde experimentera med och få feedback från. Men den fungerar ju faktiskt bra som den är, WordPress fyller sitt syfte även om det kan vara frustrerande ibland. If it ain't broke...</li>
	<li><strong><a href="http://www.fjeldstad.se/">Fjeldstad.se</a></strong>. Min "huvuddomän" skulle helt klart behöva styras upp och bli lite mer levande. Men jag vet inte riktigt vad jag skulle använda den till, och när jag inte ens kan hitta på något vettigt när jag verkligen försöker så känns det som upplagt för att jag skulle tappa sugen. Sedan vill jag ju jobba med en datadriven webbsajt som kräver inloggning (för att kunna testa LINQ to SQL respektive RPX) och det ser jag inte riktigt hur det passar in på en personlig hemsida.</li>
	<li><strong>CV/portfolio</strong>, alltså en ersättare till <a href="http://anders.fjeldstad.se/">min nuvarande presentation-av-mig-själv</a> som gått i träda efter att jag faktiskt hittat sysselsättning(ar). LinedIn är dessutom smidigare att jobba med. Även här är det svårt att se var typ hälften av den teknik jag vill använda kommer in i bilden.</li>
	<li><strong>Dobedone.com</strong>, domänen jag registrerade för min gamla ogenomförda idé till <a href="http://blogg.fjeldstad.se/2008/01/28/varldens-basta-att-gora-lista/">"världens bästa att-göra-lista"</a>. Skulle gå ut på att låta mig och övriga användare skapa listor med aktiviteter (to-do:s) som man kan arrangera hierarkiskt för att återspegla de projekt man håller på med och sedan kryssa för dem allt eftersom man genomför dem. Behöver vara snabbt och smidigt att jobba med, vara möjligt att utöka med andra applikationer genom ett API och så vidare. Hmmm...</li>
</ul>
Direkt när jag kom att tänka på Dobedone så insåg jag att jag hade en vinnare. Det är ett projekt som innehåller alla de tekniska aspekter som jag vill utforska samtidigt som det faktiskt kan bli användbart för både mig och andra. Dessutom känns det precis lagom stort och lagom svårt. Jag avgränsar mig nog lite så att jag kan fokusera på ett webb-GUI till att börja med, men det är ju fullt möjligt att senare även exponera ett API så att eventuella entusiaster kan komma åt sina listor i alla möjliga miljöer.

Än så länge har jag inget att visa upp, men jag har satt upp en lösningsstruktur och börjat få ordning på RPX-integrationen. Idag ska jag försöka yxa ihop en trevlig grafisk design i mitt nyinköpta <a href="http://www.adobe.com/products/creativesuite/designstandard/">Photoshop CS4</a>. Hela projektet känns grymt kul!
