# Dragon Tower Escape 

**Dragon Tower Escape** je textová point-and-click adventura vytvořená v čistém HTML, CSS a JavaScriptu. Hráč se ujímá role Elišky, která musí použít svůj důvtip, logiku a předměty v okolí, aby unikla z přísně střežené Dračí věže.

##  Jak hru spustit

1. Stáhni si celý projekt (všechny soubory a složku s obrázky `images/`).
2. Otevři soubor `index.html` v jakémkoli moderním webovém prohlížeči (Chrome, Firefox, Edge, Safari).
3. Klikni na tlačítko **HRÁT** a začni svůj útěk!

##  Ovládání a herní mechaniky

- **Myš (Point-and-Click):** Klikáním na interaktivní zóny (předměty, postavy, průchody) prozkoumáváš místnosti a sbíráš předměty.
- **Inventář:** Sebrané předměty se automaticky ukládají do panelu inventáře na pravé straně. Hra sama kontroluje, zda máš u sebe správný předmět pro další postup.
- **Debug Mód (Klávesa "D"):** Během hry můžeš stisknout klávesu **D** (nebo **d**), která ti vizuálně zvýrazní všechny klikací zóny v místnosti. Skvělé pro testování hry!
- **Tlačítko KONEC:** Pozor! Tlačítko ukončení hry v hlavním menu simuluje kritické selhání systému (Easter Egg v podobě falešné modré obrazovky smrti).

##  Použité technologie

Projekt je napsán s důrazem na jednoduchost a rychlost bez použití externích knihoven (Vanilla technický stack):

- **HTML5:** Struktura herních obrazovek a klikacích zón.
- **CSS3:** Stylování temné fantasy atmosféry, responzivita (pomocí `clamp()`) a plynulé přechody mezi scénami.
- **JavaScript (ES6):** Kompletní herní logika, správa inventáře, stavové proměnné (booleans) a obsluha událostí (`EventListeners`).

##  Přehled lokací

Hra obsahuje celkem 6 unikátních scén, kterými musíte projít:
1. **Cela** – Výchozí bod, kde musíte najít skrytou nápovědu.
2. **Chodba** – První nebezpečí v podobě obřího pavouka.
3. **Věžní schodiště** – Proplížení se kolem spícího hlídače a získání lana.
4. **Strážní místnost** – Hledání klíče a tajné mapy v truhle.
5. **Hradní nádvoří** – Odvedení pozornosti hlídacího psa a příprava na šplh.
6. **Vrchol věže** – Finální slanění dolů za svobodou.

---
*Vytvořeno jako ukázkový projekt interaktivní webové hry.*

