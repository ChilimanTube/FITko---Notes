> [!source]
> IEL/polovodiče
### Řešení obvodů s diodou (graficky)
> [!attention]
> **Nejspíše bude na půlsemestrální  / semestrální zkoušce**
> -> Musíme umět nakreslit, pokud dostaneme např. pouze tu přímku
![[Pasted image 20241016141726.png]]

### Aplikace diod
- Usměrňovače střídavého napětí (zdroje)
- Spínání (ochrany vstupů IO, spínané zdroje)
- Fotodioda: detekce světla, telekomunikace, fotovoltaika
- Měření teploty
- Detektory radiových signálů (přijímače)
- Modulátory, násobiče kmitočtu (vysílače)
- Detekce radiace
+ + Různé typy diod (Zenerova, LED, ...) = další aplikace
*Poznámky: sériové / paralelní zapojení diod (problémy, řešení)*

### Ochrana vstupů proti přepětí
![[Pasted image 20241016142002.png]]

### Jednocestný usměrňovač
![[Pasted image 20241016142440.png]]

-> Takto se to v praxi nedá použít, proto se používá usměrňovač s filtračním kondenzátorem (viz níže)

### Jednocestný usměrňovač s filtračním kondenzátorem
![[Pasted image 20241016142559.png]]

### Můstkový usměrňovač
![[Pasted image 20241016143131.png]]

### Dvoucestně usměrněné napětí
![[Pasted image 20241016143425.png]]

### Spínaný zdroj
- Snižující měnič (*buck converter*) - Dioda vede při rozpojení $S$
![[Pasted image 20241016143752.png]]
*Poznámka:* PWM = Pulse-Width Modulation

### Další typy diod (a typické aplikace)
![[Pasted image 20241016144435.png]]

> [!example]
> ### Příklady: LED, Zenerova dioda
> ![[Pasted image 20241016144934.png]]
> $U_{LED}$ je podle barvy světla v rozsahu 1.6V (červená) až 3.3V (bílá).
> Takzvané Zenerovy diody se běžně vyrábí pro napětí 3V až 200V.

> [!summary]
> ![[Pasted image 20241016145245.png]]



