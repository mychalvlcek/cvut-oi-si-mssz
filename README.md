cvut-oi-mssz [PDF](https://github.com/vlcekmi3/cvut-oi-si-mssz/blob/master/oi-magistr-si.pdf?raw=true)
-------------

* __témata__: [http://www.fel.cvut.cz/cz/education/master/topicsOI.html](http://www.fel.cvut.cz/cz/education/master/topicsOI.html)

### INFO & TIPS & CONVENTIONS
* `00-template` - složka obsahující šablonu pro tvorbu nové otázky
* k indentování používat 4 mezery (NE tabulátor)
* generování PDF:
  * 2-3 běhy generování (kvůli správné indexaci křížových odkazů)
* commit message při změně/úpravě otázek:
```
05/TAL
+ algoritmus
+ spravnost (variant, invariant)
```
* před commitem:
  * zkontrolovat zda neobsahuje nějaké temp soubory (případně je zahrnout do `.gitignore`)
  * přegenerovat výsledné PDF (aby repozitář vždy obsahoval aktuální PDF)

### FILES
* `reference.bib` - seznam veškeré literatury
* `/_lib/csplainnat.bst` - podpora českýho typu citací
* `/_lib/colors.sty` - vlastně definované barvy
* `/_lib/qtree.sty` - knihovna pro kreslení stromů [http://www.ling.upenn.edu/advice/latex/qtree/](http://www.ling.upenn.edu/advice/latex/qtree/)
* `/_lib/infodata.sty` - soubor s doplňujícími informacemi na úvodní stranu (nadpisy apod.)
* `/_lib/codestyle.sty` - soubor s doplňujícími příkazy pro výpisy kódu
  * definice barev pro klíčová slova kódu
  * SQL, HTML, Java, PHP
* `/_lib/mathstyle.sty` - soubor s doplňujícími příkazy pro matematické rovnice, matice apod.
* `/_lib/macros.sty` - soubor s dalšími doplňujícími příkazy)

### SI - SOFTWAROVÉ INŽENÝRSTVÍ (od 2011/2012)
01. `TPJ` - Sémantika: operační sémantika, denotační sémantika, pevný bod funkce, vázání jmen, stav programu a data.
02. `TPJ` - Statická sémantika: typy, polymorfní typy, typy vyššího řádu, rekonstrukce (inference) typů, abstraktní typy.
03. `NUR` - Teorie HCI, kognitivní aspekty, způsoby interakce, speciální uživatelská rozhraní.
04. `NUR` - Metody návrhu, uživatelské a konceptuální modely.
05. `NUR` - Formální popis uživatelských rozhraní.
06. `NUR` - Prototypování uživatelských rozhraní.
07. `OSP` - Techniky správy a organizace rozsáhlých softwarových projektů. Nástroje pro správu verzí zdrojových kódů, sledování chyb, pro automatické generování dokumentace a podporu orientace v rozsáhlých projektech. Způsoby komunikace mezi vývojáři navzájem a i s uživateli. Systémy pro sledování a řešení chyb a uživatelskou podporu. Open-source licence a z nich vyplývající práva a licence. Postup začlenění úpravy (patche) do velkého open-source projektu (např. Linuxové jádro).
08. `OSP` - Požadavky a pravidla pro tvorbu přenositelného kódu. Organizace projektů a struktura operačních systémů pro zajištění přenositelnosti mezi různými platformami (OS, CPU). Vnitřní a vnější reprezentace dat, převody mezi nimi, vztah k síťovým protokolům (endianing, serializace atd.).
09. `AOS` - Co je to architektura zaměřená na služby (SOA)? Základní pojmy, vztah k objektově orientované architektuře. Konceptuální model a formalismy pro modelování SOA.
10. `AOS` - Webové služby. K čemu slouží? Popis a vyhledávání služeb. Technologie pro implementaci a nasazení služeb a klientů. Protokoly, kódování obsahu. Top-down a bottom-up design.
11. `AOS` - Webové služby, automatická kompozice služeb. Orchestrace a choreografie, web mash-up. Modelování služeb a procesů (BPMN, BPEL).
12. `AOS` - Architektura zaměřená na služby (SOA). Kvalita, výkonost a škálování služeb. Zabezpeční, integrita, bezpečnost, a autentifikace služeb. Point-to-point a end-to-end šifrování.
13. `TVS` - Kategorizace SW chyb, optimalizace návrhu testů. Testování automatů.
14. `TVS` - Testovaní metodami bílé a černé skřínky. Strukturální, statická a dynamická analýza. Analýza datových toků. Testování objektově orientovaného softwaru.
15. `TVS` - Formální specifikace programu. Verifikace pomocí metod automatického dokazování a metody model-checking.
16. `WA2` - Architektura Java EE, funkce jednotlivých vrstev, životní cyklus standardizovaných komponent Java EE, návrhové vzory využitelné v architektuře webové aplikace.
17. `WA2` - Vhodnost nasazení jednotlivých webových architektur, sdílení dat, perzistence, webové služby a REST, asynchronnost, messaging.
18. `WA2` - Není - okruh zrušen
19. `WA2` - Cloud architektury, virtualizace, různá pojetí cloudových řešení, omezení cloudových aplikací, náklady na provoz, vlastnosti aplikací vhodných pro nasazení v cloud architektuře.
