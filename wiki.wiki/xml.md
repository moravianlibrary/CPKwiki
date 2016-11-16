## Nepovolené znaky v XML

Vzhledem k použití formátu MARCXML je třeba dát si pozor na znaky, které jsou v XML považovány za řídící a nelze je tedy jednoduše používat při zápisu dat.

| **Nepovolené znaky pro XML jsou: `<`, `>`, `&`, `"`, `'`**. |
| :----: |

Existují dvě **možnosti zápisu** těchto nepovolených znaků: 
1. **`<`** jako **`&lt;`**<br>**`>`** jako **`&gt;`**<br>**`&`**  jako **`&amp;`**<br>**`"`** jako **`&quot;`**<br>**`'`** jako **`&apos;`** 
2. **`<![CDATA[`**`Toto jsou nepovolené znaky: < > & " '`**`]]>`**  
&nbsp;  

---
[Zpět na **Zpřístupnit fond pro sklízení - OAI-PMH**](oai-pmh)  
[Zpět na hlavní stránku](Home)