A mám ještě jeden dotaz.  Jak se máme chovat k vašim nedodaným (očekávaným) periodikám? U vás v OPACu je máte schované, tzn. že v tab15 máte nastaveno N pro zobrazení na webu. Jestli je budete chtít schovat i u nás, tak bych potřebovala, aby měli v 996 podpole q 0.  

my tohle řešíme tak, že pravidelně spouštíme skript přes joblist, který posílá k reindexaci bib. záznamy, kterým se změnila jednotka za daný den.
Nakonec to chtěli nechat vidět.  

Vašek Rosecký Vám poskytne podklady pro řešení, které máme v provozu
my. U nás je to založeno na 
https://github.com/moravianlibrary/ldap-aleph (což je brána mezi
databází uživetelů v Alephu a ldapem a dělá to totéž, jako podobný
produkt od Multidata, který ale není zadarmo) a simplesamlphp. U nás
je to smložitější o to, že simplesamlphp slučuje dva ldapy, ten výše
zmíněný a pak zaměstnanecké účty v AD.