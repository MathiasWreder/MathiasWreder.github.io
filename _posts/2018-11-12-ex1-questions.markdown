---
layout: post
title:  "Frågor ex1"
date:   2018-11-12 12:33:10 -0600
categories: jekyll update
---



* **Vad tycker du om att förkompilera din CSS?** 
Det var helt ok, kändes lite rörigt i början men man ser potentialen.
    * **Jämfört med vanlig CSS?** 
    Lättare att hitta till rätt ställe i källkoden, då den är uppdelad i fler olika filer beroende på vad den styr utseendet på. Skönt att kunna använda sig av diverse tekniker för att ungå att skriva samma kod flera gånger.
    * **Vilka tekniker använde du?** 
    Jag har använt mig av variabler för att sätta färg på till exempel text och bakgrund. Sedan använde jag nästling för att ändra utseendet på diverse a-taggar. Det finns även fler tekniker i källkoden som kom med från minima, men jag valde att inte ändra på dessa då resultatet passade med den layout jag ville ha på webbplatsen. 
    * **För-och nackdelar?**
        * **Fördelar:**
            * Mindre kod att underhålla.
            * Använda sig av variabler och göra beräkningar.
            * Organisera koden bättre, till exempel med hjälp av nästling.
        * **Nackdelar:**
            * Svårare att debugga, då radnummren i webbläsaren inte stämmer med radnummren i källkoden.
            * Mer komplex kod.
            * Ökad byggtid vid större projekt.         
     <br />

* **Vad tycker du om statiska webbplats generatorer?**
Jag tycker dem verkar bra. Smidigt att skapa mallar som man sedan bakar ihop till fullstädiga sidor på webbplatsen. Kul att man kan använda markdown för att skapa innehållet. 
    * **Vilken typ av projekt är de lämpliga för?**
    De är lämpliga för webbplatser som ska klara av hög beslastning, ha snabb responstid och vara enkla att uppdatera.    
    <br />

* **Vad är robots.txt och hur har du konfigurerat det för din webbplats?**
En robots.txt fil används för att ge instruktioner till sökmotorer gällande hur de får krypa runt på en webbplats och hämta information. Filen skapas som ett enkelt textdokument och sparas i roten av din katalog för webbplatsen. Jag valde att konfiguerera min robots.txt fil så att den inte ger sökmotorer tillåtelse att krypa runt på min webbplats. 
<br />

* **Vad är humans.txt och hur har du konfigurerat det för din webbplats?**
En humans.txt fil används för att upplysa besökaren om till exempel vem/vilka som har skapat webbplatsen de besöker. Precis som robots.txt skapas filen som ett enkelt textdokument och sparas i roten av katalogen för webbplatsen. I min humans.txt fil valde jag att skriva ner webbutvecklarens namn och ort. 
<br />

* **Hur implementerade du kommentarer till dina blogginlägg?** För att få till kommentarer till mina blogginlägg har jag valt att använda en tjänst från Disqus. Jag skapade ett konto och följde deras installationsguide.
<br />

* **Vad är Open Graph och hur använder du det?** Open Graph är ett protocol som gör det möjligt att länka en webbplats som ett objekt på sociala medier. I head-delen av HTML-koden för webbplatsen lägger man in meta-taggar där man specificerar vilken information som ska presenteras i objektet. Jag har valt att lägga in title, type, url och image till mitt Open Graph protocol för min webbplasts. 
