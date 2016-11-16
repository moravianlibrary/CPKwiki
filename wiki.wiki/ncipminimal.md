## Minimální požadavky na nastavení NCIPu pro zapojení do portálu Knihovny.cz
V této podkapitole jsou vyjmenovány **služby, jejichž nastavení je nezbytné** pro zapojení Vaší knihovny do portálu.   

&nbsp;  
**Podrobnější dokumentaci** k požadavkům najdete **<a href="https://gitlab.com/cpk-main/details/wikis/ncip-details" target="_blank">zde</a>** a detailní **specifikace formátu NCIP zpráv <a href="https://gitlab.com/cpk-main/details/wikis/ncip-specs" target="_blank">zde</a>**. Oba jmenované dokumenty jsou viditelné pouze pro knihovny v procesu zapojování.
  
&nbsp;  
Protože na Knihovnách.cz máme prostřednictvím zapojených institucí zastoupeny bezmála všechny knihovnické systémy, **je téměř jisté, že Váš dodavatel knihovního softwaru již někdy řešil požadavky spojené se zapojováním knihovny do našeho portálu**. Vzhledem k předchozím zkušenostem dodavatelů už teď **půjde především o odladění specifik**, spojených se způsobem používání OPACu ve Vaší knihovně.   
Pokud používáte **Open Source** knihovní systémy (Koha, Evergreen), můžete čerpat ze zkušeností **komunity**. Pomoci a poradit Vám můžeme v rámci našich možností i my.
  
| **Každá z následujících služeb musí umět zpracovat příchozí NCIP zprávu a vrátit validní NCIP odpověď**. |
| :----: |

Služby pracují s informacemi v prvcích, které jsou buďto povinné, nebo jsou vyžadovány jen za určitých okolností. Jejich rozpis je obsažen v již zmíněné <a href="https://gitlab.com/cpk-main/details/wikis/ncip-details" target="_blank">podrobné dokumentaci</a> přístupné zapojujícím se knihovnám.

| *č. ze standardu* | *název* | *stručný popis* | *vzorový vstup* | *vzorový výstup* | 
| :----- | :----- | :----- | :----- | :----- |
| 5.3.1 | **Lookup Agency** | údaje o knihovně | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/lookup-agency.xml" target="_blank">vstup</a> | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/lookup-agency.xml" target="_blank">výstup</a> |
| 5.3.2 | **Lookup Item** | údaje o exempláři (dostupnost, lokace, rezervační fronta) |<a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/loookup-item-itemid.xml" target="_blank">vstup</a> | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/lookup-item-itemid.xml" target="_blank">výstup</a> |
| 5.3.3 | **Lookup Request** | údaje o rezervaci či objednávce | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/authorize_user_by_lookup_user.xml" target="_blank">vstup</a> <br><a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/lookup-request-requestid.xml" target="_blank">vstup</a>  | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/lookup-request-itemid.xml" target="_blank">výstup</a> |
| 5.3.4 | **Lookup User** | údaje o uživateli | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/user-lookup-by-UserId.xml" target="_blank">vstup</a> <br><a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/prolongace/user-lookup-by-UserId.xml" target="_blank">vstup (ne)prodlužování výpůjček uživatele</a><br><a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/authorize_user_by_lookup_user.xml" target="_blank">vstup pro Shibboleth IDP</a>  | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/user-lookup-by-UserId.xml" target="_blank">výstup</a><br><a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/user-ext-notloanable.xml" target="_blank">výstup pro (ne)prodlužování výpůjček</a><br><a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/authorize_user_by_lookup_user.xml" target="_blank">výstup pro Shibboleth IDP</a> |
| 5.3.6 | **Lookup Item Set** | údaje o titulu (obsahuje seznam exemplářů) | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/luis-bib-itemid-only.xml" target="_blank">vstup</a> <br><a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/luis-ext-userId.xml" target="_blank">vstup pro přihlášeného uživatele</a>  | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/luis-bib-itemid-only.xml" target="_blank">výstup</a><br><a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/luis-not-for-loan.xml" target="_blank">výstup pro přihlášeného uživatele</a> |
| 5.4.13 | **Renew Item** | prodloužení výpůjčky | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/renew-item-by-User-id.xml" target="_blank">vstup</a> | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/request-item-by-User-id.xml" target="_blank">výstup</a> |
| 5.4.15 | **Request Item** | vytvoření objednávky či rezervace | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/request-item-by-User-id.xml" target="_blank">vstup</a> | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/request-item-by-User-id.xml" target="_blank">výstup</a> |
| 5.4.16 | **Cancel Request Item** | zrušení objednávky či rezrevrace | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-input/cancel-request-item.xml" target="_blank">vstup</a> | <a href="https://gitlab.com/cpk-main/details/blob/master/ncip-output/renew-item-by-User-id.xml" target="_blank">výstup</a> |
 
_Poznámka: Náhledy na vzorové **vstupy a výstupy** jsou **přístupné pouze pro zapojující se knihovny**._   
&nbsp; 

### Projekt xcncip2toolkit
Pokud používáte Open Source knihovní systém a budete si NCIP nastavovat sami, může se Vám hodit i Open Source nástroj **xcncip2toolkit**, který pomůže Vašemu OPACu komunikovat s discovery systémy, mezi které patří i portál Knihovny.cz.  
Související odkazy:
* [O projektu](https://code.google.com/p/xcncip2toolkit/)
* [Oficiální xcncip2toolkit repozitář](https://code.google.com/archive/p/xcncip2toolkit/source)
* [xcncip2toolkit repozitář MZK](https://github.com/moravianlibrary/xcncip2toolkit) (k dispozici i dockerfile)
* [Využití ILSDIv1_1 JAXB bindingu pro zpracování Ext prvků](https://docs.google.com/document/d/1d1ebJcxp7FOsJi_vIfWI1nX3wLwrBjUCun-w7c4R3CY/edit?usp=sharing)

### Další podrobná dokumentace
Některé odkazy z této i nadřazené kapitoly. Odkazy psané *kurzívou* jsou přístupné jen pro zapojující se knihovny:
* *<a href="https://gitlab.com/cpk-main/details/wikis/ncip-details" target="_blank">Minimální NCIP požadavky</a>*
* *<a href="https://gitlab.com/cpk-main/details/wikis/ncip-specs" target="_blank">Specifikace formátu NCIP zpráv</a>*
* [Dokumentace NCIP](http://www.niso.org/workrooms/ncip) a jeho [XSD schéma](http://www.niso.org/schemas/ncip/v2_02/ncip_v2_02.xsd)

&nbsp;
---
[Zpět na **Zpřístupnit služby - NCIP**](ncip)  
[Zpět na hlavní stránku](Home)