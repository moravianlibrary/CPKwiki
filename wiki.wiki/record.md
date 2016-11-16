## Podoba záznamu
Knihovnám, které by se chtěly zapojit do projektu Knihovny.cz, doporučujeme, aby se řídily [standardy pro přispívání do Souborného katalogu ČR](http://www.caslin.cz/caslin/spoluprace/jak-prispivat-do-sk-cr/standardy/standardy-pro-souborny-katalog-cr) stanovenými Národní knihovnou (pouze části týkající se MARC 21).  
&nbsp;  
Naše nároky na kvalitu Vašich záznamů však nejsou tak vysoké, jako je tomu u Souborného katalogu. Chceme dosáhnout zapojení co největšího množství knihoven a přísnými požadavky na katalogizaci bychom je spíš odradili.  
Navíc, portál Knihovny.cz funguje jinak - **Vaše záznamy uvidí návštěvník portálu v původní podobě**, tak, jak jste si je sami vytvořili.   

|  **Informujte nás, prosím, jsou-li Vaše záznamy v něčem výrazně ne/nadstandartní** (např. pole nad rámec MARC21u a národních polí nebo naopak chybějící kódované údaje, apod.). |
| :-----: |

Samozřejmě, že **kvalitní záznamy usnadní začlenění Vašeho fondu do portálu**.  
Naše deduplikační algoritmy totiž identifikují snáze kvalitní než nekvalitní záznam. Pokud proběhne deduplikace v pořádku, čtenář uvidí, že např. Babička z Vaší knihovny vydaná roku 2002 je ta stejná, jakou mají v např. v osmi dalších knihovnách.  

| **Záznamy musí mít v rámci Vaší knihovny, jednoznačný identifikátor v poli 001 nebo jednoznačný OAI identifier.** |
| :-----: |

Zvláštní pozornost je třeba věnovat poli **008** (typ dokumentu) a v případě článků poli **773** (zdrojový dokument).

Ze záznamu by mělo být patrné, zda byl vytvořen podle pravidel RDA nebo AACR2 (pozice 18 v návěští MARCu 21: `a` pro AACR2, `i `pro RDA).    

Především je však nutné mít u všech záznamů, které mají své fyzické jednotky, **správně vyplněná podpole v poli 996**. Tomu pro jeho důležitost věnována samostatná [podkapitola](996).  


| **Záznamy, které nelze dohledat a zobrazit ve Vašem OPACu, nemají být k dohledání a zobrazení ani na portálu Knihovny.cz.** |
| :----: |
K případům, kdy se takové záznamy propíšou, může dojít např. u starých vyřazených knih. Jedná se o záznamy **bez pole 996**, které nemají **žádné fyzické jednotky** a **neexistují ani v elektronické podobě** (pro kterou máme pole 856).  

| **Pokud používáte pro své záznamy jiné kódování než UTF-8, je nutné nám to sdělit.** |
| :-----: |  

### Co může (ale taky nemusí) nastat:  
* K problémům se sklizní může dojít např. i tehdy, má-li Vaše knihovna **více než jednu siglu**. V takovém případě je třeba zvolit jen jednu z nich a používat ji pro záznamy celého Vašeho fondu.  
* Další překážka může nastat tehdy, provedete-li **změnu mapování** záznamů vzhledem k OAI-PMH. Pokud se ve změněné podobě sklízejí pouze nově přibývající záznamy, je nutné provést **přepublikování všech záznamů** (může nastat v Alephu).
&nbsp;  

---
[Zpět na **Zpřístupnit fond pro sklízení - OAI-PMH**](oai-pmh)  
[Zpět na hlavní stránku](Home)