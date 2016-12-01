# Průvodce zapojením Vaší knihovny do portálu Knihovny.cz

Tento text by Vám měl posloužit jako průvodce zapojením Vaší knihovny do našeho portálu. Jeho účel je ryze praktický, neklade si za cíl popisovat podrobnosti technického řešení portálu. Samotný **návod pro zapojení je obsažen v několika stručných kapitolách**. 

V případě, že se poštěstí, a výchozí nastavení na Vaší straně umožní hladký průchod celým procesem, bude Vám tento základní text stačit. V opačném případě pro Vás můžou být relevantní některé **podkapitoly, v nichž najdete podrobnější informace** týkající se překážek, na které lze narazit. Při jejich sestavování jsme vycházeli z řešení problémů, se kterými jsme se setkali při své dosavadní činnosti.

## Cílový stav
Jak by měl vypadat výsledek úspěšného zapojení Vaší knihovny do portálu? Na to existuje vcelku snadná odpověď:  

|  **Uživateli by mělo být umožněno provést na portálu Knihovny.cz jakoukoliv akci, kterou lze provést z Vašeho OPACu.** |
| :-----: |

Ale jak toho dosáhnout? Postup lze shrnout do následujících kroků:

1.  [Přípravné kroky](../../wiki/1.%20Přípravné%20kroky)
2.  [Zpřístupnit fond pro sklízení - OAI-PMH](../../wiki/2.%20Zpřístupnit%20fond%20pro%20sklízení%20-%20OAI-PMH)
3.  [Zpřístupnit služby - NCIP](../../wiki/3.%20Zpřístupnit%20služby%20-%20NCIP)  
4.  [Vytvořit testovací uživatele](../../wiki/4.%20Vytvořit%20testovací%20uživatele)
5.  [Zapojit se do eduID.cz](../../wiki/5.%20Zapojit%20se%20do%20eduID.cz)
6.  [Adresář knihoven](../../wiki/6.%20Adresář%20knihoven)

| **Je nutné, abychom byli informováni o aktuálním nastavení Vašeho systému.**<br><br>Ohlašujte nám, prosím, jakékoliv relevantní změny a opravy na Vaší straně, ať už se jedná o OAI provider, NCIP responder či cokoliv dalšího, co je zmíněno v tomto návodu. |
| :-----: |

Komunikace je důležitá. **Nerozpakujte se nás ptát, kdykoliv si během procesu zapojování Vaší knihovny nebudete jistí následujícím krokem.** Nejlepších výsledků lze dosáhnout právě tehdy, když budeme všichni vědět, co od sebe navzájem očekáváme.  
&nbsp;  
Co nejpohotovějšímu zodpovězení Vašich dotazů pomůžete komunikací prostřednictvím **poradny**, která je řešena pomocí **issues ve Vašem privátním GitLabovém projektu** (poskytneme Vám odkaz). Stejnou cestu preferujeme i pro ohlašování různých specifik Vaší knihovny, o něž Vás žádáme v tomto návodu.   
&nbsp;  
Pro většinu **témat, která se řeší v průběhu zapojování knihovny**, a pro zasílání **informací, které je nutné nám poskytnout**,  jsou vytvořeny **položky v kontrolním seznamu** (poskytneme Vám odkaz), **z nichž lze posílat již předem správně oštítkované issues**. Využijte, prosím, této možnosti, pokud se Váš dotaz bude týkat některé z položek v seznamu.  
&nbsp;  
Tento systém nám zpřehlední komunikaci se zapojujícími se knihovnami a pomůže urychlit řešení Vašich dotazů a připomínek.

| Vidíte v tomto návodu nějakou chybu, překlep, neplatný odkaz apod.? Ohlašte nám to [založením issue](../issues/). Děkujeme.  |
| :-----: |
