### Poznámka ke statusům (a dalším údajům o knihovních jednotkách)

Až si budete zkoušet práci s naším portálem, můžete si všimnout následující vlastnosti:  
&nbsp;  
Okamžitě při zobrazení úplného záznamu vidíte data sklizená přes OAI-PMH, tzn. údaje, které nám poskytujete ve formátu MARC.  
Načítání dostupnosti knihovních jednotek, které probíhá přes NCIP, pak může trvat několik sekund (v závislosti na výkonnosti Vašeho serveru).  
Jedná se o data, která NCIP zasílá jako odpověď na LookupItem ItemElementType.  
&nbsp;  
**NCIP však nenačítá jen dostupnost, ale můžou se přes něj dotahovat i další údaje o knihovních jednotkách** (včetně statusů), které **mají vyšší váhu** než data, která jsme od Vás sklidili přes OAI-PMH.  
&nbsp;  
Praktický důsledek lze demonstrovat na následující situaci: 
* Jako nepřihlášený uživatel vidíte ve statusech u vybraného záznamu, které jednotky si lze vypůjčit absenčně, které prezenčně atd..
* Přihlásíte-li se jako uživatel, který má v dané knihovně nějakou blokaci, můžete náhle zjistit, že se Vám všechny statusy změnily na "Nelze vypůjčit".

| Data o knihovní jednotce získáváme dvěma současně používanými způsoby:<br>1. Sklízíme je přes OAI-PMH - jsou viditelná nezávisle na NCIPu.<br>2. Načítáme je přes NCIP pokaždé, když je uživatel zobrazuje -  |
| :---- |

&nbsp;
---
[Zpět na **Zpřístupnit služby - NCIP**](ncip)   
[Zpět na hlavní stránku](Home)