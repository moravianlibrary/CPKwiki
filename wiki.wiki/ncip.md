# 3. Zpřístupnění služeb - NCIP
Údaje o Vašich registrovaných čtenářích a aktuálních statusech knihovních jednotek mají **proměnlivější a citlivější charakter než bibliografické záznamy**. Taková data není vhodné sklízet a ukládat na naší straně - **na portálu Knihovny.cz jsou pouze zobrazována**, nikoliv uchovávána.  
K načítání informací z Vašeho knihovního systému používáme **protokol NCIP**, respektive **Aleph RESTful API**.  

NCIP (respektive Aleph RESTful API) používáme k následujícím účelům:  
1. Zobrazení **informací ze čtenářského konta** (jméno, kontaktní údaje, výpůjčky, rezervace a objednávky, platnost registrace, pokuty a poplatky).  
2. Zobrazení **statusu knihovní jednotky** (tzn. zda je právě vypůjčená, zarezervovaná, k dipozici atd.).
3. **Tvorba a rušení rezervací a objednávek, prodlužování výpůjček a další akce**, které umožňuje OPAC Vaší knihovny.

Nastavení **NCIP responderu** zpravidla zajišťuje **dodavatel Vašeho knihovního systému**.   
Protože na Knihovnách.cz máme prostřednictvím zapojených institucí zastoupeny bezmála všechny knihovnické systémy, **je téměř jisté, že Váš dodavatel knihovního softwaru již někdy řešil požadavky spojené se zapojováním knihovny do našeho portálu**. Vzhledem k předchozím zkušenostem dodavatelů už teď **půjde především o odladění specifik**, spojených se způsobem používání systému ve Vaší knihovně.   
Pokud používáte **Open Source** knihovní systémy (Koha, Evergreen), můžete čerpat ze zkušeností **komunity**. Pomoci a poradit Vám můžeme v rámci našich možností i my.

| **NCIP responder musí být otevřený pro tyto IP adresy našich serverů: `195.113.155.74`, `195.113.155.141` a `195.113.155.142`** (to je frontie?).<br>V žádném případě by ale neměl být veřejně přístupný. |
| :----: |

Protože se NCIPem (Aleph RESTfulem) posílají osobní data uživatelů, není vhodné přenášet tyto informace v nešifrované podobě.

| **NCIP přenosy musí být šifrovány pomocí protokolu HTTPS s důvěryhodným SSL certifikátem.** |  
| :-----: |

Předpokládáme, že HTTPS ve svém OPACu již používáte - přinejmenším pro akce vyžadující přihlášení uživatele. V opačném případě Vám to co nejsilněji doporučujeme.  

| Jakmile budete mít nastavený NCIP (Aleph RESTful API), **budeme od Vás potřebovat adresu Vašeho NCIP responderu (resp. Aleph RESTful API)**. |
| :-----: |

## Doplňující informace
* **[Minimální požadavky](ncipminimal)**
* [Doporučené funkce](recommended)
* **[Zprostředkování plateb na portálu Knihovny.cz](transactions)** - nepovinná, leč vítaná funkce
* <a href="https://gitlab.com/cpk-main/details/wikis/ncip-details" target="_blank">Podrobná dokumentace minimálním požadavkům na nastavení NCIPu</a> - viditelné pouze pro knihovny v procesu zapojování  

## Externí odkazy
* [Dokumentace NCIP](http://www.niso.org/workrooms/ncip) a jeho [XSD schéma](http://www.niso.org/schemas/ncip/v2_02/ncip_v2_02.xsd)
* [Dokumentace Aleph RESTful](https://developers.exlibrisgroup.com/aleph/apis/Aleph-RESTful-APIs) a [návod na konfiguraci alephovského web services serveru](https://knowledge.exlibrisgroup.com/@api/deki/files/27668/How_to_Configure_the_Web_Services_Server_in_Aleph.pdf) v pdf
* [Let's Encrypt](https://letsencrypt.org/) - otevřená certifikační autorita, kde si můžete nechat zdarma zřídit SSL certifikát, pokud jej ještě nemáte  

&nbsp;  

---
[Zpět na hlavní stranu](Home)  

| [<< Na předchozí kapitolu](oai-pmh) | [Na další kapitolu >>](testusers) |
| :----- | -----: |