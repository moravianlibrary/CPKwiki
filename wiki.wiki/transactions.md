## Zprostředkování plateb na portálu Knihovny.cz

Na portálu Knihovny.cz můžete svým čtenářům umožnit přístup k zaplacení poplatků. V praxi se to projeví tak, že čtenář uvidí ve svém přehledu pokut a poplatků pod každou položkou tlačítko "Zaplatit online".  
&nbsp;  
Po kliknutím na tlačítko "Zaplatit online" bude čtenář **přesměrován na platební bránu Vaší knihovny** a poté, co ukončí své akce v rámci platební brány, se přesměruje zpět na portál Knihovny.cz, kde si přečte hlášku, zda byla platba uspěšná nebo neproběhla z důvodu zamítnutí bankou či kvůli vypršení časového limitu.

| Má-li být čtenáři umožněno zaplacení pokut a poplatků přes portál Knihovny.cz, **je nezbytné, aby Vaše knihovna sama rutinně používala on-line platby ve svém lokálním systému** a aby Vaše účtárna uměla řešit problémy vzniklé s platbami on-line. |
| :----: |

**K přesměrování čtenáře na platební bránu nedochází přímo** kvůli bezpečnostním opatřením banky, takže je nutné aby bylo **přistupování k bráně realizováno z Vaší domény s pomocí skriptu**. Potřebujeme znát **adresu Vašich skriptů pro online platby**.   
&nbsp;   
Více podrobností (především pro knihovny se systémem Aleph) se dozvíte <a href="https://gitlab.com/cpk-main/details/wikis/transactions" target="_blank">zde</a> (odkaz přístupný pouze pro zapojované knihovny).  

| **Na předávaných parametrech a návratových hodnotách se domluvíme společně.** |
| :----: |

K testování **není nutné provádět placení skutečných částek**. Jde nám hlavně o přesměrování na platební bránu a zpět do portálu (např. pomocí timeoutu).

&nbsp;

---
[Zpět na **Zpřístupnit služby - NCIP**](ncip)  
[Zpět na hlavní stránku](Home)