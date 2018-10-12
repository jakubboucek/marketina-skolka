# Markétina školka - Lekce 3
**Téma: větve a Merge**

_Návod je uzpůsoben pro Git GUI aplikaci [Fork](https://git-fork.com/)_

## Zadání
V tomto díle si ukážeme, jak dělat v Gitu větve a jak je potom spojit. Výsledek
by měl být stejný, jaký je nyní vidět v historii commitů tohoto úkolu (zobrazuje
se pouze na počítači třeba v aplikaci `Fork`, bohužel na `GitHubu` nikoliv).

### Postup vytvoření větve
- Uprav soubor (jakkoliv – možná tu nejdeš zase nějaký překlep…).
- V aplikaci `Fork` si vytvoš novou větev - na názvu nezáleží (názvy větví jsou
technické, bežně se píšou malými písmeny, bez mezer a bez diakritiky, např.:
`marketa-lesson-3`. V okně pro vytvoření větve nech zaškrnuté `Check out after create`,
aby se ta větev stala aktuální větví.
- Commitni změnu. Commit se vždy zapisuje do aktuální větve.

Větev `master` zůstane v původním stavu. V levém menu je seznam větví. Poklepáním
na vetem se do dané větve přepneš – čím se změní obsah tvého pracovního aresáře.
Zkus si to.

### Postup spojení větví
Na začátku jedna důležitá, byť trochu matoucí informace: Při spojování větví je
rozhodující, která větev je aktuální. Git totiž **dovoluje upravovat pouze autální
větev**.

Mergování „spojuje dvě větve“, takže by se mohlo zdát, že na tom nezáleží. Jenže
právě pojem „spojení dvou větví“ je mepřesný – ve skutečnosti dochází ke „zanesení
změn z jedné větve **do** jiné větve“. 

V příkladu výše sis dříve vytvořila větev `marketa-lesson-3`, která je „tvoje“.
Nyní chceš změny ze své větve dostat do větve `master`. Z toho vyplývá že změny
budou probíhat ve větvi `master`. 

Snad jsem tímto srozumitelně popsal, proč je tedy před zahájením Merge potřeba
přepnout se nejdříve do větve `master` (= větev `master` bude aktuální).

- Přepni se do větve `master`,
- Vlevo v menu klikni pravým myšítkem na tvoji větev a zvol `Merge into master…`,

Tím se vytvoří nový commit, který spojuje tvoji větev a `master`.

Nyní se změny z tvojí větve promítly do `masteru`.

Nyní můžeš tu svoji větev smazat. 

Výsledek Pushni na server, **úkol je tím hotov**.  

Kdybys narazila na jakékoliv nejasnosti, ozvi se.