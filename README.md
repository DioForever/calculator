# Kalkulačka
- ## Úvod
  Účel je udělat základní arimetické operace, funkce s pamětí (save, load, clear memory). Tento dokument je určený pro toho, kdo se snaží vytvořit Kalkulačku.
  Kontaktní informace na tvůrce dokumentu:
  - Mail: vaskodaniel1@gmail.com
  Ostatní dokumenty:
  - ?
    
- ## Popis
  - ### Funkce
    Funkce zahrnují **základní arimetické** funkce jako je sčítání, odčítání, dělení, násobení, mocniny, odmocnity a další **vědecké funkce** jako modulus, log, ln, x^y, exp. Funkce **požadované pro využití aplikace** jako vymazání současného výpočtu, zobrazení výsledku a zapisování desetiných čísel. **Rozšířené funkce** jako zobrazení čísel v binárním zobrazení či hexadecimálním, a práce s těmito čísli jako v základních funkcích. Další rozšířené funkce jsou **logické operace** jako OR, AND, XOR. **Nastavení**, kde si uživatel může nastavit počet zobrazených desetiných čísel.
        
  - ### Uživatelské skupiny
    Budou tam dva profily, které si může uživatel vybrat. **Normální uživatel**, pouze základní funkce a **programátor** by měl možnost překliknout do jiného zobrazení čísel (binárního, hexadecimálního), u kterých může využívat také základní funkce, zároveň bude moct používat logické operace. Profil **"Vědec"** přidá **vědecké funkce** k základním. Profil **"Datumy"**
    
  - ### Uživatelské prostředí
    Tlačítko, pro přestup do **nastavení**, kde si uživatel může nastavit barevnou kombinaci aplikace, font, velikost fontu a počet desetinných míst. Zobrazení **historie** výpočtů, defaultně krátkou ale s možností rozkliknout a zobrazi plnou historii. Práce s **pamětí**, ukládání/mazání výpočtů do/z paměti, načítání z paměti a mazání celé paměti. Grid tlačítek pro všechny funkce popsané ve funkcích.
    [<img src="[image.png](https://github.com/DioForever/calculator/assets/78236175/82edf66d-9a43-4421-be43-21a5d6969d97)" width="250"/>](image.png)

  - ###  Omezení návrhu a implementace
    Aplikace nebude obsahovat možnost kopírovat a vkládat, zkratky do aplikace.
  - ### Předpoklady a závislosti
    Malé využití CPU a paměti, jednoduché a rychlé používání.
- ## Požadavky na rozhraní
  - ### Uživatelské rozhraní
       Desktopová aplikace, nebude tam víc věcí než nutno, základní operace a další operace přes rozkliknutí možné přidat.
- ## Vlastnosti systému
  - ### Aritmetické výpočty
    - Důležitost: **HIGH**
    - Základní aritmetické výpočty jako sčítání, odčítání, dělení, násobení, mocniny, odmocniny.
  - ### Základní
    - Důležitost: **HIGH**
    - Mazání výpočtů, zobrazení výsledků.
  - ### Binární výpočty a logické operace
    - Důležitost: **MIDDLE**
    - Aritmemitcké výpočty s číslem zobrazené v binární podobě, možnost si zvolit kolika bitová čísla se vuyžívají. Možnost provádět logické operace, NOT, AND, OR, XOR, NAND, NOR, EXCLUSIVE OR.
    - Je potřeba aby byl zaveden systém priorit v podobě závorek, ať jsou použitelné všechny závorky. Používání desetiných čísel ve výpočtech.
  - ### Historie
    - Důležitost: **MIDDLE**
    - Zobrazení pouze průběžných výsledku (všech).
  - ### Ukládání v paměti
    - Důležitost: **LOW**
    - Ukládání průběžných výpočtů a pozdější načtení zpátky. V případě že potřebujeme vypnout aplikaci ci jít počítat něco jiného tato funkce uloží historii a současný výpočet.
    - Je potřeba aby byla zavedena hiearchie ve které byly tyto instance uloženy a aby uživatel mohl dále pokračovat ve výpočtech po načtení.
  - ### Nastavení
    - Důležitost: **LOW**
    - Přidání Binárních výpočtů a logických operací, změna fontu, změna velikosti fontu, změna zbarvení aplikace.
  - ### Popis a důležitost
    
    
