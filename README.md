# Markétina školka - Lekce 6
**Téma: Pull request**

_Tutoriál je uzpůsoben pro Git GUI aplikaci [Fork](https://git-fork.com/)_

Git, respektive GitHub (a další podobné služby: [BitBucket](https://bitbucket.org) i [GitLab](https://gitlab.com/)),
poskytují mechanismus na „nabídnutí úprav“. Jmenuje se to **Pull request** (zkratka `PR`).

> V některých systémech se používá název **Merge request**, ale prakticky jde o zcela stejnou funkcionalitu.

Ve stručnosti jde o to, že ty ve své větvi připravíš změny, uděláš push na GitHub. Na GitHubu pak vytvoříš nový
Pull request. Následně někdo jiný může zkontrolovat tvoje změny a provede Merge do větve `master`.

Tento postup je vhodný tam, kde za kód odpovídá konkrétní osoba a ostatní mohou přispívat – nicméně každá změna musí
vždy projít kontrolou a schválením.

Zkusíme si to i zde.

## Zadání
1. Vytvoř si novou větev.
2. Udělej změny (např. moje obligátní překlepy)
3. Commit & push (na rozdíl od předchozích lessons zde prvně pushujeme jinou větev než `master`)
4. Otevři si repozitář na GitHubu _(velmi pravděpodobně tě GitHub rovnou vyzve k vytvoření Pull requestu – to je 
šikovná zkratka, které můžeš využít, v takovém případě přeskoč na bod č. 7.)_.
5. Nad seznamem souborů je vlevo šedé tlačítko s nápisem `Branch: master`, na který klikneš a v nabídce se přepneš do
své větve.
6. Vedle něho je tlačítko `New pull request`, jímž se ti otevře stránka pro otevření nového PR.
7. Vyplň informace o PR a kliknutím na zelené tlačítko odešli. 

## Měla bys vědět
Pull request je takový **živý most** mezi tvojí větví a cílovou větví. Dokud tedy bude pull request otevřený, nemůžeš
větev smazat, protože by tím PR zanikl. Nicméně to má naopak výhodu, že můžeš do větve později přidat nové opravy
a ty se ihned v PR projeví.