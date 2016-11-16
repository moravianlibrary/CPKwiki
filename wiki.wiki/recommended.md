## Doporučené služby NCIPu pro zvýšení komfortu Vašich čtenářů
Následující služby sice nejsou nezbytné pro zapojení Vaší knihovny do portálu, ale **pokud je svým čtenářům poskytujete ve svém OPACu**, byla by škoda neumožnit jim totéž i na portálu Knihovny.cz.

| **Každá z následujících služeb musí umět zpracovat příchozí NCIP zprávu a vrátit validní NCIP odpověď**. |
| :----: |

Služby pracují s informacemi v prvcích, které jsou buďto povinné, nebo jsou vyžadovány jen za určitých okolností. Jejich rozpis je obsažen v již zmíněné <a href="https://gitlab.com/cpk-main/details/wikis/ncip-details" target="_blank">podrobné dokumentaci</a> přístupné zapojujícím se knihovnám.

| *č. ze standardu* | *název* | *stručný popis* |
| :----- | :----- | :----- |
| 5.4.8 | **Create User Fiscal Transaction** | Umožňuje zprostředkování online plateb. Řešeno přesměrováním na platební bránu knihovny. Na portálu Knihovny.cz lze touto službou řešit **prodlužování platnosti čtenářského průkazu**.  |
| 5.4.11 | **Recall Item** | Funkce, která umožní při rezervaci kontaktovat čtenáře, který má daný exemplář v držení, s prosbou o co nejčasnější vrácení. Předpokládá se, že se jedná o placenou službu a není nám známo, že by ji nějaká česká knihovna nabízela. |
| 5.4.12 | **Cancel Recall Item** | Zrušení požadavku popsaného na předchozím řádku. |
| 5.4.21 | **Update Request Item** | Změna místa dodání či doby zájmu o objednávaný či rezervovaný exemplář. |
| 5.4.22 | **Update User** | Změna kontaktních údajů uživatele (email, adresa). Tuto funkci zatím na portálu nepovolila žádná knihovna. |


### Další podrobná dokumentace
Některé odkazy z této i nadřazené kapitoly. Odkazy psané *kurzívou* jsou přístupné jen pro zapojující se knihovny:
* *<a href="https://gitlab.com/cpk-main/details/wikis/ncip-details" target="_blank">Minimální NCIP požadavky</a>*
* *<a href="https://gitlab.com/cpk-main/details/wikis/ncip-specs" target="_blank">Specifikace formátu NCIP zpráv</a>*
* [Dokumentace NCIP](http://www.niso.org/workrooms/ncip) 
* a jeho [XSD schéma](http://www.niso.org/schemas/ncip/v2_02/ncip_v2_02.xsd)


&nbsp;
---
[Zpět na **Zpřístupnit služby - NCIP**](ncip)  
[Zpět na hlavní stránku](Home)