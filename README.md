# Průvodce zapojením Vaší knihovny do portálu Knihovny.cz

Tento text by Vám měl posloužit jako průvodce zapojením Vaší knihovny do našeho portálu. Jeho účel je ryze praktický, neklade si za cíl popisovat podrobnosti technického řešení portálu. Samotný **návod pro zapojení je obsažen v několika stručných kapitolách**. 

V případě, že se poštěstí, a výchozí nastavení na Vaší straně umožní hladký průchod celým procesem, bude Vám tento základní text stačit. V opačném případě pro Vás můžou být relevantní některé **podkapitoly, v nichž najdete podrobnější informace** týkající se překážek, na které lze narazit. Při jejich sestavování jsme vycházeli z řešení problémů, se kterými jsme se setkali při své dosavadní činnosti.

## Cílový stav
Jak by měl vypadat výsledek úspěšného zapojení Vaší knihovny do portálu? Na to existuje vcelku snadná odpověď:  

|  **Uživateli by mělo být umožněno provést na portálu Knihovny.cz jakoukoliv akci, kterou lze provést z Vašeho OPACu.** |
| :-----: |

Ale jak toho dosáhnout? Postup lze shrnout do následujících kroků:

* [1. Přípravné kroky](1.-Přípravné kroky)
* [2. Zapojit se do eduID.cz](2.-Zapojit-se-do-eduID.cz)
* [3. Zpřístupnit fond pro sklízení - OAI-PMH](3.-Zpřístupnit-fond pro sklízení---OAI-PMH)
* [4. Zpřístupnit služby - NCIP](4.-Zpřístupnit služby---NCIP)  
* [5. Vytvořit testovací uživatele](5.-Vytvořit-testovací-uživatele)
* [6. Adresář knihoven](6.-Adresář-knihoven)
* [7. Nápověda pro Vaše čtenáře](7.-Nápověda-pro-Vaše-čtenáře)

| **Je nutné, abychom byli informováni o aktuálním nastavení Vašeho systému.**<br><br>Ohlašujte nám, prosím, jakékoliv relevantní změny a opravy na Vaší straně, ať už se jedná o OAI provider, NCIP responder či cokoliv dalšího, co je zmíněno v tomto návodu. |
| :-----: |

Komunikace je důležitá. **Nerozpakujte se nás ptát, kdykoliv si během procesu zapojování Vaší knihovny nebudete jistí následujícím krokem.** Nejlepších výsledků lze dosáhnout právě tehdy, když budeme všichni vědět, co od sebe navzájem očekáváme.  

| Vidíte v tomto návodu nějakou chybu, překlep, neplatný odkaz apod.? Ohlašte nám to [založením issue](../issues/). Děkujeme.  |
| :-----: |
