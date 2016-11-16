# 2. Zpřístupnit fond pro sklízení - OAI-PMH
Data o fondu Vaší knihovny sklízíme pomocí protokolu **OAI-PMH 2** v doporučeném formátu **MARCXML**. K tomu účelu u Vás musí být zprovozněn tzv. **OAI provider**, jehož nastavení zpravidla zařizuje **dodatavel Vašeho knihovního softwaru**.  
Protože na Knihovnách.cz máme prostřednictvím zapojených institucí zastoupeny bezmála všechny knihovnické systémy, **je téměř jisté, že Váš dodavatel knihovního softwaru již někdy řešil požadavky spojené se zapojováním knihovny do našeho portálu**. Vzhledem k předchozím zkušenostem dodavatelů už teď **půjde především o odladění specifik**, spojených se způsobem používání systému ve Vaší knihovně.   
Pokud používáte **Open Source** knihovní systémy (Koha, Evergreen), můžete čerpat ze zkušeností **komunity**. Pomoci a poradit Vám můžeme v rámci našich možností i my.  
&nbsp;  
Pro fungování v rámci našeho portálu potřebujeme sklízet nejen bibliografické záznamy, ale i **údaje o knihovních jednotkách**, které se k těmto záznamům vážou. K tomu slouží **opakovatelné MARC pole 996** (podrobnosti najdete v samostatné [podkapitole](996)).  
&nbsp;  
Jakmile budete mít OAI provider spuštěný, budeme od Vás potřebovat následující údaje:
1. **adresu OAI provideru**
2. **název setu určeného k přenosu dat** do Knihoven.cz
3. **metadatový prefix**, kde je definován formát Vašich záznamů (zpravidla MARC 21)

Odkaz, který nám pošlete, tedy bude mít následující strukturu:
`http://vaseknihovna.cz/OAI?verb=ListRecords&metadataPrefix=marc21&set=vasset`   
&nbsp;    
U většiny knihoven se všechny veřejné bibliografické záznamy nacházejí v jediném setu. 

| **Informujte nás, prosím, pokud Vaše knihovna používá více setů s veřejně dostupnými bibliografickými záznamy.** |
| :-----: |  
  

| **Ke sklizni musí být poskytnuty všechny záznamy, na které jsou navázány Vaše služby.** |
| :-----: |

Kdybychom měli k dispozici jen některé záznamy, docházelo by k situacím, kdy by čtenář viděl např. v přehledu svých výpůjček tituly, ke kterým by na portálu neexistoval záznam.  
&nbsp;  
Každý den provádíme aktualizaci nejnovějších změn ve Vašich záznamech.
 
| **Pokud v určité noční hodiny pravidelně vypínáte své servery nebo provádíte hardwarově náročnější operace** (např. generování katalogů)**, je nutné nám tuto skutečnost oznámit.** |
| :-----: |

## Doplňující informace:
* [**Pole 996**](996)
* [Jak probíhá sklizeň](harvest)
* [Podoba záznamu](record)
* [Nepovolené znaky v XML](xml)
* [Výjimky pro knihovny bez OAI provideru](no-oai)
* <a href="https://gitlab.com/cpk-main/details/wikis/oai-aleph" target="_blank">Obecný návod na zprovoznění OAI v Alephu</a> - viditelné pouze pro knihovny v procesu zapojování  

## Externí odkazy
* [Dokumentace OAI-PMH 2](http://www.openarchives.org/OAI/openarchivesprotocol.html)
* [Dokumentace MARCXML](http://www.openarchives.org/OAI/openarchivesprotocol.html)
* [How to Configure Web Services Server in Aleph](https://knowledge.exlibrisgroup.com/@api/deki/files/27668/How_to_Configure_the_Web_Services_Server_in_Aleph.pdf)    

---
[Zpět na hlavní stránku](Home)  

| [<< Na předcházející kapitolu](prepare) | [Na další kapitolu >>](ncip) |
| :----- | -----: |