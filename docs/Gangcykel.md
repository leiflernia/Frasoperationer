# Gängcykel

De flesta moderna maskiner är synkroniserade i S/Z vilket minskar behovet av att använda speciella verktygshållare för gängning.  
Maskiner som är synkroniserade i S/Z samkör spindelvarvtalet och matning exakt för att matcha stigningen på gängan.  
Den stannar sedan vid botten av cykeln och vänder håll på spindelrotationen för att dra upp gängtappen.  
Parametrarna för gängcykeln är identiska med enkel borrning (G81).

Observera att F kan betyda antingen mm/min eller matning/varv. Kontrollera maskinens manual.

**G00 X12 Y0 Z10**  
**G84 Z-15 R2.5 F20**  
**G80**
