# Markétina školka - Lekce 4
**Téma: větve a Merge**

_Návod je uzpůsoben pro Git GUI aplikaci [Fork](https://git-fork.com/)_

## Zadání
Tento úkol bude velmi podobný, jako předchozí. Ale s tím rozdílem, že nyní bude
tvůj úkol větve nejev vytvářet, ale přepínat se mezi nimi.

## Část první
Vytvoř si novou větev. V ní proveď jeden commit. Třeba oprav **tento přelkep**.


### Postup spojení větví
Na začátku jedna důležitá, byť trochu matoucí informace: Při spojování větví je
rozhodující, která větev je aktuální. Git totiž **dovoluje upravovat pouze aktuální
větev**.

Mergování „spojuje dvě větve“, takže by se mohlo zdát, že na tom nezáleží. Jenže
právě pojem „spojení dvou větví“ je nepřesný – ve skutečnosti dochází k „zanesení
změn z jedné větve **do** jiné větve“. 

V příkladu výše sis dříve vytvořila větev `marketa-lesson-3`, která je „tvoje“.
Nyní chceš změny ze své větve dostat do větve `master`. Z toho vyplývá, že změny
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