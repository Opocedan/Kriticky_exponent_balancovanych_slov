Aplikace pro výpočet Asymptotického kritického exponentu a Kritického exponentu.

Pro úspěšné spuštění je nutno z tého stránky stáhnout všechny soubory.dll a obě složky (platforms a styles), nebo stáhnout soubor apps.rar a ten rozbalit ve vybrané složce (obsahuje všechny předchozí soubory).
Následně je nutno stáhnout vybraný soubor .exe do stejné složky jako předchozí soubory. Dostupné jsou programy pro výpočet asymptotického kritického exponentu a kritického exponentu. Původní verze jsou anglicky, ty s koncovkou "CZ" jsou přeloženy do češtiny.

Následně by mělo stačit již jen spustit aplikaci Asymptotical_Critical_Exponent.exe nebo Critical_Exponent.exe. 

**Kritický exponent:** 
Zadává se předperioda a perioda řetězového zlomku theta jako přirozená čísla oddělená čárkami. 
Dále se zadávají periody slov s konstantní mezerami jako písmena a čísla anglické abecedy bez mezer a čárek. 
_Například:_
preperiod : 1,3
period : 2
y: 012345
y': 012345

**Kritický exponent:** 
Zadává se perioda, případně předperioda řetězového zlomku theta jako přirozená čísla oddělená čárkami. Pokud není zvoleno "Počítat sezadanou předperiodou", předperioda není uvažována a projdou se všechny možné.  
Dále se zadávají délky period slov s konstantními mezerami.
Nakonec je možnost volit mezi 4 různými hladinami výpisu podle toho, zda uživatele zajímá pouze výsledek, nebo i postup. 
_Například:_
Compute with qiven preperiod.
Preperiod: 2,3
Period: 2
Per y: 1
Per y': 2

V případě, že nebyly zadány platné parametry, je na to uživatel upozorněn vyskakovacím oknem a výpopčet je ukončen. 

V obou programech se po spuštění výpočtu zobrazí nové okno, do kterého se vypisuje postup výpočtu, v případě asymptotického kritického exponentu se zvolenou hladinou výpisu. Toto okno se při spuštění nového výpočtu samo zavře.
Do hlavního okna se vypíší parametry zadaného slova a následný výsledek výpočtu. 
Pokud výpočet z nějakého důvodu (primárně přetečení) nemůže doběhnout, je o tom uživatel informován právě v tomto hlavním okně. 

